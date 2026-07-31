---
title: AddImage()
second_title: Aspose.Slides untuk Referensi API C++
description: Menambahkan gambar ke presentasi.
type: docs
weight: 14
url: /id/aspose.slides/iimagecollection/addimage/
---
## IImageCollection::AddImage(System::SharedPtr\<IImage\>) metode

Menambahkan gambar ke presentasi.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IImage> image)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | Gambar yang akan ditambahkan. |

### Nilai Kembalian

Gambar yang ditambahkan.

## Catatan

Metode ini mengonversi file metafile WMF/EMF menjadi gambar PNG raster sebelum dimasukkan ke presentasi.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) metode

Menambahkan gambar dari aliran memori.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | Aliran memori. |

### Nilai Kembalian

Gambar yang ditambahkan.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) metode

Menambahkan gambar ke presentasi dari aliran.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Aliran untuk menambahkan gambar. |

### Nilai Kembalian

Gambar yang ditambahkan.

## Catatan

Metode ini dapat menambahkan file metafile WMF/EMF ke presentasi tanpa mengonversinya menjadi gambar PNG raster.

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) metode

Membuat dan menambahkan gambar ke presentasi dari aliran.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Aliran untuk menambahkan file gambar. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Perilaku yang akan diterapkan pada aliran. |

### Nilai Kembalian

Ditambahkan [IPPImage](../../ippimage/).

## IImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) metode

Menambahkan gambar ke presentasi dari buffer yang ditentukan.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer. |

### Nilai Kembalian

Gambar yang ditambahkan.

## IImageCollection::AddImage(System::SharedPtr\<IPPImage\>) metode

Menambahkan salinan gambar dari presentasi lain.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Gambar sumber. |

### Nilai Kembalian

Gambar yang ditambahkan.

## IImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) metode

Menambahkan gambar ke presentasi dari objek SVG.

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Objek gambar SVG [ISvgImage](../../isvgimage/) |

### Nilai Kembalian

Gambar yang ditambahkan.

## Lihat Juga

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [IPPImage](../../ippimage/)
* Kelas [IImage](../../iimage/)
* Kelas [IImageCollection](../)
* Kelas [MemoryStream](../../../system.io/memorystream/)
* Kelas [Stream](../../../system.io/stream/)
* Kelas [ISvgImage](../../isvgimage/)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)