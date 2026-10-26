---
title: InsertFromHtml
second_title: Referensi API Aspose.Sildes untuk .NET
description: Membuat slide dari teks HTML dan menyisipkannya ke dalam koleksi pada posisi yang ditentukan.
type: docs
weight: 140
url: /id/aspose.slides/slidecollection/insertfromhtml/
---
## InsertFromHtml(int, string, IExternalResourceResolver, string) {#insertfromhtml_7}

Membuat slide dari teks HTML dan menyisipkannya ke dalam koleksi pada posisi yang ditentukan.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | Int32 | Posisi untuk disisipkan. |
| htmlText | String | HTML yang akan ditambahkan. |
| resolver | IExternalResourceResolver | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| uri | String | URI dari HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |

### Nilai Kembalian

Slide yang ditambahkan.

### Lihat Juga

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, IExternalResourceResolver, string, bool) {#insertfromhtml_8}

Membuat slide dari teks HTML dan menyisipkannya ke dalam koleksi pada posisi yang ditentukan.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | Int32 | Posisi untuk disisipkan. |
| htmlText | String | HTML yang akan ditambahkan. |
| resolver | IExternalResourceResolver | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| uri | String | URI dari HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |
| useSlideWithIndexAsStart | Boolean | Bendera ini menentukan cara memulai penyisipan: dari slide baru atau dari slide dengan indeks yang ditentukan. Jika **true**, maka penyisipan data akan dimulai dari ruang kosong pada slide dengan indeks yang ditentukan. Jika **false**, maka data akan ditambahkan ke slide yang dibuat. |

### Nilai Kembalian

Slide yang ditambahkan.

### Lihat Juga

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string) {#insertfromhtml_6}

Membuat slide dari teks HTML dan menyisipkannya ke dalam koleksi pada posisi yang ditentukan.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | Int32 | Posisi untuk disisipkan. |
| htmlText | String | HTML yang akan ditambahkan. |

### Nilai Kembalian

Slide yang ditambahkan

### Lihat Juga

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, bool) {#insertfromhtml_9}

Membuat slide dari teks HTML dan menyisipkannya ke dalam koleksi pada posisi yang ditentukan.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, bool useSlideWithIndexAsStart)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | Int32 | Posisi untuk disisipkan. |
| htmlText | String | HTML yang akan ditambahkan. |
| useSlideWithIndexAsStart | Boolean | Bendera ini menentukan cara memulai penyisipan: dari slide baru atau dari slide dengan indeks yang ditentukan. Jika **true**, maka penyisipan data akan dimulai dari ruang kosong pada slide dengan indeks yang ditentukan. Jika **false**, maka data akan ditambahkan ke slide yang dibuat. |

### Nilai Kembalian

Slide yang ditambahkan

### Lihat Juga

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader, IExternalResourceResolver, string) {#insertfromhtml_5}

Membuat slide dari teks HTML dan menyisipkannya ke dalam koleksi pada posisi yang ditentukan.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader, 
    IExternalResourceResolver resolver, string uri)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | Int32 | Posisi untuk disisipkan. |
| htmlReader | TextReader | Objek TextReader yang akan digunakan sebagai sumber file HTML. |
| resolver | IExternalResourceResolver | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| uri | String | URI dari HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |

### Nilai Kembalian

Slide yang ditambahkan.

### Lihat Juga

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader) {#insertfromhtml_4}

Membuat slide dari teks HTML dan menyisipkannya ke dalam koleksi pada posisi yang ditentukan.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | Int32 | Posisi untuk disisipkan. |
| htmlReader | TextReader | Objek TextReader yang akan digunakan sebagai sumber file HTML. |

### Nilai Kembalian

Slide yang ditambahkan

### Lihat Juga

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string) {#insertfromhtml_1}

Membuat slide dari teks HTML dan menyisipkannya ke dalam koleksi pada posisi yang ditentukan.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | Int32 | Posisi untuk disisipkan. |
| htmlStream | Stream | Objek Stream yang akan digunakan sebagai sumber file HTML. |
| resolver | IExternalResourceResolver | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| uri | String | URI dari HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |

### Nilai Kembalian

Slide yang ditambahkan.

### Lihat Juga

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string, bool) {#insertfromhtml_2}

Membuat slide dari teks HTML dan menyisipkannya ke dalam koleksi pada posisi yang ditentukan.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | Int32 | Posisi untuk disisipkan. |
| htmlStream | Stream | Objek Stream yang akan digunakan sebagai sumber file HTML. |
| resolver | IExternalResourceResolver | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| uri | String | URI dari HTML yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |
| useSlideWithIndexAsStart | Boolean | Bendera ini menentukan cara memulai penyisipan: dari slide baru atau dari slide dengan indeks yang ditentukan. Jika **true**, maka penyisipan data akan dimulai dari ruang kosong pada slide dengan indeks yang ditentukan. Jika **false**, maka data akan ditambahkan ke slide yang dibuat. |

### Nilai Kembalian

Slide yang ditambahkan.

### Lihat Juga

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream) {#insertfromhtml}

Membuat slide dari teks HTML dan menyisipkannya ke dalam koleksi pada posisi yang ditentukan.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | Int32 | Posisi untuk disisipkan. |
| htmlStream | Stream | Objek Stream yang akan digunakan sebagai sumber file HTML. |

### Nilai Kembalian

Slide yang ditambahkan

### Lihat Juga

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, bool) {#insertfromhtml_3}

Membuat slide dari teks HTML dan menyisipkannya ke dalam koleksi pada posisi yang ditentukan.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, bool useSlideWithIndexAsStart)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | Int32 | Posisi untuk disisipkan. |
| htmlStream | Stream | Objek Stream yang akan digunakan sebagai sumber file HTML. |
| useSlideWithIndexAsStart | Boolean | Bendera ini menentukan cara memulai penyisipan: dari slide baru atau dari slide dengan indeks yang ditentukan. Jika **true**, maka penyisipan data akan dimulai dari ruang kosong pada slide dengan indeks yang ditentukan. Jika **false**, maka data akan ditambahkan ke slide yang dibuat. |

### Nilai Kembalian

Slide yang ditambahkan

### Lihat Juga

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->