---
title: get_JpegQuality()
second_title: Aspose.Slides для C++: справочник API
description: Возвращает значение, определяющее качество JPEG-изображений внутри PDF-документа. Читает uint8_t.
type: docs
weight: 144
url: /ru/aspose.slides.export/htmloptions/get_jpegquality/
---
## HtmlOptions::get_JpegQuality() метод


Возвращает значение, определяющее качество JPEG-изображений внутри PDF-документа. Читает **uint8_t**.

```cpp
uint8_t Aspose::Slides::Export::HtmlOptions::get_JpegQuality() override
```

## Примечания


Действует только когда документ содержит JPEG-изображения.

Используйте это свойство, чтобы получить или установить качество изображений внутри документа при сохранении в формате PDF. Значение может варьироваться от 0 до 100, где 0 означает худшее качество, но максимальное сжатие, а 100 — лучшее качество, но минимальное сжатие.

Значение по умолчанию — **95**.
## См. также

* Класс [HtmlOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)