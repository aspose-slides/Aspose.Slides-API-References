---
title: Bitmap()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett nytt Bitmap-objekt från den angivna befintliga bilden.
type: docs
weight: 1
url: /sv/system.drawing/bitmap/bitmap/
---
## Bitmap::Bitmap(const SharedPtr\<Image\>\&) konstruktör


Skapar ett nytt [Bitmap](../)-objekt från den angivna befintliga bilden.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Den befintliga bilden att skapa bitmap-bilden från |

## Bitmap::Bitmap(const SharedPtr\<System::IO::Stream\>\&, bool) konstruktör


Skapar ett nytt [Bitmap](../)-objekt från den angivna strömmen.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<System::IO::Stream> &stream, bool useIcm=false)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | En ström som innehåller bilddata |
| useIcm | **bool** | IGNORED |

## Bitmap::Bitmap(const String\&) konstruktör


Skapar ett nytt [Bitmap](../)-objekt från den angivna filen.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Namnet på filen som innehåller bilddata |

## Bitmap::Bitmap(const String\&, bool) konstruktör


Skapar ett nytt [Bitmap](../)-objekt från den angivna filen.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename, bool useIcm)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Namnet på filen som innehåller bilddata |
| useIcm | **bool** | IGNORED |

## Bitmap::Bitmap(int, int, Imaging::PixelFormat) konstruktör


Skapar ett nytt [Bitmap](../)-objekt som representerar en bitmap-bild med angiven bredd, höjd, pixelformat och pixeldata.

```cpp
System::Drawing::Bitmap::Bitmap(int width, int height, Imaging::PixelFormat format=Imaging::PixelFormat::Format32bppArgb)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | int | Bildens bredd |
| height | int | Bildens höjd |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Pixelformatet för bilden |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, const Size\&) konstruktör


Skapar ett nytt [Bitmap](../)-objekt från den angivna befintliga bilden, skalad till den angivna storleken.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, const Size &size)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Den befintliga bilden att skapa bitmap-bilden från |
| size | const [Size](../../size/)\& | Storleken på den nya bilden |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, int, int) konstruktör


Skapar ett nytt [Bitmap](../)-objekt från den angivna befintliga bilden med bredd och höjd skalade till de angivna värdena.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, int width, int height)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Den befintliga bilden att skapa bitmap-bilden från |
| width | int | Bredd på den nya bilden |
| height | int | Höjd på den nya bilden |

## Se även

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Image](../../image/)
* Klass [Bitmap](../)
* Klass [Stream](../../../system.io/stream/)
* Klass [String](../../../system/string/)
* Klass [Size](../../size/)
* Namnrymd [System::Drawing](../../)
* Bibliotek [Aspose.Slides](../../../)