---
title: invoke()
second_title: Aspose.Slides pro C++ API referenci
description: Vyvolá všechny delegáty, kteří jsou aktuálně přítomni ve sbírce delegátů. Delegáti jsou vyvoláni ve stejném pořadí, v jakém byli přidáni do sbírky. Metoda blokuje, dokud jsou delegáti vykonáváni.
type: docs
weight: 222
url: /cs/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/invoke/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::invoke(ArgumentTypes...) const metoda

Vyvolá všechny delegáty, které jsou aktuálně přítomny ve sbírce delegátů. Delegáty jsou vyvolány ve stejném pořadí, v jakém byly přidány do sbírky. Metoda blokuje, dokud jsou delegáti vykonáváni.

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::invoke(ArgumentTypes... args) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| args | ArgumentTypes... | Argumenty, které se předají delegátům k vyvolání |

### Návratová hodnota

Návratová hodnota posledního vyvolaného delegáta

## Viz také

* Třída [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)