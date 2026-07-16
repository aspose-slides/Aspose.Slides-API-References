---
title: BeginSend()
second_title: Référence de l'API Aspose.Slides for C++
description: Initie une opération d'envoi asynchrone.
type: docs
weight: 495
url: /fr/system.net.sockets/socket/beginsend/
---
## Socket::BeginSend(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) méthode

Initie une opération d'envoi asynchrone.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginSend(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Un tampon à partir duquel lire les données. |
| offset | **int32_t** | Le décalage en octets dans le tableau spécifié. |
| size | **int32_t** | Le nombre d'octets dans le tableau spécifié à partir du paramètre 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Le comportement d'envoi. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Une fonction de rappel qui sera appelée lorsque l'opération sera terminée. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Données fournies par l'utilisateur utilisées pour identifier de manière unique chaque opération d'envoi asynchrone. |

### Valeur de retour

Un objet [IAsyncResult](../../../system/iasyncresult/) représentant l'opération d'envoi asynchrone initiée.

## Voir aussi

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Object](../../../system/object/)
* Classe [Socket](../)
* Espace de noms [System::Net::Sockets](../../)
* Bibliothèque [Aspose.Slides](../../../)