---
title: check_write_protection method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ipresentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
Yazma korumalı bir sunum için değiştirme şifresinin doğru olup olmadığını kontrol eder.

### Returns
Sunum yazma korumalı ve şifre doğruysa True. Aksi takdirde False.



```python
def check_write_protection(self, password):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| password | **str** | Kontrol edilecek şifre. |

### Remarks

1. Bu yöntemi çağırmadan önce [`IPresentationInfo.is_write_protected`](/slides/python-net/tr/aspose.slides/ipresentationinfo/is_write_protected) özelliğini kontrol etmelisiniz.
2. Şifre None veya boş olduğunda, bu yöntem false döndürür.

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |



### Ayrıca Bakınız
* sınıf [`IPresentationInfo`](/slides/python-net/tr/aspose.slides/ipresentationinfo)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)