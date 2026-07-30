---
title: ToObject()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte il valore intero senza segno a 64 bit specificato in un membro di enumerazione.
type: docs
weight: 40
url: /it/system/enumvaluesbase/toobject/
---
## EnumValuesBase::ToObject(const TypeInfo\&, uint64_t) metodo


Converte il valore intero senza segno a 64 bit specificato in un membro di enumerazione.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, uint64_t value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Il tipo di enumerazione da restituire. |
| value | **uint64_t** | Il valore da convertire in un membro di enumerazione. |

### Valore di ritorno

Un'istanza dell'enumerazione impostata al valore.

## EnumValuesBase::ToObject(const TypeInfo\&, const SharedPtr\<Object\>\&) metodo


Converte l'oggetto specificato con un valore intero in un membro di enumerazione.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, const SharedPtr<Object> &value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Il tipo di enumerazione da restituire. |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Il valore da convertire in un membro di enumerazione. |

### Valore di ritorno

Un oggetto di enumerazione il cui valore è value.

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Object](../../object/)
* Classe [TypeInfo](../../typeinfo/)
* Classe [EnumValuesBase](../)
* Spazio dei nomi [System](../../)
* Library [Aspose.Slides](../../../)