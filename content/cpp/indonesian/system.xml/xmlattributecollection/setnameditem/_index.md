---
title: SetNamedItem()
second_title: Referensi API Aspose.Slides untuk C++
description: "Menambahkan sebuah XmlNode menggunakan hasil XmlNode::get_Name."
type: docs
weight: 14
url: /id/system.xml/xmlattributecollection/setnameditem/
---
## XmlAttributeCollection::SetNamedItem(SharedPtr\<XmlNode\>) metode

Menambahkan sebuah [XmlNode](../../xmlnode/) menggunakan hasil [XmlNode::get_Name](../../xmlnode/get_name/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttributeCollection::SetNamedItem(SharedPtr<XmlNode> node) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Sebuah node atribut untuk disimpan dalam koleksi ini. Node tersebut nantinya dapat diakses menggunakan nama node. Jika sebuah node dengan nama tersebut sudah ada dalam koleksi, node itu akan digantikan oleh yang baru; jika tidak, node akan ditambahkan ke akhir koleksi. |

### Nilai Kembali

Jika **node** menggantikan node yang ada dengan nama yang sama, node lama dikembalikan; jika tidak, node yang ditambahkan dikembalikan.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlNode](../../xmlnode/)
* Kelas [XmlAttributeCollection](../)
* Ruang Nama [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)