---
title: Save()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyimpan gambar yang diwakili oleh objek saat ini ke file yang ditentukan dalam format PNG.
type: docs
weight: 1
url: /id/system.drawing/image/save/
---
## Image::Save(const String\&) metode

Menyimpan gambar yang diwakili oleh objek saat ini ke file yang ditentukan dalam format PNG.

```cpp
void System::Drawing::Image::Save(const String &filename)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Nama file untuk menyimpan gambar |

## Image::Save(const String\&, const Imaging::ImageFormatPtr\&) metode

Menyimpan gambar yang diwakili oleh objek saat ini ke file yang ditentukan dalam format yang ditentukan.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageFormatPtr &format)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Nama file untuk menyimpan gambar |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | Format untuk menyimpan gambar |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageFormatPtr\&) metode

Menyimpan gambar yang diwakili oleh objek saat ini ke stream yang ditentukan dalam format yang ditentukan.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageFormatPtr &format)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Stream untuk menyimpan gambar |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | Format untuk menyimpan gambar |

## Image::Save(const String\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) metode

Menyimpan gambar yang diwakili oleh objek saat ini ke file yang ditentukan menggunakan encoder dan parameter encoder yang ditentukan.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Nama file untuk menyimpan gambar |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | Encoder yang akan digunakan |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | Parameter encoder yang akan digunakan |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) metode

Menyimpan gambar yang diwakili oleh objek saat ini ke stream yang ditentukan menggunakan encoder dan parameter encoder yang ditentukan.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Stream untuk menyimpan gambar |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | Encoder yang akan digunakan |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | Parameter encoder yang akan digunakan |

## Lihat Juga

* Typedef [ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)
* Typedef [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* Kelas [String](../../../system/string/)
* Kelas [Image](../)
* Kelas [Stream](../../../system.io/stream/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)