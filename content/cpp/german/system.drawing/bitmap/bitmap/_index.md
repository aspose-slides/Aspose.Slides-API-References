---
title: Bitmap()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein neues Bitmap-Objekt aus dem angegebenen vorhandenen Bild.
type: docs
weight: 1
url: /de/system.drawing/bitmap/bitmap/
---
## Bitmap::Bitmap(const SharedPtr\<Image\>\&) Konstruktor

Erstellt ein neues [Bitmap](../)-Objekt aus dem angegebenen vorhandenen Bild.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | The existing image to create the bitmap image from |

## Bitmap::Bitmap(const SharedPtr\<System::IO::Stream\>\&, bool) Konstruktor

Erstellt ein neues [Bitmap](../)-Objekt aus dem angegebenen Stream.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<System::IO::Stream> &stream, bool useIcm=false)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Ein Stream, der Bilddaten enthält |
| useIcm | **bool** | IGNIORIERT |

## Bitmap::Bitmap(const String\&) Konstruktor

Erstellt ein neues [Bitmap](../)-Objekt aus der angegebenen Datei.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Ein Name der Datei, die Bilddaten enthält |

## Bitmap::Bitmap(const String\&, bool) Konstruktor

Erstellt ein neues [Bitmap](../)-Objekt aus der angegebenen Datei.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename, bool useIcm)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Ein Name der Datei, die Bilddaten enthält |
| useIcm | **bool** | IGNIORIERT |

## Bitmap::Bitmap(int, int, Imaging::PixelFormat) Konstruktor

Erstellt ein neues [Bitmap](../)-Objekt, das ein Bitmap-Bild mit der angegebenen Breite, Höhe, Pixelformat und Pixeldaten darstellt.

```cpp
System::Drawing::Bitmap::Bitmap(int width, int height, Imaging::PixelFormat format=Imaging::PixelFormat::Format32bppArgb)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | int | Die Breite des Bildes |
| height | int | Die Höhe des Bildes |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Das Pixelformat des Bildes |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, const Size\&) Konstruktor

Erstellt ein neues [Bitmap](../)-Objekt aus dem angegebenen vorhandenen Bild, skaliert auf die angegebene Größe.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, const Size &size)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | The existing image to create the bitmap image from |
| size | const [Size](../../size/)\& | Die Größe des neuen Bildes |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, int, int) Konstruktor

Erstellt ein neues [Bitmap](../)-Objekt aus dem angegebenen vorhandenen Bild, dessen Breite und Höhe auf die angegebenen Werte skaliert wurden.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, int width, int height)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | The existing image to create the bitmap image from |
| width | int | Breite des neuen Bildes |
| height | int | Höhe des neuen Bildes |

## Siehe auch

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Image](../../image/)
* Klasse [Bitmap](../)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [String](../../../system/string/)
* Klasse [Size](../../size/)
* Namensraum [System::Drawing](../../)
* Library [Aspose.Slides](../../../)