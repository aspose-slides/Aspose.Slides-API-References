---
title: LinkEmbedDecision
second_title: Aspose.Slides for C++ API Reference
description: Determines how object will be processed during saving.
type: docs
weight: 859
url: /aspose.slides.export/linkembeddecision/
---
## LinkEmbedDecision enum


Determines how object will be processed during saving.

```cpp
enum class LinkEmbedDecision
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Link | 0 | Object will be stored externally, referrenced by URL |
| Embed | 1 | Object should be embedded to a generated file if possible. If embedding is imposible, GetUrl will be called and, depending on result, object will be referrenced by URL or ignored. |
| Ignore | 2 | Object will be ignored. |

## See Also

* Namespace [Aspose::Slides::Export](../)
* Library [Aspose.Slides](../../)