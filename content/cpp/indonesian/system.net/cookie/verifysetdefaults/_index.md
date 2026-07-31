---
title: VerifySetDefaults()
second_title: Referensi API Aspose.Slides untuk C++
description: Memverifikasi dan menetapkan nilai atribut default.
type: docs
weight: 482
url: /id/system.net/cookie/verifysetdefaults/
---
## Cookie::VerifySetDefaults(CookieVariant, System::SharedPtr\<Uri\>, bool, String, bool, bool) metode

Memverifikasi dan menetapkan nilai atribut default.

```cpp
bool System::Net::Cookie::VerifySetDefaults(CookieVariant variant, System::SharedPtr<Uri> uri, bool isLocalDomain, String localDomain, bool setDefault, bool shouldThrow)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| variant | [CookieVariant](../../cookievariant/) | Spesifikasi cookie. |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Instance kelas Uri yang digunakan untuk menginisialisasi field internal. |
| isLocalDomain | **bool** | Nilai yang menunjukkan apakah cookie dipush ke domain lokal. |
| localDomain | [String](../../../system/string/) | Nama domain lokal. |
| setDefault | **bool** | Nilai yang menunjukkan apakah atribut cookie harus diinisialisasi menggunakan nilai defaultnya. |
| shouldThrow | **bool** | Nilai yang menunjukkan apakah sebuah pengecualian harus dilemparkan ketika nilai yang ditentukan tidak valid. |

### Nilai Kembalian

True ketika semua nilai valid, selain itu false.

## Lihat Juga

* Enum [CookieVariant](../../cookievariant/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Uri](../../../system/uri/)
* Kelas [String](../../../system/string/)
* Kelas [Cookie](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)