---
title: ReadAttributeValue()
second_title: Referensi API Aspose.Slides untuk C++
description: Saat dioverride di kelas turunan, mem-parsing nilai atribut menjadi satu atau lebih node Text, EntityReference, atau EndEntity.
type: docs
weight: 677
url: /id/system.xml/xmlreader/readattributevalue/
---
## XmlReader::ReadAttributeValue() metode

When overridden in a derived class, parses the attribute value into one or more **[Text](../../../system.text/)**, **EntityReference**, or **EndEntity** nodes.

```cpp
virtual bool System::Xml::XmlReader::ReadAttributeValue()=0
```

### Nilai Kembalian

**true** jika ada node yang akan dikembalikan. **false** jika pembaca tidak berada pada node atribut ketika pemanggilan awal dilakukan atau jika semua nilai atribut telah dibaca. Atribut kosong, seperti, **misc=\"\"**, mengembalikan **true** dengan satu node dengan nilai [String::Empty](../../../system/string/empty/).

## Lihat Juga

* Kelas [XmlReader](../)
* Namespace [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)