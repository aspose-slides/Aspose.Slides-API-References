---
title: get_SpellCheck()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce un valore che indica se il controllo ortografico è abilitato per la porzione di testo. Quando questa proprietà è impostata su false, i controlli ortografici per gli elementi di testo sono soppressi. Quando è impostata su true, il controllo ortografico è consentito. Il valore predefinito è false.
type: docs
weight: 599
url: /it/aspose.slides/baseportionformat/get_spellcheck/
---
## BasePortionFormat::get_SpellCheck() metodo


Restituisce un valore che indica se il controllo ortografico è abilitato per la porzione di testo. Quando questa proprietà è impostata su false, i controlli ortografici per gli elementi di testo sono soppressi. Quando è impostata su true, il controllo ortografico è consentito. Il valore predefinito è **false**.

```cpp
bool Aspose::Slides::BasePortionFormat::get_SpellCheck() override
```

## Osservazioni


Il prossimo esempio mostra come abilitare il flag SpellCheck prima di salvare la presentazione: 
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
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)