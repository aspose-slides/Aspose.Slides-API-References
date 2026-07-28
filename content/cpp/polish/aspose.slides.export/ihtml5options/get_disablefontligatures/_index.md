---
title: get_DisableFontLigatures()
second_title: Aspose.Slides for C++ – Dokumentacja API
description: Zwraca wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. Gdy ustawione na true, ligatury zostaną wyłączone w renderowanym wyjściu. Domyślnie właściwość ma wartość false.
type: docs
weight: 131
url: /pl/aspose.slides.export/ihtml5options/get_disablefontligatures/
---
## IHtml5Options::get_DisableFontLigatures() metoda

Zwraca wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. Gdy ustawione na **true**, ligatury zostaną wyłączone w renderowanym rezultacie. Domyślnie ta właściwość ma wartość **false**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_DisableFontLigatures()=0
```

## Uwagi

Przykład:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // Wyłącz ligatury w renderowaniu tekstu

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## Zobacz także

* Klasa [IHtml5Options](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)