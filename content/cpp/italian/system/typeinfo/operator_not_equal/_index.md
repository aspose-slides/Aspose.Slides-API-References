---
title: operator!=()
second_title: Riferimento API di Aspose.Slides per C++
description: Determina se l'oggetto corrente e gli oggetti TypeInfo specificati non sono uguali.
type: docs
weight: 456
url: /it/system/typeinfo/operator_not_equal/
---
## TypeInfo::operator!=(const TypeInfo\&) const metodo

Determina se l'oggetto corrente e gli oggetti [TypeInfo](../) specificati non sono uguali.

```cpp
bool System::TypeInfo::operator!=(const TypeInfo &info) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | L'oggetto [TypeInfo](../) da confrontare |

### Valore restituito

True se gli hash degli oggetti non sono uguali, altrimenti false

## TypeInfo::operator!=(std::nullptr_t) const metodo

Determina se l'oggetto [TypeInfo](../) corrente non è un oggetto nullo, cioè rappresenta un tipo.

```cpp
bool System::TypeInfo::operator!=(std::nullptr_t) const
```

### Valore restituito

True se l'oggetto [TypeInfo](../) corrente non è un oggetto nullo, altrimenti false

## Vedi anche

* Classe [TypeInfo](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)