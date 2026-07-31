---
title: MoveToContent()
second_title: Referensi API Aspose.Slides untuk C++
description: "Memeriksa apakah node saat ini merupakan konten (teks non-spasi putih, CDATA, Element, EndElement, EntityReference, atau EndEntity). Jika node bukan node konten, pembaca melompati ke node konten berikutnya atau akhir file. Ia melompati node dengan tipe berikut: ProcessingInstruction, DocumentType, Comment, Whitespace, atau SignificantWhitespace."
type: docs
weight: 833
url: /id/system.xml/xmlreader/movetocontent/
---
## XmlReader::MoveToContent() metode


Memeriksa apakah node saat ini adalah konten (teks non-spasi putih, **CDATA**, **Element**, **EndElement**, **EntityReference**, atau **EndEntity**) node. Jika node bukan node konten, pembaca melompati ke node konten berikutnya atau akhir file. Ia melompati node dengan tipe berikut: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, atau **SignificantWhitespace**.

```cpp
virtual XmlNodeType System::Xml::XmlReader::MoveToContent()
```


### Nilai Kembali

Nilai [XmlReader::get_NodeType](../get_nodetype/) dari node saat ini yang ditemukan oleh metode atau [XmlNodeType::None](../../xmlnodetype/) jika pembaca telah mencapai akhir aliran masukan.

## Lihat Juga

* Enum [XmlNodeType](../../xmlnodetype/)
* Kelas [XmlReader](../)
* Ruang Nama [System::Xml](../../)
* Library [Aspose.Slides](../../../)