---
title: WriteStartElement()
second_title: Aspose.Slides for C++ Referensi API
description: Menulis tag pembuka yang ditentukan dan mengaitkannya dengan ruang nama dan awalan yang diberikan.
type: docs
weight: 235
url: /id/system.xml/xmltextwriter/writestartelement/
---
## XmlTextWriter::WriteStartElement(const String\&, const String\&, const String\&) method


Menulis tag pembuka yang ditentukan dan mengaitkannya dengan ruang nama dan awalan yang diberikan.

```cpp
void System::Xml::XmlTextWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Awalan ruang nama dari elemen. |
| localName | const [String](../../../system/string/)\& | Nama lokal dari elemen. |
| ns | const [String](../../../system/string/)\& | URI ruang nama yang akan dikaitkan dengan elemen. Jika ruang nama ini sudah berada dalam cakupan dan memiliki awalan yang terkait, maka penulis secara otomatis menulis awalan tersebut juga. |

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlTextWriter](../)
* Ruang Nama [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)