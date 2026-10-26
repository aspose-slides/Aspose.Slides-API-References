---
title: Is()
second_title: Aspose.Slides C++ API hivatkozás
description: 
type: docs
weight: 27
url: /hu/system.security/details_securityexception/is/
---
## Details_SecurityException::Is(const System::TypeInfo\&) const method

```cpp
bool System::Security::Details_SecurityException::Is(const System::TypeInfo &target) const override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) struktúra, amely leírja a típust, amellyel a jelenlegi objektumot teszteljük. |

### Visszatérési érték

Igaz, ha az objektum a megcímkézett típus vagy annak alosztálya, egyébként hamis.

## Megjegyzések

Ellenőrizze, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja.

## Lásd még

* Osztály [TypeInfo](../../../system/typeinfo/)
* Osztály [Details_SecurityException](../)
* Névtér [System::Security](../../)
* Könyvtár [Aspose.Slides](../../../)