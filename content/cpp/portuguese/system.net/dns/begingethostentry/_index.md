---
title: BeginGetHostEntry()
second_title: Referência da API Aspose.Slides para C++
description: Inicia uma operação assíncrona para criar uma nova instância da classe IPHostEntry usando a string especificada que contém um nome de host ou endereço IP.
type: docs
weight: 105
url: /pt/system.net/dns/begingethostentry/
---
## Dns::BeginGetHostEntry(String, AsyncCallback, System::SharedPtr\<Object\>) method

Inicia uma operação assíncrona para criar uma nova instância da classe IPHostEntry usando a string especificada que contém um nome de host ou endereço IP.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | A string que contém um nome de host ou endereço IP. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Um callback a ser chamado quando a operação for concluída. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dados fornecidos pelo usuário usados para identificar de forma única cada operação assíncrona. |

### Valor de Retorno

Um objeto [IAsyncResult](../../../system/iasyncresult/) que representa a operação assíncrona iniciada.

## Dns::BeginGetHostEntry(System::SharedPtr\<IPAddress\>, AsyncCallback, System::SharedPtr\<Object\>) method

Inicia uma operação assíncrona para criar uma nova instância da classe IPHostEntry usando o endereço IP especificado.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(System::SharedPtr<IPAddress> address, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | O endereço IP. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Um callback a ser chamado quando a operação for concluída. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dados fornecidos pelo usuário usados para identificar de forma única cada operação assíncrona. |

### Valor de Retorno

Um objeto [IAsyncResult](../../../system/iasyncresult/) que representa a operação assíncrona iniciada.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [String](../../../system/string/)
* Classe [Object](../../../system/object/)
* Classe [Dns](../)
* Classe [IPAddress](../../ipaddress/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)