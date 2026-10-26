---
title: Save()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyimpan gambar ke file.
type: docs
weight: 40
url: /id/aspose.slides/iimage/save/
---
## IImage::Save(System::String) metode

Menyimpan gambar ke file.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename)=0
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | Jalur ke file tempat gambar akan disimpan. |

## IImage::Save(System::String, ImageFormat) metode

Menyimpan gambar ke file dalam format yang ditentukan.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format)=0
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | Jalur ke file tempat gambar akan disimpan. |
| format | [ImageFormat](../../imageformat/) | Format gambar. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat) metode

Menyimpan gambar ke stream dalam format yang ditentukan.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format)=0
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Aliran tempat gambar akan disimpan. |
| format | [ImageFormat](../../imageformat/) | Format gambar. |

## IImage::Save(System::String, ImageFormat, int32_t) metode

Menyimpan gambar ke file dalam format dan kualitas yang ditentukan.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format, int32_t quality)=0
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | Jalur ke file tempat gambar akan disimpan. |
| format | [ImageFormat](../../imageformat/) | Format gambar. |
| quality | **int32_t** | Kualitas gambar yang disimpan (0 hingga 100).<br><br>Parameter ini hanya memengaruhi penyimpanan dalam [ImageFormat::Jpeg](../../imageformat/); untuk semua format lain, diabaikan. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat, int32_t) metode

Menyimpan gambar ke stream dalam format dan kualitas yang ditentukan.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format, int32_t quality)=0
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Aliran tempat gambar akan disimpan. |
| format | [ImageFormat](../../imageformat/) | Format gambar. |
| quality | **int32_t** | Kualitas gambar yang disimpan (0 hingga 100).<br><br>Parameter ini hanya memengaruhi penyimpanan dalam [ImageFormat::Jpeg](../../imageformat/); untuk semua format lain, diabaikan. |

## Lihat Juga

* Enum [ImageFormat](../../imageformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [String](../../../system/string/)
* Kelas [IImage](../)
* Kelas [Stream](../../../system.io/stream/)
* Ruang nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)