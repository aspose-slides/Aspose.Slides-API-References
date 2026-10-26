---
title: IsDefined()
second_title: Riferimento API di Aspose.Slides per C++
description: NON IMPLEMENTATO. Indica se uno o più attributi del tipo specificato o dei suoi tipi derivati è applicato a questo membro.
type: docs
weight: 157
url: /it/system/typeinfo/isdefined/
---
## TypeInfo::IsDefined(const TypeInfo\&, bool) const metodo

NON IMPLEMENTATO. Indica se uno o più attributi del tipo specificato o dei suoi tipi derivati è applicato a questo membro.

```cpp
bool System::TypeInfo::IsDefined(const TypeInfo &attributeType, bool inherit) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | Il tipo di attributo personalizzato da cercare. La ricerca include tipi derivati. |
| inherit | **bool** | true per cercare nella catena di ereditarietà di questo membro gli attributi; altrimenti, false. Questo parametro è ignorato per le proprietà e gli eventi. |

### Valore di ritorno

true se una o più istanze di attributeType o di uno qualsiasi dei suoi tipi derivati è applicato a questo membro; altrimenti, false.

## Vedi anche

* Classe [TypeInfo](../)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)