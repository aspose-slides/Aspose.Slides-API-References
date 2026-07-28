---
title: Is()
second_title: Aspose.Slides C++ API referenciája
description: 
type: docs
weight: 27
url: /hu/system.threading/details_synchronizationlockexception/is/
---
## Details_SynchronizationLockException::Is(const System::TypeInfo\&) const method

```cpp
bool System::Threading::Details_SynchronizationLockException::Is(const System::TypeInfo &target) const override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) struktúra, amely leírja a típust, amellyel a jelenlegi objektumot tesztelik. |

### Visszatérési érték

True, ha az objektum a címkézett típusba vagy annak alosztályába tartozik, egyébként false.

## Megjegyzés

Ellenőrizze, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája.

## Lásd még

* Osztály [TypeInfo](../../../system/typeinfo/)
* Osztály [Details_SynchronizationLockException](../)
* Névtér [System::Threading](../../)
* Könyvtár [Aspose.Slides](../../../)