---
title: BeginSend()
second_title: Aspose.Slides pro C++ API Reference
description: Spouští asynchronní operaci odesílání.
type: docs
weight: 495
url: /cs/system.net.sockets/socket/beginsend/
---
## Socket::BeginSend(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) metoda

Spouští asynchronní operaci odesílání.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginSend(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer, ze kterého se čtou data. |
| offset | **int32_t** | Posun v bajtech v zadaném poli. |
| size | **int32_t** | Počet bajtů v zadaném poli počínaje parametrem 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Chování odesílání. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Zpětné volání, které bude vyvoláno po dokončení operace. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Uživatelem poskytnutá data používaná k jednoznačné identifikaci každé asynchronní operace odesílání. |

### Návratová hodnota

Objekt [IAsyncResult](../../../system/iasyncresult/) představující zahájenou asynchronní operaci odesílání.

## Viz také

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Object](../../../system/object/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)