---
title: GetCustomAttributes()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce un array contenente oggetti che rappresentano tutti gli attributi personalizzati applicati al tipo rappresentato dall'oggetto corrente.
type: docs
weight: 66
url: /it/system.reflection/memberinfo/getcustomattributes/
---
## MemberInfo::GetCustomAttributes(const TypeInfo\&, bool) const metodo

Restituisce un array contenente oggetti che rappresentano tutti gli attributi personalizzati applicati al tipo rappresentato dall'oggetto corrente.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit=false) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| attributeType | const [TypeInfo](../../../system/typeinfo/)\& | Tipo di attributo da cercare. |
| inherit | **bool** | Indica se controllare anche gli attributi ereditati. |

## MemberInfo::GetCustomAttributes(bool) const metodo

Restituisce un array contenente oggetti che rappresentano tutti gli attributi personalizzati applicati al tipo rappresentato dall'oggetto corrente.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(bool inherit=false) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inherit | **bool** | Indica se controllare anche gli attributi ereditati. |

## Vedere anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [MemberInfo](../)
* Spazio dei nomi [System::Reflection](../../)
* Libreria [Aspose.Slides](../../../)