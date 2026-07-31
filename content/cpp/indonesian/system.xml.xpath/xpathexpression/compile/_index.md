---
title: Compile()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyusun ekspresi XPath yang ditentukan dan mengembalikan objek XPathExpression yang mewakili ekspresi XPath.
type: docs
weight: 66
url: /id/system.xml.xpath/xpathexpression/compile/
---
## XPathExpression::Compile(const String\&) metode

Menyusun ekspresi [XPath](../../) yang ditentukan dan mengembalikan objek [XPathExpression](../) yang mewakili ekspresi [XPath](../../).

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Sebuah ekspresi [XPath](../../). |

### Nilai Kembalian

Sebuah objek [XPathExpression](../).

## XPathExpression::Compile(const String\&, const SharedPtr\<IXmlNamespaceResolver\>\&) metode

Menyusun ekspresi [XPath](../../) yang ditentukan, dengan objek [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) yang ditentukan untuk resolusi ruang nama, dan mengembalikan objek [XPathExpression](../) yang mewakili ekspresi [XPath](../../).

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath, const SharedPtr<IXmlNamespaceResolver> &nsResolver)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Sebuah ekspresi [XPath](../../). |
| nsResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | Sebuah objek yang mengimplementasikan antarmuka [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) untuk resolusi ruang nama. |

### Nilai Kembalian

Sebuah objek [XPathExpression](../).

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XPathExpression](../)
* Kelas [String](../../../system/string/)
* Kelas [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Ruang Nama [System::Xml::XPath](../../)
* Perpustakaan [Aspose.Slides](../../../)