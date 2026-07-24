---
title: EndSend()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen eşzamanlı gönderim işlemi tamamlanana kadar bekler.
type: docs
weight: 508
url: /tr/system.net.sockets/socket/endsend/
---
## Socket::EndSend(System::SharedPtr\<IAsyncResult\>) metot

Belirtilen eşzamanlı gönderim işlemi tamamlanana kadar bekler.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Asenkron gönderim işlemini temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi. |

### Dönüş Değeri

Gönderilen baytların sayısı.

## Socket::EndSend(System::SharedPtr\<IAsyncResult\>, SocketError\&) metot

Belirtilen eşzamanlı gönderim işlemi tamamlanana kadar bekler.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Asenkron gönderim işlemini temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi. |
| errorCode | [SocketError](../../socketerror/)\& | Gönderim işlemi başarısız olduğunda hata kodunun atanacağı çıkış parametresi. |

### Dönüş Değeri

Gönderilen baytların sayısı.

## Ayrıca Bakınız

* Enum [SocketError](../../socketerror/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IAsyncResult](../../../system/iasyncresult/)
* Sınıf [Socket](../)
* Ad Alanı [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)