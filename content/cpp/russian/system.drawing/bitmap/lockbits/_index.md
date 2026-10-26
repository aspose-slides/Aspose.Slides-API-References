---
title: LockBits()
second_title: Справочник API Aspose.Slides для C++
description: Блокирует Bitmap в системной памяти.
type: docs
weight: 118
url: /ru/system.drawing/bitmap/lockbits/
---
## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat) метод

Блокирует [Bitmap](../) в системной памяти.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Прямоугольник, определяющий регион изображения для блокировки |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | Уровень доступа к битмапу |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Формат данных этого битмапа |

### Возвращаемое значение

Указатель разделяемого владения на объект BitmapData, содержащий информацию о выполненной операции блокировки

## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat, const Imaging::BitmapDataPtr\&) метод

Блокирует [Bitmap](../) в системной памяти.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format, const Imaging::BitmapDataPtr &bitmap_data)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Прямоугольник, определяющий регион изображения для блокировки |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | Уровень доступа к битмапу |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Формат данных этого битмапа |
| bitmap_data | const [Imaging::BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)\& | Содержит информацию об операции блокировки |

### Возвращаемое значение

Указатель разделяемого владения на объект BitmapData, содержащий информацию о выполненной операции блокировки

## См. также

* Enum [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)
* Class [Rectangle](../../rectangle/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)