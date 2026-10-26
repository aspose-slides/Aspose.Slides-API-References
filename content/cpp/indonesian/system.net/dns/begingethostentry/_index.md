---
title: BeginGetHostEntry()
second_title: Referensi API Aspose.Slides untuk C++
description: Memulai operasi asinkron untuk membuat instance IPHostEntry-class baru menggunakan string yang ditentukan yang berisi nama host atau alamat IP.
type: docs
weight: 105
url: /id/system.net/dns/begingethostentry/
---
## Dns::BeginGetHostEntry(String, AsyncCallback, System::SharedPtr<Object>) metode

Memulai operasi asinkron untuk membuat instance kelas IPHostEntry baru menggunakan string yang berisi nama host atau alamat IP yang ditentukan.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | String yang berisi nama host atau alamat IP. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Callback yang dipanggil ketika operasi selesai. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)<[Object](../../../system/object/)> | Data yang disediakan pengguna yang digunakan untuk mengidentifikasi setiap operasi asinkron secara unik. |

### Nilai Kembali

Sebuah objek [IAsyncResult](../../../system/iasyncresult/) yang mewakili operasi asinkron yang dimulai.

## Dns::BeginGetHostEntry(System::SharedPtr<IPAddress>, AsyncCallback, System::SharedPtr<Object>) metode

Memulai operasi asinkron untuk membuat instance kelas IPHostEntry baru menggunakan alamat IP yang ditentukan.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(System::SharedPtr<IPAddress> address, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)<[IPAddress](../../ipaddress/)> | Alamat IP. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Callback yang dipanggil ketika operasi selesai. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)<[Object](../../../system/object/)> | Data yang disediakan pengguna yang digunakan untuk mengidentifikasi setiap operasi asinkron secara unik. |

### Nilai Kembali

Sebuah objek [IAsyncResult](../../../system/iasyncresult/) yang mewakili operasi asinkron yang dimulai.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Kelas [IAsyncResult](../../../system/iasyncresult/)
* Kelas [String](../../../system/string/)
* Kelas [Object](../../../system/object/)
* Kelas [Dns](../)
* Kelas [IPAddress](../../ipaddress/)
* Ruang Nama [System::Net](../../)
* Library [Aspose.Slides](../../../)