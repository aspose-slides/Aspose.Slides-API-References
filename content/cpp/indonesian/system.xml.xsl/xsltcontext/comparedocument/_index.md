---
title: CompareDocument()
second_title: Referensi API Aspose.Slides untuk C++
description: Saat dioverride di kelas turunan, membandingkan Uniform Resource Identifier (URI) dasar dari dua dokumen berdasarkan urutan dokumen dimuat oleh prosesor XSLT (yaitu kelas XslTransform).
type: docs
weight: 53
url: /id/system.xml.xsl/xsltcontext/comparedocument/
---
## XsltContext::CompareDocument(String, String) method

Saat dioverride di kelas turunan, membandingkan Uniform Resource Identifier (URI) dasar dari dua dokumen berdasarkan urutan dokumen dimuat oleh prosesor XSLT (yaitu kelas [XslTransform](../../xsltransform/)).

```cpp
virtual int32_t System::Xml::Xsl::XsltContext::CompareDocument(String baseUri, String nextbaseUri)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| baseUri | [String](../../../system/string/) | URI dasar dari dokumen pertama yang akan dibandingkan. |
| nextbaseUri | [String](../../../system/string/) | URI dasar dari dokumen kedua yang akan dibandingkan. |

### Nilai Kembalian

Nilai integer yang menggambarkan urutan relatif dari dua URI dasar: -1 jika **baseUri** muncul sebelum **nextbaseUri**; 0 jika kedua URI dasar identik; dan 1 jika **baseUri** muncul setelah **nextbaseUri**.

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XsltContext](../)
* RuangNama [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)