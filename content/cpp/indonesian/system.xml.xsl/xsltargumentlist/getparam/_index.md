---
title: GetParam()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan parameter yang terkait dengan nama yang memenuhi syarat namespace.
type: docs
weight: 14
url: /id/system.xml.xsl/xsltargumentlist/getparam/
---
## XsltArgumentList::GetParam(const String&, const String&) metode

Mengembalikan parameter yang terkait dengan nama yang memenuhi syarat namespace.

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::GetParam(const String &name, const String &namespaceUri)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nama parameter. [XsltArgumentList](../) tidak memeriksa untuk memastikan nama yang diberikan adalah nama lokal yang valid; namun, nama tidak boleh **nullptr**. |
| namespaceUri | const [String](../../../system/string/)\& | URI namespace yang terkait dengan parameter. |

### Nilai Kembali

Objek parameter atau **nullptr** jika tidak ditemukan.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Object](../../../system/object/)
* Kelas [String](../../../system/string/)
* Kelas [XsltArgumentList](../)
* Namespace [System::Xml::Xsl](../../)
* Perpustakaan [Aspose.Slides](../../../)