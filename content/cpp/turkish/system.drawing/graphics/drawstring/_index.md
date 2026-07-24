---
title: DrawString()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen yazı tipi ve fırça kullanılarak belirtilen konumda belirtilen dizeyi çizer.
type: docs
weight: 365
url: /tr/system.drawing/graphics/drawstring/
---
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, PointF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) metodu


Belirtilen dizeyi belirtilen konumda, belirtilen yazı tipi ve fırça kullanarak çizer.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, PointF topLeft, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Çizilecek dize |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Kullanılacak bir yazı tipi |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Çizim için kullanılacak bir [Brush](../../brush/) nesnesi |
| topLeft | [PointF](../../pointf/) | Çizilen dizenin sol üst köşesinin konumunu belirtir |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Dizenin biçimini belirtir |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, RectangleF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) metodu


Belirtilen dizeyi belirtilen dikdörtgen içinde, belirtilen yazı tipi ve fırça kullanarak çizer.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, RectangleF layoutRectangle, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Çizilecek dize |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Kullanılacak bir yazı tipi |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Çizim için kullanılacak bir [Brush](../../brush/) nesnesi |
| layoutRectangle | [RectangleF](../../rectanglef/) | Dizenin çizileceği bir dikdörtgeni belirtir |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Dizenin biçimini belirtir |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, float, float, const System::SharedPtr\<System::Drawing::StringFormat\>\&) metodu


Belirtilen dizeyi belirtilen konumda, belirtilen yazı tipi ve fırça kullanarak çizer.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, float x, float y, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Çizilecek dize |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Kullanılacak bir yazı tipi |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Çizim için kullanılacak bir [Brush](../../brush/) nesnesi |
| x | **float** | Çizilen dizenin sol üst köşesinin konumunun X koordinatı |
| y | **float** | Çizilen dizenin sol üst köşesinin konumunun Y koordinatı |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Dizenin biçimini belirtir |

## İlgili

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