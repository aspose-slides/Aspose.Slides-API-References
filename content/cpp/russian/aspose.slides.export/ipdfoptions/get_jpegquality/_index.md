---
title: get_JpegQuality()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает значение, определяющее качество JPEG-изображений в PDF-документе. Читается uint8_t.
type: docs
weight: 183
url: /ru/aspose.slides.export/ipdfoptions/get_jpegquality/
---
## IPdfOptions::get_JpegQuality() метод

Возвращает значение, определяющее качество JPEG-изображений внутри PDF-документа. Читается **uint8_t**.

```cpp
virtual uint8_t Aspose::Slides::Export::IPdfOptions::get_JpegQuality()=0
```

## Примечания

Имеет эффект только когда документ содержит JPEG-изображения.

Используйте это свойство, чтобы получить или установить качество изображений внутри документа при сохранении в формате PDF. Значение может варьироваться от 0 до 100, где 0 означает худшее качество, но максимальное сжатие, а 100 — лучшее качество, но минимальное сжатие.

Значение по умолчанию — **100**.

## Смотрите также

* Класс [IPdfOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)