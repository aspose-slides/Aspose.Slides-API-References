---
title: TryCreate()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat objek Uri yang mewakili URI yang ditentukan; sebuah argumen menentukan jenis URI.
type: docs
weight: 508
url: /id/system/uri/trycreate/
---
## Uri::TryCreate(const String\&, UriKind, SharedPtr\<Uri\>\&) method


Membuat objek [Uri](../) yang mewakili URI yang ditentukan; sebuah argumen menentukan jenis URI.

```cpp
static bool System::Uri::TryCreate(const String &uriString, UriKind uriKind, SharedPtr<Uri> &result)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | The string URI to be represented by the object being constructed |
| uriKind | [UriKind](../../urikind/) | Specifies the URI kind |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | The output argument that, if the construction succeeds, points to the newly constructed [Uri](../) object on method return |

### Nilai Kembali

True jika konstruksi berhasil, jika tidak - false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const String\&, SharedPtr\<Uri\>\&) method


Membuat objek [Uri](../) dari objek [Uri](../) yang ditentukan yang mewakili URI dasar dan representasi string dari URI relatif.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const String &relativeUri, SharedPtr<Uri> &result)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | The base URI |
| relativeUri | const [String](../../string/)\& | The relative URI that is added to the base URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | The output argument that, if the construction succeeds, points to the newly constructed [Uri](../) object on method return |

### Nilai Kembali

True jika konstruksi berhasil, jika tidak - false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, SharedPtr\<Uri\>\&) method


Membuat objek [Uri](../) dari URI dasar dan relatif yang ditentukan.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri, SharedPtr<Uri> &result)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | The base URI |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | The relative URI that is added to the base URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | The output argument that, if the construction succeeds, points to the newly constructed [Uri](../) object on method return |

### Nilai Kembali

True jika konstruksi berhasil, jika tidak - false

## Lihat Juga

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Kelas [String](../../string/)
* Kelas [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)