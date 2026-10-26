---
title: BeginConnect()
second_title: Aspose.Slides for C++ API Referansı
description: Asenkron bir bağlanma işlemini başlatır.
type: docs
weight: 261
url: /tr/system.net.sockets/tcpclient/beginconnect/
---
## TcpClient::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metot

Asenkron bir bağlanma işlemini başlatır.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| host | [String](../../../system/string/) | Uzak bir ana bilgisayar adı. |
| port | **int32_t** | Uzak ana bilgisayarın bir bağlantı noktası. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | İşlem tamamlandığında çağrılacak bir geri arama. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Her asenkron bağlanma işlemini benzersiz şekilde tanımlamak için kullanılan kullanıcı sağladığı veri. |

### Dönüş Değeri

Başlatılan asenkron bağlanma işlemini temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi.

## TcpClient::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metot

Asenkron bir bağlanma işlemini başlatır.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Uzak bir ana bilgisayarın IP adresi. |
| port | **int32_t** | Uzak ana bilgisayarın bir bağlantı noktası. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | İşlem tamamlandığında çağrılacak bir geri arama. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Her asenkron bağlanma işlemini benzersiz şekilde tanımlamak için kullanılan kullanıcı sağladığı veri. |

### Dönüş Değeri

Başlatılan asenkron bağlanma işlemini temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi.

## TcpClient::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metot

Asenkron bir bağlanma işlemini başlatır.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | Uzak bir ana bilgisayarın IP adresleri. |
| port | **int32_t** | Uzak ana bilgisayarın bir bağlantı noktası. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | İşlem tamamlandığında çağrılacak bir geri arama. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Her asenkron bağlanma işlemini benzersiz şekilde tanımlamak için kullanılan kullanıcı sağladığı veri. |

### Dönüş Değeri

Başlatılan asenkron bağlanma işlemini temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi.

## İlgili

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Tip Tanımı [AsyncCallback](../../../system/asynccallback/)
* Tip Tanımı [ArrayPtr](../../../system/arrayptr/)
* Sınıf [IAsyncResult](../../../system/iasyncresult/)
* Sınıf [String](../../../system/string/)
* Sınıf [Object](../../../system/object/)
* Sınıf [TcpClient](../)
* Sınıf [IPAddress](../../../system.net/ipaddress/)
* İsim Alanı [System::Net::Sockets](../../)
* Kütüphane [Aspose.Slides](../../../)