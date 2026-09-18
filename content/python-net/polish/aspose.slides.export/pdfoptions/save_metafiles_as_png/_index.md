---
title: save_metafiles_as_png property
second_title: Aspose.Slides dla Pythona przez .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides.export/pdfoptions/save_metafiles_as_png/
weight: 200
---
## save_metafiles_as_png właściwość
True, aby przekonwertować wszystkie metafile użyte w prezentacji na obrazy PNG.
Odczyt/zapis **bool**.

### Uwagi

Domyślnie jest **true**.
Dokument PDF może zawierać grafikę wektorową i obrazy rastrowe.
Jeśli SaveMetafilesAsPng jest ustawione na true, to obraz źródłowego Metafile jest konwertowany do formatu Png i zapisywany w Pdf jako obraz rastrowy. Jeśli SaveMetafilesAsPng jest ustawione na false, to źródłowy Metafile jest konwertowany na grafikę wektorową Pdf. Każde podejście ma zalety i wady. Na przykład, jeśli Metafile jest konwertowany do PNG, możliwa jest pewna utrata jakości podczas skalowania powstałego dokumentu. Jeśli Metafile jest konwertowany do grafiki wektorowej Pdf, możliwe są problemy z wydajnością w przeglądarce Pdf.

### Definicja:
```python
@property
def save_metafiles_as_png(self):
    ...

@save_metafiles_as_png.setter
def save_metafiles_as_png(self, value):
    ...
```

### Zobacz także
* klasa [`PdfOptions`](/slides/python-net/pl/aspose.slides.export/pdfoptions)
* moduł [`aspose.slides.export`](/slides/python-net/pl/aspose.slides.export)
* biblioteka [`Aspose.Slides`](/slides/python-net)