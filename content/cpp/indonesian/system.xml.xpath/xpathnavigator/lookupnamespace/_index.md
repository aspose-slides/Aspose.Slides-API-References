---
title: LookupNamespace()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan URI namespace untuk prefiks yang ditentukan.
type: docs
weight: 404
url: /id/system.xml.xpath/xpathnavigator/lookupnamespace/
---
## XPathNavigator::LookupNamespace(const String\&) metode


Mengembalikan URI namespace untuk prefiks yang ditentukan.

```cpp
String System::Xml::XPath::XPathNavigator::LookupNamespace(const String &prefix) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Prefiks yang URI namespace-nya ingin Anda selesaikan. Untuk mencocokkan namespace bawaan, berikan [String::Empty](../../../system/string/empty/). |

### Nilai Kembalian

Sebuah [String](../../../system/string/) yang berisi URI namespace yang diberikan ke prefiks namespace yang ditentukan; **nullptr** bila tidak ada URI namespace yang diberikan ke prefiks yang ditentukan. [String](../../../system/string/) yang dikembalikan diatomisasi.

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XPathNavigator](../)
* Ruang nama [System::Xml::XPath](../../)
* Perpustakaan [Aspose.Slides](../../../)