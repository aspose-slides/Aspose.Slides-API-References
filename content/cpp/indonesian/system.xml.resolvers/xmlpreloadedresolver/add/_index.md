---
title: Add()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan array byte ke penyimpanan XmlPreloadedResolver dan memetakannya ke URI. Jika penyimpanan sudah berisi pemetaan untuk URI yang sama, pemetaan yang ada akan ditimpa.
type: docs
weight: 79
url: /id/system.xml.resolvers/xmlpreloadedresolver/add/
---
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&) method


Menambahkan array byte ke penyimpanan [XmlPreloadedResolver](../) dan memetakan ke URI. Jika penyimpanan sudah berisi pemetaan untuk URI yang sama, pemetaan yang ada akan ditimpa.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | URI data yang sedang ditambahkan ke penyimpanan [XmlPreloadedResolver](../). |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Array byte dengan data yang sesuai dengan URI yang diberikan. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Menambahkan array byte ke penyimpanan [XmlPreloadedResolver](../) dan memetakan ke URI. Jika penyimpanan sudah berisi pemetaan untuk URI yang sama, pemetaan yang ada akan ditimpa.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value, int32_t offset, int32_t count)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | URI data yang sedang ditambahkan ke penyimpanan [XmlPreloadedResolver](../). |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Array byte dengan data yang sesuai dengan URI yang diberikan. |
| offset | **int32_t** | Offset dalam array byte yang diberikan tempat data dimulai. |
| count | **int32_t** | Jumlah byte yang akan dibaca dari array byte, mulai dari offset yang diberikan. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const SharedPtr\<IO::Stream\>\&) method


Menambahkan Stream ke penyimpanan [XmlPreloadedResolver](../) dan memetakan ke URI. Jika penyimpanan sudah berisi pemetaan untuk URI yang sama, pemetaan yang ada akan ditimpa.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const SharedPtr<IO::Stream> &value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | URI data yang sedang ditambahkan ke penyimpanan [XmlPreloadedResolver](../). |
| value | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream dengan data yang sesuai dengan URI yang diberikan. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const String\&) method


Menambahkan string dengan data yang dipra-muat ke penyimpanan [XmlPreloadedResolver](../) dan memetakan ke URI. Jika penyimpanan sudah berisi pemetaan untuk URI yang sama, pemetaan yang ada akan ditimpa.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const String &value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | URI data yang sedang ditambahkan ke penyimpanan [XmlPreloadedResolver](../). |
| value | const [String](../../../system/string/)\& | Sebuah [String](../../../system/string/) dengan data yang sesuai dengan URI yang diberikan. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Uri](../../../system/uri/)
* Class [XmlPreloadedResolver](../)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)