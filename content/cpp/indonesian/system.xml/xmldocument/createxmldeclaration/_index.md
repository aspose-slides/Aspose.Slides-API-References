---
title: CreateXmlDeclaration()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat node XmlDeclaration dengan nilai yang ditentukan.
type: docs
weight: 378
url: /id/system.xml/xmldocument/createxmldeclaration/
---
## XmlDocument::CreateXmlDeclaration(const String\&, const String\&, const String\&) metode


Membuat node [XmlDeclaration](../../xmldeclaration/) dengan nilai yang ditentukan.

```cpp
virtual SharedPtr<XmlDeclaration> System::Xml::XmlDocument::CreateXmlDeclaration(const String &version, const String &encoding, const String &standalone)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| version | const [String](../../../system/string/)\& | Versi harus \"1.0\". |
| encoding | const [String](../../../system/string/)\& | Nilai atribut encoding. Ini adalah encoding yang digunakan ketika Anda menyimpan [XmlDocument](../) ke file atau aliran; oleh karena itu, harus diatur ke string yang didukung oleh kelas [Text::Encoding](../../../system.text/encoding/), jika tidak \"XmlDocument::Save(String)\" gagal. Jika ini **nullptr** atau [String::Empty](../../../system/string/empty/), metode [XmlDocument::Save](../save/) tidak menulis atribut encoding pada deklarasi XML dan sehingga encoding default, UTF-8, digunakan. |
| standalone | const [String](../../../system/string/)\& | Nilai harus \"yes\" atau \"no\". Jika ini **nullptr** atau [String::Empty](../../../system/string/empty/), metode [XmlDocument::Save](../save/) tidak menulis atribut standalone pada deklarasi XML. |

### Nilai Kembalian

Node [XmlDeclaration](../../xmldeclaration/) baru.
## Keterangan



Catatan: Jika [XmlDocument](../) disimpan ke TextWriter atau [XmlTextWriter](../../xmltextwriter/), nilai encoding ini dibuang. Sebaliknya, encoding dari TextWriter atau [XmlTextWriter](../../xmltextwriter/) yang digunakan. Ini memastikan bahwa XML yang dituliskan dapat dibaca kembali menggunakan encoding yang benar. 
## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlDeclaration](../../xmldeclaration/)
* Kelas [String](../../../system/string/)
* Kelas [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)