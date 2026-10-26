---
title: BeginSend()
second_title: Aspose.Slides for C++ API Referansı
description: Asenkron bir gönderim işlemini başlatır.
type: docs
weight: 495
url: /tr/system.net.sockets/socket/beginsend/
---
## Socket::BeginSend(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) metot

Asenkron gönderim işlemini başlatır.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginSend(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Verinin okunacağı bir tampon. |
| offset | **int32_t** | Belirtilen dizide bayt cinsinden ofset. |
| size | **int32_t** | Belirtilen dizide, 'offset' parametresinden başlayan bayt sayısı. |
| socketFlags | [SocketFlags](../../socketflags/) | Gönderim davranışı. |
| callback | [AsyncCallback](../../../system/asynccallback/) | İşlem tamamlandığında çağrılacak bir geri arama. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Her asenkron gönderim işlemini benzersiz şekilde tanımlamak için kullanılan kullanıcı tarafından sağlanan veri. |

### Dönüş Değeri

Başlatılan asenkron gönderim işlemini temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi.

## Bakınız

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Sınıf [IAsyncResult](../../../system/iasyncresult/)
* Sınıf [Object](../../../system/object/)
* Sınıf [Socket](../)
* Ad Alanı [System::Net::Sockets](../../)
* Kütüphane [Aspose.Slides](../../../)