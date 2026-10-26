---
title: GetCustomAttribute()
second_title: Aspose.Slides pro C++ API Reference
description: Vyhledá vlastní atribut aplikovaný s určeným typem a aplikovaný na typ reprezentovaný aktuálním objektem.
type: docs
weight: 573
url: /cs/system/typeinfo/getcustomattribute/
---
## TypeInfo::GetCustomAttribute(const TypeInfo\&) const metoda

Vyhledá vlastní atribut aplikovaný, který má zadaný typ a je aplikován na typ reprezentovaný aktuálním objektem.

```cpp
ObjectPtr System::TypeInfo::GetCustomAttribute(const TypeInfo &attributeType) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | Stálá reference na objekt [TypeInfo](../) představující typ atributu, který se má vyhledat |

### Návratová hodnota

Ukazatel na objekt představující nalezený atribut nebo nulový ukazatel, pokud nebyl nalezen žádný atribut odpovídající kritériím vyhledávání

## Viz také

* Třída [SmartPtr](../../smartptr/)
* Třída [TypeInfo](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)