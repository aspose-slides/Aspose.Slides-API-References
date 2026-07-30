---
title: GetName()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce il nome della costante di enumerazione che ha il valore specificato.
type: docs
weight: 40
url: /it/system/enum/getname/
---
## Enum::GetName(T) metodo


Restituisce il nome della costante di enumerazione che ha il valore specificato.

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetName(T value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | T | Il valore della costante enum il cui nome deve essere restituito |

### Valore restituito

Il nome della costante enum specificata

## Vedi anche

* Typedef [UnderlyingType](../underlyingtype/)
* Classe [String](../../string/)
* Struttura [Enum](../)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)