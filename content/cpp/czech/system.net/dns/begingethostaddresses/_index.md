---
title: BeginGetHostAddresses()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Spouští asynchronní operaci k vytvoření nové instance třídy IPHostEntry pomocí zadaného řetězce, který obsahuje název hostitele nebo IP adresu.
type: docs
weight: 131
url: /cs/system.net/dns/begingethostaddresses/
---
## Dns::BeginGetHostAddresses(String, AsyncCallback, System::SharedPtr\<Object\>) method


Spouští asynchronní operaci pro vytvoření nové instance IPHostEntry-class pomocí zadaného řetězce, který obsahuje název hostitele nebo IP adresu.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostAddresses(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | Řetězec, který obsahuje název hostitele nebo IP adresu. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Callback, který se zavolá po dokončení operace. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Uživatel poskytovaná data použité k jedinečné identifikaci každé asynchronní operace. |

### Návratová hodnota

Objekt [IAsyncResult](../../../system/iasyncresult/) představující zahájenou asynchronní operaci.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Třída [IAsyncResult](../../../system/iasyncresult/)
* Třída [String](../../../system/string/)
* Třída [Object](../../../system/object/)
* Třída [Dns](../)
* Jmenný prostor [System::Net](../../)
* Knihovna [Aspose.Slides](../../../)