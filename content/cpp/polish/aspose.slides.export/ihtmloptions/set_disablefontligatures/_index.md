---
title: set_DisableFontLigatures()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Ustawia wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. Gdy ustawiona na true, ligatury zostaną wyłączone w renderowanym wyjściu. Domyślnie, ta właściwość jest ustawiona na false.
type: docs
weight: 196
url: /pl/aspose.slides.export/ihtmloptions/set_disablefontligatures/
---
## IHtmlOptions::set_DisableFontLigatures(bool) metoda


Ustawia wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. Gdy ustawiono na **true**, ligatury zostaną wyłączone w renderowanym wyjściu. Domyślnie, ta właściwość jest ustawiona na **false**.

```cpp
virtual void Aspose::Slides::Export::IHtmlOptions::set_DisableFontLigatures(bool value)=0
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

* Klasa [IHtmlOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)