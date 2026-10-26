---
title: BeginGetHostAddresses()
second_title: Referensi API Aspose.Slides untuk C++
description: Memulai operasi asynchronous untuk membuat instance kelas IPHostEntry baru menggunakan string yang ditentukan yang berisi nama host atau alamat IP.
type: docs
weight: 131
url: /id/system.net/dns/begingethostaddresses/
---
## Dns::BeginGetHostAddresses(String, AsyncCallback, System::SharedPtr\<Object\>) method

Memulai operasi asynchronous untuk membuat instance kelas IPHostEntry baru menggunakan string yang ditentukan yang berisi nama host atau alamat IP.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostAddresses(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | Sebuah string yang berisi nama host atau alamat IP. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Sebuah callback yang dipanggil ketika operasi selesai. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Data yang disediakan pengguna yang digunakan untuk secara unik mengidentifikasi setiap operasi asynchronous. |

### Nilai Kembali

Sebuah objek [IAsyncResult](../../../system/iasyncresult/) yang mewakili operasi asynchronous yang dimulai.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Kelas [IAsyncResult](../../../system/iasyncresult/)
* Kelas [String](../../../system/string/)
* Kelas [Object](../../../system/object/)
* Kelas [Dns](../)
* Namespace [System::Net](../../)
* Perpustakaan [Aspose.Slides](../../../)