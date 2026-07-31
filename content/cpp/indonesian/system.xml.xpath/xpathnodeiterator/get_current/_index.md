---
title: get_Current()
second_title: Referensi API Aspose.Slides untuk C++
description: Saat dioverride dalam kelas turunan, mendapatkan objek XPathNavigator untuk XPathNodeIterator ini, yang diposisikan pada node konteks saat ini.
type: docs
weight: 1
url: /id/system.xml.xpath/xpathnodeiterator/get_current/
---
## XPathNodeIterator::get_Current() metode

Saat dioverride dalam kelas turunan, mendapatkan objek [XPathNavigator](../../xpathnavigator/) untuk [XPathNodeIterator](../) ini, yang diposisikan pada node konteks saat ini.

```cpp
virtual const SharedPtr<XPathNavigator> & System::Xml::XPath::XPathNodeIterator::get_Current()=0
```

### Nilai Kembali

Sebuah objek [XPathNavigator](../../xpathnavigator/) yang diposisikan pada node konteks dari mana set node dipilih. [XPathNodeIterator::MoveNext](../movenext/) metode harus dipanggil untuk memindahkan [XPathNodeIterator](../) ke node pertama dalam set yang dipilih.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XPathNavigator](../../xpathnavigator/)
* Kelas [XPathNodeIterator](../)
* Ruang Nama [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)