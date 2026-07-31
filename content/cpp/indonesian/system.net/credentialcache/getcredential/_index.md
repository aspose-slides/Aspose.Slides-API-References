---
title: GetCredential()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan kredensial untuk prefiks URI yang ditentukan dan tipe otentikasi.
type: docs
weight: 66
url: /id/system.net/credentialcache/getcredential/
---
## CredentialCache::GetCredential(System::SharedPtr\<Uri\>, String) metode


Mengembalikan kredensial untuk prefiks URI yang ditentukan dan tipe otentikasi.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(System::SharedPtr<Uri> uriPrefix, String authenticationType) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Prefiks URI. |
| authenticationType | [String](../../../system/string/) | Tipe otentikasi. |

## CredentialCache::GetCredential(String, int32_t, String) metode


Mengembalikan kredensial untuk nama host, port, dan tipe otentikasi yang ditentukan.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(String host, int32_t port, String authenticationType) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| host | [String](../../../system/string/) | Nama host yang terkait dengan kredensial. |
| port | **int32_t** | Nomor port. |
| authenticationType | [String](../../../system/string/) | Tipe otentikasi. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [NetworkCredential](../../networkcredential/)
* Kelas [Uri](../../../system/uri/)
* Kelas [String](../../../system/string/)
* Kelas [CredentialCache](../)
* Namespace [System::Net](../../)
* Pustaka [Aspose.Slides](../../../)