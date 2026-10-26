---
title: get_SaveMetafilesAsPng()
second_title: Aspose.Slides dla C++ – referencja API
description: True aby konwertować wszystkie metafile użyte w prezentacji na obrazy PNG. Odczytaj bool.
type: docs
weight: 326
url: /pl/aspose.slides.export/pdfoptions/get_savemetafilesaspng/
---
## PdfOptions::get_SaveMetafilesAsPng() metoda

True aby konwertować wszystkie metafile użyte w prezentacji na obrazy PNG. Odczytaj **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_SaveMetafilesAsPng() override
```

## Uwagi

Domyślnie jest **true**. Dokument Pdf może zawierać grafikę wektorową i obrazy rastrowe. Jeśli SaveMetafilesAsPng jest ustawione na true, to obraz źródłowy Metafile jest konwertowany do formatu Png i zapisywany w Pdf jako obraz rastrowy. Jeśli SaveMetafilesAsPng jest ustawione na false, to źródłowy Metafile jest konwertowany na grafikę wektorową Pdf. Każde podejście ma zalety i wady. Na przykład, jeśli Metafile jest konwertowany do PNG, możliwa jest pewna utrata jakości podczas skalowania powstałego dokumentu. Jeśli Metafile jest konwertowany na grafikę wektorową Pdf, możliwe są problemy z wydajnością w narzędziu do przeglądania Pdf.

## Zobacz także

* Klasa [PdfOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)