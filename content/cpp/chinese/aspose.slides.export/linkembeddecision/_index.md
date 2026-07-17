---
title: LinkEmbedDecision
second_title: Aspose.Slides for C++ API 参考
description: 确定对象在保存时的处理方式。
type: docs
weight: 911
url: /zh/aspose.slides.export/linkembeddecision/
---
## LinkEmbedDecision 枚举


确定对象在保存时将如何处理。

```cpp
enum class LinkEmbedDecision
```

### 取值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Link | 0 | 对象将被外部存储，引用自 URL |
| Embed | 1 | 如果可能，应该将对象嵌入生成的文件中。如果嵌入不可能，将调用 GetUrl，并根据结果，对象将通过 URL 引用或被忽略。 |
| Ignore | 2 | 对象将被忽略。 |

## 另见

* 命名空间 [Aspose::Slides::Export](../)
* 库 [Aspose.Slides](../../)