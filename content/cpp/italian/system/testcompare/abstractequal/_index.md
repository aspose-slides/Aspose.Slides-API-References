---
title: AbstractEqual()
second_title: Aspose.Slides per C++ Riferimento API
description: Confronta due collezioni di tipo sconosciuto.
type: docs
weight: 14
url: /it/system/testcompare/abstractequal/
---
## TestCompare::AbstractEqual(SCG::ICollection\<T\> *const, SCG::ICollection\<T\> *const) metodo

Confronta due collezioni di tipo sconosciuto.

```cpp
template<typename T> static bool System::TestCompare::AbstractEqual(SCG::ICollection<T> *const collA, SCG::ICollection<T> *const collB)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di elemento della collezione. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| collA | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | Collezione LHS. |
| collB | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | Collezione RHS. |

### Valore di ritorno

true se le collezioni corrispondono (e. g. entrambe sono null), oppure se le dimensioni corrispondono e gli elementi corrispondono, false altrimenti.

## Vedi anche

* Classe [ICollection](../../../system.collections.generic/icollection/)
* Struttura [TestCompare](../)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)