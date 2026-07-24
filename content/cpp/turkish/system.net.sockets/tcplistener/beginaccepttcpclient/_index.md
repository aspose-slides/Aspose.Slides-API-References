---
title: BeginAcceptTcpClient()
second_title: Aspose.Slides C++ için API Referansı
description: Asenkron bir kabul işlemi başlatır.
type: docs
weight: 170
url: /tr/system.net.sockets/tcplistener/beginaccepttcpclient/
---
## TcpListener::BeginAcceptTcpClient(AsyncCallback, System::SharedPtr\<Object\>) method


Asenkron bir kabul işlemi başlatır.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptTcpClient(AsyncCallback callback, System::SharedPtr<Object> state)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | İşlem tamamlandığında çağrılacak bir callback. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Kullanıcı tarafından sağlanan, her asenkron bağlanma işlemini benzersiz şekilde tanımlamak için kullanılan veri. |

### Dönüş Değeri

[IAsyncResult](../../../system/iasyncresult/) nesnesi, başlatılan asenkron kabul işlemini temsil eder.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Sınıf [IAsyncResult](../../../system/iasyncresult/)
* Sınıf [Object](../../../system/object/)
* Sınıf [TcpListener](../)
* Ad alanı [System::Net::Sockets](../../)
* Kütüphane [Aspose.Slides](../../../)