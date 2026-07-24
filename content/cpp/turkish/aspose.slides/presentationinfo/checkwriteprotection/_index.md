---
title: CheckWriteProtection()
second_title: Aspose.Slides for C++ API Referansı
description: Yazma korumalı bir sunum için değişiklik şifresinin doğru olup olmadığını kontrol eder.
type: docs
weight: 66
url: /tr/aspose.slides/presentationinfo/checkwriteprotection/
---
## PresentationInfo::CheckWriteProtection(System::String) metodu


Yazma korumalı bir sunum için değişiklik şifresinin doğru olup olmadığını kontrol eder.

```cpp
bool Aspose::Slides::PresentationInfo::CheckWriteProtection(System::String password) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Kontrol edilecek şifre. |

### Dönüş Değeri

Sunum yazma korumalı ve şifre doğruysa True. Aksi takdirde False.
## Açıklamalar



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```



1. Bu yöntemi çağırmadan önce [PresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) özelliğini kontrol etmelisiniz.
1. Şifre null veya boş olduğunda, bu yöntem false döndürür.



## Diğer Bağlantılar

* Class [String](../../../system/string/)
* Class [PresentationInfo](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)