---
title: GetEffective()
second_title: Aspose.Slides C++ API hivatkozás
description: Lekéri a tényleges bekezdésformázási adatokat a származtatás alkalmazásával.
type: docs
weight: 365
url: /hu/aspose.slides/paragraphformat/geteffective/
---
## ParagraphFormat::GetEffective() metódus


Lekéri a tényleges bekezdésformázási adatokat a származtatás alkalmazásával.

```cpp
System::SharedPtr<IParagraphFormatEffectiveData> Aspose::Slides::ParagraphFormat::GetEffective() override
```


### Visszatérési érték

A [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/).
## Megjegyzések



Ez a példa azt mutatja be, hogyan lehet lekérni néhány tényleges bekezdésformázási tulajdonságot. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveParagraphFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->GetEffective();

Console::WriteLine(String(u"Text alignment: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Alignment()));
Console::WriteLine(String(u"Indent: ") + effectiveParagraphFormat->get_Indent());
Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Bullet()->get_Type()));
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/)
* Osztály [ParagraphFormat](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)