---
title: set_SpellCheck()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in ett värde som indikerar om stavningskontroll är aktiverad för textdelen. När denna egenskap är inställd på false, undertrycks stavningskontroller för tekstelement. När den är inställd på true, är stavningskontroll tillåten. Standardvärdet är false.
type: docs
weight: 612
url: /sv/aspose.slides/ibaseportionformat/set_spellcheck/
---
## IBasePortionFormat::set_SpellCheck(bool) metod

Ställer in ett värde som indikerar om stavningskontroll är aktiverad för textdelen. När denna egenskap är inställd på false, undertrycks stavningskontroller för tekstelement. När den är inställd på true, är stavningskontroll tillåten. Standardvärdet är **false**.

```cpp
virtual void Aspose::Slides::IBasePortionFormat::set_SpellCheck(bool value)=0
```

## Anmärkningar

Nästa exempel visar hur man aktiverar SpellCheck-flaggan innan presentationen sparas: 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Åtkomst till den första textdelen i den första formen på den första bilden
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Aktivera stavningskontroll för denna textdel
portion->get_PortionFormat()->set_SpellCheck(true);
// Spara den modifierade presentationen
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Se även

* Klass [IBasePortionFormat](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)