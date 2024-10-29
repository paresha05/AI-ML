# Video Processing

Using:
- Llamaindex framework
- Lancedb vectorstore
- LLM model(GPT-4V, GEMINI-PRO-VISION)

Steps:

Download video from YouTube, process and store it in directory.

Build Multi-Modal index and vector store for both texts and images.

Generate video to image and video to text and save it in mix_data directory.

Generate text data from audio file and save it in mix_data directory.

Retrieve relevant images and context, use both to augment the prompt.

Using GPT4V for reasoning the correlations between the input query and augmented data and generating final response.