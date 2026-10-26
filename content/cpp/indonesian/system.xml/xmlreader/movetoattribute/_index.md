---
title: MoveToAttribute()
second_title: Referensi API Aspose.Slides untuk C++
description: "Ketika ditimpa di kelas turunan, memindahkan ke atribut dengan nilai XmlReader::get_Name yang ditentukan."
type: docs
weight: 625
url: /id/system.xml/xmlreader/movetoattribute/
---
## XmlReader::MoveToAttribute(String) method

When overridden in a derived class, moves to the attribute with the specified [XmlReader::get_Name](../get_name/) value.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama kualifikasi atribut. |

### Nilai Kembali

**true** jika atribut ditemukan; bila tidak, **false**. Jika **false**, posisi pembaca tidak berubah.

## XmlReader::MoveToAttribute(String, String) method

When overridden in a derived class, moves to the attribute with the specified [XmlReader::get_LocalName](../get_localname/) and [XmlReader::get_NamespaceURI](../get_namespaceuri/) values.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name, String ns)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama lokal atribut. |
| ns | [String](../../../system/string/) | URI ruang nama atribut. |

### Nilai Kembali

**true** jika atribut ditemukan; bila tidak, **false**. Jika **false**, posisi pembaca tidak berubah.

## XmlReader::MoveToAttribute(int32_t) method

When overridden in a derived class, moves to the attribute with the specified index.

```cpp
virtual void System::Xml::XmlReader::MoveToAttribute(int32_t i)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| i | **int32_t** | Indeks atribut. |

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlReader](../)
* Ruang Nama [System::Xml](../../)
* Library [Aspose.Slides](../../../)