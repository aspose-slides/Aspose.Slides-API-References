---
title: Convert()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Konwertuje wartość na podany System::TypeInfo."
type: docs
weight: 1
url: /pl/system.runtime.serialization/formatterconverter/convert/
---
## FormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) metoda

Konwertuje wartość na podany [System::TypeInfo](../../../system/typeinfo/).

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Obiekt do przekonwertowania. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Typ [System::TypeInfo](../../../system/typeinfo/), do którego wartość ma zostać przekonwertowana. |

### Wartość zwracana

Konwertowana wartość.

## FormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) metoda

Konwertuje wartość na podany [System::TypeCode](../../../system/typecode/).

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Obiekt do przekonwertowania. |
| typeCode | [TypeCode](../../../system/typecode/) | Typ [System::TypeCode](../../../system/typecode/), do którego wartość ma zostać przekonwertowana. |

### Wartość zwracana

Konwertowana wartość.

## Zobacz także

* Wyliczenie [TypeCode](../../../system/typecode/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [Object](../../../system/object/)
* Klasa [TypeInfo](../../../system/typeinfo/)
* Klasa [FormatterConverter](../)
* Przestrzeń nazw [System::Runtime::Serialization](../../)
* Biblioteka [Aspose.Slides](../../../)