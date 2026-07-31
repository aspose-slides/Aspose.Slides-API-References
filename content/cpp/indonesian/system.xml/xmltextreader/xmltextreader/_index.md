---
title: XmlTextReader()
second_title: Referensi API Aspose.Slides untuk C++
description: Menginisialisasi instance baru dari kelas XmlTextReader dengan aliran yang ditentukan.
type: docs
weight: 482
url: /id/system.xml/xmltextreader/xmltextreader/
---
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&) constructor


Menginisialisasi instance baru dari kelas [XmlTextReader](../) dengan aliran yang ditentukan.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Aliran yang berisi data XML untuk dibaca. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&) constructor


Menginisialisasi instance baru dari kelas [XmlTextReader](../) dengan URL dan aliran yang ditentukan.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL yang digunakan untuk menyelesaikan sumber daya eksternal. [XmlTextReader::get_BaseURI](../get_baseuri/) diatur ke nilai ini. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Aliran yang berisi data XML untuk dibaca. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) constructor


Menginisialisasi instance baru dari kelas [XmlTextReader](../) dengan aliran dan [XmlNameTable](../../xmlnametable/) yang ditentukan.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Aliran yang berisi data XML untuk dibaca. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) yang digunakan. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) constructor


Menginisialisasi instance baru dari kelas [XmlTextReader](../) dengan URL, aliran, dan [XmlNameTable](../../xmlnametable/) yang ditentukan.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL yang digunakan untuk menyelesaikan sumber daya eksternal. [XmlTextReader::get_BaseURI](../get_baseuri/) diatur ke nilai ini. Jika **url** adalah **nullptr**, **BaseURI** diatur ke [String::Empty](../../../system/string/empty/). |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Aliran yang berisi data XML untuk dibaca. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) yang digunakan. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&) constructor


Menginisialisasi instance baru dari kelas [XmlTextReader](../) dengan TextReader yang ditentukan.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | TextReader yang berisi data XML untuk dibaca. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&) constructor


Menginisialisasi instance baru dari kelas [XmlTextReader](../) dengan URL dan TextReader yang ditentukan.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL yang digunakan untuk menyelesaikan sumber daya eksternal. [XmlTextReader::get_BaseURI](../get_baseuri/) diatur ke nilai ini. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | TextReader yang berisi data XML untuk dibaca. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) constructor


Menginisialisasi instance baru dari kelas [XmlTextReader](../) dengan TextReader dan [XmlNameTable](../../xmlnametable/) yang ditentukan.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | TextReader yang berisi data XML untuk dibaca. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) yang digunakan. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) constructor


Menginisialisasi instance baru dari kelas [XmlTextReader](../) dengan URL, TextReader, dan [XmlNameTable](../../xmlnametable/) yang ditentukan.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL yang digunakan untuk menyelesaikan sumber daya eksternal. [XmlTextReader::get_BaseURI](../get_baseuri/) diatur ke nilai ini. Jika **url** adalah **nullptr**, **BaseURI** diatur ke [String::Empty](../../../system/string/empty/). |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | TextReader yang berisi data XML untuk dibaca. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) yang digunakan. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor


Menginisialisasi instance baru dari kelas [XmlTextReader](../) dengan aliran, XmlNodeType, dan [XmlParserContext](../../xmlparsercontext/) yang ditentukan.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Aliran yang berisi fragmen XML untuk diparse. |
| fragType | [XmlNodeType](../../xmlnodetype/) | XmlNodeType dari fragmen XML. Ini juga menentukan apa yang dapat dimuat oleh fragmen. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/) tempat **xmlFragment** akan diparse. Ini mencakup [XmlNameTable](../../xmlnametable/) yang digunakan, encoding, cakupan namespace, **xml:lang** saat ini, dan cakupan **xml:space**. |

## XmlTextReader::XmlTextReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor


Menginisialisasi instance baru dari kelas [XmlTextReader](../) dengan string, XmlNodeType, dan [XmlParserContext](../../xmlparsercontext/) yang ditentukan.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | String yang berisi fragmen XML untuk diparse. |
| fragType | [XmlNodeType](../../xmlnodetype/) | XmlNodeType dari fragmen XML. Ini juga menentukan apa yang dapat dimuat oleh fragmen string. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | [XmlParserContext](../../xmlparsercontext/) tempat **xmlFragment** akan diparse. Ini mencakup [XmlNameTable](../../xmlnametable/) yang digunakan, encoding, cakupan namespace, **xml:lang** saat ini, dan cakupan **xml:space**. |

## XmlTextReader::XmlTextReader(const String\&) constructor


Menginisialisasi instance baru dari kelas [XmlTextReader](../) dengan file yang ditentukan.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL untuk file yang berisi data XML. [XmlTextReader::get_BaseURI](../get_baseuri/) diatur ke nilai ini. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<XmlNameTable\>\&) constructor


Menginisialisasi instance baru dari kelas [XmlTextReader](../) dengan file dan [XmlNameTable](../../xmlnametable/) yang ditentukan.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<XmlNameTable> &nt)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL untuk file yang berisi data XML untuk dibaca. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) yang digunakan. |

## Lihat Juga

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlTextReader](../)
* Class [String](../../../system/string/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)