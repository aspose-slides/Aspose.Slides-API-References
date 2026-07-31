---
title: Evaluate()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengevaluasi variabel pada runtime dan mengembalikan objek yang mewakili nilai variabel.
type: docs
weight: 40
url: /id/system.xml.xsl/ixsltcontextvariable/evaluate/
---
## IXsltContextVariable::Evaluate(SharedPtr\<XsltContext\>) metode


Evaluates the variable at runtime and returns an object that represents the value of the variable.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextVariable::Evaluate(SharedPtr<XsltContext> xsltContext)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | Sebuah [XsltContext](../../xsltcontext/) yang mewakili konteks eksekusi variabel. |

## Nilai Kembalian

Sebuah [Object](../../../system/object/) yang mewakili nilai variabel. Tipe nilai yang mungkin termasuk number, string, [Boolean](../../../system/boolean/), fragmen dokumen, atau kumpulan node.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Object](../../../system/object/)
* Kelas [XsltContext](../../xsltcontext/)
* Kelas [IXsltContextVariable](../)
* Ruang Nama [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)