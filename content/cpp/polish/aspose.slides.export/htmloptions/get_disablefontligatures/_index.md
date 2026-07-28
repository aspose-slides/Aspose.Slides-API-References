---
title: get_DisableFontLigatures()
second_title: Aspose.Slides dla C++ Referencja API
description: Zwraca wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. Gdy ustawione na true, ligatury zostaną wyłączone w renderowanym wyjściu. Domyślnie ta właściwość jest ustawiona na false.
type: docs
weight: 92
url: /pl/aspose.slides.export/htmloptions/get_disablefontligatures/
---
## HtmlOptions::get_DisableFontLigatures() metoda


Zwraca wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. Gdy ustawione na **true**, ligatury zostaną wyłączone w renderowanym wyjściu. Domyślnie ta właściwość jest ustawiona na **false**.

```cpp
bool Aspose::Slides::Export::HtmlOptions::get_DisableFontLigatures() override
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