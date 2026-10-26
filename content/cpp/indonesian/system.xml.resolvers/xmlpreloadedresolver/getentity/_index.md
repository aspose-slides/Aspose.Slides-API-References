---
title: GetEntity()
second_title: Referensi API Aspose.Slides untuk C++
description: Memetakan sebuah URI ke objek yang berisi sumber daya aktual.
type: docs
weight: 53
url: /id/system.xml.resolvers/xmlpreloadedresolver/getentity/
---
## XmlPreloadedResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) metode

Memetakan sebuah URI ke objek yang berisi sumber daya aktual.

```cpp
SharedPtr<Object> System::Xml::Resolvers::XmlPreloadedResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI yang dikembalikan dari pemanggilan [XmlResolver::ResolveUri(SharedPtr<Uri>,String)](../../../system.xml/xmlresolver/resolveuri/). |
| role | [String](../../../system/string/) | Saat ini tidak digunakan. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Tipe objek yang akan dikembalikan. [XmlPreloadedResolver](../) mendukung objek Stream dan objek TextReader untuk URI yang ditambahkan sebagai [String](../../../system/string/). Jika tipe yang diminta tidak didukung oleh resolver, sebuah pengecualian akan dilemparkan. Gunakan metode XmlPreloadedResolver::SupportsType(SharedPtr<Uri>,TypeInfo) untuk menentukan apakah **Type** tertentu didukung oleh resolver ini. |

### Nilai Kembalian

Sebuah objek Stream atau TextReader yang sesuai dengan sumber asli.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Object](../../../system/object/)
* Kelas [Uri](../../../system/uri/)
* Kelas [String](../../../system/string/)
* Kelas [TypeInfo](../../../system/typeinfo/)
* Kelas [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)