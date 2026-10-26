---
title: EndReceive()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen asenkron alma işlemi tamamlanana kadar bekler.
type: docs
weight: 534
url: /tr/system.net.sockets/socket/endreceive/
---
## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>) yöntem


Belirtilen asenkron alma işlemi tamamlanana kadar bekler.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult)
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | [IAsyncResult](../../../system/iasyncresult/) nesnesi, asenkron bir alma işlemini temsil eder. |

### Dönüş Değeri

Alınan bayt sayısı.

## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>, SocketError\&) yöntemi


Belirtilen asenkron alma işlemi tamamlanana kadar bekler.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | [IAsyncResult](../../../system/iasyncresult/) nesnesi, asenkron bir alma işlemini temsil eder. |
| errorCode | [SocketError](../../socketerror/)\& | Alma işlemi başarısız olduğunda hata kodunun atanacağı çıktı parametresi. |

### Dönüş Değeri

Alınan bayt sayısı.

## Also See

* Enum [SocketError](../../socketerror/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)