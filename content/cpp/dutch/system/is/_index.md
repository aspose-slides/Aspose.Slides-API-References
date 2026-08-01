---
title: Is()
second_title: Aspose.Slides voor C++ API-referentie
description: Implementeert de vertaling van het 'is' declaratiepatroon.
type: docs
weight: 2302
url: /nl/system/is/
---
## System::Is(const ExpressionT\&, ResultT\&) functie

Implementeert de vertaling van het 'is' declaratiepatroon.

```cpp
template<class PatternT,class ExpressionT,class ResultT> bool System::Is(const ExpressionT &left, ResultT &result)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| PatternT | type om te controleren. |
| ExpressionT | type van de linkerexpressie. |
| ResultT | type van de resultaatexpressie. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | const ExpressionT\& | expressie die gecontroleerd zal worden. |
| result | ResultT\& | variabele waaraan het gecontroleerde type zal worden toegewezen. |

### Retourwaarde

true als typecontrole succesvol is, false anders.

## System::Is(const ExpressionT\&, const ConstantT\&) functie

Implementeert de vertaling van het 'is' constante patroon.

```cpp
template<class ExpressionT,class ConstantT> std::enable_if_t<!std::is_base_of<Details::Pattern, ConstantT>::value, bool> System::Is(const ExpressionT &left, const ConstantT &constant)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| ExpressionT | type van de linkerexpressie. |
| ConstantT | type van de constante-expressie. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | const ExpressionT\& | expressie die gecontroleerd zal worden. |
| constant | const ConstantT\& | expressie die wordt vergeleken met de linker. |

### Retourwaarde

true als typecontrole succesvol is, false anders.

## System::Is(const E\&, const A\&) functie

Top-level overeenstemmingsfunctie. Past een patroon toe op een waarde.

```cpp
template<typename A,typename E> std::enable_if_t<std::is_base_of<Details::Pattern, A>::value, bool> System::Is(const E &e, const A &a)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| A | Patroon type (moet overerven van Details::Pattern). |
| E | Type van de waarde om te matchen. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| e | const E\& | Waarde om tegen te matchen. |
| a | const A\& | Patroon om toe te passen. |

### Retourwaarde

true als het patroon overeenkomt met de waarde.

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)