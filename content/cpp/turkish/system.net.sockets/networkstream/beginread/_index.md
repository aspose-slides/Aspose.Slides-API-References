---
title: BeginRead()
second_title: Aspose.Slides for C++ API Referansı
description: Asenkron okuma işlemini başlatır.
type: docs
weight: 248
url: /tr/system.net.sockets/networkstream/beginread/
---
## NetworkStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) method


Asenkron okuma işlemini başlatır.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Okunan baytların yazılacağı bayt dizisi. |
| offset | **int32_t** | Belirtilen dizide bayt cinsinden ofset. |
| size | **int32_t** | Okunacak bayt sayısı. |
| callback | [AsyncCallback](../../../system/asynccallback/) | İşlem tamamlandığında çağrılacak bir geri çağırma. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Her asenkron okuma işlemini benzersiz şekilde tanımlamak için kullanılan kullanıcı tarafından sağlanan veri. |

### Dönüş Değeri

Başlatılan asenkron okuma işlemini temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Sınıf [IAsyncResult](../../../system/iasyncresult/)
* Sınıf [Object](../../../system/object/)
* Sınıf [NetworkStream](../)
* Ad Alanı [System::Net::Sockets](../../)
* Kütüphane [Aspose.Slides](../../../)