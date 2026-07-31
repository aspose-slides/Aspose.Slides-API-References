---
title: SupportsType()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah resolver mendukung Types lain selain Stream.
type: docs
weight: 66
url: /id/system.xml.resolvers/xmlpreloadedresolver/supportstype/
---
## XmlPreloadedResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) metode

Menentukan apakah resolver mendukung Types lain selain Stream.

```cpp
bool System::Xml::Resolvers::XmlPreloadedResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI absolut untuk diperiksa. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Type untuk dikembalikan. |

### Nilai Kembalian

**true** jika Type didukung; sebaliknya, **false**.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Uri](../../../system/uri/)
* Kelas [TypeInfo](../../../system/typeinfo/)
* Kelas [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)