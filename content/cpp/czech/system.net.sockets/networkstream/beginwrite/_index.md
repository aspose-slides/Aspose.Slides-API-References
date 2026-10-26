---
title: BeginWrite()
second_title: Aspose.Slides pro C++ – reference API
description: Inicializuje asynchronní zápisovou operaci.
type: docs
weight: 274
url: /cs/system.net.sockets/networkstream/beginwrite/
---
## NetworkStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metoda

Inicializuje asynchronní zápisovou operaci.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Vyrovnávací paměť obsahující data k zápisu. |
| offset | **int32_t** | offset v bytech ve specifikovaném poli. |
| size | **int32_t** | Počet bytů k zápisu. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Callback, který bude zavolán po dokončení operace. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Uživatelem poskytnutá data používaná k jedinečné identifikaci každé asynchronní zápisové operace. |

### Návratová hodnota

Objekt [IAsyncResult](../../../system/iasyncresult/) představující iniciovanou asynchronní zápisovou operaci.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Třída [IAsyncResult](../../../system/iasyncresult/)
* Třída [Object](../../../system/object/)
* Třída [NetworkStream](../)
* Jmenný prostor [System::Net::Sockets](../../)
* Knihovna [Aspose.Slides](../../../)