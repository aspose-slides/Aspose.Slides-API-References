---
title: BeginGetHostEntry()
second_title: Referencia de API de Aspose.Slides para C++
description: Inicia una operación asíncrona para crear una nueva instancia de IPHostEntry-clase usando la cadena especificada que contiene un nombre de host o una dirección IP.
type: docs
weight: 105
url: /es/system.net/dns/begingethostentry/
---
## Dns::BeginGetHostEntry(String, AsyncCallback, System::SharedPtr\<Object\>) método


Inicia una operación asíncrona para crear una nueva instancia de IPHostEntry-clase usando la cadena especificada que contiene un nombre de host o una dirección IP.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | La cadena que contiene un nombre de host o una dirección IP. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Una devolución de llamada que se invocará cuando la operación se complete. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Datos proporcionados por el usuario utilizados para identificar de forma única cada operación asíncrona. |

### Valor de retorno

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación asíncrona iniciada.

## Dns::BeginGetHostEntry(System::SharedPtr\<IPAddress\>, AsyncCallback, System::SharedPtr\<Object\>) método


Inicia una operación asíncrona para crear una nueva instancia de IPHostEntry-clase usando la dirección IP especificada.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(System::SharedPtr<IPAddress> address, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | La dirección IP. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Una devolución de llamada que se invocará cuando la operación se complete. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Datos proporcionados por el usuario utilizados para identificar de forma única cada operación asíncrona. |

### Valor de retorno

Un objeto [IAsyncResult](../../../system/iasyncresult/) que representa la operación asíncrona iniciada.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Class [Dns](../)
* Class [IPAddress](../../ipaddress/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)