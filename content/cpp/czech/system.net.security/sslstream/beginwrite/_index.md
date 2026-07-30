---
title: BeginWrite()
second_title: Aspose.Slides pro C++ API Reference
description: Zahajuje asynchronní operaci zápisu.
type: docs
weight: 443
url: /cs/system.net.security/sslstream/beginwrite/
---
## SslStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) method

Zahajuje asynchronní operaci zápisu.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Pole bajtů, do kterého se zapisují data. |
| offset | **int32_t** | Posun v bajtech v zadaném poli. |
| count | **int32_t** | Počet bajtů k zápisu. |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | Zpětné volání, které se zavolá po dokončení operace. |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Uživatelem poskytnutá data použité k jednoznačné identifikaci každé asynchronní operace zápisu. |

### Návratová hodnota

Objekt [IAsyncResult](../../../system/iasyncresult/) představující zahájenou asynchronní operaci zápisu.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Třída [IAsyncResult](../../../system/iasyncresult/)
* Třída [Object](../../../system/object/)
* Třída [SslStream](../)
* Jmenný prostor [System::Net::Security](../../)
* Knihovna [Aspose.Slides](../../../)