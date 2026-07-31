---
title: Read()
second_title: Referensi API Aspose.Slides untuk C++
description: "Membaca XML Schema dari IO::TextReader yang disediakan."
type: docs
weight: 365
url: /id/system.xml.schema/xmlschema/read/
---
## XmlSchema::Read(const SharedPtr\<IO::TextReader\>\&, ValidationEventHandler) metode


Membaca XML [Schema](../../) dari [IO::TextReader](../../../system.io/textreader/) yang disediakan.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::TextReader> &reader, ValidationEventHandler validationEventHandler)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | [IO::TextReader](../../../system.io/textreader/) yang berisi XML [Schema](../../) untuk dibaca. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Handler peristiwa validasi yang menerima informasi tentang kesalahan sintaks XML [Schema](../../). |

### Nilai Kembali

Objek [XmlSchema](../) yang mewakili XML [Schema](../../).

## XmlSchema::Read(const SharedPtr\<IO::Stream\>\&, ValidationEventHandler) metode


Membaca XML [Schema](../../) dari aliran yang disediakan.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::Stream> &stream, ValidationEventHandler validationEventHandler)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Aliran data yang disediakan. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Handler peristiwa validasi yang menerima informasi tentang kesalahan sintaks XML [Schema](../../). |

### Nilai Kembali

Objek [XmlSchema](../) yang mewakili XML [Schema](../../).

## XmlSchema::Read(const SharedPtr\<XmlReader\>\&, ValidationEventHandler) metode


Membaca XML [Schema](../../) dari [XmlReader](../../../system.xml/xmlreader/) yang disediakan.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<XmlReader> &reader, ValidationEventHandler validationEventHandler)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) yang berisi XML [Schema](../../) untuk dibaca. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Handler peristiwa validasi yang menerima informasi tentang kesalahan sintaks XML [Schema](../../). |

### Nilai Kembali

Objek [XmlSchema](../) yang mewakili XML [Schema](../../).

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Class [XmlSchema](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)