---
title: Is()
second_title: Aspose.Slides C++ API Referencia
description: 
type: docs
weight: 27
url: /hu/system.threading/details_threadabortexception/is/
---
## Részletek_ThreadAbortException::Is(const System::TypeInfo\&) const metódus

```cpp
bool System::Threading::Details_ThreadAbortException::Is(const System::TypeInfo &target) const override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) struktúra, amely leírja a típust, amelyhez a jelenlegi objektumot teszteljük. |

### Visszatérési érték

Igaz, ha az objektum a megcímkézett típus vagy annak alosztálya, egyébként hamis.

## Megjegyzések

Ellenőrizze, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája.

## Lásd még

* Osztály [TypeInfo](../../../system/typeinfo/)
* Osztály [Details_ThreadAbortException](../)
* Névterület [System::Threading](../../)
* Könyvtár [Aspose.Slides](../../../)