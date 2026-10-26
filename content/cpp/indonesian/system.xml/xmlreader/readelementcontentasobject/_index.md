---
title: ReadElementContentAsObject()
second_title: Referensi API Aspose.Slides untuk C++
description: Membaca elemen saat ini dan mengembalikan isinya sebagai Object.
type: docs
weight: 469
url: /id/system.xml/xmlreader/readelementcontentasobject/
---
## XmlReader::ReadElementContentAsObject() metode

Membaca elemen saat ini dan mengembalikan isinya sebagai [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject()
```

### Nilai Kembalian

Objek berkotak dari tipe yang paling sesuai. Nilai [XmlReader::get_ValueType](../get_valuetype/) menentukan tipe yang sesuai. Jika konten bertipe sebagai tipe daftar, metode ini mengembalikan array objek berkotak dari tipe yang sesuai.

## XmlReader::ReadElementContentAsObject(String, String) metode

Memeriksa bahwa nama lokal dan namespace URI yang ditentukan cocok dengan elemen saat ini, kemudian membaca elemen tersebut dan mengembalikan isinya sebagai [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject(String localName, String namespaceURI)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Nama lokal dari elemen. |
| namespaceURI | [String](../../../system/string/) | Namespace URI dari elemen. |

### Nilai Kembalian

Objek berkotak dari tipe yang paling sesuai. Nilai [XmlReader::get_ValueType](../get_valuetype/) menentukan tipe yang sesuai. Jika konten bertipe sebagai tipe daftar, metode ini mengembalikan array objek berkotak dari tipe yang sesuai.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Object](../../../system/object/)
* Kelas [XmlReader](../)
* Kelas [String](../../../system/string/)
* Ruang Nama [System::Xml](../../)
* Library [Aspose.Slides](../../../)