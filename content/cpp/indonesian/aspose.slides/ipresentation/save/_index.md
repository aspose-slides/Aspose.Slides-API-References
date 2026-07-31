---
title: Save()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyimpan semua slide presentasi ke sebuah file dengan format yang ditentukan.
type: docs
weight: 404
url: /id/aspose.slides/ipresentation/save/
---
## IPresentation::Save(System::String, Export::SaveFormat) method

Menyimpan semua slide presentasi ke sebuah file dengan format yang ditentukan.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Jalur ke file yang dibuat. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format data yang diekspor. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat) method

Menyimpan semua slide presentasi ke aliran dalam format yang ditentukan.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Aliran keluaran. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format data yang diekspor. |

## IPresentation::Save(System::String, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) method

Menyimpan semua slide presentasi ke file dengan format yang ditentukan dan opsi tambahan.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Jalur ke file yang dibuat. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format data yang diekspor. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Opsi format tambahan. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) method

Menyimpan semua slide presentasi ke aliran dalam format yang ditentukan dan opsi tambahan.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Aliran keluaran. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format data yang diekspor. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Opsi format tambahan. |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat) method

Menyimpan slide yang ditentukan dari presentasi ke file dengan format yang ditentukan.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Jalur ke file yang dibuat. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array dengan posisi slide, mulai dari 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format data yang diekspor. |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) method

Menyimpan slide yang ditentukan dari presentasi ke file dengan format yang ditentukan.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Jalur ke file yang dibuat. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array dengan posisi slide, mulai dari 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format data yang diekspor. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Opsi format tambahan. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat) method

Menyimpan slide yang ditentukan dari presentasi ke aliran dalam format yang ditentukan.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Aliran keluaran. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array dengan posisi slide, mulai dari 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format data yang diekspor. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) method

Menyimpan slide yang ditentukan dari presentasi ke aliran dalam format yang ditentukan.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Aliran keluaran. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array dengan posisi slide, mulai dari 1. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Format data yang diekspor. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Opsi format tambahan. |

## IPresentation::Save(System::SharedPtr\<Export::Xaml::IXamlOptions\>) method

Menyimpan semua slide presentasi ke sekumpulan file yang mewakili markup XAML.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<Export::Xaml::IXamlOptions> options)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::Xaml::IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)\> | Opsi format XAML. |

## Keterangan

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```

## Lihat Juga

* Enum [SaveFormat](../../../aspose.slides.export/saveformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [String](../../../system/string/)
* Kelas [IPresentation](../)
* Kelas [Stream](../../../system.io/stream/)
* Kelas [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Kelas [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)