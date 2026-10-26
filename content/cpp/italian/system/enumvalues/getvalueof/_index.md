---
title: GetValueOf()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce il valore boxed della costante enum con il nome specificato.
type: docs
weight: 53
url: /it/system/enumvalues/getvalueof/
---
## EnumValues::GetValueOf(const String\&, bool) const metodo

Restituisce il valore boxed della costante enum con il nome specificato.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(const String &str, bool ignoreCase) const override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const [String](../../string/)\& | Il nome della costante enum |
| ignoreCase | **bool** | Specifica se il case deve essere ignorato quando si interpreta il nome della costante enum |

### Valore di ritorno

Un valore boxed della costante enum il cui nome è specificato in **str**.

## EnumValues::GetValueOf(long) const metodo

Restituisce il valore boxed della costante enum con il valore specificato.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(long val) const override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| val | long | Il valore della costante enum |

### Valore di ritorno

Un valore boxed della costante enum il cui valore è specificato in **str**.

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Object](../../object/)
* Classe [String](../../string/)
* Classe [EnumValues](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)