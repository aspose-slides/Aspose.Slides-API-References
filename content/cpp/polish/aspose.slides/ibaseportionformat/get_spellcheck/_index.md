---
title: get_SpellCheck()
second_title: Aspose.Slides dla referencji API C++
description: Pobiera wartość wskazującą, czy sprawdzanie pisowni jest włączone dla części tekstu. Gdy ta właściwość jest ustawiona na false, sprawdzanie pisowni elementów tekstowych jest pomijane. Gdy jest ustawiona na true, sprawdzanie pisowni jest dozwolone. Domyślna wartość to false.
type: docs
weight: 599
url: /pl/aspose.slides/ibaseportionformat/get_spellcheck/
---
## IBasePortionFormat::get_SpellCheck() metoda

Pobiera wartość wskazującą, czy sprawdzanie pisowni jest włączone dla części tekstu. Gdy ta właściwość jest ustawiona na false, sprawdzanie pisowni elementów tekstowych jest pomijane. Gdy jest ustawiona na true, sprawdzanie pisowni jest dozwolone. Domyślna wartość to **false**.

```cpp
virtual bool Aspose::Slides::IBasePortionFormat::get_SpellCheck()=0
```

## Uwagi

Następny przykład demonstruje włączanie flagi SpellCheck przed zapisaniem prezentacji:
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Uzyskaj pierwszą część tekstu wewnątrz pierwszego kształtu na pierwszym slajdzie
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Włącz sprawdzanie pisowni dla tej części tekstu
portion->get_PortionFormat()->set_SpellCheck(true);
// Zapisz zmodyfikowaną prezentację
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Klasa [IBasePortionFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)