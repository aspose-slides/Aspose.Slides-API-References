---
title: set_SaveMetafilesAsPng()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Ustaw true, aby przekonwertować wszystkie metafile użyte w prezentacji na obrazy PNG. Zapisz bool.
type: docs
weight: 300
url: /pl/aspose.slides.export/ipdfoptions/set_savemetafilesaspng/
---
## IPdfOptions::set_SaveMetafilesAsPng(bool) metoda

Ustaw true, aby przekonwertować wszystkie metafile użyte w prezentacji na obrazy PNG. Zapisz **bool**.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_SaveMetafilesAsPng(bool value)=0
```

## Uwagi

Domyślnie jest **true**. Dokument Pdf może zawierać grafikę wektorową i obrazy rastrowe. Jeśli SaveMetafilesAsPng jest ustawione na true, to źródłowy obraz Metafile jest konwertowany do formatu Png i zapisywany w Pdf jako obraz rastrowy. Jeśli SaveMetafilesAsPng jest ustawione na false, to źródłowy Metafile jest konwertowany do grafiki wektorowej Pdf. Każde podejście ma swoje zalety i wady. Na przykład, jeśli Metafile jest konwertowany do PNG, możliwa jest pewna utrata jakości podczas skalowania powstałego dokumentu. Jeśli Metafile jest konwertowany do grafiki wektorowej Pdf, możliwe są problemy z wydajnością w narzędziu do przeglądania Pdf.

## Zobacz także

* Klasa [IPdfOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)