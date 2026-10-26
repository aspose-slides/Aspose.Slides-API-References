---
title: AddImage()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan salinan gambar dari presentasi lain.
type: docs
weight: 53
url: /id/aspose.slides/imagecollection/addimage/
---
## ImageCollection::AddImage(System::SharedPtr\<IPPImage\>) metode

Menambahkan salinan gambar dari presentasi lain.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Gambar sumber. |

### Nilai Kembali

Gambar ditambahkan.

## ImageCollection::AddImage(System::SharedPtr\<IImage\>) metode

Menambahkan gambar ke presentasi.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IImage> image) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | Gambar yang akan ditambahkan. |

### Nilai Kembali

Gambar ditambahkan.

## Catatan

Metode ini mengonversi berkas metafile WMF/EMF menjadi gambar PNG raster sebelum disisipkan ke presentasi.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) metode

Menambahkan gambar ke presentasi dari aliran.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | Aliran untuk menambahkan gambar dari. |

### Nilai Kembali

Gambar ditambahkan.

## Catatan

Metode ini dapat menambahkan berkas metafile WMF/EMF ke presentasi tanpa mengonversinya menjadi gambar PNG raster.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) metode

Menambahkan gambar ke presentasi dari aliran.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Aliran untuk menambahkan gambar dari. |

### Nilai Kembali

Gambar ditambahkan.

## Catatan

Metode ini dapat menambahkan berkas metafile WMF/EMF ke presentasi tanpa mengonversinya menjadi gambar PNG raster.

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) metode

Membuat dan menambahkan gambar ke presentasi dari aliran.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Aliran untuk menambahkan file gambar dari. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Perilaku yang akan diterapkan pada aliran. |

### Nilai Kembali

Ditambahkan [IPPImage](../../ippimage/).

## ImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) metode

Menambahkan gambar ke presentasi dari buffer yang ditentukan.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Penyangga. |

### Nilai Kembali

Gambar ditambahkan.

## ImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) metode

Menambahkan gambar ke presentasi dari objek Svg.

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Objek gambar Svg [ISvgImage](../../isvgimage/) |

### Nilai Kembali

Gambar ditambahkan.

## Lihat Juga

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [IPPImage](../../ippimage/)
* Kelas [ImageCollection](../)
* Kelas [IImage](../../iimage/)
* Kelas [MemoryStream](../../../system.io/memorystream/)
* Kelas [Stream](../../../system.io/stream/)
* Kelas [ISvgImage](../../isvgimage/)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)