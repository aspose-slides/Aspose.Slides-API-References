---
title: SelectSingleNode()
second_title: Referensi API Aspose.Slides untuk C++
description: Memilih satu node dalam XPathNavigator menggunakan kueri XPath yang ditentukan.
type: docs
weight: 781
url: /id/system.xml.xpath/xpathnavigator/selectsinglenode/
---
## XPathNavigator::SelectSingleNode(String) metode

Memilih satu node dalam [XPathNavigator](../) menggunakan kueri [XPath](../../) yang ditentukan.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Sebuah [String](../../../system/string/) yang mewakili ekspresi [XPath](../../). |

### Nilai Kembali

Sebuah objek [XPathNavigator](../) yang berisi node pertama yang cocok untuk kueri [XPath](../../) yang ditentukan; jika tidak, **nullptr** jika tidak ada hasil kueri.

## XPathNavigator::SelectSingleNode(String, SharedPtr\<IXmlNamespaceResolver\>) metode

Memilih satu node dalam objek [XPathNavigator](../) menggunakan kueri [XPath](../../) yang ditentukan dengan objek [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) yang ditentukan untuk menyelesaikan awalan namespace.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Sebuah [String](../../../system/string/) yang mewakili ekspresi [XPath](../../). |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Objek [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) yang digunakan untuk menyelesaikan awalan namespace dalam kueri [XPath](../../). |

### Nilai Kembali

Sebuah objek [XPathNavigator](../) yang berisi node pertama yang cocok untuk kueri [XPath](../../) yang ditentukan; jika tidak, **nullptr** jika tidak ada hasil kueri.

## XPathNavigator::SelectSingleNode(SharedPtr\<XPathExpression\>) metode

Memilih satu node dalam [XPathNavigator](../) menggunakan objek [XPathExpression](../../xpathexpression/) yang ditentukan.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(SharedPtr<XPathExpression> expression)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| expression | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Sebuah objek [XPathExpression](../../xpathexpression/) yang berisi kueri [XPath](../../) yang telah dikompilasi. |

### Nilai Kembali

Sebuah objek [XPathNavigator](../) yang berisi node pertama yang cocok untuk kueri [XPath](../../) yang ditentukan; jika tidak, **nullptr** jika tidak ada hasil kueri.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XPathNavigator](../)
* Kelas [String](../../../system/string/)
* Kelas [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Kelas [XPathExpression](../../xpathexpression/)
* Ruang Nama [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)