---
title: InsertFromHtml()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat slide dari teks HTML dan menyisipkannya ke dalam koleksi pada posisi yang ditentukan.
type: docs
weight: 209
url: /id/aspose.slides/slidecollection/insertfromhtml/
---
## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metode


Membuat slide dari teks HTML dan memasukkannya ke dalam koleksi pada posisi yang ditentukan.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Posisi untuk menyisipkan. |
| htmlText | [System::String](../../../system/string/) | HTML untuk ditambahkan. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| uri | [System::String](../../../system/string/) | URI dari HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |

### Nilai Kembalian

Slide yang ditambahkan.

## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) metode


Membuat slide dari teks HTML dan memasukkannya ke dalam koleksi pada posisi yang ditentukan.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Posisi untuk menyisipkan. |
| htmlText | [System::String](../../../system/string/) | HTML untuk ditambahkan. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| uri | [System::String](../../../system/string/) | URI dari HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |
| useSlideWithIndexAsStart | **bool** | Flag ini menentukan cara memulai penyisipan: dari slide baru atau dari slide dengan indeks yang ditentukan. Jika **true**, maka penyisipan data akan dimulai dari ruang kosong pada slide dengan indeks yang ditentukan. Jika **false**, maka data akan ditambahkan ke slide yang dibuat. |

### Nilai Kembalian

Slide yang ditambahkan.

## SlideCollection::InsertFromHtml(int32_t, System::String) metode


Membuat slide dari teks HTML dan memasukkannya ke dalam koleksi pada posisi yang ditentukan.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Posisi untuk menyisipkan. |
| htmlText | [System::String](../../../system/string/) | HTML untuk ditambahkan. |

### Nilai Kembalian

Slide yang ditambahkan

## SlideCollection::InsertFromHtml(int32_t, System::String, bool) metode


Membuat slide dari teks HTML dan memasukkannya ke dalam koleksi pada posisi yang ditentukan.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Posisi untuk menyisipkan. |
| htmlText | [System::String](../../../system/string/) | HTML untuk ditambahkan. |
| useSlideWithIndexAsStart | **bool** | Flag ini menentukan cara memulai penyisipan: dari slide baru atau dari slide dengan indeks yang ditentukan. Jika **true**, maka penyisipan data akan dimulai dari ruang kosong pada slide dengan indeks yang ditentukan. Jika **false**, maka data akan ditambahkan ke slide yang dibuat. |

### Nilai Kembalian

Slide yang ditambahkan

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metode


Membuat slide dari teks HTML dan memasukkannya ke dalam koleksi pada posisi yang ditentukan.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Posisi untuk menyisipkan. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Objek TextReader yang akan digunakan sebagai sumber file HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| uri | [System::String](../../../system/string/) | URI dari HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |

### Nilai Kembalian

Slide yang ditambahkan.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) metode


Membuat slide dari teks HTML dan memasukkannya ke dalam koleksi pada posisi yang ditentukan.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Posisi untuk menyisipkan. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Objek TextReader yang akan digunakan sebagai sumber file HTML. |

### Nilai Kembalian

Slide yang ditambahkan

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metode


Membuat slide dari teks HTML dan memasukkannya ke dalam koleksi pada posisi yang ditentukan.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Posisi untuk menyisipkan. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Objek Stream yang akan digunakan sebagai sumber file HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| uri | [System::String](../../../system/string/) | URI dari HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |

### Nilai Kembalian

Slide yang ditambahkan.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) metode


Membuat slide dari teks HTML dan memasukkannya ke dalam koleksi pada posisi yang ditentukan.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Posisi untuk menyisipkan. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Objek Stream yang akan digunakan sebagai sumber file HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| uri | [System::String](../../../system/string/) | URI dari HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |
| useSlideWithIndexAsStart | **bool** | Flag ini menentukan cara memulai penyisipan: dari slide baru atau dari slide dengan indeks yang ditentukan. Jika **true**, maka penyisipan data akan dimulai dari ruang kosong pada slide dengan indeks yang ditentukan. Jika **false**, maka data akan ditambahkan ke slide yang dibuat. |

### Nilai Kembalian

Slide yang ditambahkan.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) metode


Membuat slide dari teks HTML dan memasukkannya ke dalam koleksi pada posisi yang ditentukan.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Posisi untuk menyisipkan. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Objek Stream yang akan digunakan sebagai sumber file HTML. |

### Nilai Kembalian

Slide yang ditambahkan

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) metode


Membuat slide dari teks HTML dan memasukkannya ke dalam koleksi pada posisi yang ditentukan.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Posisi untuk menyisipkan. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Objek Stream yang akan digunakan sebagai sumber file HTML. |
| useSlideWithIndexAsStart | **bool** | Flag ini menentukan cara memulai penyisipan: dari slide baru atau dari slide dengan indeks yang ditentukan. Jika **true**, maka penyisipan data akan dimulai dari ruang kosong pada slide dengan indeks yang ditentukan. Jika **false**, maka data akan ditambahkan ke slide yang dibuat. |

### Nilai Kembalian

Slide yang ditambahkan

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [String](../../../system/string/)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Class [SlideCollection](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)