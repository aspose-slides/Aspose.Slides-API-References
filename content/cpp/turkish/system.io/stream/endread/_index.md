---
title: EndRead()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen asenkron okuma işlemi tamamlanana kadar bekler.
type: docs
weight: 183
url: /tr/system.io/stream/endread/
---
## Stream::EndRead(System::SharedPtr\<System::IAsyncResult\>) metot

Belirtilen asenkron okuma işlemi tamamlanana kadar bekler.

```cpp
virtual int System::IO::Stream::EndRead(System::SharedPtr<System::IAsyncResult> asyncResult)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[System::IAsyncResult](../../../system/iasyncresult/)\> | Asenkron okuma işlemini temsil eden bir [IAsyncResult](../../../system/iasyncresult/) nesnesi |

### Dönüş Değeri

**asyncResult** tarafından temsil edilen okuma işlemi sırasında okunan bayt sayısı

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IAsyncResult](../../../system/iasyncresult/)
* Sınıf [Stream](../)
* Ad Alanı [System::IO](../../)
* Library [Aspose.Slides](../../../)