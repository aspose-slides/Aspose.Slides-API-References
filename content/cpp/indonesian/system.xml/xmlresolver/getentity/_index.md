---
title: GetEntity()
second_title: Referensi API Aspose.Slides untuk C++
description: Saat dioverride dalam kelas turunan, memetakan URI ke objek yang berisi sumber daya sebenarnya.
type: docs
weight: 14
url: /id/system.xml/xmlresolver/getentity/
---
## XmlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) method

Saat dioverride dalam kelas turunan, memetakan URI ke objek yang berisi sumber daya sebenarnya.

```cpp
virtual SharedPtr<Object> System::Xml::XmlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI yang dikembalikan dari panggilan [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/). |
| role | [String](../../../system/string/) | Saat ini tidak digunakan. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Tipe objek yang akan dikembalikan. Versi saat ini hanya mengembalikan objek Stream. |

### Nilai Kembali

Objek stream atau **nullptr** jika tipe selain stream ditentukan.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)