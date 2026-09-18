---
title: check_password method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/presentationinfo/check_password/
weight: 10
---
## check_password(self, password) {#str}
Açık parola ile korunan bir sunum için parolanın doğru olup olmadığını kontrol eder.

### Döndürür

Sunum açık parola ile korunuyorsa ve parola doğruysa True, aksi takdirde false.

```python
def check_password(self, password):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| password | **str** | Kontrol edilecek parola. |

### Açıklamalar

Parola None veya boş olduğunda, bu yöntem false döner.

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |
| **RuntimeError(Proxy error(NotSupportedException))** |  |

### Ayrıca Bakınız
* sınıf [`PresentationInfo`](/slides/python-net/tr/aspose.slides/presentationinfo)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)