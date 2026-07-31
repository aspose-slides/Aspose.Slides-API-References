---
title: Item()
second_title: Aspose.Slides untuk Referensi API C++
description: Mengambil node pada indeks yang ditentukan di XmlNamedNodeMap.
type: docs
weight: 53
url: /id/system.xml/xmlnamednodemap/item/
---
## XmlNamedNodeMap::Item(int32_t) metode


Mengambil node pada indeks yang ditentukan di [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::Item(int32_t index)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Posisi indeks node yang akan diambil dari [XmlNamedNodeMap](../). Indeks bersifat nol-berbasis; oleh karena itu, indeks node pertama adalah 0 dan indeks node terakhir adalah [XmlNamedNodeMap::get_Count](../get_count/) - 1. |

### Nilai Kembalian

[XmlNode](../../xmlnode/) pada indeks yang ditentukan. Jika **index** kurang dari 0 atau lebih besar atau sama dengan nilai [XmlNamedNodeMap::get_Count](../get_count/), **nullptr** dikembalikan.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlNode](../../xmlnode/)
* Kelas [XmlNamedNodeMap](../)
* Ruang Nama [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)