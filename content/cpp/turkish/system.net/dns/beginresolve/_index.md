---
title: BeginResolve()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen host adını kullanarak yeni bir IPHostEntry-sınıfı örneği oluşturmak için asenkron bir işlem başlatır.
type: docs
weight: 157
url: /tr/system.net/dns/beginresolve/
---
## Dns::BeginResolve(String, AsyncCallback, System::SharedPtr\<Object\>) metodu

Belirtilen host adını kullanarak yeni bir IPHostEntry-sınıfı örneği oluşturmak için asenkron bir işlem başlatır.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginResolve(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | Yeni bir [IPHostEntry](../../iphostentry/) sınıfı örneği oluşturmak için kullanılan bir host adı. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | İşlem tamamlandığında çağrılacak bir geri arama. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Her asenkron işlemi benzersiz şekilde tanımlamak için kullanılan, kullanıcı tarafından sağlanan veri. |

### Dönüş Değeri

Başlatılan asenkron işlemi temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi.

## Ayrıca

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Sınıf [IAsyncResult](../../../system/iasyncresult/)
* Sınıf [String](../../../system/string/)
* Sınıf [Object](../../../system/object/)
* Sınıf [Dns](../)
* AdAlanı [System::Net](../../)
* Kütüphane [Aspose.Slides](../../../)