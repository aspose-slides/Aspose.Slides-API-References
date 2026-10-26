---
title: Is()
second_title: Aspose.Slides for C++ API Referencia
description: 
type: docs
weight: 27
url: /hu/system.runtime.serialization/details_serializationexception/is/
---
## Details_SerializationException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Runtime::Serialization::Details_SerializationException::Is(const System::TypeInfo &target) const override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) struktúra, amely leírja a típust, amellyel a jelenlegi objektumot teszteljük. |

### Visszatérési érték

Igaz, ha az objektum a megcímkézett típushoz vagy annak alosztályához tartozik, egyébként hamis.

## Megjegyzés

Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. 

## Lásd még

* Osztály [TypeInfo](../../../system/typeinfo/)
* Osztály [Details_SerializationException](../)
* Névtér [System::Runtime::Serialization](../../)
* Könyvtár [Aspose.Slides](../../../)