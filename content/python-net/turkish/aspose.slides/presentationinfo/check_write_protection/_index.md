---
title: check_write_protection method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/presentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
Yazma korumalı bir sunumda değişiklik yapmak için şifrenin doğru olup olmadığını kontrol eder.

### Döndürür

True, sunum yazma korumalıysa ve şifre doğruysa. False, aksi takdirde.



```python
def check_write_protection(self, password):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| password | **str** | Kontrol edilecek şifre. |

### Açıklamalar

1. Bu yöntemi çağırmadan önce [`PresentationInfo.is_write_protected`](/slides/python-net/tr/aspose.slides/presentationinfo/is_write_protected) özelliğini kontrol etmelisiniz.
2. Şifre None veya boş olduğunda, bu yöntem false döndürür.

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |

### Ayrıca Bakınız
* sınıf [`PresentationInfo`](/slides/python-net/tr/aspose.slides/presentationinfo)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)