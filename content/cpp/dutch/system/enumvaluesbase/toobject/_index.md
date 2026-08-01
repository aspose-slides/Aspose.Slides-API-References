---
title: ToObject()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de opgegeven 64-bit unsigned integer-waarde naar een enumeratielid.
type: docs
weight: 40
url: /nl/system/enumvaluesbase/toobject/
---
## EnumValuesBase::ToObject(const TypeInfo\&, uint64_t) method


Converteert de opgegeven 64-bit unsigned integer-waarde naar een enumeratie-lid.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, uint64_t value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Het te retourneren enumeratietype. |
| value | **uint64_t** | De waarde om te converteren naar een enumeratie-lid. |

### Retourwaarde

Een instantie van de enumeratie ingesteld op de waarde.

## EnumValuesBase::ToObject(const TypeInfo\&, const SharedPtr\<Object\>\&) method


Converteert het opgegeven object met een integer-waarde naar een enumeratie-lid.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, const SharedPtr<Object> &value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Het te retourneren enumeratietype. |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | De waarde om te converteren naar een enumeratie-lid. |

### Retourwaarde

Een enumeratie-object waarvan de waarde gelijk is aan de opgegeven waarde.

## Zie ook

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [TypeInfo](../../typeinfo/)
* Class [EnumValuesBase](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)