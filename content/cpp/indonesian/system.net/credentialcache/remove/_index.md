---
title: Remove()
second_title: Referensi API Aspose.Slides untuk C++
description: Menghapus kredensial jaringan untuk prefiks URI dan tipe otentikasi yang ditentukan.
type: docs
weight: 53
url: /id/system.net/credentialcache/remove/
---
## CredentialCache::Remove(System::SharedPtr\<Uri\>, String) metode

Menghapus kredensial jaringan untuk prefiks URI dan tipe otentikasi yang ditentukan.

```cpp
void System::Net::CredentialCache::Remove(System::SharedPtr<Uri> uriPrefix, String authenticationType)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Prefiks URI. |
| authenticationType | [String](../../../system/string/) | Tipe otentikasi. |

## CredentialCache::Remove(String, int32_t, String) metode

Menghapus kredensial jaringan untuk nama host, port, dan tipe otentikasi yang ditentukan.

```cpp
void System::Net::CredentialCache::Remove(String host, int32_t port, String authenticationType)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| host | [String](../../../system/string/) | Nama host yang terkait dengan kredensial. |
| port | **int32_t** | Nomor port. |
| authenticationType | [String](../../../system/string/) | Sebuah tipe otentikasi. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)