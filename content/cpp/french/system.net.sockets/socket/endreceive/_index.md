---
title: EndReceive()
second_title: Référence API Aspose.Slides pour C++
description: Attend que l'opération de réception asynchrone spécifiée soit terminée.
type: docs
weight: 534
url: /fr/system.net.sockets/socket/endreceive/
---
## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>) méthode


Attend que l'opération de réception asynchrone spécifiée soit terminée.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Un objet [IAsyncResult](../../../system/iasyncresult/) qui représente une opération de réception asynchrone. |

### Valeur de retour

Le nombre d'octets reçus.

## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>, SocketError\&) méthode


Attend que l'opération de réception asynchrone spécifiée soit terminée.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Un objet [IAsyncResult](../../../system/iasyncresult/) qui représente une opération de réception asynchrone. |
| errorCode | [SocketError](../../socketerror/)\& | Le paramètre de sortie où le code d'erreur sera assigné lorsque l'opération de réception échoue. |

### Valeur de retour

Le nombre d'octets reçus.

## Voir aussi

* Enum [SocketError](../../socketerror/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)