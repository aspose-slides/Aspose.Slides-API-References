---
title: set_SpellCheck()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Ustawia wartość wskazującą, czy sprawdzanie pisowni jest włączone dla fragmentu tekstu. Gdy ta właściwość jest ustawiona na false, sprawdzanie pisowni elementów tekstowych jest pomijane. Gdy jest ustawiona na true, sprawdzanie pisowni jest dozwolone. Domyślna wartość to false.
type: docs
weight: 612
url: /pl/aspose.slides/ibaseportionformat/set_spellcheck/
---
## IBasePortionFormat::set_SpellCheck(bool) metoda


Ustawia wartość wskazującą, czy sprawdzanie pisowni jest włączone dla fragmentu tekstu. Gdy ta właściwość jest ustawiona na false, sprawdzanie pisowni elementów tekstowych jest pomijane. Gdy jest ustawiona na true, sprawdzanie pisowni jest dozwolone. Domyślna wartość to **false**.

```cpp
virtual void Aspose::Slides::IBasePortionFormat::set_SpellCheck(bool value)=0
```

## Uwagi


Następny przykład demonstruje włączenie flagi SpellCheck przed zapisaniem prezentacji: 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Access the first portion of text inside the first shape on the first slide
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Enable spell checking for this text portion
portion->get_PortionFormat()->set_SpellCheck(true);
// Save the modified presentation
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Klasa [IBasePortionFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)