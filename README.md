# freecad-openwebui-mcp

Open-source FreeCAD + AI modeling with Open WebUI, mcpo, and DeepSeek on Linux Mint.

I was stunned by [a MakeForm video of Claude building parts in FreeCAD from plain-English prompts](https://www.youtube.com/watch?v=6trAkQY5_kc), so I replicated the setup with open-source tools. In this setup, Open WebUI chats with a DeepSeek model on Ollama Cloud, and mcpo connects it to FreeCAD.

## The guide

[**Connect Open WebUI to FreeCAD on Linux Mint**](guide.md) covers how a prompt becomes a part, the step-by-step installation, a test that checks the model sees FreeCAD's screenshots, a prompt library, and troubleshooting.

## Tested setup

| Component | Version |
| --- | --- |
| Linux Mint | 22.2 |
| FreeCAD | 1.1.4 |
| Open WebUI | v0.11.4 |
| mcpo | 0.0.20 |
| FreeCAD MCP add-on | 0.1.25 |
| Model | `deepseek-v4.1-flash:cloud` on Ollama Cloud |

## Credits

- [freecad-mcp](https://github.com/neka-nat/freecad-mcp) by neka-nat provides the FreeCAD add-on and MCP server.
- [MakeForm](https://www.youtube.com/watch?v=6trAkQY5_kc) made the video that inspired this setup.

## License

See [LICENSE](LICENSE).
