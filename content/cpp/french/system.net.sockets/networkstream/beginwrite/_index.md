---
title: BeginWrite()
second_title: Référence de l'API Aspose.Slides pour C++
description: Initie une opération d'écriture asynchrone.
type: docs
weight: 274
url: /fr/system.net.sockets/networkstream/beginwrite/
---
## NetworkStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) method

Initie une opération d'écriture asynchrone.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Un tampon contenant les données à écrire. |
| offset | **int32_t** | Le décalage en octets dans le tableau spécifié. |
| size | **int32_t** | Le nombre d'octets à écrire. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Un rappel à appeler lorsque l'opération est terminée. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Données fournies par l'utilisateur utilisées pour identifier de manière unique chaque opération d'écriture asynchrone. |

### Valeur de retour

Un objet [IAsyncResult](../../../system/iasyncresult/) représentant l'opération d'écriture asynchrone initiée.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Object](../../../system/object/)
* Classe [NetworkStream](../)
* Espace de noms [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)