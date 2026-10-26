---
title: BeginGetHostByName()
second_title: Aspose.Slides untuk C++ Referensi API
description: Memulai operasi asinkron untuk membuat instance kelas IPHostEntry baru menggunakan nama host yang ditentukan.
type: docs
weight: 53
url: /id/system.net/dns/begingethostbyname/
---
## Dns::BeginGetHostByName(String, AsyncCallback, System::SharedPtr\<Object\>) metode

Memulai operasi asinkron untuk membuat instance kelas IPHostEntry baru menggunakan nama host yang ditentukan.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostByName(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | Sebuah nama host. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Callback yang akan dipanggil ketika operasi selesai. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Data yang diberikan pengguna untuk mengidentifikasi setiap operasi asinkron secara unik. |

### Nilai Kembali

Sebuah objek [IAsyncResult](../../../system/iasyncresult/) yang mewakili operasi asinkron yang dimulai.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Kelas [IAsyncResult](../../../system/iasyncresult/)
* Kelas [String](../../../system/string/)
* Kelas [Object](../../../system/object/)
* Kelas [Dns](../)
* Ruang Nama [System::Net](../../)
* Perpustakaan [Aspose.Slides](../../../)