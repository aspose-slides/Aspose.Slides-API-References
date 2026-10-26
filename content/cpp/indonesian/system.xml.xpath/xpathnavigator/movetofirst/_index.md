---
title: MoveToFirst()
second_title: Referensi API Aspose.Slides untuk C++
description: Memindahkan XPathNavigator ke node saudara pertama dari node saat ini.
type: docs
weight: 612
url: /id/system.xml.xpath/xpathnavigator/movetofirst/
---
## XPathNavigator::MoveToFirst() metode

Memindahkan [XPathNavigator](../) ke node saudara pertama dari node saat ini.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirst()
```

### Nilai Kembalian

**true** jika [XPathNavigator](../) berhasil berpindah ke node saudara pertama dari node saat ini; **false** jika tidak ada saudara pertama, atau jika [XPathNavigator](../) saat ini berada pada node atribut. Jika [XPathNavigator](../) sudah berada pada saudara pertama, [XPathNavigator](../) akan mengembalikan **true** dan tidak akan memindahkan posisinya. Jika [XPathNavigator::MoveToFirst](./) mengembalikan **false** karena tidak ada saudara pertama, atau jika [XPathNavigator](../) saat ini berada pada atribut, posisi [XPathNavigator](../) tidak berubah.

## Lihat Juga

* Kelas [XPathNavigator](../)
* Ruang Nama [System::Xml::XPath](../../)
* Pustaka [Aspose.Slides](../../../)