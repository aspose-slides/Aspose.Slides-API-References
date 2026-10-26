---
title: DrawString()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Rysuje określony ciąg znaków w podanej lokalizacji przy użyciu określonej czcionki i pędzla.
type: docs
weight: 365
url: /pl/system.drawing/graphics/drawstring/
---
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, PointF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) metoda

Rysuje określony ciąg znaków w podanej lokalizacji przy użyciu określonej czcionki i pędzla.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, PointF topLeft, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Ciąg znaków do rysowania |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Czcionka do użycia |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Obiekt [Brush](../../brush/) do użycia przy rysowaniu |
| topLeft | [PointF](../../pointf/) | Określa położenie lewego górnego rogu rysowanego ciągu znaków |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Określa format ciągu znaków |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, RectangleF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) metoda

Rysuje określony ciąg znaków w podanym prostokącie przy użyciu określonej czcionki i pędzla.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, RectangleF layoutRectangle, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Ciąg znaków do rysowania |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Czcionka do użycia |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Obiekt [Brush](../../brush/) do użycia przy rysowaniu |
| layoutRectangle | [RectangleF](../../rectanglef/) | Określa prostokąt, w którym rysowany jest ciąg znaków |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Określa format ciągu znaków |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, float, float, const System::SharedPtr\<System::Drawing::StringFormat\>\&) metoda

Rysuje określony ciąg znaków w podanej lokalizacji przy użyciu określonej czcionki i pędzla.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, float x, float y, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Ciąg znaków do rysowania |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Czcionka do użycia |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Obiekt [Brush](../../brush/) do użycia przy rysowaniu |
| x | **float** | Współrzędna X lewego górnego rogu rysowanego ciągu znaków |
| y | **float** | Współrzędna Y lewego górnego rogu rysowanego ciągu znaków |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Określa format ciągu znaków |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [String](../../../system/string/)
* Klasa [Font](../../font/)
* Klasa [Brush](../../brush/)
* Klasa [PointF](../../pointf/)
* Klasa [StringFormat](../../stringformat/)
* Klasa [Graphics](../)
* Klasa [RectangleF](../../rectanglef/)
* Przestrzeń nazw [System::Drawing](../../)
* Library [Aspose.Slides](../../../)