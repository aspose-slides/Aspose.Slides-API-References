---
title: EndGetHostAddresses()
second_title: Référence de l'API Aspose.Slides pour C++
description: Attend que l'opération asynchrone spécifiée pour créer une nouvelle instance de la classe IPHostEntry se termine.
type: docs
weight: 144
url: /fr/system.net/dns/endgethostaddresses/
---
## Dns::EndGetHostAddresses(System::SharedPtr\<IAsyncResult\>) méthode

Attend que l'opération asynchrone spécifiée pour créer une nouvelle instance de la classe IPHostEntry se termine.

```cpp
static System::ArrayPtr<System::SharedPtr<IPAddress>> System::Net::Dns::EndGetHostAddresses(System::SharedPtr<IAsyncResult> asyncResult)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Un objet [IAsyncResult](../../../system/iasyncresult/) qui représente une opération asynchrone. |

### Valeur de retour

Une instance nouvellement créée de la classe IPHostEntry.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPAddress](../../ipaddress/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)