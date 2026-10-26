---
title: ImageFlags
second_title: Справочник API Aspose.Slides для C++
description: Представляет атрибуты пиксельных данных, представленных объектом Image.
type: docs
weight: 274
url: /ru/system.drawing.imaging/imageflags/
---
## ImageFlags enum

Представляет атрибуты пиксельных данных, представленных объектом [Image](../../system.drawing/image/).

```cpp
enum class ImageFlags
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| None | 0 |  |
| Scalable | 1 | Масштабируемый. |
| HasAlpha | 2 | Содержит альфа-информацию. |
| HasTranslucent | 4 | Есть альфа-значения больше 0 и меньше 255. |
| PartiallyScalable | 8 |  |
| ColorSpaceRgb | 16 | Пиксельные данные представлены в цветовом пространстве RGB. |
| ColorSpaceCmyk | 32 | Пиксельные данные представлены в цветовом пространстве CMYK. |
| ColorSpaceGray | 64 | Пиксельные данные в градациях серого. |
| ColorSpaceYcbcr | 128 | Пиксельные данные представлены в цветовом пространстве YCBCR. |
| ColorSpaceYcck | 256 | Пиксельные данные представлены в цветовом пространстве YCCK. |
| HasRealDpi | 4096 | Информация о DPI хранится в изображении. |
| HasRealPixelSize | 8192 | Размер пикселя хранится в изображении. |
| ReadOnly | 65536 | Пиксельные данные только для чтения. |
| Caching | 131072 | Можно кэшировать для более быстрого доступа. |

## См. также

* Пространство имён [System::Drawing::Imaging](../)
* Библиотека [Aspose.Slides](../../)