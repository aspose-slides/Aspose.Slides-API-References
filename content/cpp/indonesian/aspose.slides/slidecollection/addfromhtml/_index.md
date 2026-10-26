---
title: AddFromHtml()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi.
type: docs
weight: 196
url: /id/aspose.slides/slidecollection/addfromhtml/
---
## SlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metode

Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | Html yang akan ditambahkan. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| uri | [System::String](../../../system/string/) | URI dari HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |

### Nilai Kembali

Slide yang ditambahkan.

## SlideCollection::AddFromHtml(System::String) metode

Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | Html yang akan ditambahkan. |

### Nilai Kembali

Slide yang ditambahkan

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metode

Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Objek TextReader yang akan digunakan sebagai sumber file HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| uri | [System::String](../../../system/string/) | URI dari HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |

### Nilai Kembali

Slide yang ditambahkan.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) metode

Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Objek TextReader yang akan digunakan sebagai sumber file HTML. |

### Nilai Kembali

Slide yang ditambahkan

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metode

Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Objek Stream yang akan digunakan sebagai sumber file HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| uri | [System::String](../../../system/string/) | URI dari HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |

### Nilai Kembali

Slide yang ditambahkan.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) metode

Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Objek Stream yang akan digunakan sebagai sumber file HTML. |

### Nilai Kembali

Slide yang ditambahkan

## Catatan

```cpp
// Buat sebuah instance dari kelas Presentation.
auto presentation = System::MakeObject<Presentation>();

{
    auto htmlStream = System::IO::File::OpenRead(u"page.html");

    // Panggil metode AddFromHtml dan berikan file HTML.
    presentation->get_Slides()->AddFromHtml(htmlStream);
}

// Gunakan metode Save untuk menyimpan file sebagai dokumen PowerPoint.
presentation->Save(u"MyPresentation.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ISlide](../../islide/)
* Kelas [String](../../../system/string/)
* Kelas [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Kelas [SlideCollection](../)
* Kelas [TextReader](../../../system.io/textreader/)
* Kelas [Stream](../../../system.io/stream/)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)