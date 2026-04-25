# HaaigWriter — ENG4U-26A A 线范文项目

## 项目概述

ENG4U-26A 课程 A 线（全球议题研究）的完整范文示例，供学习参考。

- **研究问题：** What policy interventions can effectively reduce plastic pollution in Southeast Asia's river systems?
- **覆盖作业：** 1-2E Annotated Bibliography (5%) + 2-2E Research Presentation (7%)

## 文件结构

| 文件 | 说明 |
|------|------|
| `index.html` | 首页，自动跳转至范文 |
| `a-line-sample.html` | A 线范文（含 3 条完整 annotation + 12 张幻灯片结构 + 2 分钟讲稿 + self-check） |

## 历史记录

### 2026-04-25 — 初始创建与部署

1. **浏览课程网站** — 查看了 https://study.knowitfoundation.com/courses/eng4u-26a/ 的 A 线内容
   - 读取了「详细打法」—— 三个作业依赖关系、好题标准
   - 读取了「关键节点」—— 一级/二级/三级节点
   - 读取了「1-2E 模板」—— 6 步 annotation 骨架（介绍/方法/发现/结论/局限/用途）
   - 读取了「2-2E 模板」—— 9-14 张幻灯片结构 + Section 4 视频讲稿骨架

2. **编写范文** — 基于模板结构撰写完整示例
   - 选材：Southeast Asia river plastic pollution（符合当下、可论证、有分析空间）
   - 引用 3 篇真实学术论文（Lebreton 2017, Jambeck 2015, Vince & Hardesty 2018）
   - 按 6 步骨架完成每条 annotation
   - 设计 12 张幻灯片 + 完整 2 分钟讲稿（EPR+Community Incentive 方案）
   - 附提交前 self-check 清单

3. **部署至 GitHub Pages**
   - `git init` → `git commit` → `gh repo create`
   - 添加 `.nojekyll` 解决 Jekyll 冲突
   - 上线地址：https://zzr0708.github.io/haaigwriter/

4. **部署至 Netlify**
   - 用户手动在 Netlify UI 中 Import from Git（GitHub repo）
   - 修正 index.html 跳转路径（`/haaigwriter/` → `/`）
   - 上线地址：https://rococo-cheesecake-744586.netlify.app/

## 自动部署

推送到 GitHub `main` 分支后，两个平台自动更新：
- GitHub Pages：~1-2 分钟
- Netlify：~2-3 分钟
