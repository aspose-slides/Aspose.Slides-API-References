---
title: ReadAttributeValue()
second_title: Referensi API Aspose.Slides untuk C++
description: Menganalisis nilai atribut menjadi satu atau lebih node Text, EntityReference, atau EndEntity.
type: docs
weight: 560
url: /id/system.xml/xmltextreader/readattributevalue/
---
## XmlTextReader::ReadAttributeValue() metode


Menganalisis nilai atribut menjadi satu atau lebih **[Text](../../../system.text/)**, **EntityReference**, atau **EndEntity** node.

```cpp
bool System::Xml::XmlTextReader::ReadAttributeValue() override
```


### Nilai Kembali

**true** jika ada node yang akan dikembalikan. **false** jika pembaca tidak berada pada node atribut saat pemanggilan pertama dilakukan atau jika semua nilai atribut telah dibaca. Atribut kosong, seperti **misc=\"\"**, mengembalikan **true** dengan satu node yang memiliki nilai [String::Empty](../../../system/string/empty/).

## Lihat Juga

* Kelas [XmlTextReader](../)
* Ruang Nama [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)