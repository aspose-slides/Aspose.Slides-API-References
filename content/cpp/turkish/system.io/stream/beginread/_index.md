---
title: BeginRead()
second_title: Aspose.Slides for C++ API Referansı
description: Asenkron bir okuma işlemi başlatır.
type: docs
weight: 157
url: /tr/system.io/stream/beginread/
---
## Stream::BeginRead(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) metod

Asenkron okuma işlemini başlatır.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginRead(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Okunacak bir tampon |
| offset | int | Okunan verinin yazılmaya başlanacağı konumu gösteren **buffer** içinde 0 tabanlı bir kaydırma |
| count | int | Okunacak bayt sayısı |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | İşlem tamamlandığında çağrılacak bir geri arama |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Her asenkron okuma işlemini benzersiz şekilde tanımlamak için kullanılan kullanıcı tarafından sağlanan veri |

### Dönüş Değeri

İşlete başlatılan asenkron okuma işlemini temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Sınıf [IAsyncResult](../../../system/iasyncresult/)
* Sınıf [Object](../../../system/object/)
* Sınıf [Stream](../)
* AdAlanı [System::IO](../../)
* Library [Aspose.Slides](../../../)