---
title: ResolveUri()
second_title: Aspose.Slides untuk Referensi API C++
description: Menyelesaikan URI absolut dari URI dasar dan relatif dengan memanggil ResolveUri pada XmlResolver yang mendasarinya.
type: docs
weight: 40
url: /id/system.xml/xmlsecureresolver/resolveuri/
---
## XmlSecureResolver::ResolveUri(SharedPtr\<Uri\>, String) metode


Menyelesaikan URI absolut dari URI dasar dan relatif dengan memanggil **ResolveUri** pada [XmlResolver](../../xmlresolver/) yang mendasarinya.

```cpp
SharedPtr<Uri> System::Xml::XmlSecureResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI dasar yang digunakan untuk menyelesaikan URI relatif. |
| relativeUri | [String](../../../system/string/) | URI yang akan diselesaikan. URI dapat berupa absolut atau relatif. Jika absolut, nilai ini secara efektif menggantikan nilai **baseUri**. Jika relatif, ia digabungkan dengan **baseUri** untuk membuat URI absolut. |

### Nilai Kembali

URI absolut atau **nullptr** jika URI relatif tidak dapat diselesaikan (diperoleh dengan memanggil **ResolveUri** pada [XmlResolver](../../xmlresolver/) yang mendasarinya).

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Uri](../../../system/uri/)
* Kelas [String](../../../system/string/)
* Kelas [XmlSecureResolver](../)
* Ruang Nama [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)