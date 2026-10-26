---
title: CreateElement()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat elemen dengan nama yang ditentukan.
type: docs
weight: 339
url: /id/system.xml/xmldocument/createelement/
---
## XmlDocument::CreateElement(const String\&) metode

Membuat elemen dengan nama yang ditentukan.

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &name)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nama yang memenuhi syarat dari elemen. Jika nama mengandung titik dua maka nilai [XmlNode::get_Prefix](../../xmlnode/get_prefix/) mencerminkan bagian nama sebelum titik dua dan nilai [XmlDocument::get_LocalName](../get_localname/) mencerminkan bagian nama setelah titik dua. Nama yang memenuhi syarat tidak boleh menyertakan awalan **xmlns**. |

### Nilai Kembali

[XmlElement](../../xmlelement/) baru.

## XmlDocument::CreateElement(const String\&, const String\&) metode

Membuat sebuah [XmlElement](../../xmlelement/) dengan nama yang memenuhi syarat dan [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &qualifiedName, const String &namespaceURI)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | Nama yang memenuhi syarat dari elemen. Jika nama mengandung titik dua maka nilai [XmlNode::get_Prefix](../../xmlnode/get_prefix/) akan mencerminkan bagian nama sebelum titik dua dan nilai [XmlDocument::get_LocalName](../get_localname/) akan mencerminkan bagian nama setelah titik dua. Nama yang memenuhi syarat tidak boleh menyertakan awalan **xmlns**. |
| namespaceURI | const [String](../../../system/string/)\& | URI ruang nama dari elemen. |

### Nilai Kembali

[XmlElement](../../xmlelement/) baru.

## XmlDocument::CreateElement(const String\&, const String\&, const String\&) metode

Membuat elemen dengan [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/), dan [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) yang ditentukan.

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &prefix, const String &localName, const String &namespaceURI)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Awalan elemen baru (jika ada). [String::Empty](../../../system/string/empty/) dan **nullptr** setara. |
| localName | const [String](../../../system/string/)\& | Nama lokal elemen baru. |
| namespaceURI | const [String](../../../system/string/)\& | URI ruang nama dari elemen baru (jika ada). [String::Empty](../../../system/string/empty/) dan **nullptr** setara. |

### Nilai Kembali

[XmlElement](../../xmlelement/) baru.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlElement](../../xmlelement/)
* Kelas [String](../../../system/string/)
* Kelas [XmlDocument](../)
* Namespace [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)