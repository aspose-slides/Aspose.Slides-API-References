---
title: Bitmap()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een nieuw Bitmap-object van de opgegeven bestaande afbeelding.
type: docs
weight: 1
url: /nl/system.drawing/bitmap/bitmap/
---
## Bitmap::Bitmap(const SharedPtr\<Image\>\&) constructor


Construeert een nieuw [Bitmap](../) object van de opgegeven bestaande afbeelding.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | De bestaande afbeelding waaruit het bitmap-object wordt gemaakt |

## Bitmap::Bitmap(const SharedPtr\<System::IO::Stream\>\&, bool) constructor


Construeert een nieuw [Bitmap](../) object van de opgegeven stroom.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<System::IO::Stream> &stream, bool useIcm=false)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Een stroom die afbeeldingsgegevens bevat |
| useIcm | **bool** | IGNORED |

## Bitmap::Bitmap(const String\&) constructor


Construeert een nieuw [Bitmap](../) object van het opgegeven bestand.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | De naam van het bestand dat afbeeldingsgegevens bevat |

## Bitmap::Bitmap(const String\&, bool) constructor


Construeert een nieuw [Bitmap](../) object van het opgegeven bestand.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename, bool useIcm)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | De naam van het bestand dat afbeeldingsgegevens bevat |
| useIcm | **bool** | IGNORED |

## Bitmap::Bitmap(int, int, Imaging::PixelFormat) constructor


Construeert een nieuw [Bitmap](../) object dat een bitmap-afbeelding vertegenwoordigt met de opgegeven breedte, hoogte, pixelformaat en pixelgegevens.

```cpp
System::Drawing::Bitmap::Bitmap(int width, int height, Imaging::PixelFormat format=Imaging::PixelFormat::Format32bppArgb)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| width | int | De breedte van de afbeelding |
| height | int | De hoogte van de afbeelding |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Het pixelformaat van de afbeelding |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, const Size\&) constructor


Construeert een nieuw [Bitmap](../) object van de opgegeven bestaande afbeelding, geschaald naar de opgegeven grootte.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, const Size &size)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | De bestaande afbeelding waaruit het bitmap-object wordt gemaakt |
| size | const [Size](../../size/)\& | De grootte van de nieuwe afbeelding |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, int, int) constructor


Construeert een nieuw [Bitmap](../) object van de opgegeven bestaande afbeelding met breedte en hoogte geschaald naar de opgegeven waarden.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, int width, int height)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | De bestaande afbeelding waaruit het bitmap-object wordt gemaakt |
| width | int | Breedte van de nieuwe afbeelding |
| height | int | Hoogte van de nieuwe afbeelding |

## See Also

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Bitmap](../)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [Size](../../size/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)