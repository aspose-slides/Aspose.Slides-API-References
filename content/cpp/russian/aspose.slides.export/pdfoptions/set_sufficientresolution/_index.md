---
title: set_SufficientResolution()
second_title: Aspose.Slides для C++ API Reference
description: Устанавливает значение, определяющее разрешение изображений внутри PDF-документа.
type: docs
weight: 365
url: /ru/aspose.slides.export/pdfoptions/set_sufficientresolution/
---
## PdfOptions::set_SufficientResolution(float) метод

Устанавливает значение, определяющее разрешение изображений внутри PDF-документа.

```cpp
void Aspose::Slides::Export::PdfOptions::set_SufficientResolution(float value) override
```

## Примечание

Свойство влияет на размер файла, время экспорта и качество изображения.

Значение по умолчанию — **96**.

Эффект этого параметра зависит от нескольких факторов. Алгоритм пытается получить наилучший размер итогового изображения в соответствии со значением свойства, размером исходного изображения и размером рамки изображения. Использование схожих значений свойства может дать одинаковый результат. Рекомендуется использовать шаг 16 или 32 для заметного эффекта.

Записать **float**. 
## См. также

* Класс [PdfOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)