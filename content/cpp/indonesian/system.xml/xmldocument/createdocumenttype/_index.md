---
title: CreateDocumentType()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan objek XmlDocumentType baru.
type: docs
weight: 313
url: /id/system.xml/xmldocument/createdocumenttype/
---
## XmlDocument::CreateDocumentType(const String\&, const String\&, const String\&, const String\&) metode


Mengembalikan objek [XmlDocumentType](../../xmldocumenttype/) baru.

```cpp
virtual SharedPtr<XmlDocumentType> System::Xml::XmlDocument::CreateDocumentType(const String &name, const String &publicId, const String &systemId, const String &internalSubset)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nama tipe dokumen. |
| publicId | const [String](../../../system/string/)\& | Pengidentifikasi publik dari tipe dokumen atau **nullptr**. Anda dapat menentukan URI publik dan juga pengidentifikasi sistem untuk mengidentifikasi lokasi subset DTD eksternal. |
| systemId | const [String](../../../system/string/)\& | Pengidentifikasi sistem dari tipe dokumen atau **nullptr**. Menentukan URL lokasi file untuk subset DTD eksternal. |
| internalSubset | const [String](../../../system/string/)\& | Subset internal DTD dari tipe dokumen atau **nullptr**. |

### Nilai Kembalian

[XmlDocumentType](../../xmldocumenttype/) baru.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlDocumentType](../../xmldocumenttype/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)