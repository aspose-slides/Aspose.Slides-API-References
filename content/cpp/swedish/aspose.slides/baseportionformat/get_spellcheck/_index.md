---
title: get_SpellCheck()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar ett värde som anger om stavningskontroll är aktiverad för textdelen. När denna egenskap är satt till false, undertrycks stavningskontroller för textelement. När den är satt till true, tillåts stavningskontroll. Standardvärdet är false.
type: docs
weight: 599
url: /sv/aspose.slides/baseportionformat/get_spellcheck/
---
## BasePortionFormat::get_SpellCheck() metod


Hämtar ett värde som anger om stavningskontroll är aktiverad för textdelen. När denna egenskap är satt till false, undertrycks stavningskontroller för textelement. När den är satt till true, tillåts stavningskontroll. Standardvärdet är **false**.

```cpp
bool Aspose::Slides::BasePortionFormat::get_SpellCheck() override
```

## Anmärkningar


Nästa exempel visar hur man aktiverar SpellCheck-flaggot innan presentationen sparas: 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Hämta den första textdelen i den första formen på den första bilden
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Aktivera stavningskontroll för denna textdel
portion->get_PortionFormat()->set_SpellCheck(true);
// Spara den ändrade presentationen
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Se även

* Klass [BasePortionFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)