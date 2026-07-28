---
title: set_DisableFontLigatures()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Ustawia wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. Gdy ustawione na true, ligatury będą wyłączone w renderowanym wyjściu. Domyślnie ta właściwość jest ustawiona na false.
type: docs
weight: 105
url: /pl/aspose.slides.export/htmloptions/set_disablefontligatures/
---
## HtmlOptions::set_DisableFontLigatures(bool) metoda

Ustawia wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. Gdy ustawione na **true**, ligatury będą wyłączone w renderowanym wyjściu. Domyślnie ta właściwość jest ustawiona na **false**.

```cpp
void Aspose::Slides::Export::HtmlOptions::set_DisableFontLigatures(bool value) override
```

## Uwagi

Przykład:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // Wyłącz ligatury w renderowaniu tekstu

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## Zobacz także

* Klasa [HtmlOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)