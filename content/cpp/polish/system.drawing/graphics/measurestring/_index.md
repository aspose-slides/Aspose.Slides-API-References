---
title: MeasureString()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Zwraca rozmiar określonego ciągu rysowanego podaną czcionką w określonym formacie.
type: docs
weight: 521
url: /pl/system.drawing/graphics/measurestring/
---
## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, PointF const\&, System::SharedPtr\<StringFormat\> const\&) const method

Zwraca rozmiar określonego ciągu rysowanego podaną czcionką w określonym formacie.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, PointF const &origin=PointF(0, 0), System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Arguments

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | Ciąg znaków, którego rozmiar ma zostać obliczony |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | Czcionka używana do rysowania ciągu |
| origin | [PointF](../../pointf/) const\& | Określa położenie lewego górnego rogu ciągu |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Określa format ciągu |

### Return Value

Obiekt [SizeF](../../sizef/) reprezentujący rozmiar ciągu w jednostkach miary określonych przez właściwość PageUnit bieżącego obiektu Graphics.

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, int, System::SharedPtr\<StringFormat\> const\&) const method

Zwraca rozmiar określonego ciągu rysowanego podaną czcionką w określonym formacie.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, int width, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Arguments

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | Ciąg znaków, którego rozmiar ma zostać obliczony |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | Czcionka używana do rysowania ciągu |
| width | int | Maksymalna szerokość ciągu |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Określa format ciągu |

### Return Value

Obiekt [SizeF](../../sizef/) reprezentujący rozmiar ciągu w jednostkach miary określonych przez właściwość PageUnit bieżącego obiektu Graphics.

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&, int\&, int\&) const method

NIE ZAIMPLEMENTOWANO.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat, int &charactersFitted, int &linesFilled) const
```

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&) const method

Zwraca rozmiar określonego ciągu rysowanego podaną czcionką w określonym formacie.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Arguments

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | Ciąg znaków, którego rozmiar ma zostać obliczony |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | Czcionka używana do rysowania ciągu |
| layoutArea | [SizeF](../../sizef/) const\& | Maksymalny obszar układu ciągu |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Określa format ciągu |

### Return Value

Obiekt [SizeF](../../sizef/) reprezentujący rozmiar ciągu w jednostkach miary określonych przez właściwość PageUnit bieżącego obiektu Graphics.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [SizeF](../../sizef/)
* Klasa [String](../../../system/string/)
* Klasa [Font](../../font/)
* Klasa [PointF](../../pointf/)
* Klasa [StringFormat](../../stringformat/)
* Klasa [Graphics](../)
* Przestrzeń nazw [System::Drawing](../../)
* Biblioteka [Aspose.Slides](../../../)