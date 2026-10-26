---
title: EndGetHostByName()
second_title: Aspose.Slides pro C++ API Reference
description: Čeká, dokud nedokončí zadaná asynchronní operace vytvoření nové instance třídy IPHostEntry.
type: docs
weight: 66
url: /cs/system.net/dns/endgethostbyname/
---
## Dns::EndGetHostByName(System::SharedPtr\<IAsyncResult\>) metoda


Čeká, dokud se nedokončí zadaná asynchronní operace vytvoření nové instance třídy IPHostEntry.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::EndGetHostByName(System::SharedPtr<IAsyncResult> asyncResult)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Objekt [IAsyncResult](../../../system/iasyncresult/) představuje asynchronní operaci. |

### Vrácená hodnota

Nově vytvořená instance třídy IPHostEntry.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IPHostEntry](../../iphostentry/)
* Třída [IAsyncResult](../../../system/iasyncresult/)
* Třída [Dns](../)
* Jmenný prostor [System::Net](../../)
* Knihovna [Aspose.Slides](../../../)