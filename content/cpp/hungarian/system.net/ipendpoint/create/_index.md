---
title: Create()
second_title: Aspose.Slides for C++ API hivatkozás
description: Az EndPoint osztály új példányának létrehozása a megadott socket cím használatával.
type: docs
weight: 92
url: /hu/system.net/ipendpoint/create/
---
## IPEndPoint::Create(System::SharedPtr\<SocketAddress\>) metódus

Új példányt hoz létre a [EndPoint](../../endpoint/) osztályból a megadott socket cím használatával.

```cpp
System::SharedPtr<EndPoint> System::Net::IPEndPoint::Create(System::SharedPtr<SocketAddress> socketAddress) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| socketAddress | [System::SharedPtr](../../../system/sharedptr/)\<[SocketAddress](../../socketaddress/)\> | Az a socket cím, amelyet egy új példány inicializálásához fognak használni. |

### Visszatérési érték

Egy újonnan létrehozott EndPoint osztályú példány.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [EndPoint](../../endpoint/)
* Osztály [SocketAddress](../../socketaddress/)
* Osztály [IPEndPoint](../)
* Névtér [System::Net](../../)
* Könyvtár [Aspose.Slides](../../../)