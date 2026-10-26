---
title: jpeg_quality property
second_title: Aspose.Slides dla Pythona przez .NET Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.export/ihtmloptions/jpeg_quality/
weight: 80
---
## jpeg_quality właściwość
Zwraca lub ustawia wartość określającą jakość obrazów JPEG w dokumencie PDF.
            Odczyt/zapis **int**.


### Uwagi

Ma wpływ tylko wtedy, gdy dokument zawiera obrazy JPEG.


Użyj tej właściwości, aby pobrać lub ustawić jakość obrazów w dokumencie podczas zapisywania w formacie PDF.
            Wartość może wynosić od 0 do 100, gdzie 0 oznacza najgorszą jakość, ale maksymalną kompresję, a 100 oznacza najlepszą jakość, ale minimalną kompresję.


Domyślna wartość to **95** .

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
* klasa [`IHtmlOptions`](/slides/python-net/pl/aspose.slides.export/ihtmloptions)
* moduł [`aspose.slides.export`](/slides/python-net/pl/aspose.slides.export)
* biblioteka [`Aspose.Slides`](/slides/python-net)