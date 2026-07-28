---
title: set_DisableFontLigatures()
second_title: Odwołanie do API Aspose.Slides dla C++
description: Ustawia wartość określającą, czy tekst jest renderowany bez użycia ligatur. Gdy ustawione na true, ligatury będą wyłączone w renderowanym wyniku. Domyślnie ta właściwość jest ustawiona na false.
type: docs
weight: 339
url: /pl/aspose.slides.export/isvgoptions/set_disablefontligatures/
---
## ISVGOptions::set_DisableFontLigatures(bool) metoda

Ustawia wartość określającą, czy tekst jest renderowany bez użycia ligatur. Gdy ustawione na **true**, ligatury będą wyłączone w renderowanym wyniku. Domyślnie ta właściwość jest ustawiona na **false**.

```cpp
virtual void Aspose::Slides::Export::ISVGOptions::set_DisableFontLigatures(bool value)=0
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