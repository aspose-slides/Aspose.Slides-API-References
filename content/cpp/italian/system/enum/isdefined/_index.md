---
title: IsDefined()
second_title: Riferimento API Aspose.Slides per C++
description: Determina se il valore specificato è un membro del tipo di enumerazione E.
type: docs
weight: 27
url: /it/system/enum/isdefined/
---
## Enum::IsDefined(E) metodo

Determina se il valore specificato è un membro del tipo di enumerazione **E**.

```cpp
static bool System::Enum<E, Guard>::IsDefined(E value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | E | Il valore da verificare |

### Valore restituito

True se **value** è un membro dell'enumerazione **E**, altrimenti - false

## Enum::IsDefined(T) metodo

Determina se il valore specificato è un membro del tipo di enumerazione **T**.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, UnderlyingType>::value, bool>::type System::Enum<E, Guard>::IsDefined(T value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | T | Il valore da verificare |

### Valore restituito

True se **value** è un membro dell'enumerazione **T**, altrimenti - false

## Enum::IsDefined(const String\&) metodo

Determina se il valore con il nome specificato è tra i membri dell'enum **E**.

```cpp
static bool System::Enum<E, Guard>::IsDefined(const String &name)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | const [String](../../string/)\& | Il nome da verificare |

### Valore restituito

True se esiste un membro dell'enum **E** con il nome specificato.

## Vedi anche

* Typedef [UnderlyingType](../underlyingtype/)
* Classe [String](../../string/)
* Struttura [Enum](../)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)