---
title: GetHostByAddress()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat instance IPHostEntry-class baru menggunakan representasi string yang ditentukan dari sebuah alamat IP.
type: docs
weight: 14
url: /id/system.net/dns/gethostbyaddress/
---
## Dns::GetHostByAddress(String) metode

Membuat instance IPHostEntry-class baru menggunakan representasi string yang ditentukan dari sebuah alamat IP.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(String address)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| address | [String](../../../system/string/) | Representasi string dari sebuah alamat IP. |

### Nilai Kembalian

Sebuah instance IPHostEntry-class yang baru dibuat.

## Dns::GetHostByAddress(System::SharedPtr\<IPAddress\>) metode

Membuat instance IPHostEntry-class baru menggunakan alamat IP yang ditentukan.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(System::SharedPtr<IPAddress> address)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | Alamat IP. |

### Nilai Kembalian

Sebuah instance IPHostEntry-class yang baru dibuat.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IPHostEntry](../../iphostentry/)
* Kelas [String](../../../system/string/)
* Kelas [Dns](../)
* Kelas [IPAddress](../../ipaddress/)
* Namespace [System::Net](../../)
* Perpustakaan [Aspose.Slides](../../../)