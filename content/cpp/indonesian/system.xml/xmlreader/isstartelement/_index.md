---
title: IsStartElement()
second_title: Referensi API Aspose.Slides untuk C++
description: "Memanggil XmlReader::MoveToContent dan menguji apakah node konten saat ini adalah tag pembuka atau tag elemen kosong."
type: docs
weight: 885
url: /id/system.xml/xmlreader/isstartelement/
---
## XmlReader::IsStartElement() metode

Memanggil [XmlReader::MoveToContent](../movetocontent/) dan menguji apakah node konten saat ini adalah tag pembuka atau tag elemen kosong.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement()
```

### Nilai Kembalian

**true** jika [XmlReader::MoveToContent](../movetocontent/) menemukan tag pembuka atau tag elemen kosong; **false** jika tipe node selain [XmlNodeType::Element](../../xmlnodetype/) ditemukan.

## XmlReader::IsStartElement(String) metode

Memanggil [XmlReader::MoveToContent](../movetocontent/) dan menguji apakah node konten saat ini adalah tag pembuka atau tag elemen kosong serta apakah nilai [XmlReader::get_Name](../get_name/) dari elemen yang ditemukan cocok dengan argumen yang diberikan.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String name)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | String yang dicocokkan dengan nilai **Name** dari elemen yang ditemukan. |

### Nilai Kembalian

**true** jika node yang dihasilkan adalah elemen dan nilai **Name** cocok dengan string yang ditentukan. **false** jika tipe node selain [XmlNodeType::Element](../../xmlnodetype/) ditemukan atau nilai **Name** elemen tidak cocok dengan string yang ditentukan.

## XmlReader::IsStartElement(String, String) metode

Memanggil [XmlReader::MoveToContent](../movetocontent/) dan menguji apakah node konten saat ini adalah tag pembuka atau tag elemen kosong serta apakah nilai [XmlReader::get_LocalName](../get_localname/) dan [XmlReader::get_NamespaceURI](../get_namespaceuri/) dari elemen yang ditemukan cocok dengan string yang diberikan.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String localname, String ns)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localname | [String](../../../system/string/) | String yang akan dicocokkan dengan nilai **LocalName** dari elemen yang ditemukan. |
| ns | [String](../../../system/string/) | String yang akan dicocokkan dengan nilai **NamespaceURI** dari elemen yang ditemukan. |

### Nilai Kembalian

**true** jika node yang dihasilkan adalah elemen. **false** jika tipe node selain [XmlNodeType::Element](../../xmlnodetype/) ditemukan atau nilai **LocalName** dan **NamespaceURI** dari elemen tidak cocok dengan string yang ditentukan.

## Lihat Juga

* Kelas [XmlReader](../)
* Kelas [String](../../../system/string/)
* Ruang Nama [System::Xml](../../)
* Pustaka [Aspose.Slides](../../../)