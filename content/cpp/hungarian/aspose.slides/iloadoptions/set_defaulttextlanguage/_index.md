---
title: set_DefaultTextLanguage()
second_title: Aspose.Slides C++ API Referencia
description: "Beállítja a prezentáció szövegének alapértelmezett nyelvét. Írja be a System::String-et."
type: docs
weight: 326
url: /hu/aspose.slides/iloadoptions/set_defaulttextlanguage/
---
## ILoadOptions::set_DefaultTextLanguage(System::String) metódus

Beállítja az alapértelmezett nyelvet a prezentáció szövegéhez. Írja be a [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::ILoadOptions::set_DefaultTextLanguage(System::String value)=0
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
* Osztály [ILoadOptions](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)