---
title: EndGetHostAddresses()
second_title: Aspose.Slides für C++ API-Referenz
description: Wartet, bis die angegebene asynchrone Operation zur Erstellung einer neuen IPHostEntry-class-Instanz abgeschlossen ist.
type: docs
weight: 144
url: /de/system.net/dns/endgethostaddresses/
---
## Dns::EndGetHostAddresses(System::SharedPtr\<IAsyncResult\>) Methode

Wartet, bis die angegebene asynchrone Operation zur Erstellung einer neuen IPHostEntry-class-Instanz abgeschlossen ist.

```cpp
static System::ArrayPtr<System::SharedPtr<IPAddress>> System::Net::Dns::EndGetHostAddresses(System::SharedPtr<IAsyncResult> asyncResult)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Ein [IAsyncResult](../../../system/iasyncresult/)-Objekt, das eine asynchrone Operation darstellt. |

### Rückgabewert

Eine neu erstellte IPHostEntry-class-Instanz.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPAddress](../../ipaddress/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [Dns](../)
* Namensraum [System::Net](../../)
* Library [Aspose.Slides](../../../)