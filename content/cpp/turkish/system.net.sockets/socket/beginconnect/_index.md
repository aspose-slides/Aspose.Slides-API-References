---
title: BeginConnect()
second_title: Aspose.Slides for C++ API Referansı
description: Asenkron bir bağlanma işlemini başlatır.
type: docs
weight: 573
url: /tr/system.net.sockets/socket/beginconnect/
---
## Socket::BeginConnect(System::SharedPtr\<EndPoint\>, AsyncCallback, System::SharedPtr\<Object\>) metodu

Asenkron bir bağlanma işlemini başlatır.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<EndPoint> remoteEP, AsyncCallback callback, System::SharedPtr<Object> state)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Uzak uç nokta. |
| callback | [AsyncCallback](../../../system/asynccallback/) | İşlem tamamlandığında çağrılacak bir geri arama. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | İşlem başına eşsiz kimlik sağlamak için kullanıcı tarafından sağlanan veri. |

### Dönüş Değeri

Başlatılan eşzamansız bağlanma işlemini temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi.

## Socket::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metodu

Asenkron bir bağlanma işlemini başlatır.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| host | [String](../../../system/string/) | Uzak ana bilgisayar adı. |
| port | **int32_t** | Uzak ana bilgisayarın port numarası. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | İşlem tamamlandığında çağrılacak bir geri arama. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | İşlem başına eşsiz kimlik sağlamak için kullanıcı tarafından sağlanan veri. |

### Dönüş Değeri

Başlatılan eşzamansız bağlanma işlemini temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi.

## Socket::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metodu

Asenkron bir bağlanma işlemini başlatır.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Uzak ana bilgisayarın IP adresi. |
| port | **int32_t** | Uzak ana bilgisayarın port numarası. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | İşlem tamamlandığında çağrılacak bir geri arama. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | İşlem başına eşsiz kimlik sağlamak için kullanıcı tarafından sağlanan veri. |

### Dönüş Değeri

Başlatılan eşzamansız bağlanma işlemini temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi.

## Socket::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metodu

Asenkron bir bağlanma işlemini başlatır.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | Uzak ana bilgisayarın IP adresleri. |
| port | **int32_t** | Uzak ana bilgisayarın port numarası. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | İşlem tamamlandığında çağrılacak bir geri arama. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | İşlem başına eşsiz kimlik sağlamak için kullanıcı tarafından sağlanan veri. |

### Dönüş Değeri

Başlatılan eşzamansız bağlanma işlemini temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi.

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [IAsyncResult](../../../system/iasyncresult/)
* Sınıf [EndPoint](../../../system.net/endpoint/)
* Sınıf [Object](../../../system/object/)
* Sınıf [Socket](../)
* Sınıf [String](../../../system/string/)
* Sınıf [IPAddress](../../../system.net/ipaddress/)
* AdAlanı [System::Net::Sockets](../../)
* Kütüphane [Aspose.Slides](../../../)