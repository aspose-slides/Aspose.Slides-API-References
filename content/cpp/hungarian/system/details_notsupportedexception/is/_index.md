---
title: Is()
second_title: Aspose.Slides for C++ API-referencia
description: 
type: docs
weight: 27
url: /hu/system/details_notsupportedexception/is/
---
## Details_NotSupportedException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Details_NotSupportedException::Is(const System::TypeInfo &target) const override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) struktúra, amely leírja a típust, amelyet a jelenlegi objektum ellen kell tesztelni. |

### Visszatérési érték

Igaz, ha az objektum a megcímkézett típusú vagy annak alosztálya, különben hamis.

## Megjegyzés


Ellenőrizze, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. 

## Lásd még

* Osztály [TypeInfo](../../typeinfo/)
* Osztály [Details_NotSupportedException](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)