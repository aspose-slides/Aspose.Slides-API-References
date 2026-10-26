---
title: save_metafiles_as_png property
second_title: Aspose.Slides dla Pythona przy użyciu .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.export/ipdfoptions/save_metafiles_as_png/
weight: 190
---
## save_metafiles_as_png właściwość
True, aby przekonwertować wszystkie metafile użyte w prezentacji na obrazy PNG.
            Odczyt/zapis **bool**.

### Uwagi

Default is **true** .
            Dokument Pdf może zawierać grafikę wektorową i obrazy rastrowe. 
            Jeśli SaveMetafilesAsPng jest ustawione na true, wtedy źródłowy Metafile 
            obraz jest konwertowany do formatu Png i zapisywany w Pdf jako obraz rastrowy 
            obraz. Jeśli SaveMetafilesAsPng jest ustawione na false, wtedy źródłowy Metafile 
            jest konwertowany do grafiki wektorowej Pdf. Każde podejście ma zalety 
            i wady. Na przykład, jeśli Metafile jest konwertowany do PNG, 
            wtedy możliwe jest pewne utracenie jakości podczas skalowania 
            wynikowego dokumentu. Jeśli Metafile jest konwertowany do grafiki wektorowej Pdf, 
            wtedy możliwe są problemy z wydajnością w narzędziu do przeglądania Pdf.

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
* klasa [`IPdfOptions`](/slides/python-net/pl/aspose.slides.export/ipdfoptions)
* moduł [`aspose.slides.export`](/slides/python-net/pl/aspose.slides.export)
* biblioteka [`Aspose.Slides`](/slides/python-net)