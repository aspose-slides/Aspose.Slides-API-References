---
title: set_DefaultTextLanguage()
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt de standaardtaal in voor presentatie-tekst. Schrijf System::String."
type: docs
weight: 326
url: /nl/aspose.slides/iloadoptions/set_defaulttextlanguage/
---
## ILoadOptions::set_DefaultTextLanguage(System::String) methode


Stelt de standaardtaal in voor presentatie-tekst. Schrijf [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::ILoadOptions::set_DefaultTextLanguage(System::String value)=0
```

## Opmerkingen


Voorbeeld: 
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

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [ILoadOptions](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)