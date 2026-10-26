---
title: SlidesAIAgent
second_title: Aspose.Sildes for PHP via Java API 参考文档
description: 
type: docs

url: /zh/aspose.slides/slidesaiagent/
---
## SlidesAIAgent 类

提供用于处理演示文稿的 AI 驱动功能。

### SlidesAIAgent {#SlidesAIAgent}

| 名称 | 描述 |
| --- | --- |
| SlidesAIAgent([OpenAIWebClient](../openaiwebclient)) | SlidesAIAgent 函数 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| aiClient | [OpenAIWebClient](../openaiwebclient) | AI 客户端实例 |

**返回：**
SlidesAIAgent

**错误**

| 错误 | 条件 |
| --- | --- |
|  | ArgumentNullException | 未提供 AI 客户端实例 |

---


### generatePresentation {#generatePresentation}

| 名称 | 描述 |
| --- | --- |
| generatePresentation (String, int) | 从文本描述生成演示文稿实例。提供所需语言的主题、想法、引用或文本片段。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| description | String | 主题、想法、引用或文本片段。 |
| presentationContentAmount | int | 生成的演示文稿中内容的数量。 String prompt = "Generate a presentation about Aspose.Slides for Java. Highlight its key features, use cases, and explain why it is better than its competitors."; OpenAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null); try { SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient); IPresentation pres = aiAgent.generatePresentation(prompt, PresentationContentAmountType.Brief); pres.save("result.pptx", SaveFormat.Pptx); } finally { if (aiWebClient != null) aiWebClient.close(); } |

**返回：**
[Presentation](../presentation)

**异常**

| 错误 | 条件 |
| --- | --- |
|  | ArgumentException | AI 聊天指令不能为空或为空。 |

---


### generatePresentation {#generatePresentation}

| 名称 | 描述 |
| --- | --- |
| generatePresentation (String, int, [Presentation](../presentation)) | 从文本描述生成演示文稿实例。提供所需语言的主题、想法、引用或文本片段。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| description | String | 主题、想法、引用或文本片段。 |
| presentationContentAmount | int | 生成的演示文稿中内容的数量。 |
| presentationTemplate | [Presentation](../presentation) | 用于布局和设计的模板演示文稿，替代默认模板。 String prompt = "Generate a presentation about Aspose.Slides for Java. Highlight its key features, use cases, and explain why it is better than its competitors."; IPresentation template = new Presentation("masterPresentation.pptx"); try { OpenAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null); try { SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient); IPresentation pres = aiAgent.generatePresentation(prompt, PresentationContentAmountType.Brief, template); pres.save("result.pptx", SaveFormat.Pptx); } finally { if (aiWebClient != null) aiWebClient.close(); } } finally { if (template != null) template.dispose(); } |

**返回：**
[Presentation](../presentation)

**异常**

| 错误 | 条件 |
| --- | --- |
|  | ArgumentException | AI 聊天指令不能为空或为空。 |

---


### translate {#translate}

| 名称 | 描述 |
| --- | --- |
| translate ([Presentation](../presentation), String) | 使用 AI 将演示文稿翻译成指定语言（同步版本）。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| presentation | [Presentation](../presentation) | 目标演示文稿 |
| language | String | 目标语言 Presentation presentation = new Presentation("Presentation.pptx"); try { IAIWebClient aiWebClient = new OpenAIWebClient("gpt-4o-mini", "apiKey", null); SlidesAIAgent aiAgent = new SlidesAIAgent(aiWebClient); aiAgent.translate(presentation, "spanish"); presentation.save("translated.pptx", SaveFormat.Pptx); } finally { if (presentation != null) presentation.dispose(); } |

**返回：**
void

**异常**

| 错误 | 条件 |
| --- | --- |
|  | ArgumentException | 语言值不能为空或为空 |