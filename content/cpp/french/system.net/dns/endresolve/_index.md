---
title: EndResolve()
second_title: Référence de l'API Aspose.Slides pour C++
description: Attend que l'opération asynchrone spécifiée pour créer une nouvelle instance de la classe IPHostEntry se termine.
type: docs
weight: 170
url: /fr/system.net/dns/endresolve/
---
## Dns::EndResolve(System::SharedPtr\<IAsyncResult\>) method

Attendre jusqu'à ce que l'opération asynchrone spécifiée pour créer une nouvelle instance de la classe IPHostEntry se termine.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::EndResolve(System::SharedPtr<IAsyncResult> asyncResult)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Un [IAsyncResult](../../../system/iasyncresult/) objet qui représente une opération asynchrone. |

### Valeur de retour

Une instance IPHostEntry-class nouvellement créée.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPHostEntry](../../iphostentry/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)