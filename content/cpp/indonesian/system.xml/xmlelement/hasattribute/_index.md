---
title: HasAttribute()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah node saat ini memiliki atribut dengan nama yang ditentukan.
type: docs
weight: 300
url: /id/system.xml/xmlelement/hasattribute/
---
## XmlElement::HasAttribute(String) metode

Menentukan apakah node saat ini memiliki atribut dengan nama yang ditentukan.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String name)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama atribut yang dicari. Ini adalah nama yang memenuhi syarat. Nilai ini dicocokkan dengan nilai **get_Name** dari node yang cocok. |

### Nilai Kembali

**true** jika node saat ini memiliki atribut yang ditentukan; jika tidak, **false**.

## XmlElement::HasAttribute(String, String) metode

Menentukan apakah node saat ini memiliki atribut dengan nama lokal dan URI namespace yang ditentukan.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String localName, String namespaceURI)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Nama lokal atribut yang dicari. |
| namespaceURI | [String](../../../system/string/) | URI namespace dari atribut yang dicari. |

### Nilai Kembali

**true** jika node saat ini memiliki atribut yang ditentukan; jika tidak, **false**.

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlElement](../)
* Namespace [System::Xml](../../)
* Pustaka [Aspose.Slides](../../../)