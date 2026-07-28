---
title: set_DefaultTextLanguage()
second_title: Aspose.Slides for C++ API referenciája
description: "Beállítja a prezentáció szövegéhez az alapértelmezett nyelvet. Írja be System::String."
type: docs
weight: 326
url: /hu/aspose.slides/loadoptions/set_defaulttextlanguage/
---
## LoadOptions::set_DefaultTextLanguage(System::String) metódus


Beállítja az alapértelmezett nyelvet a prezentáció szövegéhez. Írja be [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_DefaultTextLanguage(System::String value) override
```

## Megjegyzések


Példa: 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DefaultTextLanguage(u"en-US");

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(loadOptions);

// Add new rectangle shape with text
System::SharedPtr<IAutoShape> shp = pres->get_Slide(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 50.0f, 50.0f, 150.0f, 50.0f);
shp->get_TextFrame()->set_Text(u"New Text");

// Check the first portion language
System::SharedPtr<IPortion> portion = shp->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
System::Console::WriteLine(portion->get_PortionFormat()->get_LanguageId());
```


## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [LoadOptions](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)