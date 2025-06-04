# langja
A jinja2-like renderer powerer by LLM

- examples: see  [./langja/examples/](./langja/examples/)

### Feature
- LLM rendered: prompts to induce llm to render a structured output
  - [TODO] benchmark different llm for their performance in mimicking a jinja renderer
- [TODO] python rendered: prompts that only calls LLM when needed.

### Known Challenge:
- This prompt could only be rendered on Claude sonnet 4.0, failed on many other models https://github.com/shouldsee/langja/blob/main/langja/examples/05_error_log.j2
