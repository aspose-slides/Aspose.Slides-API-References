---
title: set_DefaultTextLanguage()
second_title: Aspose.Slides pro C++ API Reference
description: "Nastaví výchozí jazyk pro text prezentace. Zapište System::String."
type: docs
weight: 326
url: /cs/aspose.slides/iloadoptions/set_defaulttextlanguage/
---
## ILoadOptions::set_DefaultTextLanguage(System::String) metoda

Nastaví výchozí jazyk pro text prezentace. Zapište [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::ILoadOptions::set_DefaultTextLanguage(System::String value)=0
```

## Poznámky

Příklad: 
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

## Viz také

* třída [String](../../../system/string/)
* třída [ILoadOptions](../)
* jmenný prostor [Aspose::Slides](../../)
* knihovna [Aspose.Slides](../../../)