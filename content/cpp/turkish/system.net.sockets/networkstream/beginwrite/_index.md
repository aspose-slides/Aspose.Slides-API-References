---
title: BeginWrite()
second_title: Aspose.Slides için C++ API Referansı
description: Asenkron bir yazma işlemini başlatır.
type: docs
weight: 274
url: /tr/system.net.sockets/networkstream/beginwrite/
---
## NetworkStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metod

Asenkron bir yazma işlemini başlatır.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Yazılacak verileri içeren bir tampon. |
| offset | **int32_t** | Belirtilen dizideki bayt cinsinden ofset. |
| size | **int32_t** | Yazılacak bayt sayısı. |
| callback | [AsyncCallback](../../../system/asynccallback/) | İşlem tamamlandığında çağrılacak bir geri çağırma. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Her asenkron yazma işlemini benzersiz şekilde tanımlamak için kullanıcı tarafından sağlanan veri. |

### Dönüş Değeri

Başlatılan asenkron yazma işlemini temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi.

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Sınıf [IAsyncResult](../../../system/iasyncresult/)
* Sınıf [Object](../../../system/object/)
* Sınıf [NetworkStream](../)
* Ad alanı [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)