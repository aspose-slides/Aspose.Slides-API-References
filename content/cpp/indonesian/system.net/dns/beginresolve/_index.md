---
title: BeginResolve()
second_title: Referensi API Aspose.Slides untuk C++
description: Memulai operasi asynchronous untuk membuat instance baru IPHostEntry-class menggunakan nama host yang ditentukan.
type: docs
weight: 157
url: /id/system.net/dns/beginresolve/
---
## Dns::BeginResolve(String, AsyncCallback, System::SharedPtr\<Object\>) metode

Memulai operasi asynchronous untuk membuat instance baru IPHostEntry-class menggunakan nama host yang ditentukan.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginResolve(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | Nama host yang digunakan untuk membuat instance baru [IPHostEntry](../../iphostentry/) class. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Callback yang akan dipanggil ketika operasi selesai. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Data yang disediakan pengguna yang digunakan untuk mengidentifikasi secara unik setiap operasi asynchronous. |

### Nilai Kembali

Objek [IAsyncResult](../../../system/iasyncresult/) yang mewakili operasi asynchronous yang dimulai.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Kelas [IAsyncResult](../../../system/iasyncresult/)
* Kelas [String](../../../system/string/)
* Kelas [Object](../../../system/object/)
* Kelas [Dns](../)
* Ruang Nama [System::Net](../../)
* Library [Aspose.Slides](../../../)