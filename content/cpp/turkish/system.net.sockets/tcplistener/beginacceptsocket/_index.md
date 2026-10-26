---
title: BeginAcceptSocket()
second_title: Aspose.Slides for C++ API Referansı
description: Asenkron bir kabul işlemi başlatır.
type: docs
weight: 144
url: /tr/system.net.sockets/tcplistener/beginacceptsocket/
---
## TcpListener::BeginAcceptSocket(AsyncCallback, System::SharedPtr\<Object\>) metod


Asenkron bir kabul işlemi başlatır.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptSocket(AsyncCallback callback, System::SharedPtr<Object> state)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | İşlem tamamlandığında çağrılacak bir geri çağırma. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Her asenkron bağlanma işlemini benzersiz şekilde tanımlamak için kullanılan kullanıcı tarafından sağlanan veri. |

### Dönüş Değeri

Başlatılan asenkron kabul işlemini temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi.

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Sınıf [IAsyncResult](../../../system/iasyncresult/)
* Sınıf [Object](../../../system/object/)
* Sınıf [TcpListener](../)
* İsim Alanı [System::Net::Sockets](../../)
* Kütüphane [Aspose.Slides](../../../)