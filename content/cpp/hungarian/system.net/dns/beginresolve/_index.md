---
title: BeginResolve()
second_title: Aspose.Slides C++ API hivatkozás
description: Elindít egy aszinkron műveletet, hogy a megadott gépnév használatával új IPHostEntry-class példányt hozzon létre.
type: docs
weight: 157
url: /hu/system.net/dns/beginresolve/
---
## Dns::BeginResolve(String, AsyncCallback, System::SharedPtr\<Object\>) metódus

Elindít egy aszinkron műveletet, hogy létrehozzon egy új IPHostEntry-osztály példányt a megadott gépnév használatával.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginResolve(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | A gépnév, amelyet az új [IPHostEntry](../../iphostentry/) osztály példányának létrehozásához használnak. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Egy visszahívás, amelyet a művelet befejezésekor hívnak meg. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Felhasználó által megadott adat, amelyet az egyes aszinkron műveletek egyedi azonosítására használnak. |

### Visszatérési érték

Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely az elindított aszinkron műveletet képviseli.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)