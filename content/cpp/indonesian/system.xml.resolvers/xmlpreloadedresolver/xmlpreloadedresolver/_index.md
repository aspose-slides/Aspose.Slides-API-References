---
title: XmlPreloadedResolver()
second_title: Aspose.Slides untuk Referensi API C++
description: Menginisialisasi instance baru dari kelas XmlPreloadedResolver.
type: docs
weight: 27
url: /id/system.xml.resolvers/xmlpreloadedresolver/xmlpreloadedresolver/
---
## XmlPreloadedResolver::XmlPreloadedResolver() konstruktor

Menginisialisasi instance baru dari kelas [XmlPreloadedResolver](../).

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver()
```

## XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds) konstruktor

Menginisialisasi instance baru dari kelas [XmlPreloadedResolver](../) dengan DTD yang dikenal sebelumnya yang telah dimuat.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds preloadedDtds)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | DTD yang dikenal sebelumnya yang harus dimasukkan ke dalam cache. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&) konstruktor

Menginisialisasi instance baru dari kelas [XmlPreloadedResolver](../) dengan resolver cadangan yang ditentukan.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) atau resolver buatan Anda. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds) konstruktor

Menginisialisasi instance baru dari kelas [XmlPreloadedResolver](../) dengan resolver cadangan yang ditentukan dan DTD yang dikenal sebelumnya yang telah dimuat.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) atau resolver buatan Anda. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | DTD yang dikenal sebelumnya yang harus dimasukkan ke dalam cache. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds, const SharedPtr\<Collections::Generic::IEqualityComparer\<SharedPtr\<Uri\>\>\>\&) konstruktor

Menginisialisasi instance baru dari kelas [XmlPreloadedResolver](../) dengan resolver cadangan yang ditentukan, DTD yang dikenal sebelumnya yang telah dimuat, dan pembanding kesetaraan URI.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds, const SharedPtr<Collections::Generic::IEqualityComparer<SharedPtr<Uri>>> &uriComparer)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) atau resolver buatan Anda. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | DTD yang dikenal sebelumnya yang harus dimasukkan ke dalam cache. |
| uriComparer | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\>\>\& | Implementasi antarmuka IEqualityComparer yang digunakan saat membandingkan URI. |

## Lihat Juga

* Enum [XmlKnownDtds](../../xmlknowndtds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlPreloadedResolver](../)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)
* Class [Uri](../../../system/uri/)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)