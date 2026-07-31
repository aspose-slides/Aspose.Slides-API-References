---
title: ConformanceLevel
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan jumlah pemeriksaan input atau output yang dilakukan oleh objek XmlReader dan XmlWriter.
type: docs
weight: 625
url: /id/system.xml/conformancelevel/
---
## ConformanceLevel enum

Menentukan jumlah pemeriksaan input atau output yang dilakukan oleh objek [XmlReader](../xmlreader/) dan [XmlWriter](../xmlwriter/).

```cpp
enum class ConformanceLevel
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Auto | 0 | Objek [XmlReader](../xmlreader/) atau [XmlWriter](../xmlwriter/) secara otomatis mendeteksi apakah pemeriksaan tingkat dokumen atau tingkat fragmen yang harus dilakukan, dan melakukan pemeriksaan yang sesuai. Jika Anda membungkus objek [XmlReader](../xmlreader/) atau [XmlWriter](../xmlwriter/) lainnya, objek luar tidak melakukan pemeriksaan konformitas tambahan. Pemeriksaan konformitas diserahkan kepada objek yang mendasarinya. |
| Fragment | 1 | Data XML adalah sebuah [well-formed XML fragment](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities), seperti yang didefinisikan oleh W3C. Tingkat konformitas ini mewakili dokumen XML yang mungkin tidak memiliki elemen akar tetapi tetap terstruktur dengan baik. Tingkat pemeriksaan ini memastikan bahwa aliran yang dibaca atau ditulis dapat diproses oleh penyaji mana pun sebagai [XML 1.0 external parsed entity](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities). |
| Document | 2 | Data XML mematuhi aturan untuk [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed) yang terstruktur dengan baik, seperti yang didefinisikan oleh W3C. Tingkat pemeriksaan ini memastikan bahwa aliran yang dibaca atau ditulis dapat diproses oleh penyaji mana pun sebagai [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed). |

## Lihat Juga

* Ruang nama [System::Xml](../)
* Perpustakaan [Aspose.Slides](../../)