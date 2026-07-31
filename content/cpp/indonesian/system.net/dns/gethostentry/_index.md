---
title: GetHostEntry()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah instance kelas IPHostEntry-class baru menggunakan string yang ditentukan yang berisi nama host atau alamat IP.
type: docs
weight: 79
url: /id/system.net/dns/gethostentry/
---
## Dns::GetHostEntry(String) metode

Membuat sebuah instance kelas IPHostEntry baru menggunakan string yang ditentukan yang berisi nama host atau alamat IP.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(String hostNameOrAddress)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | Sebuah string yang berisi nama host atau alamat IP. |

### Nilai Kembali

Sebuah instance kelas IPHostEntry yang baru dibuat.

## Dns::GetHostEntry(System::SharedPtr\<IPAddress\>) metode

Membuat sebuah instance kelas IPHostEntry baru menggunakan alamat IP yang ditentukan.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(System::SharedPtr<IPAddress> address)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | Alamat IP. |

### Nilai Kembali

Sebuah instance kelas IPHostEntry yang baru dibuat.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IPHostEntry](../../iphostentry/)
* Kelas [String](../../../system/string/)
* Kelas [Dns](../)
* Kelas [IPAddress](../../ipaddress/)
* Ruang Nama [System::Net](../../)
* Perpustakaan [Aspose.Slides](../../../)