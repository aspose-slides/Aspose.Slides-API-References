---
title: Is()
second_title: Aspose.Slides pro C++ - referenční dokumentace API
description: 
type: docs
weight: 27
url: /cs/system.runtime.serialization/details_serializationexception/is/
---
## Details_SerializationException::Is(const System::TypeInfo\&) const metoda

```cpp
bool System::Runtime::Serialization::Details_SerializationException::Is(const System::TypeInfo &target) const override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) struktura popisující typ, proti kterému se testuje aktuální objekt. |

### Návratová hodnota

True pokud je objekt označeného typu nebo jeho podtřídy, false jinak.

## Poznámky

Zkontrolujte, zda objekt představuje instanci typu popsaného pomocí targetType. Analogie operátoru C# 'is'.

## Viz také

* Třída [TypeInfo](../../../system/typeinfo/)
* Třída [Details_SerializationException](../)
* Jmenný prostor [System::Runtime::Serialization](../../)
* Knihovna [Aspose.Slides](../../../)