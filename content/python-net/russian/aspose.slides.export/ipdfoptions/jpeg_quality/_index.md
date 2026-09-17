---
title: jpeg_quality property
second_title: Aspose.Slides для Python через .NET API
description: 
type: docs
url: /ru/aspose.slides.export/ipdfoptions/jpeg_quality/
weight: 150
---
## jpeg_quality свойство
Возвращает или задает значение, определяющее качество JPEG-изображений внутри PDF-документа.
            Чтение/запись **int**.


### Примечания

Имеет эффект только когда документ содержит изображения JPEG.


Используйте это свойство, чтобы получать или задавать качество изображений внутри документа при сохранении в формате PDF.
            Значение может варьироваться от 0 до 100, где 0 означает наихудшее качество, но максимальное сжатие, а 100 — лучшее качество, но минимальное сжатие.


Значение по умолчанию — **100** .

### Определение:
```python
@property
def jpeg_quality(self):
    ...

@jpeg_quality.setter
def jpeg_quality(self, value):
    ...
```


### См. также
* класс [`IPdfOptions`](/slides/python-net/ru/aspose.slides.export/ipdfoptions)
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)