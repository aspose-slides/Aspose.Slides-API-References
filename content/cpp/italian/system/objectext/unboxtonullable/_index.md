---
title: UnboxToNullable()
second_title: Aspose.Slides per C++ - Riferimento API
description: Esegue il deboxing dell'oggetto in un tipo nullable.
type: docs
weight: 79
url: /it/system/objectext/unboxtonullable/
---
## ObjectExt::UnboxToNullable(const SmartPtr\<Object\>\&, bool) metodo

Esegue il deboxing dell'oggetto in un tipo nullable.

```cpp
template<class T> static Nullable<T> System::ObjectExt::UnboxToNullable(const SmartPtr<Object> &obj, bool safe=1)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo di destinazione. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) per il deboxing. |
| safe | **bool** | Se vero, restituisce nullptr in caso di errore, altrimenti lancia InvalidCastException. |

### Valore di ritorno

Valore nullable deboxato (potrebbe essere null).

## Vedi anche

* Classe [Nullable](../../nullable/)
* Classe [SmartPtr](../../smartptr/)
* Classe [Object](../../object/)
* Classe [ObjectExt](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)