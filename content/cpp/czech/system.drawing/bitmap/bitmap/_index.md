---
title: Bitmap()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří nový objekt Bitmap ze zadaného existujícího obrázku.
type: docs
weight: 1
url: /cs/system.drawing/bitmap/bitmap/
---
## Bitmap::Bitmap(const SharedPtr\<Image\>\&) konstruktor


Vytvoří nový objekt [Bitmap](../) ze zadaného existujícího obrázku.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Existující obrázek, ze kterého se vytvoří bitmapový obrázek |

## Bitmap::Bitmap(const SharedPtr\<System::IO::Stream\>\&, bool) konstruktor


Vytvoří nový objekt [Bitmap](../) ze zadaného proudu.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<System::IO::Stream> &stream, bool useIcm=false)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Proud obsahující data obrázku |
| useIcm | **bool** | IGNOROVÁNO |

## Bitmap::Bitmap(const String\&) konstruktor


Vytvoří nový objekt [Bitmap](../) ze zadaného souboru.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Název souboru, který obsahuje data obrázku |

## Bitmap::Bitmap(const String\&, bool) konstruktor


Vytvoří nový objekt [Bitmap](../) ze zadaného souboru.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename, bool useIcm)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Název souboru, který obsahuje data obrázku |
| useIcm | **bool** | IGNOROVÁNO |

## Bitmap::Bitmap(int, int, Imaging::PixelFormat) konstruktor


Vytvoří nový objekt [Bitmap](../), který představuje bitmapový obrázek se zadanou šířkou, výškou, formátem pixelů a daty pixelů.

```cpp
System::Drawing::Bitmap::Bitmap(int width, int height, Imaging::PixelFormat format=Imaging::PixelFormat::Format32bppArgb)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| width | int | Šířka obrázku |
| height | int | Výška obrázku |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Formát pixelů obrázku |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, const Size\&) konstruktor


Vytvoří nový objekt [Bitmap](../) ze zadaného existujícího obrázku, přepočítaný na zadanou velikost.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, const Size &size)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Existující obrázek, ze kterého se vytvoří bitmapový obrázek |
| size | const [Size](../../size/)\& | Velikost nového obrázku |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, int, int) konstruktor


Vytvoří nový objekt [Bitmap](../) ze zadaného existujícího obrázku se šířkou a výškou přepočítanými na zadané hodnoty.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, int width, int height)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Existující obrázek, ze kterého se vytvoří bitmapový obrázek |
| width | int | Šířka nového obrázku |
| height | int | Výška nového obrázku |

## Viz také

* Výčet [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [Image](../../image/)
* Třída [Bitmap](../)
* Třída [Stream](../../../system.io/stream/)
* Třída [String](../../../system/string/)
* Třída [Size](../../size/)
* Jmenný prostor [System::Drawing](../../)
* Knihovna [Aspose.Slides](../../../)