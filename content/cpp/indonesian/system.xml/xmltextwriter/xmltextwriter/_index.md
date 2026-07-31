---
title: XmlTextWriter()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah instance dari kelas XmlTextWriter menggunakan stream dan encoding yang ditentukan.
type: docs
weight: 183
url: /id/system.xml/xmltextwriter/xmltextwriter/
---
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Text::Encoding\>\&) konstruktor

Membuat sebuah instance dari kelas [XmlTextWriter](../) menggunakan stream dan encoding yang ditentukan.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::Stream> &w, const SharedPtr<Text::Encoding> &encoding)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream yang ingin Anda tulis ke dalamnya. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Encoding yang akan dihasilkan. Jika encoding **nullptr**, maka akan menulis stream sebagai UTF-8 dan menghilangkan atribut encoding dari **ProcessingInstruction**. |

## XmlTextWriter::XmlTextWriter(const String\&, const SharedPtr\<Text::Encoding\>\&) konstruktor

Membuat sebuah instance dari kelas [XmlTextWriter](../) menggunakan file yang ditentukan.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const String &filename, const SharedPtr<Text::Encoding> &encoding)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Nama file untuk ditulisi. Jika file sudah ada, akan memotongnya dan menimpa dengan konten baru. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Encoding yang akan dihasilkan. Jika encoding **nullptr**, maka akan menulis file sebagai UTF-8 dan menghilangkan atribut encoding dari **ProcessingInstruction**. |

## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::TextWriter\>\&) konstruktor

Membuat sebuah instance dari kelas [XmlTextWriter](../) menggunakan TextWriter yang ditentukan.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::TextWriter> &w)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter untuk menulis. Diasumsikan TextWriter sudah diatur ke encoding yang benar. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Stream](../../../system.io/stream/)
* Kelas [Encoding](../../../system.text/encoding/)
* Kelas [XmlTextWriter](../)
* Kelas [String](../../../system/string/)
* Kelas [TextWriter](../../../system.io/textwriter/)
* Namespace [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)