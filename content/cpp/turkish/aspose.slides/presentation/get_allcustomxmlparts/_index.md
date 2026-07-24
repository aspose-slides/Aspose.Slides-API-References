---
title: get_AllCustomXmlParts()
second_title: Aspose.Slides for C++ API Referansı
description: Sunumda bulunan tüm özel veri bölümlerini döndürür. Yalnızca okuma ICustomXmlPart[].
type: docs
weight: 287
url: /tr/aspose.slides/presentation/get_allcustomxmlparts/
---
## Presentation::get_AllCustomXmlParts() metod

Returns all custom data parts in the presentaion. Yalnızca okuma [ICustomXmlPart](../../icustomxmlpart/)[].

```cpp
System::ArrayPtr<System::SharedPtr<ICustomXmlPart>> Aspose::Slides::Presentation::get_AllCustomXmlParts() override
```

## Açıklamalar

The following examples show how to clear all custom xml parts from PowerPoint [Presentation](../). 

```cpp
auto pres = System::MakeObject<Presentation>(u"PresentationWithCustomXml.pptx");

// Tüm özel XML parçalarını yinele
for (System::SharedPtr<ICustomXmlPart> item : pres->get_AllCustomXmlParts())
{
    item->Remove();
}

pres->Save(u"out.pptx", SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ICustomXmlPart](../../icustomxmlpart/)
* Sınıf [Presentation](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)