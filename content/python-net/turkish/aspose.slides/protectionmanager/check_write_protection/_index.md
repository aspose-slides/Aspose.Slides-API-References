---
title: check_write_protection method
second_title: Aspose.Slides için Python üzerinden .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/protectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
Bir sunumun değiştirilmesi için şifre korumalı olup olmadığını belirler.

### Dönüş Değeri

True if the password is valid; otherwise, false.



```python
def check_write_protection(self, password):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| password | **str** | Kontrol için şifre. |

### Açıklamalar

1. Bu yöntemi çağırmadan önce [`ProtectionManager.is_write_protected`](/slides/python-net/tr/aspose.slides/protectionmanager/is_write_protected) özelliğini kontrol etmelisiniz.
2. Şifre None veya boş olduğunda, bu yöntem false döndürür.



### Ayrıca Bakınız
* sınıf [`ProtectionManager`](/slides/python-net/tr/aspose.slides/protectionmanager)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)