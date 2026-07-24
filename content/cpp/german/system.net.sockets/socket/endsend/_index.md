---
title: EndSend()
second_title: Aspose.Slides für C++ API Referenz
description: Wartet, bis die angegebene asynchrone Sendeoperation abgeschlossen ist.
type: docs
weight: 508
url: /de/system.net.sockets/socket/endsend/
---
## Socket::EndSend(System::SharedPtr\<IAsyncResult\>) Methode


Wartet, bis die angegebene asynchrone Sendeoperation abgeschlossen ist.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Ein [IAsyncResult](../../../system/iasyncresult/)-Objekt, das eine asynchrone Sendeoperation darstellt. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## Socket::EndSend(System::SharedPtr\<IAsyncResult\>, SocketError\&) Methode


Wartet, bis die angegebene asynchrone Sendeoperation abgeschlossen ist.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Ein [IAsyncResult](../../../system/iasyncresult/)-Objekt, das eine asynchrone Sendeoperation darstellt. |
| errorCode | [SocketError](../../socketerror/)\& | Der Ausgabeparameter, dem der Fehlercode zugewiesen wird, wenn die Sendeoperation fehlschlägt. |

### Rückgabewert

Die Anzahl der gesendeten Bytes.

## Siehe auch

* Enum [SocketError](../../socketerror/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [Socket](../)
* Namensraum [System::Net::Sockets](../../)
* Bibliothek [Aspose.Slides](../../../)