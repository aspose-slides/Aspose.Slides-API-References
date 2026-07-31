---
title: Deserialize()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendeserialisasi dokumen XML menjadi objek.
type: docs
weight: 14
url: /id/system.xml.serialization/xmlserializer/deserialize/
---
## XmlSerializer::Deserialize(System::SharedPtr\<IO::Stream\>) metode

Mendeserialisasi dokumen XML menjadi objek.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::Stream> stream)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Aliran untuk membaca dokumen. |

### Nilai Kembalian

[Object](../../../system/object/) yang sebelumnya diserialkan ke dalam dokumen yang diberikan.

## XmlSerializer::Deserialize(System::SharedPtr\<IO::TextReader\>) metode

Mendeserialisasi dokumen XML menjadi objek.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::TextReader> textReader)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| textReader | [System::SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | Pembaca untuk membaca dokumen. |

### Nilai Kembalian

[Object](../../../system/object/) yang sebelumnya diserialkan ke dalam dokumen yang diberikan.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>) metode

Mendeserialisasi dokumen XML menjadi objek.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Pembaca untuk membaca dokumen. |

### Nilai Kembalian

[Object](../../../system/object/) yang sebelumnya diserialkan ke dalam dokumen yang diberikan.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>, String) metode

Mendeserialisasi dokumen XML menjadi objek.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader, String encodingStyle)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Pembaca untuk membaca dokumen. |
| encodingStyle | [String](../../../system/string/) | Gaya yang digunakan untuk menyerialkan objek. |

### Nilai Kembalian

[Object](../../../system/object/) yang sebelumnya diserialkan ke dalam dokumen yang diberikan.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Object](../../../system/object/)
* Kelas [Stream](../../../system.io/stream/)
* Kelas [XmlSerializer](../)
* Kelas [TextReader](../../../system.io/textreader/)
* Kelas [XmlReader](../../../system.xml/xmlreader/)
* Kelas [String](../../../system/string/)
* Ruang Nama [System::Xml::Serialization](../../)
* Perpustakaan [Aspose.Slides](../../../)