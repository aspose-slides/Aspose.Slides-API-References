---
title: BeginGetHostEntry()
second_title: Aspose.Slides für C++ API-Referenz
description: Startet eine asynchrone Operation, um eine neue IPHostEntry-class Instanz zu erstellen, wobei die angegebene Zeichenfolge verwendet wird, die einen Hostnamen oder eine IP-Adresse enthält.
type: docs
weight: 105
url: /de/system.net/dns/begingethostentry/
---
## Dns::BeginGetHostEntry(String, AsyncCallback, System::SharedPtr\<Object\>) Methode

Startet eine asynchrone Operation, um eine neue IPHostEntry-class Instanz zu erstellen, wobei die angegebene Zeichenfolge verwendet wird, die einen Hostnamen oder eine IP-Adresse enthält.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | Die Zeichenfolge, die einen Hostnamen oder eine IP-Adresse enthält. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Ein Callback, der aufgerufen wird, wenn die Operation abgeschlossen ist. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Vom Benutzer bereitgestellte Daten, die verwendet werden, um jede asynchrone Operation eindeutig zu identifizieren. |

### Rückgabewert

Ein [IAsyncResult](../../../system/iasyncresult/) Objekt, das die gestartete asynchrone Operation darstellt.

## Dns::BeginGetHostEntry(System::SharedPtr\<IPAddress\>, AsyncCallback, System::SharedPtr\<Object\>) Methode

Startet eine asynchrone Operation, um eine neue IPHostEntry-class Instanz zu erstellen, wobei die angegebene IP-Adresse verwendet wird.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(System::SharedPtr<IPAddress> address, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | Die IP-Adresse. |
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
* Klasse [IPAddress](../../ipaddress/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)