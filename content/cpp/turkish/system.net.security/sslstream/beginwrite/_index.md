---
title: BeginWrite()
second_title: Aspose.Slides for C++ API Referansı
description: Eşzamansız bir yazma işlemini başlatır.
type: docs
weight: 443
url: /tr/system.net.security/sslstream/beginwrite/
---
## SslStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metot

İşlemi eşzamanlı bir yazma operasyonu olarak başlatır.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Verinin yazılacağı bayt dizisi. |
| offset | **int32_t** | Belirtilen dizide bayt cinsinden ofset. |
| count | **int32_t** | Yazılacak bayt sayısı. |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | İşlem tamamlandığında çağrılacak bir geri çağırma. |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Her bir eşzamanlı yazma işlemini benzersiz şekilde tanımlamak için kullanıcı tarafından sağlanan veri. |

### Dönüş Değeri

Başlatılan eşzamanlı yazma işlemini temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Object](../../../system/object/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)