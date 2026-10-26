---
title: get_JpegQuality()
second_title: Aspose.Slides для C++ справка по API
description: Возвращает значение, определяющее качество JPEG-изображений внутри PDF-документа. Читает uint8_t.
type: docs
weight: 79
url: /ru/aspose.slides.export/ihtmloptions/get_jpegquality/
---
## IHtmlOptions::get_JpegQuality() метод

Возвращает значение, определяющее качество JPEG-изображений внутри PDF-документа. Читает **uint8_t**.

```cpp
virtual uint8_t Aspose::Slides::Export::IHtmlOptions::get_JpegQuality()=0
```

## Примечания

Оказывает влияние только когда документ содержит JPEG-изображения.

Используйте это свойство, чтобы получить или установить качество изображений внутри документа при сохранении в формате PDF. Значение может изменяться от 0 до 100, где 0 означает худшее качество, но максимальное сжатие, а 100 — лучшее качество, но минимальное сжатие.

Значение по умолчанию — **95**.
## См. также

* Класс [IHtmlOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)