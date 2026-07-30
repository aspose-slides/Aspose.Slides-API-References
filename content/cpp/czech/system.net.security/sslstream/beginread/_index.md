---
title: BeginRead()
second_title: Aspose.Slides pro C++ – dokumentace API
description: Inicializuje asynchronní operaci čtení.
type: docs
weight: 417
url: /cs/system.net.security/sslstream/beginread/
---
## SslStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metoda

Inicializuje asynchronní operaci čtení.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Pole bytů, ze kterého se čtou data. |
| offset | **int32_t** | Posun v bajtech v určeném poli. |
| count | **int32_t** | Počet bajtů ke čtení. |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | Callback, který bude volán po dokončení operace. |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Uživatelem poskytnutá data sloužící k jedinečné identifikaci každé asynchronní operace čtení. |

### Návratová hodnota

Objekt [IAsyncResult](../../../system/iasyncresult/) představující inicializovanou asynchronní operaci čtení.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Třída [IAsyncResult](../../../system/iasyncresult/)
* Třída [Object](../../../system/object/)
* Třída [SslStream](../)
* Jmenný prostor [System::Net::Security](../../)
* Knihovna [Aspose.Slides](../../../)