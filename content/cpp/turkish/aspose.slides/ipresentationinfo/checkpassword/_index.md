---
title: CheckPassword()
second_title: Aspose.Slides için C++ API Referansı
description: Açık şifreyle korunan bir sunum için şifrenin doğru olup olmadığını kontrol eder.
type: docs
weight: 53
url: /tr/aspose.slides/ipresentationinfo/checkpassword/
---
## IPresentationInfo::CheckPassword(System::String) method

Açık şifreyle korunan bir sunum için şifrenin doğru olup olmadığını kontrol eder.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckPassword(System::String password)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Kontrol edilecek şifre. |

### Dönüş Değeri

True if the presentation is protected with open password and the password is correct and false otherwise.

## Açıklamalar

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```

Şifre null veya boş olduğunda, bu yöntem false döndürür. 

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [IPresentationInfo](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)