---
title: Is()
second_title: Aspose.Slides C++ API referenciája
description: 
type: docs
weight: 27
url: /hu/system.io/details_fileloadexception/is/
---
## Details_FileLoadException::Is(const System::TypeInfo\&) const metódus




```cpp
bool System::IO::Details_FileLoadException::Is(const System::TypeInfo &target) const override
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) struktúra, amely leírja a típust, amellyel a jelenlegi objektumot teszteljük. |

### Visszatérési érték

Igaz, ha az objektum a megcímkézett típusba vagy annak alosztályába tartozik, egyébként hamis.

## Megjegyzés

Ellenőrizze, hogy az objektum a targetType által leírt típus példányát képviseli-e. A C# 'is' operátor analógja.

## Lásd még

* Osztály [TypeInfo](../../../system/typeinfo/)
* Osztály [Details_FileLoadException](../)
* Névterület [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)