---
title: InsertFromHtml()
second_title: Aspose.Slides untuk Referensi API C++
description: Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan.
type: docs
weight: 157
url: /id/aspose.slides/islidecollection/insertfromhtml/
---
## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Posisi untuk menyisipkan. |
| htmlText | [System::String](../../../system/string/) | HTML untuk ditambahkan. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| uri | [System::String](../../../system/string/) | URI dari HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |

### Nilai Kembali

Slide yang ditambahkan.

## ISlideCollection::InsertFromHtml(int32_t, System::String) method

Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Posisi untuk menyisipkan. |
| htmlText | [System::String](../../../system/string/) | HTML untuk ditambahkan. |

### Nilai Kembali

Slide yang ditambahkan

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Posisi untuk menyisipkan. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Objek TextReader yang akan digunakan sebagai sumber file HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| uri | [System::String](../../../system/string/) | URI dari HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |

### Nilai Kembali

Slide yang ditambahkan.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) method

Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Posisi untuk menyisipkan. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Objek TextReader yang akan digunakan sebagai sumber file HTML. |

### Nilai Kembali

Slide yang ditambahkan

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Posisi untuk menyisipkan. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Objek Stream yang akan digunakan sebagai sumber file HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| uri | [System::String](../../../system/string/) | URI dari HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |

### Nilai Kembali

Slide yang ditambahkan.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) method

Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Posisi untuk menyisipkan. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Objek Stream yang akan digunakan sebagai sumber file HTML. |

### Nilai Kembali

Slide yang ditambahkan

## ISlideCollection::InsertFromHtml(int32_t, System::String, bool) method

Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Posisi untuk menyisipkan. |
| htmlText | [System::String](../../../system/string/) | HTML untuk ditambahkan. |
| useSlideWithIndexAsStart | **bool** | Flag ini menentukan cara memulai penyisipan: dari slide baru atau dari slide dengan indeks yang ditentukan. Jika **true**, penyisipan data akan dimulai dari ruang kosong pada slide dengan indeks yang ditentukan. Jika **false**, data akan ditambahkan ke slide yang dibuat. |

### Nilai Kembali

Slide yang ditambahkan

## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) method

Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Posisi untuk menyisipkan. |
| htmlText | [System::String](../../../system/string/) | HTML untuk ditambahkan. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| uri | [System::String](../../../system/string/) | URI dari HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |
| useSlideWithIndexAsStart | **bool** | Flag ini menentukan cara memulai penyisipan: dari slide baru atau dari slide dengan indeks yang ditentukan. Jika **true**, penyisipan data akan dimulai dari ruang kosong pada slide dengan indeks yang ditentukan. Jika **false**, data akan ditambahkan ke slide yang dibuat. |

### Nilai Kembali

Slide yang ditambahkan.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) method

Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Posisi untuk menyisipkan. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Objek Stream yang akan digunakan sebagai sumber file HTML. |
| useSlideWithIndexAsStart | **bool** | Flag ini menentukan cara memulai penyisipan: dari slide baru atau dari slide dengan indeks yang ditentukan. Jika **true**, penyisipan data akan dimulai dari ruang kosong pada slide dengan indeks yang ditentukan. Jika **false**, data akan ditambahkan ke slide yang dibuat. |

### Nilai Kembali

Slide yang ditambahkan

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) method

Membuat slide dari teks HTML dan menyisipkannya ke koleksi pada posisi yang ditentukan.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Posisi untuk menyisipkan. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Objek Stream yang akan digunakan sebagai sumber file HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| uri | [System::String](../../../system/string/) | URI dari HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |
| useSlideWithIndexAsStart | **bool** | Flag ini menentukan cara memulai penyisipan: dari slide baru atau dari slide dengan indeks yang ditentukan. Jika **true**, penyisipan data akan dimulai dari ruang kosong pada slide dengan indeks yang ditentukan. Jika **false**, data akan ditambahkan ke slide yang dibuat. |

### Nilai Kembali

Slide yang ditambahkan.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [String](../../../system/string/)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Class [ISlideCollection](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)