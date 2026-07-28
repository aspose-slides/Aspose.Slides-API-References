---
title: invoke()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Wywołuje wszystkie delegaty aktualnie znajdujące się w kolekcji delegatów. Delegaty są wywoływane w takiej samej kolejności, w jakiej zostały dodane do kolekcji. Metoda blokuje się, dopóki delegaty są wykonywane.
type: docs
weight: 222
url: /pl/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/invoke/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::invoke(ArgumentTypes...) const metoda


Wywołuje wszystkie delegaty aktualnie znajdujące się w kolekcji delegatów. Delegaty są wywoływane w tej samej kolejności, w jakiej zostały dodane do kolekcji. Metoda blokuje się, dopóki delegaty są wykonywane.

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::invoke(ArgumentTypes... args) const
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