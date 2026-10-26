---
title: BeginWrite()
second_title: Référence API Aspose.Slides pour C++
description: Initie une opération d'écriture asynchrone.
type: docs
weight: 443
url: /fr/system.net.security/sslstream/beginwrite/
---
## SslStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) méthode

Initie une opération d'écriture asynchrone.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Le tableau d'octets dans lequel écrire les données. |
| offset | **int32_t** | Le décalage en octets dans le tableau spécifié. |
| count | **int32_t** | Le nombre d'octets à écrire. |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | Un rappel qui sera appelé lorsque l'opération se termine. |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Données fournies par l'utilisateur utilisées pour identifier de manière unique chaque opération d'écriture asynchrone. |

### Valeur de retour

Un objet [IAsyncResult](../../../system/iasyncresult/) représentant l'opération d'écriture asynchrone initiée.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Object](../../../system/object/)
* Classe [SslStream](../)
* Espace de noms [System::Net::Security](../../)
* Bibliothèque [Aspose.Slides](../../../)