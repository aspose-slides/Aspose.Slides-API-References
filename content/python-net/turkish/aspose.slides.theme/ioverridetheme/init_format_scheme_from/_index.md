---
title: init_format_scheme_from method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.theme/ioverridetheme/init_format_scheme_from/
weight: 100
---
## init_format_scheme_from(self, format_scheme) {#iformatscheme}
Yeni bir nesne ile FormatScheme’i başlatarak InheritedTheme’in FormatScheme’ini geçersiz kılar.

```python
def init_format_scheme_from(self, format_scheme):
    ...
```

| Parametre | Tip | Açıklama |
| :- | :- | :- |
| format_scheme | [`IFormatScheme`](/slides/python-net/tr/aspose.slides.theme/iformatscheme) | Başlatma için veri. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | FormatScheme zaten başlatılmışsa (None değil) atılır. |
| **RuntimeError(Proxy error(ArgumentNullException))** | formatScheme parametresi None ise atılır. |

### Ayrıca Bakınız
* sınıf [`IFormatScheme`](/slides/python-net/tr/aspose.slides.theme/iformatscheme)
* sınıf [`IOverrideTheme`](/slides/python-net/tr/aspose.slides.theme/ioverridetheme)
* modül [`aspose.slides.theme`](/slides/python-net/tr/aspose.slides.theme)
* kütüphane [`Aspose.Slides`](/slides/python-net)