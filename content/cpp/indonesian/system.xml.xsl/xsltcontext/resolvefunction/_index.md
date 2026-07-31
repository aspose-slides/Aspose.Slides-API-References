---
title: ResolveFunction()
second_title: Referensi API Aspose.Slides untuk C++
description: Saat di-override dalam kelas turunan, menyelesaikan referensi fungsi dan mengembalikan IXsltContextFunction yang mewakili fungsi tersebut. IXsltContextFunction digunakan pada waktu eksekusi untuk mendapatkan nilai kembali dari fungsi.
type: docs
weight: 27
url: /id/system.xml.xsl/xsltcontext/resolvefunction/
---
## XsltContext::ResolveFunction(String, String, ArrayPtr\<System::Xml::XPath::XPathResultType\>) metode

When overridden in a derived class, resolves a function reference and returns an [IXsltContextFunction](../../ixsltcontextfunction/) representing the function. The [IXsltContextFunction](../../ixsltcontextfunction/) is used at execution time to get the return value of the function.

```cpp
virtual SharedPtr<IXsltContextFunction> System::Xml::Xsl::XsltContext::ResolveFunction(String prefix, String name, ArrayPtr<System::Xml::XPath::XPathResultType> ArgTypes)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Awalan fungsi sebagaimana muncul dalam ekspresi [XPath](../../../system.xml.xpath/). |
| name | [String](../../../system/string/) | Nama fungsi. |
| ArgTypes | [ArrayPtr](../../../system/arrayptr/)\<[System::Xml::XPath::XPathResultType](../../../system.xml.xpath/xpathresulttype/)\> | Sebuah array tipe argumen untuk fungsi yang diselesaikan. Ini memungkinkan Anda memilih di antara metode dengan nama yang sama (misalnya, metode yang di-overload). |

### Nilai Kembalian

Sebuah [IXsltContextFunction](../../ixsltcontextfunction/) yang mewakili fungsi.

## Lihat Juga

* Enum [XPathResultType](../../../system.xml.xpath/xpathresulttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IXsltContextFunction](../../ixsltcontextfunction/)
* Class [String](../../../system/string/)
* Class [XsltContext](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)