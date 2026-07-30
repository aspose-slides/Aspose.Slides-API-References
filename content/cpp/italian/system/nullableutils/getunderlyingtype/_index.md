---
title: GetUnderlyingType()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce l'argomento di tipo sottostante del tipo nullable specificato.
type: docs
weight: 1
url: /it/system/nullableutils/getunderlyingtype/
---
## NullableUtils::GetUnderlyingType(const System::TypeInfo\&) metodo

Restituisce l'argomento di tipo sottostante del tipo nullable specificato.

```cpp
static const System::TypeInfo & System::NullableUtils::GetUnderlyingType(const System::TypeInfo &nullableType)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nullableType | const [System::TypeInfo](../../typeinfo/)\& | Un oggetto System.Type che descrive un tipo nullable generico chiuso. |

### Valore restituito

L'argomento di tipo del parametro nullableType, se il parametro nullableType è un tipo nullable generico chiuso; altrimenti, null

## Vedi anche

* Classe [TypeInfo](../../typeinfo/)
* Classe [NullableUtils](../)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)