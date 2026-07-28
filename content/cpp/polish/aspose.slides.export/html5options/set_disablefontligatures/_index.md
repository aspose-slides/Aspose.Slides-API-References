---
title: set_DisableFontLigatures()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Ustawia wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. Gdy ustawione na true, ligatury będą wyłączone w renderowanym wyjściu. Domyślnie ta właściwość jest ustawiona na false.
type: docs
weight: 144
url: /pl/aspose.slides.export/html5options/set_disablefontligatures/
---
## Html5Options::set_DisableFontLigatures(bool) metoda

Ustawia wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. Gdy ustawione na **true**, ligatury będą wyłączone w renderowanym wyjściu. Domyślnie ta właściwość jest ustawiona na **false**.

```cpp
void Aspose::Slides::Export::Html5Options::set_DisableFontLigatures(bool value) override
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

* Klasa [Html5Options](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)