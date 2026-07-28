---
title: BeginGetHostEntry()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Inicjuje asynchroniczną operację tworzenia nowej instancji klasy IPHostEntry przy użyciu określonego ciągu znaków zawierającego nazwę hosta lub adres IP.
type: docs
weight: 105
url: /pl/system.net/dns/begingethostentry/
---
## Dns::BeginGetHostEntry(String, AsyncCallback, System::SharedPtr\<Object\>) metoda


Inicjuje asynchroniczną operację tworzenia nowej instancji klasy IPHostEntry przy użyciu podanego ciągu znaków zawierającego nazwę hosta lub adres IP.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | Ciąg znaków zawierający nazwę hosta lub adres IP. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Wywołanie zwrotne, które zostanie wywołane po zakończeniu operacji. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dane dostarczone przez użytkownika używane do jednoznacznego identyfikowania każdej asynchronicznej operacji. |

### Wartość zwracana

Obiekt [IAsyncResult](../../../system/iasyncresult/) reprezentujący zainicjowaną asynchroniczną operację.

## Dns::BeginGetHostEntry(System::SharedPtr\<IPAddress\>, AsyncCallback, System::SharedPtr\<Object\>) metoda


Inicjuje asynchroniczną operację tworzenia nowej instancji klasy IPHostEntry przy użyciu określonego adresu IP.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(System::SharedPtr<IPAddress> address, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | Adres IP. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Wywołanie zwrotne, które zostanie wywołane po zakończeniu operacji. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dane dostarczone przez użytkownika używane do jednoznacznego identyfikowania każdej asynchronicznej operacji. |

### Wartość zwracana

Obiekt [IAsyncResult](../../../system/iasyncresult/) reprezentujący zainicjowaną asynchroniczną operację.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasa [IAsyncResult](../../../system/iasyncresult/)
* Klasa [String](../../../system/string/)
* Klasa [Object](../../../system/object/)
* Klasa [Dns](../)
* Klasa [IPAddress](../../ipaddress/)
* Przestrzeń nazw [System::Net](../../)
* Biblioteka [Aspose.Slides](../../../)