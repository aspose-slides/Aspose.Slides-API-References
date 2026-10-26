---
title: ReadAttributeValue()
second_title: Referensi API Aspose.Slides untuk C++
description: Menganalisis nilai atribut menjadi satu atau lebih node Text, EntityReference, atau EndEntity.
type: docs
weight: 508
url: /id/system.xml/xmlvalidatingreader/readattributevalue/
---
## XmlValidatingReader::ReadAttributeValue() metode

Menganalisis nilai atribut menjadi satu atau lebih node **[Text](../../../system.text/)**, **EntityReference**, atau **EndEntity**.

```cpp
bool System::Xml::XmlValidatingReader::ReadAttributeValue() override
```

### Nilai Kembali

**true** jika ada node yang akan dikembalikan. **false** jika pembaca tidak berada pada node atribut ketika pemanggilan awal dilakukan atau jika semua nilai atribut telah dibaca. Atribut kosong, misalnya **misc=\"\"**, mengembalikan **true** dengan satu node yang memiliki nilai [String::Empty](../../../system/string/empty/).

## Lihat Juga

* Kelas [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)