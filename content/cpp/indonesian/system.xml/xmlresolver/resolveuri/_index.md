---
title: ResolveUri()
second_title: Referensi API Aspose.Slides untuk C++
description: Saat dioverride dalam kelas turunan, menyelesaikan URI absolut dari URI dasar dan relatif.
type: docs
weight: 27
url: /id/system.xml/xmlresolver/resolveuri/
---
## XmlResolver::ResolveUri(SharedPtr\<Uri\>, String) metode


Saat dioverride dalam kelas turunan, menyelesaikan URI absolut dari URI dasar dan relatif.

```cpp
virtual SharedPtr<Uri> System::Xml::XmlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI dasar yang digunakan untuk menyelesaikan URI relatif. |
| relativeUri | [String](../../../system/string/) | URI yang akan diselesaikan. URI dapat bersifat absolut atau relatif. Jika absolut, nilai ini secara efektif menggantikan nilai **baseUri**. Jika relatif, nilai ini digabungkan dengan **baseUri** untuk membuat URI absolut. |

### Nilai Kembalian

URI absolut atau **nullptr** jika URI relatif tidak dapat diselesaikan.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Uri](../../../system/uri/)
* Kelas [String](../../../system/string/)
* Kelas [XmlResolver](../)
* Namespace [System::Xml](../../)
* Pustaka [Aspose.Slides](../../../)