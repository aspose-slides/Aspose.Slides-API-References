---
title: EndGetHostByName()
second_title: Aspose.Slides für C++ API-Referenz
description: Wartet, bis die angegebene asynchrone Operation zum Erstellen einer neuen IPHostEntry-class Instanz abgeschlossen ist.
type: docs
weight: 66
url: /de/system.net/dns/endgethostbyname/
---
## Dns::EndGetHostByName(System::SharedPtr\<IAsyncResult\>) Methode

Wartet, bis die angegebene asynchrone Operation, zum Erstellen einer neuen IPHostEntry-Klasse-Instanz, abgeschlossen ist.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::EndGetHostByName(System::SharedPtr<IAsyncResult> asyncResult)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Ein [IAsyncResult](../../../system/iasyncresult/)-Objekt, das eine asynchrone Operation darstellt. |

### Rückgabewert

Eine neu erstellte IPHostEntry-Klasse-Instanz.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPHostEntry](../../iphostentry/)
* Klasse [IAsyncResult](../../../system/iasyncresult/)
* Klasse [Dns](../)
* Namensraum [System::Net](../../)
* Bibliothek [Aspose.Slides](../../../)