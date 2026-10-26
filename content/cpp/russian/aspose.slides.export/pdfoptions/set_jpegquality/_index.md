---
title: set_JpegQuality()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает значение, определяющее качество JPEG-изображений внутри PDF-документа. Запишите uint8_t.
type: docs
weight: 235
url: /ru/aspose.slides.export/pdfoptions/set_jpegquality/
---
## PdfOptions::set_JpegQuality(uint8_t) method

Устанавливает значение, определяющее качество JPEG-изображений внутри PDF-документа. Запишите **uint8_t**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_JpegQuality(uint8_t value) override
```

## Примечания

Имеет эффект только когда документ содержит JPEG-изображения.

Используйте это свойство, чтобы получить или установить качество изображений внутри документа при сохранении в формате PDF. Значение может варьироваться от 0 до 100, где 0 означает наихудшее качество, но максимальное сжатие, а 100 — наилучшее качество, но минимальное сжатие.

Значение по умолчанию — **100**.
## См. также

* Class [PdfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)