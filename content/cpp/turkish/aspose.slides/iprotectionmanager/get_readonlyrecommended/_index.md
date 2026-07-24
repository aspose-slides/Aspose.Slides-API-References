---
title: get_ReadOnlyRecommended()
second_title: Aspose.Slides for C++ API Referansı
description: Salt okunur öneriyi alır. Bool değerini okur.
type: docs
weight: 79
url: /tr/aspose.slides/iprotectionmanager/get_readonlyrecommended/
---
## IProtectionManager::get_ReadOnlyRecommended() yöntemi


Salt okunur önerisini alır. Okunan **bool**.

```cpp
virtual bool Aspose::Slides::IProtectionManager::get_ReadOnlyRecommended()=0
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