---
title: Bitmap()
second_title: Aspose.Slides for C++ API Referenciája
description: Új Bitmap objektumot hoz létre a megadott meglévő képből.
type: docs
weight: 1
url: /hu/system.drawing/bitmap/bitmap/
---
## Bitmap::Bitmap(const SharedPtr\<Image\>\&) constructor


Új [Bitmap](../) objektumot hoz létre a megadott meglévő képből.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A meglévő kép, amelyből a bitmap képet létrehozzuk |

## Bitmap::Bitmap(const SharedPtr\<System::IO::Stream\>\&, bool) constructor


Új [Bitmap](../) objektumot hoz létre a megadott adatfolyamból.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<System::IO::Stream> &stream, bool useIcm=false)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Az adatfolyam, amely képadatot tartalmaz |
| useIcm | **bool** | IGNORED |

## Bitmap::Bitmap(const String\&) constructor


Új [Bitmap](../) objektumot hoz létre a megadott fájlból.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | A fájl neve, amely képadatot tartalmaz |

## Bitmap::Bitmap(const String\&, bool) constructor


Új [Bitmap](../) objektumot hoz létre a megadott fájlból.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename, bool useIcm)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | A fájl neve, amely képadatot tartalmaz |
| useIcm | **bool** | IGNORED |

## Bitmap::Bitmap(int, int, Imaging::PixelFormat) constructor


Új [Bitmap](../) objektumot hoz létre, amely a megadott szélességű, magasságú, pixelformátumú és pixeltartalmú bitmap képet ábrázolja.

```cpp
System::Drawing::Bitmap::Bitmap(int width, int height, Imaging::PixelFormat format=Imaging::PixelFormat::Format32bppArgb)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| width | int | A kép szélessége |
| height | int | A kép magassága |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | A kép pixelformátuma |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, const Size\&) constructor


Új [Bitmap](../) objektumot hoz létre a megadott meglévő képből, a megadott méretre méretezve.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, const Size &size)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A meglévő kép, amelyből a bitmap képet létrehozzuk |
| size | const [Size](../../size/)\& | Az új kép mérete |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, int, int) constructor


Új [Bitmap](../) objektumot hoz létre a megadott meglévő képből, a szélesség és magasság a megadott értékekre méretezve.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, int width, int height)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | A meglévő kép, amelyből a bitmap képet létrehozzuk |
| width | int | Az új kép szélessége |
| height | int | Az új kép magassága |

## Lásd még

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Image](../../image/)
* Osztály [Bitmap](../)
* Osztály [Stream](../../../system.io/stream/)
* Osztály [String](../../../system/string/)
* Osztály [Size](../../size/)
* Névtér [System::Drawing](../../)
* Könyvtár [Aspose.Slides](../../../)