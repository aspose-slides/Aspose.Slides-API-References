---
title: BeginGetHostByName()
second_title: Odwołanie API Aspose.Slides dla C++
description: Inicjuje operację asynchroniczną tworzącą nową instancję klasy IPHostEntry przy użyciu podanej nazwy hosta.
type: docs
weight: 53
url: /pl/system.net/dns/begingethostbyname/
---
## Dns::BeginGetHostByName(String, AsyncCallback, System::SharedPtr\<Object\>) metoda

Inicjuje operację asynchroniczną tworzącą nową instancję klasy IPHostEntry przy użyciu podanej nazwy hosta.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostByName(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | Nazwa hosta. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Wywołanie zwrotne wywoływane po zakończeniu operacji. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dane dostarczone przez użytkownika używane do unikalnego identyfikowania każdej asynchronicznej operacji. |

### Wartość zwracana

Obiekt [IAsyncResult](../../../system/iasyncresult/) reprezentujący rozpoczętą operację asynchroniczną.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)