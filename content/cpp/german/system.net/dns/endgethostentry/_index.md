---
title: EndGetHostEntry()
second_title: Aspose.Slides für C++ API-Referenz
description: Wartet, bis die angegebene asynchrone Operation zur Erstellung einer neuen IPHostEntry-Klasseninstanz abgeschlossen ist.
type: docs
weight: 118
url: /de/system.net/dns/endgethostentry/
---
## Dns::EndGetHostEntry(System::SharedPtr\<IAsyncResult\>) Methode

Wartet, bis die angegebene asynchrone Operation zur Erstellung einer neuen IPHostEntry-Klasseninstanz abgeschlossen ist.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::EndGetHostEntry(System::SharedPtr<IAsyncResult> asyncResult)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Ein [IAsyncResult](../../../system/iasyncresult/) Objekt, das einen asynchronen Vorgang darstellt. |

### Rückgabewert

Eine neu erstellte IPHostEntry-Klasseninstanz.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPHostEntry](../../iphostentry/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)