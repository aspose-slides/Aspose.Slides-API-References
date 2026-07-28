---
title: BeginResolve()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Inicjuje operację asynchroniczną tworzącą nową instancję klasy IPHostEntry przy użyciu określonej nazwy hosta.
type: docs
weight: 157
url: /pl/system.net/dns/beginresolve/
---
## Dns::BeginResolve(String, AsyncCallback, System::SharedPtr\<Object\>) metoda


Inicjuje operację asynchroniczną tworzącą nową instancję klasy IPHostEntry przy użyciu określonej nazwy hosta.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginResolve(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | Nazwa hosta używana do utworzenia nowej instancji klasy [IPHostEntry](../../iphostentry/). |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Wywołanie zwrotne wywoływane po zakończeniu operacji. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dane dostarczone przez użytkownika używane do jednoznacznej identyfikacji każdej operacji asynchronicznej. |

### Wartość zwracana

Obiekt [IAsyncResult](../../../system/iasyncresult/) reprezentujący zainicjowaną operację asynchroniczną.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasa [IAsyncResult](../../../system/iasyncresult/)
* Klasa [String](../../../system/string/)
* Klasa [Object](../../../system/object/)
* Klasa [Dns](../)
* Przestrzeń nazw [System::Net](../../)
* Biblioteka [Aspose.Slides](../../../)