---
title: EndRead()
second_title: Référence de l'API Aspose.Slides pour C++
description: Attend jusqu'à ce que l'opération de lecture asynchrone spécifiée soit terminée.
type: docs
weight: 261
url: /fr/system.net.sockets/networkstream/endread/
---
## NetworkStream::EndRead(System::SharedPtr\<IAsyncResult\>) méthode

Attend jusqu'à ce que l'opération de lecture asynchrone spécifiée soit terminée.

```cpp
int32_t System::Net::Sockets::NetworkStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Un objet [IAsyncResult](../../../system/iasyncresult/) qui représente une opération de lecture asynchrone |

### Valeur de retour

Le nombre d'octets lus pendant l'opération de lecture représentée par **asyncResult**

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [NetworkStream](../)
* Espace de noms [System::Net::Sockets](../../)
* Bibliothèque [Aspose.Slides](../../../)