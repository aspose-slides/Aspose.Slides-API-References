---
title: IsBypassed()
second_title: Aspose.Slides for C++ API referencia
description: Visszaad egy értéket, amely jelzi, hogy a proxyt nem kell használni a megadott kiszolgálóhoz.
type: docs
weight: 40
url: /hu/system.net/iwebproxy/isbypassed/
---
## IWebProxy::IsBypassed(System::SharedPtr\<Uri\>) metódus

Visszaad egy értéket, amely jelzi, hogy a proxyt nem kell használni a megadott kiszolgálóhoz.

```cpp
virtual bool System::Net::IWebProxy::IsBypassed(System::SharedPtr<Uri> host)=0
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| host | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | A vizsgálandó kiszolgáló URI. |

### Visszatérési érték

True, ha a proxy szervert nem kell használni, egyébként false.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Uri](../../../system/uri/)
* Osztály [IWebProxy](../)
* Névtér [System::Net](../../)
* Könyvtár [Aspose.Slides](../../../)