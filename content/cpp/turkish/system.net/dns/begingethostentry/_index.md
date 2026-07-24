---
title: BeginGetHostEntry()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen ana bilgisayar adı veya IP adresi içeren dizeyi kullanarak yeni bir IPHostEntry-class örneği oluşturmak için eşzamanlı olmayan bir işlem başlatır.
type: docs
weight: 105
url: /tr/system.net/dns/begingethostentry/
---
## Dns::BeginGetHostEntry(String, AsyncCallback, System::SharedPtr\<Object\>) yöntemi


Belirtilen ana bilgisayar adı veya IP adresi içeren dizeyi kullanarak yeni bir IPHostEntry sınıfı örneği oluşturmak için eşzamanlı olmayan bir işlem başlatır.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | Ana bilgisayar adı veya IP adresi içeren dize. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | İşlem tamamlandığında çağrılacak geri arama. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Her bir eşzamanlı işlemi benzersiz şekilde tanımlamak için kullanıcı tarafından sağlanan veri. |

### Dönen Değer

Başlatılan eşzamanlı işlemi temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi.

## Dns::BeginGetHostEntry(System::SharedPtr\<IPAddress\>, AsyncCallback, System::SharedPtr\<Object\>) yöntemi


Belirtilen IP adresini kullanarak yeni bir IPHostEntry sınıfı örneği oluşturmak için eşzamanlı olmayan bir işlem başlatır.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(System::SharedPtr<IPAddress> address, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | IP adresi. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | İşlem tamamlandığında çağrılacak geri arama. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Her bir eşzamanlı işlemi benzersiz şekilde tanımlamak için kullanıcı tarafından sağlanan veri. |

### Dönen Değer

Başlatılan eşzamanlı işlemi temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi.

## Diğer Bağlantılar

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Class [Dns](../)
* Class [IPAddress](../../ipaddress/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)