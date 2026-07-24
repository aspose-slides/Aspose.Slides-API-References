---
title: BeginGetHostByName()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen host adını kullanarak yeni bir IPHostEntry-sınıfı örneği oluşturmak için asenkron bir işlem başlatır.
type: docs
weight: 53
url: /tr/system.net/dns/begingethostbyname/
---
## Dns::BeginGetHostByName(String, AsyncCallback, System::SharedPtr\<Object\>) metodu


Belirtilen host adını kullanarak yeni bir IPHostEntry-sınıf örneği oluşturmak için asenkron bir işlem başlatır.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostByName(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | Bir host adı. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | İşlem tamamlandığında çağrılacak bir geri arama. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Her asenkron işlemi benzersiz şekilde tanımlamak için kullanıcı tarafından sağlanan veri. |

### Dönüş Değeri

Başlatılan asenkron işlemi temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)