---
title: ReadPresentation()
second_title: Referensi API Aspose.Slides untuk C++
description: Membaca presentasi yang ada dari array
type: docs
weight: 27
url: /id/aspose.slides/ipresentationfactory/readpresentation/
---
## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) metode

Membaca presentasi yang ada dari array

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array untuk dibaca |

### Nilai Kembalian

Presentasi yang dibaca

## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) metode

Membaca presentasi yang ada dari array dengan opsi pemuatan tambahan

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array untuk dibaca |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Opsi pemuatan |

### Nilai Kembalian

Presentasi yang dibaca

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) metode

Membaca presentasi yang ada dari stream

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream masukan untuk dibaca |

### Nilai Kembalian

Presentasi yang dibaca

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) metode

Membaca presentasi yang ada dari stream dengan opsi pemuatan tambahan

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream masukan untuk dibaca |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Opsi pemuatan |

### Nilai Kembalian

Presentasi yang dibaca

## IPresentationFactory::ReadPresentation(System::String) metode

Membaca presentasi yang ada dari file

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Nama file |

### Nilai Kembalian

Presentasi yang dibaca

## IPresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) metode

Membaca presentasi yang ada dari stream dengan opsi pemuatan tambahan

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Nama file |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Opsi pemuatan |

### Nilai Kembalian

Presentasi yang dibaca

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [IPresentation](../../ipresentation/)
* Kelas [IPresentationFactory](../)
* Kelas [ILoadOptions](../../iloadoptions/)
* Kelas [Stream](../../../system.io/stream/)
* Kelas [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)