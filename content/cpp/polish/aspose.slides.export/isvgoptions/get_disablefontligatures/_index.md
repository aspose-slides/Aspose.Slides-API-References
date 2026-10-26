---
title: get_DisableFontLigatures()
second_title: Dokumentacja API Aspose.Slides dla C++
description: Zwraca wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. Gdy ustawiono na true, ligatury będą wyłączone w wyniku renderowania. Domyślnie ta właściwość ma wartość false.
type: docs
weight: 326
url: /pl/aspose.slides.export/isvgoptions/get_disablefontligatures/
---
## ISVGOptions::get_DisableFontLigatures() metoda


Zwraca wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. Gdy ustawiono **true**, ligatury będą wyłączone w wyniku renderowania. Domyślnie ta właściwość ma wartość **false**.

```cpp
virtual bool Aspose::Slides::Export::ISVGOptions::get_DisableFontLigatures()=0
```

## Uwagi


Przykład: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // Wyłącz ligatury w renderowaniu tekstu

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Zobacz także

* Klasa [ISVGOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)