# deep-fact-search

深度事实穿透检索与零幻觉校验工具。

## 🌟 核心特性与原则
- **拒绝脑补（Zero-Hallucination Gate）**：未在官方/权威长文中明确提及的内容，强制声明【未公布/不可查】，杜绝小说式虚构。
- **正文穿透（Full-text Extraction）**：绕过 100 字 Snippet，直接拉取深度复盘长文与官方场记。
- **本地预清洗（Token Saver）**：本地正则秒级提取核心锚点（死亡、结局、反转、漏洞），节省 80% Token。

## 🚀 使用方法
`ash
python scripts/extract_facts.py --id <条目ID>
`
