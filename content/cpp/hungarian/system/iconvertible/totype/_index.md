---
title: ToType()
second_title: Aspose.Slides C++ API referencia
description: "Átalakítja ennek a példánynak az értékét egy System::Object-re a megadott System::Type-ból, amely ekvivalens értékkel rendelkezik, a megadott kultúra-specifikus formázási információk használatával."
type: docs
weight: 209
url: /hu/system/iconvertible/totype/
---
## IConvertible::ToType(const TypeInfo\&, System::SharedPtr\<System::IFormatProvider\>) metódus


Átalakítja ennek a példánynak az értékét a megadott System::Type egy [System::Object](../../object/)-jává, amelynek ekvivalens értéke van, a megadott kultúra-specifikus formázási információk használatával.

```cpp
virtual System::SharedPtr<System::Object> System::IConvertible::ToType(const TypeInfo &conversionType, System::SharedPtr<System::IFormatProvider> provider)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| conversionType | const [TypeInfo](../../typeinfo/)\& | A System::Type, amelyre ennek a példánynak az értéke konvertálódik. |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | Egy [System::IFormatProvider](../../iformatprovider/) interfész implementáció, amely kultúra-specifikus formázási információkat biztosít. |

### Visszatérési érték

Egy [System::Object](../../object/) példány a conversionType típusából, amelynek értéke ekvivalens ennek a példánynak az értékével.

## Lásd még

* Típusdefiníció [SharedPtr](../../sharedptr/)
* Osztály [Object](../../object/)
* Osztály [TypeInfo](../../typeinfo/)
* Osztály [IFormatProvider](../../iformatprovider/)
* Osztály [IConvertible](../)
* Névterület [System](../../)
* Könyvtár [Aspose.Slides](../../../)