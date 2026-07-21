---
title: get_JpegQuality()
second_title: Aspose.Slides для C++ API Справка
description: Возвращает значение, определяющее качество изображений JPEG внутри PDF-документа. Читает uint8_t.
type: docs
weight: 222
url: /ru/aspose.slides.export/pdfoptions/get_jpegquality/
---
## PdfOptions::get_JpegQuality() метод

Возвращает значение, определяющее качество изображений JPEG внутри PDF-документа. Читает **uint8_t**.

```cpp
uint8_t Aspose::Slides::Export::PdfOptions::get_JpegQuality() override
```

## Примечания

Действует только когда документ содержит изображения JPEG.

Используйте это свойство, чтобы получить или задать качество изображений внутри документа при сохранении в формате PDF. Значение может варьироваться от 0 до 100, где 0 означает наихудшее качество, но максимальное сжатие, а 100 — лучшее качество, но минимальное сжатие.

Значение по умолчанию — **100**.

## См. также

* Класс [PdfOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)