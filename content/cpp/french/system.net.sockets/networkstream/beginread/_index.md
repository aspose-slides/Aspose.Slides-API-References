---
title: BeginRead()
second_title: Référence API Aspose.Slides pour C++
description: Initie une opération de lecture asynchrone.
type: docs
weight: 248
url: /fr/system.net.sockets/networkstream/beginread/
---
## NetworkStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) method


Initie une opération de lecture asynchrone.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Le tableau d'octets où les octets lus seront écrits. |
| offset | **int32_t** | Le décalage en octets dans le tableau spécifié. |
| size | **int32_t** | Le nombre d'octets à lire. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Un rappel qui sera appelé lorsque l'opération se termine. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Données fournies par l'utilisateur utilisées pour identifier de manière unique chaque opération de lecture asynchrone. |

### Valeur retournée

Un objet [IAsyncResult](../../../system/iasyncresult/) représentant l'opération de lecture asynchrone initiée.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Object](../../../system/object/)
* Classe [NetworkStream](../)
* Espace de noms [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)