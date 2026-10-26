---
title: ResolveUri()
second_title: Aspose.Slides untuk Referensi API C++
description: Menyelesaikan URI absolut dari URI dasar dan relatif.
type: docs
weight: 66
url: /id/system.xml/xmlurlresolver/resolveuri/
---
## XmlUrlResolver::ResolveUri(SharedPtr\<Uri\>, String) metode

Menyelesaikan URI absolut dari URI dasar dan relatif.

```cpp
SharedPtr<Uri> System::Xml::XmlUrlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI dasar yang digunakan untuk menyelesaikan URI relatif. |
| relativeUri | [String](../../../system/string/) | URI yang akan diselesaikan. URI dapat berupa absolut atau relatif. Jika absolut, nilai ini secara efektif menggantikan nilai **baseUri**. Jika relatif, nilai ini digabungkan dengan **baseUri** untuk membuat URI absolut. |

### Nilai Kembali

URI absolut, atau **nullptr** jika URI relatif tidak dapat diselesaikan.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Uri](../../../system/uri/)
* Kelas [String](../../../system/string/)
* Kelas [XmlUrlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)