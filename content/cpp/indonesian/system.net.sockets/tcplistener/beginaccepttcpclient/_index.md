---
title: BeginAcceptTcpClient()
second_title: Referensi API Aspose.Slides untuk C++
description: Memulai operasi penerimaan secara asinkron.
type: docs
weight: 170
url: /id/system.net.sockets/tcplistener/beginaccepttcpclient/
---
## TcpListener::BeginAcceptTcpClient(AsyncCallback, System::SharedPtr\<Object\>) metode

Memulai operasi penerimaan secara asinkron.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptTcpClient(AsyncCallback callback, System::SharedPtr<Object> state)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Callback yang akan dipanggil ketika operasi selesai. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Data yang disediakan pengguna digunakan untuk mengidentifikasi secara unik setiap operasi koneksi asinkron. |

### Nilai Kembali

Sebuah objek [IAsyncResult](../../../system/iasyncresult/) yang mewakili operasi penerimaan asinkron yang dimulai.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Kelas [IAsyncResult](../../../system/iasyncresult/)
* Kelas [Object](../../../system/object/)
* Kelas [TcpListener](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)