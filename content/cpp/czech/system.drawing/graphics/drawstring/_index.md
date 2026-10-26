---
title: DrawString()
second_title: Aspose.Slides pro C++ - reference API
description: Vykreslí zadaný řetězec na zadané místo pomocí zadaného písma a štětce.
type: docs
weight: 365
url: /cs/system.drawing/graphics/drawstring/
---
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, PointF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) metoda


Vykreslí zadaný řetězec na zadané místo pomocí zadaného písma a štětce.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, PointF topLeft, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Řetězec k vykreslení |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Písmo k použití |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Objekt [Brush](../../brush/) k použití při kreslení |
| topLeft | [PointF](../../pointf/) | Určuje umístění levého horního rohu vykresleného řetězce |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Určuje formát řetězce |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, RectangleF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) metoda


Vykreslí zadaný řetězec v zadaném obdélníku pomocí zadaného písma a štětce.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, RectangleF layoutRectangle, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Řetězec k vykreslení |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Písmo k použití |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Objekt [Brush](../../brush/) k použití při kreslení |
| layoutRectangle | [RectangleF](../../rectanglef/) | Určuje obdélník, ve kterém se má řetězec vykreslit |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Určuje formát řetězce |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, float, float, const System::SharedPtr\<System::Drawing::StringFormat\>\&) metoda


Vykreslí zadaný řetězec na zadané místo pomocí zadaného písma a štětce.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, float x, float y, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Řetězec k vykreslení |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Písmo k použití |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Objekt [Brush](../../brush/) k použití při kreslení |
| x | **float** | Souřadnice X umístění levého horního rohu vykresleného řetězce |
| y | **float** | Souřadnice Y umístění levého horního rohu vykresleného řetězce |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Určuje formát řetězce |

## Viz také

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