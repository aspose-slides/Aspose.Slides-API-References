---
title: GetCustomAttributes()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce un array contenente oggetti che rappresentano tutti gli attributi personalizzati applicati al tipo.
type: docs
weight: 586
url: /it/system/typeinfo/getcustomattributes/
---
## TypeInfo::GetCustomAttributes() const metodo

Restituisce un array contenente oggetti che rappresentano tutti gli attributi personalizzati applicati al tipo.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes() const
```

## TypeInfo::GetCustomAttributes(const TypeInfo\&, bool) const metodo

Restituisce un array contenente oggetti che rappresentano attributi specifici applicati al tipo.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | Tipo dell'attributo da cercare. |
| inherit | **bool** | Indica se cercare anche gli attributi ereditati. |

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [SmartPtr](../../smartptr/)
* Classe [TypeInfo](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)