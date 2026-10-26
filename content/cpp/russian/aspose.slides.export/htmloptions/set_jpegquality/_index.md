---
title: set_JpegQuality()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает значение, определяющее качество JPEG-изображений внутри PDF-документа. Записывайте uint8_t.
type: docs
weight: 157
url: /ru/aspose.slides.export/htmloptions/set_jpegquality/
---
## HtmlOptions::set_JpegQuality(uint8_t) метод

Устанавливает значение, определяющее качество JPEG-изображений внутри PDF-документа. Записывайте **uint8_t**.

```cpp
void Aspose::Slides::Export::HtmlOptions::set_JpegQuality(uint8_t value) override
```

## Примечания

Действует только когда документ содержит JPEG-изображения.

Используйте это свойство для получения или установки качества изображений внутри документа при сохранении в формате PDF. Значение может варьироваться от 0 до 100, где 0 означает наихудшее качество, но максимальное сжатие, а 100 — лучшее качество, но минимальное сжатие.

Значение по умолчанию — **95**.

## См. также

* Класс [HtmlOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)