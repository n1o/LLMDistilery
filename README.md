# llm_distil
## Idea
Since there is this paper [MiniLLM](https://arxiv.org/abs/2306.08543) I do not see any problem of having an general framework for Knowledge Distillation. The only limitation is that 2 models should share the same Tokenizer, and maybe booth have to have the same CausalLM Denoising objective, but I thing it would be enough that they predict token by token.
