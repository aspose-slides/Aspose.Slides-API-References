---
title: ToObject()
second_title: Aspose.Slides pro C++ API Reference
description: Převádí zadanou 64-bitovou nezápornou celočíselnou hodnotu na člena výčtu.
type: docs
weight: 40
url: /cs/system/enumvaluesbase/toobject/
---
## EnumValuesBase::ToObject(const TypeInfo\&, uint64_t) metoda

Převádí zadanou 64-bitovou nezápornou celočíselnou hodnotu na člena výčtu.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, uint64_t value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Typ výčtu, který má být vrácen. |
| value | **uint64_t** | Hodnota, která má být převedena na člena výčtu. |

### Návratová hodnota

Instance výčtu nastavená na hodnotu.

## EnumValuesBase::ToObject(const TypeInfo\&, const SharedPtr\<Object\>\&) metoda

Převádí zadaný objekt s celočíselnou hodnotou na člena výčtu.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, const SharedPtr<Object> &value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Typ výčtu, který má být vrácen. |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Hodnota převáděná na člena výčtu. |

### Návratová hodnota

Objekt výčtu, jehož hodnota je value.

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [TypeInfo](../../typeinfo/)
* Class [EnumValuesBase](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)