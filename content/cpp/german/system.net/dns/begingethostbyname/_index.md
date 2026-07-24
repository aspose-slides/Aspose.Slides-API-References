---
title: BeginGetHostByName()
second_title: Aspose.Slides für C++ API-Referenz
description: Startet eine asynchrone Operation, um eine neue IPHostEntry-class Instanz mit dem angegebenen Hostnamen zu erstellen.
type: docs
weight: 53
url: /de/system.net/dns/begingethostbyname/
---
## Dns::BeginGetHostByName(String, AsyncCallback, System::SharedPtr\<Object\>) Methode

Startet eine asynchrone Operation, um eine neue IPHostEntry-class Instanz mit dem angegebenen Hostnamen zu erstellen.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostByName(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | Ein Hostname. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Ein Callback, der aufgerufen wird, wenn die Operation abgeschlossen ist. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Vom Benutzer bereitgestellte Daten, die verwendet werden, um jede asynchrone Operation eindeutig zu identifizieren. |

### Rückgabewert

Ein [IAsyncResult](../../../system/iasyncresult/) Objekt, das die gestartete asynchrone Operation darstellt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [String](../../../system/string/)
* Klasse [Object](../../../system/object/)
* Klasse [Dns](../)
* Namensraum [System::Net](../../)
* Bibliothek [Aspose.Slides](../../../)