---
title: get_SpellCheck()
second_title: Aspose.Slides voor C++ API-referentie
description: Geeft een waarde die aangeeft of spellingcontrole is ingeschakeld voor het tekstgedeelte. Wanneer deze eigenschap op false is ingesteld, worden spellingcontroles voor textelementen onderdrukt. Wanneer deze op true is ingesteld, is spellingcontrole toegestaan. Standaardwaarde is false.
type: docs
weight: 599
url: /nl/aspose.slides/baseportionformat/get_spellcheck/
---
## BasePortionFormat::get_SpellCheck() methode


Geeft een waarde die aangeeft of spellingcontrole is ingeschakeld voor het tekstgedeelte. Wanneer deze eigenschap op false is ingesteld, worden spellingcontroles voor textelementen onderdrukt. Wanneer deze op true is ingesteld, is spellingcontrole toegestaan. Standaardwaarde is **false**.

```cpp
bool Aspose::Slides::BasePortionFormat::get_SpellCheck() override
```

## Opmerkingen


Het volgende voorbeeld laat zien hoe de SpellCheck-vlag wordt ingeschakeld vóór het opslaan van de presentatie: 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Toegang tot het eerste tekstgedeelte binnen de eerste vorm op de eerste dia
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Schakel spellingcontrole in voor dit tekstgedeelte
portion->get_PortionFormat()->set_SpellCheck(true);
// Sla de gewijzigde presentatie op
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Zie ook

* Klasse [BasePortionFormat](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)