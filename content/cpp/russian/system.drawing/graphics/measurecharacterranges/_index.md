---
title: MeasureCharacterRanges()
second_title: Aspose.Slides для справки API C++
description: Возвращает массив областей, каждая из которых ограничивает позиции символов в указанной строке.
type: docs
weight: 508
url: /ru/system.drawing/graphics/measurecharacterranges/
---
## Graphics::MeasureCharacterRanges(const System::String&, const SharedPtr<Font>&, RectangleF, const SharedPtr<StringFormat>&) метод

Возвращает массив областей, каждая из которых ограничивает позиции символов в указанной строке.

```cpp
ArrayPtr<SharedPtr<Region>> System::Drawing::Graphics::MeasureCharacterRanges(const System::String &text, const SharedPtr<Font> &font, RectangleF layoutRect, const SharedPtr<StringFormat> &stringFormat)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)& | Строка для измерения |
| font | const [SharedPtr](../../../system/sharedptr/)<[Font](../../font/)>& | Шрифт, используемый при измерении строки |
| layoutRect | [RectangleF](../../rectanglef/) | Прямоугольник макета, используемый при измерении строки |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)<[StringFormat](../../stringformat/)>& | Формат строки, содержащий диапазоны символов для измерения |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Region](../../region/)
* Класс [String](../../../system/string/)
* Класс [Font](../../font/)
* Класс [RectangleF](../../rectanglef/)
* Класс [StringFormat](../../stringformat/)
* Класс [Graphics](../)
* Пространство имён [System::Drawing](../../)
* Библиотека [Aspose.Slides](../../../)