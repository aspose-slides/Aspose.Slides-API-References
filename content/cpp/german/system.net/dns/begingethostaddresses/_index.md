---
title: BeginGetHostAddresses()
second_title: Aspose.Slides für C++ API-Referenz
description: Startet einen asynchronen Vorgang, um eine neue IPHostEntry-Klasseninstanz mit dem angegebenen String zu erstellen, der einen Hostnamen oder eine IP-Adresse enthält.
type: docs
weight: 131
url: /de/system.net/dns/begingethostaddresses/
---
## Dns::BeginGetHostAddresses(String, AsyncCallback, System::SharedPtr\<Object\>) Methode

Startet einen asynchronen Vorgang, um eine neue IPHostEntry-Klasseninstanz mit dem angegebenen String zu erstellen, der einen Hostnamen oder eine IP-Adresse enthält.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostAddresses(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | Ein String, der einen Hostnamen oder eine IP-Adresse enthält. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Ein Callback, der aufgerufen wird, wenn der Vorgang abgeschlossen ist. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Vom Benutzer bereitgestellte Daten, die verwendet werden, um jeden asynchronen Vorgang eindeutig zu identifizieren. |

### Rückgabewert

Ein [IAsyncResult](../../../system/iasyncresult/) Objekt, das den initiierten asynchronen Vorgang darstellt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [String](../../../system/string/)
* Klasse [Object](../../../system/object/)
* Klasse [Dns](../)
* Namensraum [System::Net](../../)
* Bibliothek [Aspose.Slides](../../../)