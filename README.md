# webgpu-lab

公众号「小明学GIS」· AI学WebGPU 系列的交互实验页，通过 GitHub Pages 发布：

https://mrpan.github.io/webgpu-lab/

每篇文章对应一个目录，目录下的 `index.html` 是该篇的实验索引：

| 目录 | 对应文章 | 实验 |
|------|---------|------|
| `01/` | AI学WebGPU①：我的浏览器能跑WebGPU吗 | `env-check.html` WebGPU 环境检测；`gpu-steps.html` GPU 入口步进器 |

纯静态 HTML，无构建步骤、无外部依赖，单个文件可直接复制运行。
WebGPU 只在安全上下文（HTTPS 或 localhost）下可用，本地调试请起一个本地服务，例如：

```bash
python -m http.server 8000
```
