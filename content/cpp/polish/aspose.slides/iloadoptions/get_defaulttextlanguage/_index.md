---
title: get_DefaultTextLanguage()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Zwraca domyślny język tekstu prezentacji. Czytaj System::String."
type: docs
weight: 313
url: /pl/aspose.slides/iloadoptions/get_defaulttextlanguage/
---
## ILoadOptions::get_DefaultTextLanguage() metoda


Zwraca domyślny język tekstu prezentacji. Czytaj [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::ILoadOptions::get_DefaultTextLanguage()=0
```

## Uwagi


Przykład: 
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

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [ILoadOptions](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)