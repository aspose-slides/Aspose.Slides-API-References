---
title: BeginResolve()
second_title: Aspose.Slides pro C++ API Reference
description: Spouští asynchronní operaci k vytvoření nové instance třídy IPHostEntry pomocí zadaného názvu hostitele.
type: docs
weight: 157
url: /cs/system.net/dns/beginresolve/
---
## Dns::BeginResolve(String, AsyncCallback, System::SharedPtr\<Object\>) method


Spouští asynchronní operaci k vytvoření nové instance IPHostEntry-class pomocí zadaného názvu hostitele.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginResolve(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | Název hostitele, který se používá k vytvoření nové instance třídy [IPHostEntry](../../iphostentry/). |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Zpětné volání, které se zavolá po dokončení operace. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Uživatelem poskytnutá data používaná k jedinečné identifikaci každé asynchronní operace. |

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
* Library [Aspose.Slides](../../../)