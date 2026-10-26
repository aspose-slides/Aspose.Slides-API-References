---
title: get_font_embedding_level method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/fontsmanager/get_font_embedding_level/
weight: 40
---
## get_font_embedding_level(self, font_bytes, font_name) {#bytes-str}
سطح جاسازی یک قلم را از آرایه بایتی داده شده و نام قلم تعیین می‌کند.

### Returns
سطح جاسازی قلم مشخص شده.

```python
def get_font_embedding_level(self, font_bytes, font_name):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| font_bytes | **bytes** | آرایه بایتی که حاوی داده‌های قلم است. |
| font_name | **str** | نام قلم. |

### Exceptions
| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | زمانی که `font_bytes` مقدار None باشد، پرتاب می‌شود. |

### See Also
* enumeration [`EmbeddingLevel`](/slides/python-net/fa/aspose.slides/embeddinglevel)
* class [`FontsManager`](/slides/python-net/fa/aspose.slides/fontsmanager)
* module [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)