---
title: get_SpellCheck()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt een waarde op die aangeeft of spellingscontrole is ingeschakeld voor het tekstgedeelte. Wanneer deze eigenschap is ingesteld op false, worden spellingcontroles voor textelementen onderdrukt. Wanneer deze is ingesteld op true, is spellingscontrole toegestaan. Standaardwaarde is false.
type: docs
weight: 599
url: /nl/aspose.slides/ibaseportionformat/get_spellcheck/
---
## IBasePortionFormat::get_SpellCheck() methode


Retourneert een waarde die aangeeft of spellingscontrole is ingeschakeld voor het tekstgedeelte. Wanneer deze eigenschap is ingesteld op false, worden spellingcontroles voor textelementen onderdrukt. Wanneer ingesteld op true, is spellingscontrole toegestaan. Standaardwaarde is **false**.

```cpp
virtual bool Aspose::Slides::IBasePortionFormat::get_SpellCheck()=0
```

## Opmerkingen


Het volgende voorbeeld toont het inschakelen van de SpellCheck flag vóór het opslaan van de presentatie: 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Toegang tot het eerste tekstgedeelte binnen de eerste vorm op de eerste dia
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Schakel spellingscontrole in voor dit tekstgedeelte
portion->get_PortionFormat()->set_SpellCheck(true);
// Sla de gewijzigde presentatie op
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Zie ook

* Klasse [IBasePortionFormat](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)