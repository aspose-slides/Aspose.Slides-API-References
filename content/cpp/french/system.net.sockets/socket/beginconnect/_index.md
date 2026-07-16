---
title: BeginConnect()
second_title: Référence de l'API Aspose.Slides pour C++
description: Initie une opération de connexion asynchrone.
type: docs
weight: 573
url: /fr/system.net.sockets/socket/beginconnect/
---
## Socket::BeginConnect(System::SharedPtr\<EndPoint\>, AsyncCallback, System::SharedPtr\<Object\>) méthode


Initie une opération de connexion asynchrone.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<EndPoint> remoteEP, AsyncCallback callback, System::SharedPtr<Object> state)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Le point de terminaison distant. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Un rappel qui sera appelé lorsque l'opération sera terminée. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Données fournies par l'utilisateur utilisées pour identifier de manière unique chaque opération de connexion asynchrone. |

### Valeur de retour

Un objet [IAsyncResult](../../../system/iasyncresult/) représentant l'opération de connexion asynchrone initiée.

## Socket::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) méthode


Initie une opération de connexion asynchrone.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| host | [String](../../../system/string/) | Le nom d'hôte distant. |
| port | **int32_t** | Le numéro de port de l'hôte distant. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Un rappel qui sera appelé lorsque l'opération sera terminée. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Données fournies par l'utilisateur utilisées pour identifier de manière unique chaque opération de connexion asynchrone. |

### Valeur de retour

Un objet [IAsyncResult](../../../system/iasyncresult/) représentant l'opération de connexion asynchrone initiée.

## Socket::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) méthode


Initie une opération de connexion asynchrone.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | L'adresse IP de l'hôte distant. |
| port | **int32_t** | Le numéro de port de l'hôte distant. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Un rappel qui sera appelé lorsque l'opération sera terminée. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Données fournies par l'utilisateur utilisées pour identifier de manière unique chaque opération de connexion asynchrone. |

### Valeur de retour

Un objet [IAsyncResult](../../../system/iasyncresult/) représentant l'opération de connexion asynchrone initiée.

## Socket::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) méthode


Initie une opération de connexion asynchrone.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | Les adresses IP de l'hôte distant. |
| port | **int32_t** | Le numéro de port de l'hôte distant. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Un rappel qui sera appelé lorsque l'opération sera terminée. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Données fournies par l'utilisateur utilisées pour identifier de manière unique chaque opération de connexion asynchrone. |

### Valeur de retour

Un objet [IAsyncResult](../../../system/iasyncresult/) représentant l'opération de connexion asynchrone initiée.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [EndPoint](../../../system.net/endpoint/)
* Classe [Object](../../../system/object/)
* Classe [Socket](../)
* Classe [String](../../../system/string/)
* Classe [IPAddress](../../../system.net/ipaddress/)
* Espace de noms [System::Net::Sockets](../../)
* Bibliothèque [Aspose.Slides](../../../)