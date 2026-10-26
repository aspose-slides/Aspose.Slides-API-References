---
title: Select()
second_title: Referensi API Aspose.Slides untuk C++
description: Memilih sekumpulan node, menggunakan ekspresi XPath yang ditentukan.
type: docs
weight: 794
url: /id/system.xml.xpath/xpathnavigator/select/
---
## XPathNavigator::Select(String) metode

Memilih satu set node, menggunakan ekspresi [XPath](../../) yang ditentukan.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Sebuah [String](../../../system/string/) yang mewakili ekspresi [XPath](../../). |

### Nilai Kembalian

Sebuah [XPathNodeIterator](../../xpathnodeiterator/) yang menunjuk ke set node yang dipilih.

## XPathNavigator::Select(String, SharedPtr\<IXmlNamespaceResolver\>) metode

Memilih satu set node menggunakan ekspresi [XPath](../../) yang ditentukan dengan objek [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) yang digunakan untuk menyelesaikan prefiks namespace.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Sebuah [String](../../../system/string/) yang mewakili ekspresi [XPath](../../). |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Objek [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) yang digunakan untuk menyelesaikan prefiks namespace. |

### Nilai Kembalian

Sebuah [XPathNodeIterator](../../xpathnodeiterator/) yang menunjuk ke set node yang dipilih.

## XPathNavigator::Select(SharedPtr\<XPathExpression\>) metode

Memilih satu set node menggunakan [XPathExpression](../../xpathexpression/) yang ditentukan.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(SharedPtr<XPathExpression> expr)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Sebuah objek [XPathExpression](../../xpathexpression/) yang berisi kueri [XPath](../../) yang telah dikompilasi. |

### Nilai Kembalian

Sebuah [XPathNodeIterator](../../xpathnodeiterator/) yang menunjuk ke set node yang dipilih.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XPathNodeIterator](../../xpathnodeiterator/)
* Kelas [String](../../../system/string/)
* Kelas [XPathNavigator](../)
* Kelas [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Kelas [XPathExpression](../../xpathexpression/)
* Ruang Nama [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)