---
title: DrawString()
second_title: Aspose.Slides för C++ API-referens
description: Ritar den angivna strängen på den angivna platsen med det angivna typsnittet och penseln.
type: docs
weight: 365
url: /sv/system.drawing/graphics/drawstring/
---
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, PointF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) metod

Ritar den angivna strängen på den angivna platsen med det angivna typsnittet och penseln.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, PointF topLeft, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Strängen att rita |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Ett typsnitt att använda |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Ett [Brush](../../brush/)-objekt att använda för ritning |
| topLeft | [PointF](../../pointf/) | Anger platsen för det övre vänstra hörnet av den ritade strängen |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Anger formatet för strängen |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, RectangleF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) metod


Ritar den angivna strängen i den angivna rektangeln med det angivna typsnittet och penseln.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, RectangleF layoutRectangle, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Strängen att rita |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Ett typsnitt att använda |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Ett [Brush](../../brush/)-objekt att använda för ritning |
| layoutRectangle | [RectangleF](../../rectanglef/) | Anger en rektangel att rita strängen i |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Anger formatet för strängen |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, float, float, const System::SharedPtr\<System::Drawing::StringFormat\>\&) metod


Ritar den angivna strängen på den angivna platsen med det angivna typsnittet och penseln.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, float x, float y, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Strängen att rita |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Ett typsnitt att använda |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Ett [Brush](../../brush/)-objekt att använda för ritning |
| x | **float** | X-koordinaten för platsen för det övre vänstra hörnet av den ritade strängen |
| y | **float** | Y-koordinaten för platsen för det övre vänstra hörnet av den ritade strängen |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Anger formatet för strängen |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [Font](../../font/)
* Klass [Brush](../../brush/)
* Klass [PointF](../../pointf/)
* Klass [StringFormat](../../stringformat/)
* Klass [Graphics](../)
* Klass [RectangleF](../../rectanglef/)
* Namnrymd [System::Drawing](../../)
* Library [Aspose.Slides](../../../)