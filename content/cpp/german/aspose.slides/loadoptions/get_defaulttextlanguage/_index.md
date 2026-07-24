---
title: get_DefaultTextLanguage()
second_title: Aspose.Slides für C++ API-Referenz
description: "Gibt die Standardsprache für Präsentationstext zurück. Lesen Sie System::String."
type: docs
weight: 313
url: /de/aspose.slides/loadoptions/get_defaulttextlanguage/
---
## LoadOptions::get_DefaultTextLanguage() Methode

Gibt die Standardsprache für Präsentationstext zurück. Lesen Sie [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_DefaultTextLanguage() override
```

## Hinweise


Beispiel: 
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

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [LoadOptions](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)