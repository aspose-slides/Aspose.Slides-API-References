---
title: WaitOne()
second_title: Aspose.Slides C++ API referencia
description: Zárolja a szemafort. Korlátlan várakozást végez, ha szükséges.
type: docs
weight: 40
url: /hu/system.threading/semaphore/waitone/
---
## Semaphore::WaitOne() metódus


Zárolja a szemafort. Korlátlan várakozást hajt végre, ha szükséges.

```cpp
virtual bool System::Threading::Semaphore::WaitOne() override
```


### Visszatérési érték

Mindig true értéket ad vissza, mivel nem tér vissza, amíg a szemafor nincs lezárva.

## Semaphore::WaitOne(int) metódus


Zárolja a szemafort. Várakozást hajt végre, ha szükséges.

```cpp
virtual bool System::Threading::Semaphore::WaitOne(int millisecondsTimeout) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| millisecondsTimeout | int | Várakozási időkorlát ezredmásodpercben. |

### Visszatérési érték

True értéket ad vissza, ha a szemafor le van zárva, vagy false értéket, ha az időkorlát lejárt.

## Lásd még

* Osztály [Semaphore](../)
* Névtere [System::Threading](../../)
* Könyvtár [Aspose.Slides](../../../)