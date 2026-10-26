---
title: jpeg_quality property
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides.export/pdfoptions/jpeg_quality/
weight: 160
---
## jpeg_quality свойство
Возвращает или задаёт значение, определяющее качество изображений JPEG внутри PDF-документа.
            Чтение/запись **int**.

### Примечания

Имеет эффект только когда документ содержит изображения JPEG.

Используйте это свойство, чтобы получить или установить качество изображений внутри документа при сохранении в формате PDF.
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
* класс [`PdfOptions`](/slides/python-net/ru/aspose.slides.export/pdfoptions)
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)