---
title: BeginGetHostAddresses()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Inicjuje asynchroniczną operację tworzenia nowej instancji klasy IPHostEntry przy użyciu określonego ciągu znaków zawierającego nazwę hosta lub adres IP.
type: docs
weight: 131
url: /pl/system.net/dns/begingethostaddresses/
---
## Dns::BeginGetHostAddresses(String, AsyncCallback, System::SharedPtr\<Object\>) metoda

Inicjuje asynchroniczną operację tworzenia nowej instancji klasy IPHostEntry przy użyciu określonego ciągu znaków zawierającego nazwę hosta lub adres IP.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostAddresses(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | Ciąg znaków zawierający nazwę hosta lub adres IP. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Wywołanie zwrotne, które zostanie wywołane po zakończeniu operacji. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dane dostarczone przez użytkownika używane do jednoznacznej identyfikacji każdej asynchronicznej operacji. |

### Wartość zwracana

Obiekt [IAsyncResult](../../../system/iasyncresult/) reprezentujący zainicjowaną asynchroniczną operację.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Klasa [IAsyncResult](../../../system/iasyncresult/)
* Klasa [String](../../../system/string/)
* Klasa [Object](../../../system/object/)
* Klasa [Dns](../)
* Przestrzeń nazw [System::Net](../../)
* Biblioteka [Aspose.Slides](../../../)