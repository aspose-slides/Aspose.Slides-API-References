---
title: Is()
second_title: Aspose.Slides a C++ API-referencia
description: 
type: docs
weight: 27
url: /hu/system.io/details_invaliddataexception/is/
---
## Details_InvalidDataException::Is(const System::TypeInfo\&) const method

```cpp
bool System::IO::Details_InvalidDataException::Is(const System::TypeInfo &target) const override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) struktúra, amely leírja a típust, amellyel a jelenlegi objektumot tesztelni kell. |

### Visszatérési érték

Igaz, ha az objektum a megcímkézett típus vagy annak alosztálya, különben hamis.

## Megjegyzés

Ellenőrizze, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja.

## Lásd még

* Osztály [TypeInfo](../../../system/typeinfo/)
* Osztály [Details_InvalidDataException](../)
* Névtere [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)