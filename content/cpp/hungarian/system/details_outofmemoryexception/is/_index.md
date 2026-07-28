---
title: Is()
second_title: Aspose.Slides C++ API hivatkozás
description: 
type: docs
weight: 27
url: /hu/system/details_outofmemoryexception/is/
---
## Details_OutOfMemoryException::Is(const System::TypeInfo\&) const metódus

```cpp
bool System::Details_OutOfMemoryException::Is(const System::TypeInfo &target) const override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) struktúra, amely leírja a típust, amelyet az aktuális objektum ellen kell tesztelni. |

### Visszatérési érték

Igaz, ha az objektum a megcímkézett típushoz vagy annak alosztályához tartozik, különben hamis.

## Megjegyzések

Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja.

## Lásd még

* Osztály [TypeInfo](../../typeinfo/)
* Osztály [Details_OutOfMemoryException](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)