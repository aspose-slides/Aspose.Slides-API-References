---
title: AddFromHtml()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan teks dari string html yang ditentukan ke koleksi.
type: docs
weight: 92
url: /id/aspose.slides/iparagraphcollection/addfromhtml/
---
## IParagraphCollection::AddFromHtml(System::String) metode

Menambahkan teks dari string html yang ditentukan ke koleksi.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Teks HTML. |

## IParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metode

Menambahkan teks dari string html yang ditentukan ke koleksi.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Teks HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objek callback resolver yang menyelesaikan URI dan mengambil objek yang dirujuk. |
| uri | [System::String](../../../system/string/) | URI untuk menambahkan dokumen HTML. Digunakan untuk menyelesaikan tautan relatif. |
## Catatan

Menentukan resolver dapat berpotensi menyebabkan kerentanan. Gunakan dengan hati-hati.
## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [String](../../../system/string/)
* Kelas [IParagraphCollection](../)
* Kelas [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)