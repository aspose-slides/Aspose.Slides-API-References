---
title: get_AllCustomXmlParts()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vrací všechny vlastní datové části v prezentaci. Pouze pro čtení ICustomXmlPart[].
type: docs
weight: 287
url: /cs/aspose.slides/presentation/get_allcustomxmlparts/
---
## Presentation::get_AllCustomXmlParts() metoda


Vrací všechny vlastní datové části v prezentaci. Pouze pro čtení [ICustomXmlPart](../../icustomxmlpart/)[].

```cpp
System::ArrayPtr<System::SharedPtr<ICustomXmlPart>> Aspose::Slides::Presentation::get_AllCustomXmlParts() override
```

## Poznámky


Následující příklady ukazují, jak vymazat všechny vlastní xml části z PowerPointu [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"PresentationWithCustomXml.pptx");

// Procházejte všechny vlastní XML části
for (System::SharedPtr<ICustomXmlPart> item : pres->get_AllCustomXmlParts())
{
    item->Remove();
}

pres->Save(u"out.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ICustomXmlPart](../../icustomxmlpart/)
* Třída [Presentation](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)