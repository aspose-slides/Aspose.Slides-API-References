---
title: BeginReceive()
second_title: Aspose.Slides for C++ API Referansı
description: Asenkron bir yazma işlemini başlatır.
type: docs
weight: 521
url: /tr/system.net.sockets/socket/beginreceive/
---
## Socket::BeginReceive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) metod


Alasenkron bir yazma işlemi başlatır.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginReceive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Alınan verinin atanacağı bir tampon. |
| offset | **int32_t** | Belirtilen dizi içindeki bayt cinsinden ofset. |
| size | **int32_t** | 'offset' parametresinden başlayarak belirtilen dizideki bayt sayısı. |
| socketFlags | [SocketFlags](../../socketflags/) | Alım davranışı. |
| callback | [AsyncCallback](../../../system/asynccallback/) | İşlem tamamlandığında çağrılacak bir geri arama. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Her asenkron alım işlemini benzersiz bir şekilde tanımlamak için kullanılan kullanıcı tarafından sağlanan veri. |

### Dönüş Değeri

Başlatılan asenkron alım işlemini temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi.

## İlgili

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Object](../../../system/object/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)