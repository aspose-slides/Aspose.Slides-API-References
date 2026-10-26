---
title: operator()()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Wywołuje wszystkie delegaty aktualnie znajdujące się w kolekcji delegatów. Delegaty są wywoływane w takiej samej kolejności, w jakiej zostały dodane do kolekcji. Operator blokuje się, dopóki delegaty są wykonywane.
type: docs
weight: 235
url: /pl/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/operator_call/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes...) const metoda


Wywołuje wszystkie delegaty aktualnie znajdujące się w kolekcji delegatów. Delegaty są wywoływane w takiej samej kolejności, w jakiej zostały dodane do kolekcji. Operator blokuje się, dopóki delegaty są wykonywane.

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes... args) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| args | ArgumentTypes... | Argumenty przekazywane delegatom do wywołania |

### Wartość zwracana

Wartość zwracana ostatniego wywołanego delegata

## Zobacz także

* Klasa [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)