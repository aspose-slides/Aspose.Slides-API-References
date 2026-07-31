---
title: PrependChild()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan node yang ditentukan ke awal daftar node anak untuk node ini.
type: docs
weight: 261
url: /id/system.xml/xmlattribute/prependchild/
---
## XmlAttribute::PrependChild(SharedPtr\<XmlNode\>) metode


Menambahkan node yang ditentukan ke awal daftar node anak untuk node ini.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::PrependChild(SharedPtr<XmlNode> newChild) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/) yang akan ditambahkan. Jika itu adalah [XmlDocumentFragment](../../xmldocumentfragment/), seluruh isi fragmen dokumen dipindahkan ke dalam daftar anak node ini. |

### Nilai Kembalian

[XmlNode](../../xmlnode/) yang ditambahkan.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlNode](../../xmlnode/)
* Kelas [XmlAttribute](../)
* Ruang Nama [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)