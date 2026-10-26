---
title: GetDescription()
second_title: Aspose.Slides per C++ API Reference
description: Restituisce il nome della costante di enumerazione che ha il valore specificato.
type: docs
weight: 53
url: /it/system/enum/getdescription/
---
## Enum::GetDescription(T) metodo

Restituisce il nome della costante enum che ha il valore specificato.

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetDescription(T value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | T | Il valore della costante enum il cui nome deve essere restituito |

## Valore restituito

Il nome della costante enum specificata

## Vedi anche

* Typedef [UnderlyingType](../underlyingtype/)
* Classe [String](../../string/)
* Struct [Enum](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)