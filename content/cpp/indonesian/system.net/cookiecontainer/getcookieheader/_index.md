---
title: GetCookieHeader()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan header HTTP yang berisi cookie yang terkait dengan URI yang ditentukan.
type: docs
weight: 170
url: /id/system.net/cookiecontainer/getcookieheader/
---
## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>) metode

Mengembalikan header HTTP yang berisi cookie yang terkait dengan URI yang ditentukan.

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI yang akan digunakan untuk membangun nama header. |

### Nilai Kembalian

Header HTTP yang berisi cookie yang terkait dengan URI yang ditentukan.

## CookieContainer::GetCookieHeader(System::SharedPtr\<Uri\>, String\&) metode

Mengembalikan header HTTP yang berisi cookie yang terkait dengan URI yang ditentukan.

```cpp
String System::Net::CookieContainer::GetCookieHeader(System::SharedPtr<Uri> uri, String &optCookie2)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI yang akan digunakan untuk membangun nama header. |
| optCookie2 | [String](../../../system/string/)\& | Parameter output di mana cookie dengan versi dukungan maksimum akan diberikan. |

### Nilai Kembalian

Header HTTP yang berisi cookie yang terkait dengan URI yang ditentukan.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [String](../../../system/string/)
* Kelas [Uri](../../../system/uri/)
* Kelas [CookieContainer](../)
* Ruang Nama [System::Net](../../)
* Perpustakaan [Aspose.Slides](../../../)