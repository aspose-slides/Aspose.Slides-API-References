---
title: Load()
second_title: Referensi API Aspose.Slides untuk C++
description: Memuat dokumen XML dari URL yang ditentukan.
type: docs
weight: 508
url: /id/system.xml/xmldocument/load/
---
## XmlDocument::Load(String) metode

Membaca dokumen XML dari URL yang ditentukan.

```cpp
virtual void System::Xml::XmlDocument::Load(String filename)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filename | [String](../../../system/string/) | URL untuk file yang berisi dokumen XML yang akan dimuat. URL dapat berupa file lokal atau URL HTTP (alamat [Web](../../../system.web/)). |

## XmlDocument::Load(SharedPtr\<IO::Stream\>) metode

Membaca dokumen XML dari aliran yang ditentukan.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::Stream> inStream)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Aliran yang berisi dokumen XML yang akan dimuat. |

## XmlDocument::Load(SharedPtr\<IO::TextReader\>) metode

Membaca dokumen XML dari TextReader yang ditentukan.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::TextReader> txtReader)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| txtReader | [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | TextReader yang digunakan untuk memasukkan data XML ke dalam dokumen. |

## XmlDocument::Load(SharedPtr\<XmlReader\>) metode

Membaca dokumen XML dari [XmlReader](../../xmlreader/) yang ditentukan.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<XmlReader> reader)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | [XmlReader](../../xmlreader/) yang digunakan untuk memasukkan data XML ke dalam dokumen. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [String](../../../system/string/)
* Kelas [XmlDocument](../)
* Kelas [Stream](../../../system.io/stream/)
* Kelas [TextReader](../../../system.io/textreader/)
* Kelas [XmlReader](../../xmlreader/)
* Ruang nama [System::Xml](../../)
* Library [Aspose.Slides](../../../)