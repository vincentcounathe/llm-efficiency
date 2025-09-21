# LLM Efficiency

Compare three approaches on a small language model:
- full fine-tuning
- LoRA fine-tuning
- post-training quantization

The notebook trains/evaluates DistilGPT-2 on a tiny slice of WikiText-2.  
It reports eval loss/perplexity, % trainable parameters, and model size before/after quantization.