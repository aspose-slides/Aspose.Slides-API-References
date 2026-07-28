---
title: set_DisableFontLigatures()
second_title: Aspose.Slides – odniesienie API dla C++
description: Ustawia wartość określającą, czy tekst jest renderowany bez użycia ligatur. Gdy ustawione na true, ligatury będą wyłączone w renderowanym wyjściu. Domyślnie, ta właściwość jest ustawiona na false.
type: docs
weight: 339
url: /pl/aspose.slides.export/svgoptions/set_disablefontligatures/
---
## SVGOptions::set_DisableFontLigatures(bool) metoda


Ustawia wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. Gdy ustawione na **true**, ligatury będą wyłączone w renderowanym wyjściu. Domyślnie, ta właściwość jest ustawiona na **false**.

```cpp
void Aspose::Slides::Export::SVGOptions::set_DisableFontLigatures(bool value) override
```

## Uwagi


Przykład: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // Wyłącz ligatury przy renderowaniu tekstu

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Zobacz także

* Klasa [SVGOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)