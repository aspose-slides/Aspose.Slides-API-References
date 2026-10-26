---
title: WriteNode()
second_title: Referensi API Aspose.Slides untuk C++
description: Saat ditimpa dalam kelas turunan, menyalin semua dari pembaca ke penulis dan memindahkan pembaca ke awal saudara berikutnya.
type: docs
weight: 430
url: /id/system.xml/xmlwriter/writenode/
---
## XmlWriter::WriteNode(SharedPtr\<XmlReader\>, bool) method

Saat ditimpa dalam kelas turunan, menyalin semua dari reader ke writer dan memindahkan reader ke awal saudara berikutnya.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XmlReader> reader, bool defattr)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | [XmlReader](../../xmlreader/) untuk dibaca. |
| defattr | **bool** | **true** untuk menyalin atribut default dari [XmlReader](../../xmlreader/); jika tidak, **false**. |

## XmlWriter::WriteNode(SharedPtr\<XPath::XPathNavigator\>, bool) method

Menyalin semua dari objek XPathNavigator ke writer. Posisi XPathNavigator tetap tidak berubah.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XPath::XPathNavigator> navigator, bool defattr)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| navigator | [SharedPtr](../../../system/sharedptr/)\<[XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | XPathNavigator untuk disalin. |
| defattr | **bool** | **true** untuk menyalin atribut default; jika tidak, **false**. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlReader](../../xmlreader/)
* Kelas [XmlWriter](../)
* Kelas [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)