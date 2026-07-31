---
title: GetCredential()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan kredensial untuk URI dan jenis autentikasi yang ditentukan.
type: docs
weight: 92
url: /id/system.net/networkcredential/getcredential/
---
## NetworkCredential::GetCredential(System::SharedPtr\<Uri\>, String) metode


Mengembalikan kredensial untuk URI dan jenis autentikasi yang ditentukan.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(System::SharedPtr<Uri> uri, String authenticationType) override
```


### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI. |
| authenticationType | [String](../../../system/string/) | Jenis autentikasi. |

## NetworkCredential::GetCredential(String, int32_t, String) metode


Mengembalikan kredensial untuk nama host, port, dan jenis autentikasi yang ditentukan.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(String host, int32_t port, String authenticationType) override
```


### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| host | [String](../../../system/string/) | Nama host. |
| port | **int32_t** | Nomor port. |
| authenticationType | [String](../../../system/string/) | Jenis autentikasi. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [NetworkCredential](../)
* Kelas [Uri](../../../system/uri/)
* Kelas [String](../../../system/string/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)