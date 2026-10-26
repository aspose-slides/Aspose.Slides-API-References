---
title: set_ReadOnlyRecommended()
second_title: Aspose.Slides for C++ API Referansı
description: Salt-okunur önerisini ayarlar. bool yazın.
type: docs
weight: 92
url: /tr/aspose.slides/iprotectionmanager/set_readonlyrecommended/
---
## IProtectionManager::set_ReadOnlyRecommended(bool) method


Salt-okunur önerisini ayarlar. **bool** yazın.

```cpp
virtual void Aspose::Slides::IProtectionManager::set_ReadOnlyRecommended(bool value)=0
```

## Açıklamalar



```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Sınıf [IProtectionManager](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)