---
title: SetNamedItem()
second_title: Referensi API Aspose.Slides untuk C++
description: "Menambahkan sebuah XmlNode menggunakan nilai XmlNode::get_Name-nya."
type: docs
weight: 27
url: /id/system.xml/xmlnamednodemap/setnameditem/
---
## XmlNamedNodeMap::SetNamedItem(SharedPtr\<XmlNode\>) method


Menambahkan sebuah [XmlNode](../../xmlnode/) menggunakan nilai [XmlNode::get_Name](../../xmlnode/get_name/)-nya.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::SetNamedItem(SharedPtr<XmlNode> node)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Sebuah [XmlNode](../../xmlnode/) untuk disimpan dalam [XmlNamedNodeMap](../). Jika sebuah node dengan nama itu sudah ada dalam peta, maka akan digantikan oleh yang baru. |

### Nilai Kembalian

Jika **node** menggantikan node yang ada dengan nama yang sama, node lama dikembalikan; jika tidak, **nullptr** dikembalikan.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)