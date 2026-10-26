---
title: Parse()
second_title: Aspose.Slides dla C++ – referencja API
description: Zwraca obiekt reprezentujący wartość stałej wyliczeniowej określonego typu wyliczenia o podanej nazwie.
type: docs
weight: 27
url: /pl/system/enumvaluesbase/parse/
---
## EnumValuesBase::Parse(const TypeInfo\&, const String\&, bool) metoda

Zwraca obiekt reprezentujący wartość stałej wyliczeniowej określonego typu wyliczenia o podanej nazwie.

```cpp
static SharedPtr<Object> System::EnumValuesBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Obiekt [TypeInfo](../../typeinfo/) reprezentujący typ wartości wyliczenia do zwrócenia |
| str | const [String](../../string/)\& | Nazwa stałej wyliczeniowej |
| ignoreCase | **bool** | Określa, czy wielkość liter ma być ignorowana podczas interpretacji nazwy stałej wyliczeniowej |

### Wartość zwracana

Obiekt reprezentujący wartość stałej wyliczeniowej, której nazwa jest podana w **str**.

## Zobacz także

* Typedef [SharedPtr](../../sharedptr/)
* Klasa [Object](../../object/)
* Klasa [TypeInfo](../../typeinfo/)
* Klasa [String](../../string/)
* Klasa [EnumValuesBase](../)
* Przestrzeń nazw [System](../../)
* Library [Aspose.Slides](../../../)