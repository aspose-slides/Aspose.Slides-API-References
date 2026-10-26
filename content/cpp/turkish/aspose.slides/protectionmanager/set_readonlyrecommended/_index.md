---
title: set_ReadOnlyRecommended()
second_title: C++ API Referansı için Aspose.Slides
description: Okuma-yazma önerisini ayarlar. bool yazar.
type: docs
weight: 92
url: /tr/aspose.slides/protectionmanager/set_readonlyrecommended/
---
## ProtectionManager::set_ReadOnlyRecommended(bool) metodu

Okuma-yazma önerisini ayarlar. **bool** değerini yazar.

```cpp
void Aspose::Slides::ProtectionManager::set_ReadOnlyRecommended(bool value) override
```

## Açıklamalar

Aşağıdaki örnek kod, [Aspose.Slides](../../) kullanarak C# içinde bir PowerPoint [Presentation](../../presentation/) dosyasını Salt Okunur olarak nasıl ayarlayacağınızı gösterir. 
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Sınıf [ProtectionManager](../)
* İsim Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)