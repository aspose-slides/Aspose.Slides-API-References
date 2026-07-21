---
title: set_JpegQuality()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает значение, определяющее качество JPEG-изображений внутри PDF-документа. Записывает uint8_t.
type: docs
weight: 196
url: /ru/aspose.slides.export/ipdfoptions/set_jpegquality/
---
## IPdfOptions::set_JpegQuality(uint8_t) метод

Устанавливает значение, определяющее качество JPEG-изображений внутри PDF-документа. Записывает **uint8_t**.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_JpegQuality(uint8_t value)=0
```

## Примечания

Действует только в том случае, когда документ содержит JPEG-изображения.

Используйте это свойство, чтобы получить или установить качество изображений внутри документа при сохранении в формате PDF. Значение может варьироваться от 0 до 100, где 0 означает самое плохое качество, но максимальное сжатие, а 100 — лучшее качество, но минимальное сжатие.

Значение по умолчанию — **100**.

## См. также

* Класс [IPdfOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)