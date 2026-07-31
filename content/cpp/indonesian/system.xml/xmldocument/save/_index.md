---
title: Save()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyimpan dokumen XML ke file yang ditentukan. Jika file yang ditentukan sudah ada, metode ini akan menimpanya.
type: docs
weight: 534
url: /id/system.xml/xmldocument/save/
---
## XmlDocument::Save(String) metode

Menyimpan dokumen XML ke file yang ditentukan. Jika file yang ditentukan sudah ada, metode ini akan menimpanya.

```cpp
virtual void System::Xml::XmlDocument::Save(String filename)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filename | [String](../../../system/string/) | Lokasi file tempat Anda ingin menyimpan dokumen. |

## XmlDocument::Save(SharedPtr\<IO::Stream\>) metode

Menyimpan dokumen XML ke aliran yang ditentukan.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::Stream> outStream)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Aliran tempat Anda ingin menyimpan. |

## XmlDocument::Save(SharedPtr\<IO::TextWriter\>) metode

Menyimpan dokumen XML ke TextWriter yang ditentukan.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::TextWriter> writer)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| writer | [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\> | TextWriter tempat Anda ingin menyimpan. |

## XmlDocument::Save(SharedPtr\<XmlWriter\>) metode

Menyimpan dokumen XML ke [XmlWriter](../../xmlwriter/) yang ditentukan.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<XmlWriter> w)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| w | [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../xmlwriter/)\> | [XmlWriter](../../xmlwriter/) tempat Anda ingin menyimpan. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Class [Stream](../../../system.io/stream/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XmlWriter](../../xmlwriter/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)