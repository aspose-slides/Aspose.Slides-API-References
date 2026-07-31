---
title: GetEntity()
second_title: Referensi API Aspose.Slides untuk C++
description: Memetakan URI ke objek yang berisi sumber daya sebenarnya.
type: docs
weight: 53
url: /id/system.xml/xmlurlresolver/getentity/
---
## XmlUrlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) metode

Memetakan URI ke objek yang berisi sumber daya sebenarnya.

```cpp
SharedPtr<Object> System::Xml::XmlUrlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI yang dikembalikan dari pemanggilan [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../../xmlresolver/resolveuri/). |
| role | [String](../../../system/string/) | Saat ini tidak digunakan. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Tipe objek yang akan dikembalikan. Implementasi saat ini hanya mengembalikan objek Stream. |

### Nilai Kembalian

Objek stream atau **nullptr** jika tipe selain stream ditentukan.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Object](../../../system/object/)
* Kelas [Uri](../../../system/uri/)
* Kelas [String](../../../system/string/)
* Kelas [TypeInfo](../../../system/typeinfo/)
* Kelas [XmlUrlResolver](../)
* Ruang Nama [System::Xml](../../)
* Pustaka [Aspose.Slides](../../../)