---
title: set_SpellCheck()
second_title: Aspose.Slides dla C++ – Referencja API
description: Ustawia wartość wskazującą, czy sprawdzanie pisowni jest włączone dla fragmentu tekstu. Gdy ta właściwość ma wartość false, sprawdzanie pisowni elementów tekstowych jest pomijane. Gdy ma wartość true, sprawdzanie pisowni jest dozwolone. Domyślna wartość to false.
type: docs
weight: 612
url: /pl/aspose.slides/baseportionformat/set_spellcheck/
---
## BasePortionFormat::set_SpellCheck(bool) metoda

Ustawia wartość wskazującą, czy sprawdzanie pisowni jest włączone dla fragmentu tekstu. Gdy ta właściwość ma wartość false, sprawdzanie pisowni dla elementów tekstowych jest pomijane. Gdy ma wartość true, sprawdzanie pisowni jest dozwolone. Domyślna wartość to **false**.

```cpp
void Aspose::Slides::BasePortionFormat::set_SpellCheck(bool value) override
```

## Uwagi

Następny przykład pokazuje włączanie flagi SpellCheck przed zapisaniem prezentacji:
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Uzyskaj pierwszy fragment tekstu wewnątrz pierwszego kształtu na pierwszym slajdzie
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Włącz sprawdzanie pisowni dla tego fragmentu tekstu
portion->get_PortionFormat()->set_SpellCheck(true);
// Zapisz zmodyfikowaną prezentację
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Klasa [BasePortionFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)