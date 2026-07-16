---
title: BeginRead()
second_title: Référence de l'API Aspose.Slides pour C++
description: Initie une opération de lecture asynchrone.
type: docs
weight: 417
url: /fr/system.net.security/sslstream/beginread/
---
## SslStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) method

Initie une opération de lecture asynchrone.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Le tableau d'octets à partir duquel lire les données. |
| offset | **int32_t** | Le décalage en octets dans le tableau spécifié. |
| count | **int32_t** | Le nombre d'octets à lire. |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | Un rappel à appeler lorsque l'opération se termine. |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Données fournies par l'utilisateur utilisées pour identifier de manière unique chaque opération de lecture asynchrone. |

### Return Value

Un objet [IAsyncResult](../../../system/iasyncresult/) représentant l'opération de lecture asynchrone initiée.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Object](../../../system/object/)
* Classe [SslStream](../)
* Espace de noms [System::Net::Security](../../)
* Bibliothèque [Aspose.Slides](../../../)