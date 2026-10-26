---
title: check_write_protection method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/iprotectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
Bir sunumun değiştirilmek için parola korumalı olup olmadığını belirler.

### Returns
True if the password is valid; otherwise, false.

```python
def check_write_protection(self, password):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| password | **str** | Kontrol için parola. |

### Remarks
1. Bu yöntemi çağırmadan önce [`IProtectionManager.is_write_protected`](/slides/python-net/tr/aspose.slides/iprotectionmanager/is_write_protected) özelliğini kontrol etmelisiniz.
2. Parola None veya boş olduğunda, bu yöntem false döndürür.

### See Also
* sınıf [`IProtectionManager`](/slides/python-net/tr/aspose.slides/iprotectionmanager)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)