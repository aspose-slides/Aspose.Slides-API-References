---
title: Uri()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah objek Uri yang merepresentasikan URI yang ditentukan.
type: docs
weight: 287
url: /id/system/uri/uri/
---
## Uri::Uri(const String\&) constructor

Membuat sebuah objek [Uri](../) yang merepresentasikan URI yang ditentukan.

```cpp
System::Uri::Uri(const String &uriString)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | The string URI to be represented by the object being constructed |

## Uri::Uri(const String\&, bool) constructor

Membuat sebuah objek [Uri](../) yang merepresentasikan URI yang ditentukan; sebuah argumen menentukan apakah URI harus di-escape.

```cpp
System::Uri::Uri(const String &uriString, bool dontEscape)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | The string URI to be represented by the object being constructed |
| dontEscape | **bool** | Menentukan apakah URI tidak perlu di-escape |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&, bool) constructor

Membuat sebuah [Uri](../) objek dari [Uri](../) yang ditentukan yang merepresentasikan URI dasar dan representasi string dari URI relatif; sebuah argumen menentukan apakah URI harus di-escape.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri, bool dontEscape)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | URI dasar |
| relativeUri | const [String](../../string/)\& | URI relatif yang ditambahkan ke URI dasar |
| dontEscape | **bool** | Menentukan apakah URI tidak perlu di-escape |

## Uri::Uri(const String\&, UriKind) constructor

Membuat sebuah objek [Uri](../) yang merepresentasikan URI yang ditentukan; sebuah argumen menentukan jenis URI.

```cpp
System::Uri::Uri(const String &uriString, UriKind uriKind)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | The string URI to be represented by the object being constructed |
| uriKind | [UriKind](../../urikind/) | Specifies the URI kind |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&) constructor

Membuat sebuah [Uri](../) objek dari URI dasar dan relatif yang ditentukan.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | URI dasar |
| relativeUri | const [String](../../string/)\& | URI relatif yang ditambahkan ke URI dasar |

## Uri::Uri(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) constructor

Membuat sebuah [Uri](../) objek dari URI dasar dan relatif yang ditentukan.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | URI dasar |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | URI relatif yang ditambahkan ke URI dasar |

## Lihat Juga

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)