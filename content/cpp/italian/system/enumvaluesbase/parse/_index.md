---
title: Parse()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce un oggetto che rappresenta il valore di una costante di enumerazione del tipo di enumerazione specificato con il nome specificato.
type: docs
weight: 27
url: /it/system/enumvaluesbase/parse/
---
## EnumValuesBase::Parse(const TypeInfo\&, const String\&, bool) metodo

Restituisce un oggetto che rappresenta il valore di una costante di enumerazione del tipo di enumerazione specificato con il nome specificato.

```cpp
static SharedPtr<Object> System::EnumValuesBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | L'oggetto [TypeInfo](../../typeinfo/) che rappresenta il tipo del valore di enumerazione da restituire |
| str | const [String](../../string/)\& | Il nome della costante enum |
| ignoreCase | **bool** | Specifica se il case deve essere ignorato quando si interpreta il nome della costante enum |

### Valore restituito

Un oggetto che rappresenta il valore della costante enum il cui nome è specificato in **str**.

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Object](../../object/)
* Classe [TypeInfo](../../typeinfo/)
* Classe [String](../../string/)
* Classe [EnumValuesBase](../)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)