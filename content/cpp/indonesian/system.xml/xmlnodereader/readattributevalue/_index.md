---
title: ReadAttributeValue()
second_title: Aspose.Slides untuk Referensi API C++
description: Menganalisis nilai atribut menjadi satu atau lebih node Text, EntityReference, atau EndEntity.
type: docs
weight: 430
url: /id/system.xml/xmlnodereader/readattributevalue/
---
## XmlNodeReader::ReadAttributeValue() method

Menganalisis nilai atribut menjadi satu atau lebih **[Text](../../../system.text/)**, **EntityReference**, atau **EndEntity** node.

```cpp
bool System::Xml::XmlNodeReader::ReadAttributeValue() override
```

### Nilai Kembali

**true** jika ada node yang akan dikembalikan. **false** jika pembaca tidak berada pada node atribut ketika pemanggilan pertama dilakukan atau jika semua nilai atribut telah dibaca. Atribut kosong, misalnya, **misc=\"\"**, mengembalikan **true** dengan satu node dengan nilai [String::Empty](../../../system/string/empty/).

## Lihat Juga

* Kelas [XmlNodeReader](../)
* Ruang Nama [System::Xml](../../)
* Pustaka [Aspose.Slides](../../../)