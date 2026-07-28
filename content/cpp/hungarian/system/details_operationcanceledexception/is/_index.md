---
title: Is()
second_title: Aspose.Slides C++ API Referenciája
description: 
type: docs
weight: 27
url: /hu/system/details_operationcanceledexception/is/
---
## Részletek_OperationCanceledException::Is(const System::TypeInfo\&) const metódus




```cpp
bool System::Details_OperationCanceledException::Is(const System::TypeInfo &target) const override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) struktúra, amely leírja a típust, amely ellen a jelenlegi objektumot teszteljük. |

### Visszatérési érték

Igaz, ha az objektum a megcímkézett típusú vagy annak alosztálya, egyébként hamis.

## Megjegyzések

Ellenőrizze, hogy az objektum a targetType által leírt típus egy példányát képviseli-e. A C# 'is' operátor analógiája.

## Lásd még

* Osztály [TypeInfo](../../typeinfo/)
* Osztály [Details_OperationCanceledException](../)
* Névterület [System](../../)
* Könyvtár [Aspose.Slides](../../../)