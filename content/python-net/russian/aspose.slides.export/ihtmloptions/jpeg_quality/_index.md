---
title: jpeg_quality property
second_title: Aspose.Slides для Python через .NET Справка API
description: 
type: docs
url: /ru/aspose.slides.export/ihtmloptions/jpeg_quality/
weight: 80
---
## jpeg_quality свойство
Возвращает или задает значение, определяющее качество JPEG-изображений внутри PDF-документа.
            Чтение/запись **int**.

### Примечания

Имеет эффект только когда документ содержит JPEG-изображения.

Используйте это свойство для получения или установки качества изображений внутри документа при сохранении в формате PDF.
            Значение может варьироваться от 0 до 100, где 0 означает наихудшее качество, но максимальное сжатие, а 100 — лучшее качество, но минимальное сжатие.

Значение по умолчанию — **95** .

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
* класс [`IHtmlOptions`](/slides/python-net/ru/aspose.slides.export/ihtmloptions)
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)