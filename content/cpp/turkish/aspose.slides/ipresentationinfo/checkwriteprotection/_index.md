---
title: CheckWriteProtection()
second_title: Aspose.Slides C++ için API Referansı
description: Yazma korumalı bir sunum için değişiklik şifresinin doğru olup olmadığını denetler.
type: docs
weight: 66
url: /tr/aspose.slides/ipresentationinfo/checkwriteprotection/
---
## IPresentationInfo::CheckWriteProtection(System::String) yöntemi

Yazma korumalı bir sunum için değişiklik şifresinin doğru olup olmadığını kontrol eder.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckWriteProtection(System::String password)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Kontrol edilecek şifre. |

### Dönüş Değeri

Sunum yazma korumalı ve şifre doğruysa true; aksi takdirde false.

## Açıklamalar

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```

1. Bu yöntemi çağırmadan önce [IPresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) özelliğini kontrol etmelisiniz.
1. Şifre null ya da boş olduğunda, bu yöntem false döndürür.

## Ayrıca

* Sınıf [String](../../../system/string/)
* Sınıf [IPresentationInfo](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)