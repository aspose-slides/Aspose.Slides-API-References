---
title: GetEntity()
second_title: Referensi API Aspose.Slides untuk C++
description: Memetakan URI ke objek yang berisi sumber daya sebenarnya.
type: docs
weight: 27
url: /id/system.xml/xmlsecureresolver/getentity/
---
## XmlSecureResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) metode

Memetakan URI ke objek yang berisi sumber daya sebenarnya.

```cpp
SharedPtr<Object> System::Xml::XmlSecureResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI yang dikembalikan dari pemanggilan [XmlSecureResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/). |
| role | [String](../../../system/string/) | Saat ini tidak digunakan. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Tipe objek yang akan dikembalikan. Versi saat ini hanya mengembalikan objek Stream. |

### Nilai Kembalian

Stream yang dikembalikan dengan memanggil **GetEntity** pada [XmlResolver](../../xmlresolver/) yang mendasari. Jika tipe selain Stream yang ditentukan, metode ini mengembalikan **nullptr**.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Object](../../../system/object/)
* Kelas [Uri](../../../system/uri/)
* Kelas [String](../../../system/string/)
* Kelas [TypeInfo](../../../system/typeinfo/)
* Kelas [XmlSecureResolver](../)
* Ruang Nama [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)