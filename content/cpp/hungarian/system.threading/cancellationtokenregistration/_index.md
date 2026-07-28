---
title: CancellationTokenRegistration
second_title: Aspose.Slides for C++ API referenciája
description: Egy lemondási token visszahívás regisztrációját képviseli.
type: docs
weight: 27
url: /hu/system.threading/cancellationtokenregistration/
---
## CancellationTokenRegistration osztály


Egy lemondási token visszahívás regisztrációját képviseli.

```cpp
class CancellationTokenRegistration
```

## Módszerek

| Method | Leírás |
| --- | --- |
| void [Dispose](./dispose/)() | Megszünteti a regisztrációt, és eltávolítja a visszahívást a kapcsolódó [CancellationTokenSource](../cancellationtokensource/)-ből. A metódus meghívása után a regisztrált visszahívás többé nem lesz meghívva, amikor a kapcsolódó [CancellationTokenSource](../cancellationtokensource/) le lesz mondva. |
## Megjegyzések


Ez az osztály lehetővé teszi egy visszahívás leiratkoztatását egy lemondási tokenből. Megszüntetésekor eltávolítja a visszahívást a kapcsolódó [CancellationTokenSource](../cancellationtokensource/)-ből. 
Ez az osztályt nem szabad közvetlenül létrehozni - azt a [CancellationToken](../cancellationtoken/) regisztrációs metódusok adják vissza. 

## Lásd még

* Névterület [System::Threading](../)
* Könyvtár [Aspose.Slides](../../)