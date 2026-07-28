---
title: BeginGetHostByName()
second_title: Aspose.Slides C++ API referencia
description: Elindít egy aszinkron műveletet egy új IPHostEntry-class példány létrehozásához a megadott host név használatával.
type: docs
weight: 53
url: /hu/system.net/dns/begingethostbyname/
---
## Dns::BeginGetHostByName(String, AsyncCallback, System::SharedPtr\<Object\>) metódus

Elindít egy aszinkron műveletet egy új IPHostEntry-class példány létrehozásához a megadott host név használatával.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostByName(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | Egy host név. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Egy visszahívás, amelyet a művelet befejeződésekor hívnak meg. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | A felhasználó által biztosított adat, amely egyedileg azonosítja az egyes aszinkron műveleteket. |

### Visszatérési érték

Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely a kezdeményezett aszinkron műveletet reprezentálja.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Osztály [IAsyncResult](../../../system/iasyncresult/)
* Osztály [String](../../../system/string/)
* Osztály [Object](../../../system/object/)
* Osztály [Dns](../)
* Névtér [System::Net](../../)
* Library [Aspose.Slides](../../../)