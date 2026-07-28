---
title: ToObject()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Konwertuje określoną 64-bitową wartość całkowitą bez znaku na element wyliczenia.
type: docs
weight: 40
url: /pl/system/enumvaluesbase/toobject/
---
## EnumValuesBase::ToObject(const TypeInfo\&, uint64_t) metoda

Konwertuje określoną 64-bitową liczbę całkowitą bez znaku na element wyliczenia.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, uint64_t value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Typ wyliczenia do zwrócenia. |
| value | **uint64_t** | Wartość do konwersji na element wyliczenia. |

### Wartość zwracana

Instancja wyliczenia ustawiona na wartość.

## EnumValuesBase::ToObject(const TypeInfo\&, const SharedPtr\<Object\>\&) metoda

Konwertuje określony obiekt z wartością całkowitą na element wyliczenia.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, const SharedPtr<Object> &value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Typ wyliczenia do zwrócenia. |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Wartość konwertowana na element wyliczenia. |

### Wartość zwracana

Obiekt wyliczenia, którego wartość to wartość.

## Zobacz także

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [TypeInfo](../../typeinfo/)
* Class [EnumValuesBase](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)