---
title: CancellationToken
second_title: Aspose.Slides C++ API hivatkozás
description: Közvetíti azt az értesítést, hogy a műveleteket le kell állítani. Ez az osztály egy mechanizmust biztosít a szálak közötti együttműködő leállításhoz, lehetővé téve, hogy egy szál értesítse a többit, hogy egy műveletet le kell állítani.
type: docs
weight: 14
url: /hu/system.threading/cancellationtoken/
---
## CancellationToken osztály


Közvetíti azt az értesítést, hogy a műveleteket le kell állítani. Ez az osztály egy mechanizmust biztosít a szálak közötti együttműködő leállításhoz, lehetővé téve, hogy egy szál értesítse a többit, hogy egy műveletet le kell állítani.

```cpp
class CancellationToken : public System::Details::BoxableObjectBase
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
|  [CancellationToken](./cancellationtoken/)() | Alapértelmezett konstruktor. |
| **bool** [get_CanBeCanceled](./get_canbecanceled/)() const | Megadja, hogy ez a token képes-e a leállított állapotban lenni. |
| **bool** [get_IsCancellationRequested](./get_iscancellationrequested/)() const | Megadja, hogy a leállítást kérte-e ez a token. |
| static [CancellationToken](./) [get_None](./get_none/)() | Visszaad egy üres [System::Threading::CancellationToken](./) értéket. |
| [CancellationTokenRegistration](../cancellationtokenregistration/) [Register](./register/)(const [Action](../../system/action/)<>\&) const | Regisztrál egy visszahívást, amely akkor lesz meghívva, amikor a leállítást kérik. |
| void [ThrowIfCancellationRequested](./throwifcancellationrequested/)() const | Kivételt dob, ha a leállítást kérik (OperationCanceledException). |
## Megjegyzések



A [CancellationToken](./) csak a hozzá tartozó [CancellationTokenSource](../cancellationtokensource/) használatával mondható le. 

## Lásd még

* Névtér [System::Threading](../)
* Könyvtár [Aspose.Slides](../../)