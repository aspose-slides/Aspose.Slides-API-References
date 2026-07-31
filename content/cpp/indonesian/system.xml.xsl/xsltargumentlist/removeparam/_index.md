---
title: RemoveParam()
second_title: Referensi API Aspose.Slides untuk C++
description: Menghapus parameter dari XsltArgumentList.
type: docs
weight: 66
url: /id/system.xml.xsl/xsltargumentlist/removeparam/
---
## XsltArgumentList::RemoveParam(const String\&, const String\&) metode

Menghapus parameter dari [XsltArgumentList](../).

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::RemoveParam(const String &name, const String &namespaceUri)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nama parameter yang akan dihapus. [XsltArgumentList](../) tidak melakukan pemeriksaan untuk memastikan bahwa nama yang diberikan adalah nama lokal yang valid; namun, nama tidak boleh **nullptr**. |
| namespaceUri | const [String](../../../system/string/)\& | URI namespace dari parameter yang akan dihapus. |

### Nilai Kembali

Objek parameter atau **nullptr** jika tidak ditemukan.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Object](../../../system/object/)
* Kelas [String](../../../system/string/)
* Kelas [XsltArgumentList](../)
* Ruang Nama [System::Xml::Xsl](../../)
* Pustaka [Aspose.Slides](../../../)