---
title: EndRead()
second_title: Referensi API Aspose.Slides untuk C++
description: Menunggu hingga operasi pembacaan asinkron yang ditentukan selesai.
type: docs
weight: 261
url: /id/system.net.sockets/networkstream/endread/
---
## NetworkStream::EndRead(System::SharedPtr\<IAsyncResult\>) metode

Menunggu sampai operasi pembacaan asinkron yang ditentukan selesai.

```cpp
int32_t System::Net::Sockets::NetworkStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Sebuah objek [IAsyncResult](../../../system/iasyncresult/) yang mewakili operasi pembacaan asinkron |

### Return Value

Jumlah byte yang dibaca selama operasi pembacaan yang diwakili oleh **asyncResult**

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IAsyncResult](../../../system/iasyncresult/)
* Kelas [NetworkStream](../)
* Ruang Nama [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)