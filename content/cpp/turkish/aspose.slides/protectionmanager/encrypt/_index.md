---
title: Encrypt()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen şifre ile Sunumu şifreler.
type: docs
weight: 105
url: /tr/aspose.slides/protectionmanager/encrypt/
---
## ProtectionManager::Encrypt(System::String) yöntemi

Belirtilen şifre ile [Presentation](../../presentation/) şifreler.

```cpp
void Aspose::Slides::ProtectionManager::Encrypt(System::String encryptionPassword) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| encryptionPassword | [System::String](../../../system/string/) | Şifre. |

## Açıklamalar



Aşağıdaki örnek kod, bir PowerPoint [Presentation](../../presentation/)'yi nasıl şifreleyeceğinizi gösterir.
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.pptx", SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [ProtectionManager](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)