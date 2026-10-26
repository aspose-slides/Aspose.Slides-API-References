---
title: ResolveUri()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyelesaikan URI absolut dari URI dasar dan relatif.
type: docs
weight: 40
url: /id/system.xml.resolvers/xmlpreloadedresolver/resolveuri/
---
## XmlPreloadedResolver::ResolveUri(SharedPtr\<Uri\>, String) metode

Menyelesaikan URI absolut dari URI dasar dan relatif.

```cpp
SharedPtr<Uri> System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI dasar yang digunakan untuk menyelesaikan URI relatif. |
| relativeUri | [String](../../../system/string/) | URI yang akan diselesaikan. URI dapat berupa absolut atau relatif. Jika absolut, nilai ini secara efektif menggantikan nilai **baseUri**. Jika relatif, nilai ini digabungkan dengan **baseUri** untuk membuat URI absolut. |

### Nilai Kembali

[Uri](../../../system/uri/) yang mewakili URI absolut atau **nullptr** jika URI relatif tidak dapat diselesaikan.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Uri](../../../system/uri/)
* Kelas [String](../../../system/string/)
* Kelas [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Perpustakaan [Aspose.Slides](../../../)