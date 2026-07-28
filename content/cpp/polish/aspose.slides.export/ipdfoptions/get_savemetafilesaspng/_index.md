---
title: get_SaveMetafilesAsPng()
second_title: Aspose.Slides for C++ Dokumentacja API
description: True, aby konwertować wszystkie metafile użyte w prezentacji na obrazy PNG. Odczytuje bool.
type: docs
weight: 287
url: /pl/aspose.slides.export/ipdfoptions/get_savemetafilesaspng/
---
## IPdfOptions::get_SaveMetafilesAsPng() metoda

True, aby konwertować wszystkie metafile użyte w prezentacji na obrazy PNG. Odczytuje **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_SaveMetafilesAsPng()=0
```

## Uwagi

Domyślnie jest **true**. Dokument PDF może zawierać grafikę wektorową i obrazy rastrowe. Jeśli SaveMetafilesAsPng jest ustawione na true, to źródłowy obraz Metafile jest konwertowany na format Png i zapisywany w Pdf jako obraz rastrowy. Jeśli SaveMetafilesAsPng jest ustawione na false, to źródłowy Metafile jest konwertowany na grafikę wektorową Pdf. Każde podejście ma swoje zalety i wady. Na przykład, jeśli Metafile jest konwertowany na PNG, możliwe jest pewne utracenie jakości podczas skalowania powstałego dokumentu. Jeśli Metafile jest konwertowany na grafikę wektorową Pdf, możliwe są problemy z wydajnością w narzędziu do przeglądania PDF. 

## Zobacz także

* Klasa [IPdfOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)