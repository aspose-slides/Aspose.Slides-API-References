---
title: Evaluate()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengevaluasi ekspresi XPath yang ditentukan dan mengembalikan hasil berjenis.
type: docs
weight: 807
url: /id/system.xml.xpath/xpathnavigator/evaluate/
---
## XPathNavigator::Evaluate(String) metode

Mengevaluasi ekspresi [XPath](../../) yang ditentukan dan mengembalikan hasil berjenis.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Sebuah string yang mewakili ekspresi [XPath](../../) yang dapat dievaluasi. |

### Nilai Kembali

Hasil dari ekspresi ([Boolean](../../../system/boolean/), number, string, atau node set). Ini berkorespondensi dengan objek [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/), atau [XPathNodeIterator](../../xpathnodeiterator/) masing-masing.

## XPathNavigator::Evaluate(String, SharedPtr\<IXmlNamespaceResolver\>) metode

Mengevaluasi ekspresi [XPath](../../) yang ditentukan dan mengembalikan hasil berjenis, menggunakan objek [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) yang ditentukan untuk menyelesaikan prefiks namespace dalam ekspresi [XPath](../../).

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Sebuah string yang mewakili ekspresi [XPath](../../) yang dapat dievaluasi. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Objek [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) yang digunakan untuk menyelesaikan prefiks namespace dalam ekspresi [XPath](../../). |

### Nilai Kembali

Hasil dari ekspresi ([Boolean](../../../system/boolean/), number, string, atau node set). Ini berkorespondensi dengan objek [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/), atau [XPathNodeIterator](../../xpathnodeiterator/) masing-masing.

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>) metode

Mengevaluasi [XPathExpression](../../xpathexpression/) dan mengembalikan hasil berjenis.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Sebuah [XPathExpression](../../xpathexpression/) yang dapat dievaluasi. |

### Nilai Kembali

Hasil dari ekspresi ([Boolean](../../../system/boolean/), number, string, atau node set). Ini berkorespondensi dengan objek [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/), atau [XPathNodeIterator](../../xpathnodeiterator/) masing-masing.

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>, SharedPtr\<XPathNodeIterator\>) metode

Menggunakan konteks yang disediakan untuk mengevaluasi [XPathExpression](../../xpathexpression/), dan mengembalikan hasil berjenis.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr, SharedPtr<XPathNodeIterator> context)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Sebuah [XPathExpression](../../xpathexpression/) yang dapat dievaluasi. |
| context | [SharedPtr](../../../system/sharedptr/)\<[XPathNodeIterator](../../xpathnodeiterator/)\> | Sebuah [XPathNodeIterator](../../xpathnodeiterator/) yang menunjuk ke himpunan node terpilih tempat evaluasi akan dilakukan. |

### Nilai Kembali

Hasil dari ekspresi ([Boolean](../../../system/boolean/), number, string, atau node set). Ini berkorespondensi dengan objek [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/), atau [XPathNodeIterator](../../xpathnodeiterator/) masing-masing.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Object](../../../system/object/)
* Kelas [String](../../../system/string/)
* Kelas [XPathNavigator](../)
* Kelas [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Kelas [XPathExpression](../../xpathexpression/)
* Kelas [XPathNodeIterator](../../xpathnodeiterator/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)