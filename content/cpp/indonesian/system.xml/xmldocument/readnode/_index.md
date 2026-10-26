---
title: ReadNode()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat objek XmlNode berdasarkan informasi dalam XmlReader. Pembaca harus berada pada node atau atribut.
type: docs
weight: 495
url: /id/system.xml/xmldocument/readnode/
---
## XmlDocument::ReadNode(SharedPtr\<XmlReader\>) metode

Membuat objek [XmlNode](../../xmlnode/) berdasarkan informasi dalam [XmlReader](../../xmlreader/). Pembaca harus ditempatkan pada node atau atribut.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::ReadNode(SharedPtr<XmlReader> reader)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | Sumber XML. |

### Nilai Kembalian

[XmlNode](../../xmlnode/) baru atau **nullptr** jika tidak ada lagi node.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlNode](../../xmlnode/)
* Kelas [XmlReader](../../xmlreader/)
* Kelas [XmlDocument](../)
* Ruang Nama [System::Xml](../../)
* Library [Aspose.Slides](../../../)