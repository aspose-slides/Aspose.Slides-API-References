---
title: CheckPassword()
second_title: Aspose.Slides for C++ API Referansı
description: Açık şifre ile korunan bir sunum için şifrenin doğru olup olmadığını kontrol eder.
type: docs
weight: 53
url: /tr/aspose.slides/presentationinfo/checkpassword/
---
## PresentationInfo::CheckPassword(System::String) metot

Açık şifre ile korunan bir sunum için şifrenin doğru olup olmadığını kontrol eder.

```cpp
bool Aspose::Slides::PresentationInfo::CheckPassword(System::String password) override
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

Şifre null veya boş olduğunda, bu metot false döner.

## Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [PresentationInfo](../)
* Ad Alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)