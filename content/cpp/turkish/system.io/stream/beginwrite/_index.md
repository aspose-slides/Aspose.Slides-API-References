---
title: BeginWrite()
second_title: Aspose.Slides for C++ API Referansı
description: Asenkron bir yazma işlemini başlatır.
type: docs
weight: 170
url: /tr/system.io/stream/beginwrite/
---
## Stream::BeginWrite(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) metod

Asenkron bir yazma işlemini başlatır.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Yazılacak verileri içeren bir tampon |
| offset | int | Yazılacak verilerin başladığı konumu gösteren **buffer** içindeki 0 tabanlı offset |
| count | int | Yazılacak bayt sayısı |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | İşlem tamamlandığında çağrılacak bir geri arama |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Her bir asenkron yazma işlemini benzersiz şekilde tanımlamak için kullanılan kullanıcı tarafından sağlanan veri |

### Dönüş Değeri

Başlatılan asenkron yazma işlemini temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Sınıf [IAsyncResult](../../../system/iasyncresult/)
* Sınıf [Object](../../../system/object/)
* Sınıf [Stream](../)
* Ad Alanı [System::IO](../../)
* Library [Aspose.Slides](../../../)