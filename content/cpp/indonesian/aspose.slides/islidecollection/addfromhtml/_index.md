---
title: AddFromHtml()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi.
type: docs
weight: 144
url: /id/aspose.slides/islidecollection/addfromhtml/
---
## ISlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | Html untuk ditambahkan. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| uri | [System::String](../../../system/string/) | URI dari HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |

### Nilai Kembalian

Slide yang ditambahkan.

## ISlideCollection::AddFromHtml(System::String) method

Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | Html untuk ditambahkan. |

### Nilai Kembalian

Slide yang ditambahkan

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Objek TextReader yang akan digunakan sebagai sumber file HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| uri | [System::String](../../../system/string/) | URI dari HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |

### Nilai Kembalian

Slide yang ditambahkan.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) method

Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Objek TextReader yang akan digunakan sebagai sumber file HTML. |

### Nilai Kembalian

Slide yang ditambahkan

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Objek Stream yang akan digunakan sebagai sumber file HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| uri | [System::String](../../../system/string/) | URI dari HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |

### Nilai Kembalian

Slide yang ditambahkan.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) method

Membuat slide dari teks HTML dan menambahkannya ke akhir koleksi.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Objek Stream yang akan digunakan sebagai sumber file HTML. |

### Nilai Kembalian

Slide yang ditambahkan

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ISlide](../../islide/)
* Kelas [String](../../../system/string/)
* Kelas [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Kelas [ISlideCollection](../)
* Kelas [TextReader](../../../system.io/textreader/)
* Kelas [Stream](../../../system.io/stream/)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)