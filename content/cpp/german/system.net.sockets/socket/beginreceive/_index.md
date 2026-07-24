---
title: BeginReceive()
second_title: Aspose.Slides für C++ API-Referenz
description: Startet einen asynchronen Schreibvorgang.
type: docs
weight: 521
url: /de/system.net.sockets/socket/beginreceive/
---
## Socket::BeginReceive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) Methode

Startet einen asynchronen Schreibvorgang.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginReceive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ein Puffer, in dem die empfangenen Daten zugewiesen werden. |
| offset | **int32_t** | Der Offset in Bytes im angegebenen Array. |
| size | **int32_t** | Die Anzahl der Bytes im angegebenen Array, beginnend beim Parameter 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Das Empfangsverhalten. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Ein Rückruf, der aufgerufen wird, wenn der Vorgang abgeschlossen ist. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Vom Benutzer bereitgestellte Daten, die verwendet werden, um jede asynchrone Empfangsoperation eindeutig zu identifizieren. |

### Rückgabewert

Ein [IAsyncResult](../../../system/iasyncresult/)-Objekt, das die initiierte asynchrone Empfangsoperation darstellt.

## Siehe auch

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [Object](../../../system/object/)
* Klasse [Socket](../)
* Namensraum [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)