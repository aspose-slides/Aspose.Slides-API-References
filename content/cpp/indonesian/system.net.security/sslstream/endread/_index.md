---
title: EndRead()
second_title: Referensi API Aspose.Slides untuk C++
description: Menunggu sampai operasi baca asynchronous yang ditentukan selesai.
type: docs
weight: 430
url: /id/system.net.security/sslstream/endread/
---
## SslStream::EndRead(System::SharedPtr\<IAsyncResult\>) metode

Menunggu sampai operasi baca asynchronous yang ditentukan selesai.

```cpp
int32_t System::Net::Security::SslStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Sebuah objek [IAsyncResult](../../../system/iasyncresult/) yang mewakili operasi baca asynchronous |

### Nilai Kembalian

Jumlah byte yang dibaca selama operasi baca yang diwakili oleh **asyncResult**

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)