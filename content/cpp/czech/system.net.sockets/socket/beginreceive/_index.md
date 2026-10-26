---
title: BeginReceive()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Spouští asynchronní operaci zápisu.
type: docs
weight: 521
url: /cs/system.net.sockets/socket/beginreceive/
---
## Socket::BeginReceive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) metoda

Inicializuje asynchronní operaci zápisu.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginReceive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer, do kterého budou přiřazena přijatá data. |
| offset | **int32_t** | Posun v bajtech ve specifikovaném poli. |
| size | **int32_t** | Počet bajtů ve specifikovaném poli počínaje parametrem 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování přijímání. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Callback, který bude zavolán po dokončení operace. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Uživatelem poskytnutá data používaná k jedinečné identifikaci každé asynchronní operace přijímání. |

### Návratová hodnota

Objekt [IAsyncResult](../../../system/iasyncresult/) představující iniciovanou asynchronní operaci přijímání.

## Viz také

* Výčet [SocketFlags](../../socketflags/)
* Definice typu [SharedPtr](../../../system/sharedptr/)
* Definice typu [ArrayPtr](../../../system/arrayptr/)
* Definice typu [AsyncCallback](../../../system/asynccallback/)
* Třída [IAsyncResult](../../../system/iasyncresult/)
* Třída [Object](../../../system/object/)
* Třída [Socket](../)
* Jmenný prostor [System::Net::Sockets](../../)
* Knihovna [Aspose.Slides](../../../)