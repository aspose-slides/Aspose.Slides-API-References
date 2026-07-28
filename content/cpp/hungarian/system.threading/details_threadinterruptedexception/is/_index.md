---
title: Is()
second_title: Aspose.Slides C++ API referencia
description: 
type: docs
weight: 27
url: /hu/system.threading/details_threadinterruptedexception/is/
---
## Details_ThreadInterruptedException::Is(const System::TypeInfo\&) const method

```cpp
bool System::Threading::Details_ThreadInterruptedException::Is(const System::TypeInfo &target) const override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) struktúra, amely leírja a típust, amely ellenőrizni kell az aktuális objektumra. |

### Visszatérési érték

Igaz, ha az objektum a megcímkézett típus vagy annak alosztálya, egyébként hamis.

## Megjegyzések

Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja.

## Lásd még

* Osztály [TypeInfo](../../../system/typeinfo/)
* Osztály [Details_ThreadInterruptedException](../)
* Névterület [System::Threading](../../)
* Könyvtár [Aspose.Slides](../../../)