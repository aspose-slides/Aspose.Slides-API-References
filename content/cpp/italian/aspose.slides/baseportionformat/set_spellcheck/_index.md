---
title: set_SpellCheck()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta un valore che indica se il controllo ortografico è abilitato per la porzione di testo. Quando questa proprietà è impostata su false, i controlli ortografici per gli elementi di testo sono soppressi. Quando è impostata su true, il controllo ortografico è consentito. Il valore predefinito è false.
type: docs
weight: 612
url: /it/aspose.slides/baseportionformat/set_spellcheck/
---
## BasePortionFormat::set_SpellCheck(bool) metodo


Imposta un valore che indica se il controllo ortografico è abilitato per la porzione di testo. Quando questa proprietà è impostata su false, i controlli ortografici per gli elementi di testo sono soppressi. Quando è impostata su true, il controllo ortografico è consentito. Il valore predefinito è **false**.

```cpp
void Aspose::Slides::BasePortionFormat::set_SpellCheck(bool value) override
```

## Osservazioni


Il prossimo esempio dimostra l'attivazione del flag SpellCheck prima di salvare la presentazione: 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Accedi alla prima porzione di testo all'interno della prima forma nella prima diapositiva
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Abilita il controllo ortografico per questa porzione di testo
portion->get_PortionFormat()->set_SpellCheck(true);
// Salva la presentazione modificata
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Classe [BasePortionFormat](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)