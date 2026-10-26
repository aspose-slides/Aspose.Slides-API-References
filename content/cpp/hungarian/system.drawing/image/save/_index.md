---
title: Save()
second_title: Aspose.Slides for C++ API Referenciája
description: Elmenti az aktuális objektum által képviselt képet a megadott fájlba PNG formátumban.
type: docs
weight: 1
url: /hu/system.drawing/image/save/
---
## Image::Save(const String\&) metódus

Elmenti az aktuális objektum által képviselt képet a megadott fájlba PNG formátumban.

```cpp
void System::Drawing::Image::Save(const String &filename)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | A fájl neve, amelybe a képet menteni kell |

## Image::Save(const String\&, const Imaging::ImageFormatPtr\&) metódus

Elmenti az aktuális objektum által képviselt képet a megadott fájlba a megadott formátumban.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageFormatPtr &format)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | A fájl neve, amelybe a képet menteni kell |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | A kép mentéséhez használandó formátum |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageFormatPtr\&) metódus

Elmenti az aktuális objektum által képviselt képet a megadott adatfolyamba a megadott formátumban.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageFormatPtr &format)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Az adatfolyam, amelybe a képet menteni kell |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | A kép mentéséhez használandó formátum |

## Image::Save(const String\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) metódus

Elmenti az aktuális objektum által képviselt képet a megadott fájlba a megadott kódoló és kódoló paraméterek használatával.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | A fájl neve, amelybe a képet menteni kell |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | A használandó kódoló |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | A használandó kódoló paraméterei |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) metódus

Elmenti az aktuális objektum által képviselt képet a megadott adatfolyamba a megadott kódoló és kódoló paraméterek használatával.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Az adatfolyam, amelybe a képet menteni kell |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | A használandó kódoló |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | A használandó kódoló paraméterei |

## Lásd még

* Typedef [ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)
* Typedef [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* Osztály [String](../../../system/string/)
* Osztály [Image](../)
* Osztály [Stream](../../../system.io/stream/)
* Névtér [System::Drawing](../../)
* Könyvtár [Aspose.Slides](../../../)