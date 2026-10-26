---
title: SetAttribute()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengatur nilai atribut dengan nama yang ditentukan.
type: docs
weight: 222
url: /id/system.xml/xmlelement/setattribute/
---
## XmlElement::SetAttribute(String, String) metode


Mengatur nilai atribut dengan nama yang ditentukan.

```cpp
virtual void System::Xml::XmlElement::SetAttribute(String name, String value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama atribut yang akan dibuat atau diubah. Ini adalah nama yang memenuhi syarat. Jika nama mengandung tanda titik dua, maka akan diurai menjadi komponen prefiks dan nama lokal. |
| value | [String](../../../system/string/) | Nilai yang akan diatur untuk atribut. |

## XmlElement::SetAttribute(String, String, String) metode


Mengatur nilai atribut dengan nama lokal dan URI ruang nama yang ditentukan.

```cpp
virtual String System::Xml::XmlElement::SetAttribute(String localName, String namespaceURI, String value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Nama lokal atribut. |
| namespaceURI | [String](../../../system/string/) | URI ruang nama atribut. |
| value | [String](../../../system/string/) | Nilai yang akan diatur untuk atribut. |

### Nilai Kembali

Nilai atribut.

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlElement](../)
* Ruang Nama [System::Xml](../../)
* Pustaka [Aspose.Slides](../../../)