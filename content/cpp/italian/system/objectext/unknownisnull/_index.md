---
title: UnknownIsNull()
second_title: Riferimento API di Aspose.Slides per C++
description: Verifica se l'oggetto di tipo sconosciuto è nullptr. Sovraccarico per tipi non scalari.
type: docs
weight: 144
url: /it/system/objectext/unknownisnull/
---
## ObjectExt::UnknownIsNull(T) metodo

Verifica se l'oggetto di tipo sconosciuto è nullptr. Sovraccarico per tipi non scalari.

```cpp
template<typename T> static std::enable_if<!std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | [Object](../../object/) type. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | T | [Object](../../object/) to check. |

### Valore restituito

True se 'obj == nullptr' è true, false altrimenti.

## ObjectExt::UnknownIsNull(T) metodo

Verifica se l'oggetto di tipo sconosciuto è nullptr. Sovraccarico per tipi scalari.

```cpp
template<typename T> static std::enable_if<std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | [Object](../../object/) type. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | T | [Object](../../object/) to check. |

### Valore restituito

Always returns false.

## Vedi anche

* Classe [ObjectExt](../)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)