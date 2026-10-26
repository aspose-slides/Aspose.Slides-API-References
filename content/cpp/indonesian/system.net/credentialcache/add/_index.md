---
title: Add()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan kredensial jaringan yang ditentukan ke cache.
type: docs
weight: 40
url: /id/system.net/credentialcache/add/
---
## CredentialCache::Add(System::SharedPtr\<Uri\>, String, System::SharedPtr\<NetworkCredential\>) metode

Menambahkan kredensial jaringan yang ditentukan ke cache.

```cpp
void System::Net::CredentialCache::Add(System::SharedPtr<Uri> uriPrefix, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Prefiks URI sumber daya yang terkait dengan kredensial. |
| authenticationType | [String](../../../system/string/) | Skema otentikasi. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | Kredensial yang akan ditambahkan. |

## CredentialCache::Add(String, int32_t, String, System::SharedPtr\<NetworkCredential\>) metode

Menambahkan kredensial jaringan yang ditentukan ke cache.

```cpp
void System::Net::CredentialCache::Add(String host, int32_t port, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| host | [String](../../../system/string/) | Nama host yang terkait dengan kredensial. |
| port | **int32_t** | Nomor port. |
| authenticationType | [String](../../../system/string/) | Skema otentikasi. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | Kredensial yang akan ditambahkan. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Uri](../../../system/uri/)
* Kelas [String](../../../system/string/)
* Kelas [NetworkCredential](../../networkcredential/)
* Kelas [CredentialCache](../)
* Ruang Nama [System::Net](../../)
* Library [Aspose.Slides](../../../)