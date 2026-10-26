---
title: MeasureString()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает размер указанной строки при отрисовке её указанным шрифтом в указанном формате.
type: docs
weight: 521
url: /ru/system.drawing/graphics/measurestring/
---
## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, PointF const\&, System::SharedPtr\<StringFormat\> const\&) const method

Возвращает размер указанной строки при отрисовке её указанным шрифтом в указанном формате.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, PointF const &origin=PointF(0, 0), System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | Строка, размер которой нужно вычислить |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | Шрифт, используемый для отрисовки строки |
| origin | [PointF](../../pointf/) const\& | Указывает положение верхнего левого угла строки |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Указывает формат строки |

### Возвращаемое значение

Объект [SizeF](../../sizef/), представляющий размер строки в единицах измерения, указанных свойством PageUnit текущего объекта Grapphics.

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, int, System::SharedPtr\<StringFormat\> const\&) const method

Возвращает размер указанной строки при отрисовке её указанным шрифтом в указанном формате.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, int width, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | Строка, размер которой нужно вычислить |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | Шрифт, используемый для отрисовки строки |
| width | int | Максимальная ширина строки |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Указывает формат строки |

### Возвращаемое значение

Объект [SizeF](../../sizef/), представляющий размер строки в единицах измерения, указанных свойством PageUnit текущего объекта Grapphics.

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&, int\&, int\&) const method

НЕ РЕАЛИЗОВАНО.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat, int &charactersFitted, int &linesFilled) const
```

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&) const method

Возвращает размер указанной строки при отрисовке её указанным шрифтом в указанном формате.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | Строка, размер которой нужно вычислить |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | Шрифт, используемый для отрисовки строки |
| layoutArea | [SizeF](../../sizef/) const\& | Максимальная область размещения строки |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Указывает формат строки |

### Возвращаемое значение

Объект [SizeF](../../sizef/), представляющий размер строки в единицах измерения, указанных свойством PageUnit текущего объекта Grapphics.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [SizeF](../../sizef/)
* Класс [String](../../../system/string/)
* Класс [Font](../../font/)
* Класс [PointF](../../pointf/)
* Класс [StringFormat](../../stringformat/)
* Класс [Graphics](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)