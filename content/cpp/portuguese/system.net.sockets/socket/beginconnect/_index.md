---
title: BeginConnect()
second_title: Aspose.Slides para C++ Referência da API
description: Inicia uma operação de conexão assíncrona.
type: docs
weight: 573
url: /pt/system.net.sockets/socket/beginconnect/
---
## Socket::BeginConnect(System::SharedPtr\<EndPoint\>, AsyncCallback, System::SharedPtr\<Object\>) método


Inicia uma operação de conexão assíncrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<EndPoint> remoteEP, AsyncCallback callback, System::SharedPtr<Object> state)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | O ponto de extremidade remoto. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Um callback que será chamado quando a operação for concluída. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dados fornecidos pelo usuário usados para identificar de forma exclusiva cada operação de conexão assíncrona. |

### Valor de retorno

Um objeto [IAsyncResult](../../../system/iasyncresult/) que representa a operação de conexão assíncrona iniciada.

## Socket::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) método


Inicia uma operação de conexão assíncrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| host | [String](../../../system/string/) | O nome do host remoto. |
| port | **int32_t** | O número da porta do host remoto. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Um callback que será chamado quando a operação for concluída. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dados fornecidos pelo usuário usados para identificar de forma exclusiva cada operação de conexão assíncrona. |

### Valor de retorno

Um objeto [IAsyncResult](../../../system/iasyncresult/) que representa a operação de conexão assíncrona iniciada.

## Socket::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) método


Inicia uma operação de conexão assíncrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | O endereço IP do host remoto. |
| port | **int32_t** | O número da porta do host remoto. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Um callback que será chamado quando a operação for concluída. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dados fornecidos pelo usuário usados para identificar de forma exclusiva cada operação de conexão assíncrona. |

### Valor de retorno

Um objeto [IAsyncResult](../../../system/iasyncresult/) que representa a operação de conexão assíncrona iniciada.

## Socket::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) método


Inicia uma operação de conexão assíncrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | Os endereços IP do host remoto. |
| port | **int32_t** | O número da porta do host remoto. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Um callback que será chamado quando a operação for concluída. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dados fornecidos pelo usuário usados para identificar de forma exclusiva cada operação de conexão assíncrona. |

### Valor de retorno

Um objeto [IAsyncResult](../../../system/iasyncresult/) que representa a operação de conexão assíncrona iniciada.

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [EndPoint](../../../system.net/endpoint/)
* Classe [Object](../../../system/object/)
* Classe [Socket](../)
* Classe [String](../../../system/string/)
* Classe [IPAddress](../../../system.net/ipaddress/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)