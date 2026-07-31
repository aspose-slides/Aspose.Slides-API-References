---
title: XmlValidatingReader()
second_title: Referensi API Aspose.Slides untuk C++
description: Menginisialisasi sebuah instance baru dari kelas XmlValidatingReader yang memvalidasi konten yang dikembalikan dari XmlReader yang diberikan.
type: docs
weight: 430
url: /id/system.xml/xmlvalidatingreader/xmlvalidatingreader/
---
## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<XmlReader\>\&) constructor


Menginisialisasi sebuah instance baru dari kelas [XmlValidatingReader](../) yang memvalidasi konten yang dikembalikan dari [XmlReader](../../xmlreader/) yang diberikan.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<XmlReader> &reader)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\>\& | [XmlReader](../../xmlreader/) yang akan dibaca saat memvalidasi. Implementasi saat ini hanya mendukung [XmlTextReader](../../xmltextreader/). |

## XmlValidatingReader::XmlValidatingReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor


Menginisialisasi sebuah instance baru dari kelas [XmlValidatingReader](../) dengan nilai yang ditentukan.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | String yang berisi fragmen XML yang akan diparsing. |
| fragType | [XmlNodeType](../../xmlnodetype/) | XmlNodeType dari fragmen XML. Ini juga menentukan apa yang dapat berisi string fragmen (lihat tabel di bawah). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/) tempat fragmen XML akan diparsing. Ini mencakup [NameTable](../../nametable/) yang akan digunakan, encoding, ruang lingkup namespace, **xml:lang** saat ini, dan ruang lingkup **xml:space**. |

## Keterangan



Tabel berikut mencantumkan nilai yang valid untuk **fragType** dan bagaimana pembaca mem-parsing setiap tipe node yang berbeda. 

| XmlNodeType | Fragment May Contain |
| --- | --- |
| Element| Konten elemen yang valid (misalnya, kombinasi elemen, komentar, instruksi pemrosesan, cdata, teks, dan referensi entitas). |
| [Attribute](../../../system/attribute/)| Nilai atribut (bagian di dalam tanda kutip). |
| Document| Isi dari seluruh dokumen XML; ini menegakkan aturan tingkat dokumen. |


## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor


Menginisialisasi sebuah instance baru dari kelas [XmlValidatingReader](../) dengan nilai yang ditentukan.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream yang berisi fragmen XML yang akan diparsing. |
| fragType | [XmlNodeType](../../xmlnodetype/) | XmlNodeType dari fragmen XML. Ini menentukan apa yang dapat berisi fragmen (lihat tabel di bawah). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/) tempat fragmen XML akan diparsing. Ini mencakup [XmlNameTable](../../xmlnametable/) yang akan digunakan, encoding, ruang lingkup namespace, **xml:lang** saat ini, dan ruang lingkup **xml:space**. |

## Keterangan



Tabel berikut mencantumkan nilai yang valid untuk **fragType** dan bagaimana pembaca mem-parsing setiap tipe node yang berbeda. 

| XmlNodeType | Fragment May Contain |
| --- | --- |
| Element| Konten elemen yang valid (misalnya, kombinasi elemen, komentar, instruksi pemrosesan, cdata, teks, dan referensi entitas). |
| [Attribute](../../../system/attribute/)| Nilai atribut (bagian di dalam tanda kutip). |
| Document| Isi dari seluruh dokumen XML; ini menegakkan aturan tingkat dokumen. |


## Lihat Juga

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlReader](../../xmlreader/)
* Kelas [XmlValidatingReader](../)
* Kelas [String](../../../system/string/)
* Kelas [XmlParserContext](../../xmlparsercontext/)
* Kelas [Stream](../../../system.io/stream/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)