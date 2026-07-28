---
title: BeginGetHostEntry()
second_title: Aspose.Slides C++ API Referenciája
description: Elindít egy aszinkron műveletet egy új IPHostEntry-osztálypéldány létrehozásához a megadott karakterláncot felhasználva, amely egy gépnevet vagy IP-címet tartalmaz.
type: docs
weight: 105
url: /hu/system.net/dns/begingethostentry/
---
## Dns::BeginGetHostEntry(String, AsyncCallback, System::SharedPtr\<Object\>) metódus

Elindít egy aszinkron műveletet egy új IPHostEntry-osztálypéldány létrehozásához a megadott karakterláncot felhasználva, amely egy gépnevet vagy IP-címet tartalmaz.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | A karakterlánc, amely egy gépnevet vagy IP-címet tartalmaz. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Egy visszahívás, amelyet a művelet befejeződésekor hívnak meg. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Felhasználó által biztosított adatok, amelyeket az egyes aszinkron műveletek egyedi azonosítására használnak. |

### Visszatérési érték

Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely a elindított aszinkron műveletet képviseli.

## Dns::BeginGetHostEntry(System::SharedPtr\<IPAddress\>, AsyncCallback, System::SharedPtr\<Object\>) metódus

Elindít egy aszinkron műveletet egy új IPHostEntry-osztálypéldány létrehozásához a megadott IP-címet felhasználva.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(System::SharedPtr<IPAddress> address, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | Az IP-cím. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Egy visszahívás, amelyet a művelet befejeződésekor hívnak meg. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Felhasználó által biztosított adatok, amelyeket az egyes aszinkron műveletek egyedi azonosítására használnak. |

### Visszatérési érték

Egy [IAsyncResult](../../../system/iasyncresult/) objektum, amely a elindított aszinkron műveletet képviseli.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Típusdefiníció [AsyncCallback](../../../system/asynccallback/)
* Osztály [IAsyncResult](../../../system/iasyncresult/)
* Osztály [String](../../../system/string/)
* Osztály [Object](../../../system/object/)
* Osztály [Dns](../)
* Osztály [IPAddress](../../ipaddress/)
* Névtér [System::Net](../../)
* Könyvtár [Aspose.Slides](../../../)