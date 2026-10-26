---
title: ReadStartElement()
second_title: Referensi API Aspose.Slides untuk C++
description: Memeriksa bahwa node saat ini adalah elemen dan memajukan pembaca ke node berikutnya.
type: docs
weight: 846
url: /id/system.xml/xmlreader/readstartelement/
---
## XmlReader::ReadStartElement() metode

Memeriksa bahwa node saat ini adalah elemen dan memajukan pembaca ke node berikutnya.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement()
```

## XmlReader::ReadStartElement(String) metode

Memeriksa bahwa node konten saat ini adalah elemen dengan nilai [XmlReader::get_Name](../get_name/) yang diberikan dan memajukan pembaca ke node berikutnya.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String name)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama terkwalifikasi dari elemen. |

## XmlReader::ReadStartElement(String, String) metode

Memeriksa bahwa node konten saat ini adalah elemen dengan nilai [XmlReader::get_LocalName](../get_localname/) dan [XmlReader::get_NamespaceURI](../get_namespaceuri/) yang diberikan dan memajukan pembaca ke node berikutnya.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String localname, String ns)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Nama lokal elemen. |
| ns | [String](../../../system/string/) | URI namespace dari elemen. |

## Lihat Juga

* Kelas [XmlReader](../)
* Kelas [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)