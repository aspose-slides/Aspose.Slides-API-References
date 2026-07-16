---
title: EndRead()
second_title: Référence de l'API Aspose.Slides pour C++
description: Attend jusqu'à ce que l'opération de lecture asynchrone spécifiée soit terminée.
type: docs
weight: 183
url: /fr/system.io/stream/endread/
---
## Stream::EndRead(System::SharedPtr\<System::IAsyncResult\>) méthode

Attend jusqu'à ce que l'opération de lecture asynchrone spécifiée soit terminée.

```cpp
virtual int System::IO::Stream::EndRead(System::SharedPtr<System::IAsyncResult> asyncResult)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[System::IAsyncResult](../../../system/iasyncresult/)\> | Un objet [IAsyncResult](../../../system/iasyncresult/) qui représente une opération de lecture asynchrone |

### Valeur de retour

Le nombre d'octets lus pendant l'opération de lecture représentée par **asyncResult**

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Stream](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)