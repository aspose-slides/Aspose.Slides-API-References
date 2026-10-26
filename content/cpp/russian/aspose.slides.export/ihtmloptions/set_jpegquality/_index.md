---
title: set_JpegQuality()
second_title: Aspose.Slides для C++ справочник API
description: Устанавливает значение, определяющее качество JPEG-изображений в документе PDF. Запишите uint8_t.
type: docs
weight: 92
url: /ru/aspose.slides.export/ihtmloptions/set_jpegquality/
---
## IHtmlOptions::set_JpegQuality(uint8_t) method


Устанавливает значение, определяющее качество JPEG-изображений в документе PDF. Запишите **uint8_t**.

```cpp
virtual void Aspose::Slides::Export::IHtmlOptions::set_JpegQuality(uint8_t value)=0
```

## Примечания


Действует только тогда, когда документ содержит JPEG-изображения.

Используйте это свойство для получения или установки качества изображений внутри документа при сохранении в формате PDF. Значение может варьироваться от 0 до 100, где 0 означает худшее качество, но максимальное сжатие, а 100 — лучшее качество, но минимальное сжатие.

Значение по умолчанию — **95**.

## См. также

* Класс [IHtmlOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)