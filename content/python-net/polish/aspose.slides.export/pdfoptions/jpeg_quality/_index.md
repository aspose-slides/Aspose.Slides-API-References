---
title: jpeg_quality property
second_title: Aspose.Slides dla Pythona poprzez .NET API Reference
description: 
type: docs
url: /pl/aspose.slides.export/pdfoptions/jpeg_quality/
weight: 160
---
## Właściwość jpeg_quality
Zwraca lub ustawia wartość określającą jakość obrazów JPEG wewnątrz dokumentu PDF.
            Odczyt/zapis **int**.

### Uwagi

Ma wpływ tylko wtedy, gdy dokument zawiera obrazy JPEG.

Użyj tej właściwości, aby pobrać lub ustawić jakość obrazów wewnątrz dokumentu przy zapisie w formacie PDF.
            Wartość może wynosić od 0 do 100, gdzie 0 oznacza najgorszą jakość, ale maksymalną kompresję, a 100 oznacza najlepszą jakość, ale minimalną kompresję.

Domyślna wartość to **100** .

### Definicja:
```python
@property
def jpeg_quality(self):
    ...

@jpeg_quality.setter
def jpeg_quality(self, value):
    ...
```

### Zobacz także
* klasa [`PdfOptions`](/slides/python-net/pl/aspose.slides.export/pdfoptions)
* moduł [`aspose.slides.export`](/slides/python-net/pl/aspose.slides.export)
* biblioteka [`Aspose.Slides`](/slides/python-net)