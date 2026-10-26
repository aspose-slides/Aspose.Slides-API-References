---
title: BeginGetHostAddresses()
second_title: Aspose.Slides for C++ API-referencia
description: Aszinkron műveletet indít egy új IPHostEntry-class példány létrehozásához a megadott karakterlánc használatával, amely gazdagépnevet vagy IP-címet tartalmaz.
type: docs
weight: 131
url: /hu/system.net/dns/begingethostaddresses/
---
## Dns::BeginGetHostAddresses(String, AsyncCallback, System::SharedPtr\<Object\>) metódus


Aszinkron műveletet indít egy új IPHostEntry-osztálypéldány létrehozásához a megadott karakterlánc segítségével, amely egy gazdagépnevet vagy IP-címet tartalmaz.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostAddresses(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | Egy karakterlánc, amely egy gazdagépnevet vagy IP-címet tartalmaz. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Egy visszahívás, amelyet a művelet befejeződésénél hívnak meg. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | A felhasználó által biztosított adat, amely egyedileg azonosítja az aszinkron műveletet. |

### Visszatérési érték

Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely a kezdeményezett aszinkron műveletet képviseli.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Típusdefiníció [AsyncCallback](../../../system/asynccallback/)
* Osztály [IAsyncResult](../../../system/iasyncresult/)
* Osztály [String](../../../system/string/)
* Osztály [Object](../../../system/object/)
* Osztály [Dns](../)
* Névtér [System::Net](../../)
* Könyvtár [Aspose.Slides](../../../)