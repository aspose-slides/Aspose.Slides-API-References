---
title: get_AllCustomXmlParts()
second_title: Aspose.Slides for C++ API Reference
description: Returns all custom data parts in the presentaion. Read-only ICustomXmlPart[].
type: docs
weight: 287
url: /cpp/aspose.slides/presentation/get_allcustomxmlparts/
---
## Presentation::get_AllCustomXmlParts() method


Returns all custom data parts in the presentaion. Read-only [ICustomXmlPart](../../icustomxmlpart/)[].

```cpp
System::ArrayPtr<System::SharedPtr<ICustomXmlPart>> Aspose::Slides::Presentation::get_AllCustomXmlParts() override
```

## Remarks


The following examples show how to clear all custom xml parts from PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"PresentationWithCustomXml.pptx");

// Iterate all custom XML Parts
for (System::SharedPtr<ICustomXmlPart> item : pres->get_AllCustomXmlParts())
{
    item->Remove();
}

pres->Save(u"out.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICustomXmlPart](../../icustomxmlpart/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
