---
title: PreserveWhitespace()
second_title: Referensi API Aspose.Slides untuk C++
description: Saat dioverride di kelas turunan, mengevaluasi apakah akan mempertahankan node spasi putih atau menghapusnya untuk konteks yang diberikan.
type: docs
weight: 40
url: /id/system.xml.xsl/xsltcontext/preservewhitespace/
---
## XsltContext::PreserveWhitespace(SharedPtr\<System::Xml::XPath::XPathNavigator\>) metode

When overridden in a derived class, evaluates whether to preserve white space nodes or strip them for the given context.

```cpp
virtual bool System::Xml::Xsl::XsltContext::PreserveWhitespace(SharedPtr<System::Xml::XPath::XPathNavigator> node)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | Node spasi putih yang harus dipertahankan atau dihapus dalam konteks saat ini. |

### Nilai Kembali

**true** jika spasi putih harus dipertahankan; **false** jika spasi putih harus dihapus.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Kelas [XsltContext](../)
* Ruang Nama [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)