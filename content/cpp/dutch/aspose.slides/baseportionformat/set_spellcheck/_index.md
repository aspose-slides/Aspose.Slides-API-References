---
title: set_SpellCheck()
second_title: Aspose.Slides for C++ API-referentie
description: Stelt een waarde in die aangeeft of spellingcontrole is ingeschakeld voor het tekstgedeelte. Wanneer deze eigenschap op false is ingesteld, worden spellingcontroles voor textelementen onderdrukt. Wanneer deze op true is ingesteld, is spellingcontrole toegestaan. Standaardwaarde is false.
type: docs
weight: 612
url: /nl/aspose.slides/baseportionformat/set_spellcheck/
---
## BasePortionFormat::set_SpellCheck(bool) methode

Stelt een waarde in die aangeeft of spellingcontrole is ingeschakeld voor het tekstgedeelte. Wanneer deze eigenschap is ingesteld op false, worden spellingcontroles voor textelementen onderdrukt. Wanneer deze is ingesteld op true, is spellingcontrole toegestaan. Standaardwaarde is **false**.

```cpp
void Aspose::Slides::BasePortionFormat::set_SpellCheck(bool value) override
```

## Opmerkingen

Het volgende voorbeeld toont het inschakelen van de SpellCheck-vlag vóór het opslaan van de presentatie:
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Toegang tot het eerste tekstgedeelte binnen de eerste vorm op de eerste dia
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Spellingcontrole inschakelen voor dit tekstgedeelte
portion->get_PortionFormat()->set_SpellCheck(true);
// De gewijzigde presentatie opslaan
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Zie ook

* Klasse [BasePortionFormat](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)