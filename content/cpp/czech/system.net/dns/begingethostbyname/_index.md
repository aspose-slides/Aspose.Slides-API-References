---
title: BeginGetHostByName()
second_title: Aspose.Slides pro C++ - reference API
description: Spouští asynchronní operaci vytvoření nové instance třídy IPHostEntry pomocí zadaného názvu hostitele.
type: docs
weight: 53
url: /cs/system.net/dns/begingethostbyname/
---
## Dns::BeginGetHostByName(String, AsyncCallback, System::SharedPtr\<Object\>) metoda

Spouští asynchronní operaci vytvoření nové instance třídy IPHostEntry pomocí zadaného názvu hostitele.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostByName(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | Název hostitele. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Callback, který bude volán po dokončení operace. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Uživatelem poskytnutá data používaná k jednoznačnému identifikování každé asynchronní operace. |

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