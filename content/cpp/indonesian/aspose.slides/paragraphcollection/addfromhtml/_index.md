---
title: AddFromHtml()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan teks dari string html yang ditentukan ke dalam koleksi.
type: docs
weight: 157
url: /id/aspose.slides/paragraphcollection/addfromhtml/
---
## ParagraphCollection::AddFromHtml(System::String) metode


Menambahkan teks dari string html yang ditentukan ke koleksi.

```cpp
void Aspise::Slides::ParagraphCollection::AddFromHtml(System::String text) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Teks HTML. |

## ParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metode


Menambahkan teks dari string html yang ditentukan ke koleksi.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Teks HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Objek panggilan balik resolver yang menyelesaikan URI dan mengambil objek yang direferensikan. |
| uri | [System::String](../../../system/string/) | URI untuk menambahkan dokumen HTML. Digunakan untuk menyelesaikan tautan relatif. |
## Catatan



Menentukan resolver dapat berpotensi memperkenalkan kerentanan. Gunakan dengan hati-hati.
## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [String](../../../system/string/)
* Kelas [ParagraphCollection](../)
* Kelas [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)