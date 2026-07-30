---
title: Parse()
second_title: Riferimento API di Aspose.Slides per C++
description: Confeziona il valore della costante di enumerazione dell'enumerazione specificata con il nome specificato. Un parametro specifica se il caso deve essere ignorato durante l'interpretazione della stringa che specifica il nome della costante di enumerazione.
type: docs
weight: 53
url: /it/system/boxedvaluebase/parse/
---
## BoxedValueBase::Parse(const TypeInfo\&, const String\&, bool) metodo

Confeziona il valore della costante di enumerazione dell'enumerazione specificata con il nome specificato. Un parametro indica se il caso deve essere ignorato durante l'interpretazione della stringa che specifica il nome della costante di enumerazione.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Specifica il tipo dell'enumerazione |
| str | const [String](../../string/)\& | Il nome della costante di enumerazione, il cui valore deve essere confezionato |
| ignoreCase | **bool** | Specifica se il caso deve essere ignorato durante l'interpretazione della stringa che rappresenta il nome della costante di enumerazione |

### Valore restituito

Un puntatore condiviso all'oggetto che rappresenta il valore confezionato della costante di enumerazione specificata

## BoxedValueBase::Parse(const TypeInfo\&, const String\&) metodo

Confeziona il valore della costante di enumerazione dell'enumerazione specificata con il nome specificato.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Specifica il tipo dell'enumerazione |
| str | const [String](../../string/)\& | Il nome della costante di enumerazione, il cui valore deve essere confezionato |

### Valore restituito

Un puntatore condiviso all'oggetto che rappresenta il valore confezionato della costante di enumerazione specificata

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Object](../../object/)
* Classe [TypeInfo](../../typeinfo/)
* Classe [String](../../string/)
* Classe [BoxedValueBase](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)