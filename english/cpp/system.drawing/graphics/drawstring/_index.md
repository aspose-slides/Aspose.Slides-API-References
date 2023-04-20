---
title: DrawString()
second_title: Aspose.Slides for C++ API Reference
description: Draws the specified string at the specified location using the specified font and brush.
type: docs
weight: 365
url: /cpp/system.drawing/graphics/drawstring/
---
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, PointF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) method


Draws the specified string at the specified location using the specified font and brush.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, PointF topLeft, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | The string to draw |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | A font to use |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | A [Brush](../../brush/) object to use for drawing |
| topLeft | [PointF](../../pointf/) | Specifies the location of the upper left corner of the drawn string |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Specified the format of the string |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, RectangleF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) method


Draws the specified string in the specified rectangle using the specified font and brush.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, RectangleF layoutRectangle, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | The string to draw |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | A font to use |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | A [Brush](../../brush/) object to use for drawing |
| layoutRectangle | [RectangleF](../../rectanglef/) | Specifies a rectangle to draw the string in |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Specified the format of the string |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, float, float, const System::SharedPtr\<System::Drawing::StringFormat\>\&) method


Draws the specified string at the specified location using the specified font and brush.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, float x, float y, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | The string to draw |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | A font to use |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | A [Brush](../../brush/) object to use for drawing |
| x | **float** | The X coordinate of the location of the upper left corner of the drawn string |
| y | **float** | The Y coordinate of the location of the upper left corner of the drawn string |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Specified the format of the string |

## See Also

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