---
title: DrawString()
second_title: Справочник API Aspose.Slides для C++
description: Рисует указанную строку в указанном месте, используя указанный шрифт и кисть.
type: docs
weight: 365
url: /ru/system.drawing/graphics/drawstring/
---
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, PointF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) method

Рисует указанную строку в указанном месте, используя указанный шрифт и кисть.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, PointF topLeft, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Строка для рисования |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Шрифт для использования |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Объект [Brush](../../brush/) для рисования |
| topLeft | [PointF](../../pointf/) | Указывает расположение верхнего левого угла рисуемой строки |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Указывает формат строки |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, RectangleF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) method

Рисует указанную строку в указанном прямоугольнике, используя указанный шрифт и кисть.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, RectangleF layoutRectangle, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Строка для рисования |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Шрифт для использования |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Объект [Brush](../../brush/) для рисования |
| layoutRectangle | [RectangleF](../../rectanglef/) | Указывает прямоугольник, в котором будет рисоваться строка |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Указывает формат строки |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, float, float, const System::SharedPtr\<System::Drawing::StringFormat\>\&) method

Рисует указанную строку в указанном месте, используя указанный шрифт и кисть.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, float x, float y, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Строка для рисования |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Шрифт для использования |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Объект [Brush](../../brush/) для рисования |
| x | **float** | Координата X расположения верхнего левого угла рисуемой строки |
| y | **float** | Координата Y расположения верхнего левого угла рисуемой строки |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Указывает формат строки |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Font](../../font/)
* Class [Brush](../../brush/)
* Class [PointF](../../pointf/)
* Class [StringFormat](../../stringformat/)
* Class [Graphics](../)
* Class [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)