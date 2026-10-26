---
title: SupportsType()
second_title: Referensi API Aspose.Slides untuk C++
description: Memungkinkan resolver mengembalikan tipe selain Stream.
type: docs
weight: 40
url: /id/system.xml/xmlresolver/supportstype/
---
## XmlResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) metode

Memungkinkan resolver mengembalikan tipe selain Stream.

```cpp
virtual bool System::Xml::XmlResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Tipe yang akan dikembalikan. |

### Nilai Kembalian

**true** jika **type** didukung; jika tidak, **false**.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Uri](../../../system/uri/)
* Kelas [TypeInfo](../../../system/typeinfo/)
* Kelas [XmlResolver](../)
* Namespace [System::Xml](../../)
* Pustaka [Aspose.Slides](../../../)