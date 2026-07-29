---
title: get_SpellCheck()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar ett värde som indikerar om stavningskontroll är aktiverad för textdelen. När den här egenskapen är satt till false, undertrycks stavningskontroller för textelement. När den är satt till true, tillåts stavningskontroll. Standardvärdet är false.
type: docs
weight: 599
url: /sv/aspose.slides/ibaseportionformat/get_spellcheck/
---
## IBasePortionFormat::get_SpellCheck() metod

Hämtar ett värde som indikerar om stavningskontroll är aktiverad för textdelen. När den här egenskapen är satt till false undertrycks stavningskontroller för textelement. När den är satt till true tillåts stavningskontroll. Standardvärdet är **false**.

```cpp
virtual bool Aspose::Slides::IBasePortionFormat::get_SpellCheck()=0
```

## Anmärkningar

Nästa exempel visar hur man aktiverar SpellCheck flagga innan presentationen sparas:
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Åtkomst till den första textdelen i den första formen på den första bilden
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Aktivera stavningskontroll för den här textdelen
portion->get_PortionFormat()->set_SpellCheck(true);
// Spara den ändrade presentationen
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Se också

* Klass [IBasePortionFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)