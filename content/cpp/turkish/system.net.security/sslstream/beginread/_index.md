---
title: BeginRead()
second_title: Aspose.Slides for C++ API Referansı
description: Asenkron bir okuma işlemi başlatır.
type: docs
weight: 417
url: /tr/system.net.security/sslstream/beginread/
---
## SslStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) method


Asenkron bir okuma işlemi başlatır.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```


### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Verinin okunacağı bayt dizisi. |
| offset | **int32_t** | Belirtilen dizideki bayt cinsinden offset. |
| count | **int32_t** | Okunacak bayt sayısı. |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | İşlem tamamlandığında çağrılacak bir geri çağırma. |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Her asenkron okuma işlemini benzersiz şekilde tanımlamak için kullanılan, kullanıcı tarafından sağlanan veri. |

### Return Value

Başlatılan asenkron okuma işlemini temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Sınıf [IAsyncResult](../../../system/iasyncresult/)
* Sınıf [Object](../../../system/object/)
* Sınıf [SslStream](../)
* Ad Alanı [System::Net::Security](../../)
* Kütüphane [Aspose.Slides](../../../)