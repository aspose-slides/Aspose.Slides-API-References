---
title: get_ParentNode()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan induk dari node ini (untuk node yang dapat memiliki induk).
type: docs
weight: 53
url: /id/system.xml/xmlnode/get_parentnode/
---
## XmlNode::get_ParentNode() metode


Mengembalikan induk dari node ini (untuk node yang dapat memiliki induk).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::get_ParentNode() final
```


### Nilai Kembali

The [XmlNode](../) yang merupakan induk dari node saat ini.
## Catatan



Jika sebuah node baru saja dibuat dan belum ditambahkan ke pohon, atau jika node tersebut telah dihapus dari pohon, induknya adalah **nullptr**. Untuk semua node lainnya, nilai yang dikembalikan bergantung pada [XmlNode::get_NodeType](../get_nodetype/) dari node tersebut. Tabel berikut menjelaskan nilai kembali yang mungkin untuk metode **get_NodeType**. 

| NodeType | Nilai Kembali dari ParentNode |
| --- | --- |
| [Attribute](../../../system/attribute/), Document, DocumentFragment, Entity, Notation | Mengembalikan `nullptr`; node-node ini tidak memiliki induk. |
| CDATA | Mengembalikan elemen atau referensi entitas yang berisi bagian CDATA. |
| Comment | Mengembalikan elemen, referensi entitas, tipe dokumen, atau dokumen yang berisi komentar. |
| DocumentType | Mengembalikan node dokumen. |
| Element | Mengembalikan node induk dari elemen. Jika elemen adalah node akar dalam pohon, induknya adalah node dokumen. |
| EntityReference | Mengembalikan elemen, atribut, atau referensi entitas yang berisi referensi entitas. |
| ProcessingInstruction | Mengembalikan dokumen, elemen, tipe dokumen, atau referensi entitas yang berisi instruksi pemrosesan. |
| [Text](../../../system.text/)| Mengembalikan elemen induk, atribut, atau referensi entitas yang berisi node teks. |


## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlNode](../)
* Ruang Nama [System::Xml](../../)
* Library [Aspose.Slides](../../../)