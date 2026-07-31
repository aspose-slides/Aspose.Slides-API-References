---
title: XmlNodeType
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan jenis node.
type: docs
weight: 833
url: /id/system.xml/xmlnodetype/
---
## XmlNodeType enum

Menentukan jenis node.

```cpp
enum class XmlNodeType
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| None | 0 | Ini dikembalikan oleh [XmlReader](../xmlreader/) jika metode **Read** belum dipanggil. |
| Element | 1 | Sebuah elemen (misalnya, **<item>**). |
| Attribute | 2 | Sebuah atribut (misalnya, **id='123'**). |
| Text | 3 | Konten teks dari sebuah node. Node [XmlNodeType::Text](./) tidak dapat memiliki node anak. Itu dapat muncul sebagai node anak dari node [XmlNodeType::Attribute](./), [XmlNodeType::DocumentFragment](./), [XmlNodeType::Element](./), dan [XmlNodeType::EntityReference](./). |
| CDATA | 4 | Sebuah bagian CDATA (misalnya, **my escaped text**). |
| EntityReference | 5 | Referensi ke entitas (misalnya, **&num;**). |
| Entity | 6 | Deklarasi entitas (misalnya, **<!ENTITY...>**). |
| ProcessingInstruction | 7 | Instruksi pemrosesan (misalnya, **<?pi test?>**). |
| Comment | 8 | Sebuah komentar (misalnya, ****). |
| Document | 9 | Objek dokumen yang, sebagai akar pohon dokumen, memberikan akses ke seluruh dokumen XML. |
| DocumentType | 10 | Deklarasi tipe dokumen, ditunjukkan oleh tag berikut (misalnya, **<!DOCTYPE...>**). |
| DocumentFragment | 11 | Sebuah fragmen dokumen. |
| Notation | 12 | Notasi dalam deklarasi tipe dokumen (misalnya, **<!NOTATION...>**). |
| Whitespace | 13 | Spasi putih di antara markup. |
| SignificantWhitespace | 14 | Spasi putih di antara markup dalam model konten campuran atau spasi putih di dalam ruang lingkup **xml:space=\"preserve\"**. |
| EndElement | 15 | Tag elemen akhir (misalnya, ****). |
| EndEntity | 16 | Dikembalikan ketika [XmlReader](../xmlreader/) mencapai akhir penggantian entitas sebagai hasil pemanggilan [XmlReader::ResolveEntity](../xmlreader/resolveentity/). |
| XmlDeclaration | 17 | Deklarasi XML (misalnya, **<?xml version='1.0'?>**). Node [XmlNodeType::XmlDeclaration](./) harus menjadi node pertama dalam dokumen. Node ini tidak dapat memiliki anak. Itu adalah anak dari node [XmlNodeType::Document](./). Ia dapat memiliki atribut yang menyediakan informasi versi dan enkoding. |

## Lihat Juga

* Ruang Nama [System::Xml](../)
* Pustaka [Aspose.Slides](../../)