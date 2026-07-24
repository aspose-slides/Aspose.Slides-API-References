---
title: BeginResolve()
second_title: Aspose.Slides für C++ API-Referenz
description: Startet eine asynchrone Operation, um eine neue IPHostEntry-Klasseninstanz mit dem angegebenen Hostnamen zu erstellen.
type: docs
weight: 157
url: /de/system.net/dns/beginresolve/
---
## Dns::BeginResolve(String, AsyncCallback, System::SharedPtr\<Object\>) Methode

Startet eine asynchrone Operation, um eine neue IPHostEntry-Klasse-Instanz mit dem angegebenen Hostnamen zu erstellen.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginResolve(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | Ein Hostname, der verwendet wird, um eine neue Instanz der [IPHostEntry](../../iphostentry/) Klasse zu erstellen. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Ein Callback, das aufgerufen wird, wenn die Operation abgeschlossen ist. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Benutzerbereitgestellte Daten, die verwendet werden, um jede asynchrone Operation eindeutig zu identifizieren. |

### Rückgabewert

Ein [IAsyncResult](../../../system/iasyncresult/) Objekt, das die gestartete asynchrone Operation darstellt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)