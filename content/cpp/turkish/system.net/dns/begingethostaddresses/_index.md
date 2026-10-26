---
title: BeginGetHostAddresses()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen dizeyi, bir ana bilgisayar adı veya IP adresi içeren, kullanarak yeni bir IPHostEntry sınıfı örneği oluşturmak için asenkron bir işlem başlatır.
type: docs
weight: 131
url: /tr/system.net/dns/begingethostaddresses/
---
## Dns::BeginGetHostAddresses(String, AsyncCallback, System::SharedPtr\<Object\>) metodu

Belirtilen, bir ana bilgisayar adı veya IP adresi içeren dizeyi kullanarak yeni bir IPHostEntry sınıfı örneği oluşturmak için asenkron bir işlem başlatır.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostAddresses(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Arguments

| Parameter | Tür | Açıklama |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | Ana bilgisayar adı veya IP adresi içeren bir dize. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | İşlem tamamlandığında çağrılacak bir geri çağırma. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Her asenkron işlemi benzersiz şekilde tanımlamak için kullanılan, kullanıcı tarafından sağlanan veri. |

### Return Value

Başlatılan asenkron işlemi temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Sınıf [IAsyncResult](../../../system/iasyncresult/)
* Sınıf [String](../../../system/string/)
* Sınıf [Object](../../../system/object/)
* Sınıf [Dns](../)
* Ad Alanı [System::Net](../../)
* Library [Aspose.Slides](../../../)