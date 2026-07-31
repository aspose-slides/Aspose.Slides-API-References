---
title: Invoke()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyediakan metode untuk memanggil fungsi dengan argumen yang diberikan dalam konteks yang diberikan.
type: docs
weight: 53
url: /id/system.xml.xsl/ixsltcontextfunction/invoke/
---
## IXsltContextFunction::Invoke(SharedPtr\<XsltContext\>, ArrayPtr\<SharedPtr\<Object\>\>, SharedPtr\<System::Xml::XPath::XPathNavigator\>) metode

Menyediakan metode untuk memanggil fungsi dengan argumen yang diberikan dalam konteks yang diberikan.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextFunction::Invoke(SharedPtr<XsltContext> xsltContext, ArrayPtr<SharedPtr<Object>> args, SharedPtr<System::Xml::XPath::XPathNavigator> docContext)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | Konteks XSLT untuk pemanggilan fungsi. |
| args | [ArrayPtr](../../../system/arrayptr/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | Argumen panggilan fungsi. Setiap argumen adalah elemen dalam array. |
| docContext | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | Node konteks untuk pemanggilan fungsi. |

### Nilai Kembali

Sebuah [Object](../../../system/object/) yang mewakili nilai kembali dari fungsi.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [Object](../../../system/object/)
* Kelas [XsltContext](../../xsltcontext/)
* Kelas [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Kelas [IXsltContextFunction](../)
* Namespace [System::Xml::Xsl](../../)
* Pustaka [Aspose.Slides](../../../)