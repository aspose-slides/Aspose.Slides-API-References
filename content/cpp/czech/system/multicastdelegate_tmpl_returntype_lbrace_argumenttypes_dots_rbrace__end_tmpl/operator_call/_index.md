---
title: operator()()
second_title: Aspose.Slides pro C++ API Reference
description: Vyvolá všechny delegáty aktuálně přítomné v kolekci delegátů. Delegáty jsou vyvolány ve stejném pořadí, v jakém byly přidány do kolekce. Operátor blokuje, dokud jsou delegáti prováděni.
type: docs
weight: 235
url: /cs/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/operator_call/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes...) const metoda


Vyvolá všechny delegáty aktuálně přítomné v kolekci delegátů. Delegáty jsou vyvolány ve stejném pořadí, v jakém byly přidány do kolekce. Operátor blokuje, dokud jsou delegáti prováděni.

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes... args) const
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| args | ArgumentTypes... | Argumenty, které se předají delegátům k vyvolání |

### Návratová hodnota

Návratová hodnota posledního vyvolaného delegáta

## Viz také

* Třída [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)