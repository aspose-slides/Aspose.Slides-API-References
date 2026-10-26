---
title: EndSend()
second_title: Référence de l'API Aspose.Slides pour C++
description: Attend jusqu'à ce que l'opération d'envoi asynchrone spécifiée soit terminée.
type: docs
weight: 508
url: /fr/system.net.sockets/socket/endsend/
---
## Socket::EndSend(System::SharedPtr\<IAsyncResult\>) méthode

Attend jusqu'à ce que l'opération d'envoi asynchrone spécifiée soit terminée.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Un objet [IAsyncResult](../../../system/iasyncresult/) qui représente une opération d'envoi asynchrone. |

### Valeur de retour

Le nombre d'octets envoyés.

## Socket::EndSend(System::SharedPtr\<IAsyncResult\>, SocketError\&) méthode

Attend jusqu'à ce que l'opération d'envoi asynchrone spécifiée soit terminée.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Un objet [IAsyncResult](../../../system/iasyncresult/) qui représente une opération d'envoi asynchrone. |
| errorCode | [SocketError](../../socketerror/)\& | Le paramètre de sortie où le code d'erreur sera affecté lorsque l'opération d'envoi échoue. |

### Valeur de retour

Le nombre d'octets envoyés.

## Voir aussi

* Enum [SocketError](../../socketerror/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Socket](../)
* Espace de noms [System::Net::Sockets](../../)
* Bibliothèque [Aspose.Slides](../../../)