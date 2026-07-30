---
title: get_DefaultTextLanguage()
second_title: Aspose.Slides pro C++ – reference API
description: "Vrací výchozí jazyk pro text prezentace. Přečtěte si System::String."
type: docs
weight: 313
url: /cs/aspose.slides/loadoptions/get_defaulttextlanguage/
---
## LoadOptions::get_DefaultTextLanguage() metoda


Vrací výchozí jazyk pro text prezentace. Přečtěte si [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_DefaultTextLanguage() override
```

## Poznámky


Příklad:
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DefaultTextLanguage(u"en-US");

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(loadOptions);

// Přidejte nový obdélníkový tvar s textem
System::SharedPtr<IAutoShape> shp = pres->get_Slide(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 50.0f, 50.0f, 150.0f, 50.0f);
shp->get_TextFrame()->set_Text(u"New Text");

// Zkontrolujte jazyk první části
System::SharedPtr<IPortion> portion = shp->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
System::Console::WriteLine(portion->get_PortionFormat()->get_LanguageId());
```

## Viz také

* Třída [String](../../../system/string/)
* Třída [LoadOptions](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)