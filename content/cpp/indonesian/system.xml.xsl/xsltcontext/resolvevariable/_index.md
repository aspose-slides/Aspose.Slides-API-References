---
title: ResolveVariable()
second_title: Referensi API Aspose.Slides untuk C++
description: Saat ditimpa dalam kelas turunan, menyelesaikan referensi variabel dan mengembalikan sebuah IXsltContextVariable yang mewakili variabel.
type: docs
weight: 14
url: /id/system.xml.xsl/xsltcontext/resolvevariable/
---
## XsltContext::ResolveVariable(String, String) metode

Saat ditimpa dalam kelas turunan, menyelesaikan referensi variabel dan mengembalikan sebuah [IXsltContextVariable](../../ixsltcontextvariable/) yang mewakili variabel.

```cpp
virtual SharedPtr<IXsltContextVariable> System::Xml::Xsl::XsltContext::ResolveVariable(String prefix, String name)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Awalan variabel sebagaimana muncul dalam ekspresi [XPath](../../../system.xml.xpath/). |
| name | [String](../../../system/string/) | Nama variabel. |

### Nilai Kembalian

Sebuah [IXsltContextVariable](../../ixsltcontextvariable/) yang mewakili variabel pada waktu berjalan.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IXsltContextVariable](../../ixsltcontextvariable/)
* Kelas [String](../../../system/string/)
* Kelas [XsltContext](../)
* Ruang Nama [System::Xml::Xsl](../../)
* Perpustakaan [Aspose.Slides](../../../)