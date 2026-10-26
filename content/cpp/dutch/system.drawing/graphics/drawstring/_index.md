---
title: DrawString()
second_title: Aspose.Slides voor C++ API-referentie
description: Tekent de opgegeven tekenreeks op de opgegeven locatie met het opgegeven lettertype en penseel.
type: docs
weight: 365
url: /nl/system.drawing/graphics/drawstring/
---
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, PointF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) methode

Tekent de opgegeven tekenreeks op de opgegeven locatie met het opgegeven lettertype en penseel.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, PointF topLeft, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | De te tekenen tekenreeks |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Een te gebruiken lettertype |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Een [Brush](../../brush/) object om te gebruiken voor tekenen |
| topLeft | [PointF](../../pointf/) | Specificeert de locatie van de linkerbovenhoek van de getekende tekenreeks |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Geeft het formaat van de tekenreeks op |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, RectangleF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) methode

Tekent de opgegeven tekenreeks in het opgegeven rechthoek met het opgegeven lettertype en penseel.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, RectangleF layoutRectangle, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | De te tekenen tekenreeks |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Een te gebruiken lettertype |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Een [Brush](../../brush/) object om te gebruiken voor tekenen |
| layoutRectangle | [RectangleF](../../rectanglef/) | Specificeert een rechthoek waarin de tekenreeks wordt getekend |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Geeft het formaat van de tekenreeks op |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, float, float, const System::SharedPtr\<System::Drawing::StringFormat\>\&) methode

Tekent de opgegeven tekenreeks op de opgegeven locatie met het opgegeven lettertype en penseel.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, float x, float y, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | De te tekenen tekenreeks |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Een te gebruiken lettertype |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Een [Brush](../../brush/) object om te gebruiken voor tekenen |
| x | **float** | De X-coördinaat van de locatie van de linkerbovenhoek van de getekende tekenreeks |
| y | **float** | De Y-coördinaat van de locatie van de linkerbovenhoek van de getekende tekenreeks |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Geeft het formaat van de tekenreeks op |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [Font](../../font/)
* Klasse [Brush](../../brush/)
* Klasse [PointF](../../pointf/)
* Klasse [StringFormat](../../stringformat/)
* Klasse [Graphics](../)
* Klasse [RectangleF](../../rectanglef/)
* Naamruimte [System::Drawing](../../)
* Library [Aspose.Slides](../../../)