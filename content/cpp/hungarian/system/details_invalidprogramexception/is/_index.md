---
title: Is()
second_title: Aspose.Slides C++ API Referenciája
description: 
type: docs
weight: 27
url: /hu/system/details_invalidprogramexception/is/
---
## Details_InvalidProgramException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Details_InvalidProgramException::Is(const System::TypeInfo &target) const override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) struktúra, amely leírja a típust, amely ellen a jelenlegi objektumot tesztelik. |

### Visszatérési érték

Igaz, ha az objektum a megcímkézett típushoz vagy annak alosztályához tartozik, egyébként hamis.

## Megjegyzés

Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. 

## Lásd még

* Osztály [TypeInfo](../../typeinfo/)
* Osztály [Details_InvalidProgramException](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)