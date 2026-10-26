---
title: Is()
second_title: Aspose.Slides för C++ API-referens
description: Implementerar översättning av 'is' deklarationsmönster.
type: docs
weight: 2302
url: /sv/system/is/
---
## System::Is(const ExpressionT\&, ResultT\&) funktion

Implementerar 'is' deklarationsmönsteröversättning.

```cpp
template<class PatternT,class ExpressionT,class ResultT> bool System::Is(const ExpressionT &left, ResultT &result)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| PatternT | type to check. |
| ExpressionT | left expression type. |
| ResultT | type of result expression. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | const ExpressionT\& | expression which will be checked. |
| result | ResultT\& | variable which will be assigned to checked type. |

### Returvärde

true if type check is successful, false otherwise.

## System::Is(const ExpressionT\&, const ConstantT\&) funktion

Implementerar 'is' constant pattern translation.

```cpp
template<class ExpressionT,class ConstantT> std::enable_if_t<!std::is_base_of<Details::Pattern, ConstantT>::value, bool> System::Is(const ExpressionT &left, const ConstantT &constant)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| ExpressionT | left expression type. |
| ConstantT | type of constant expression. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | const ExpressionT\& | expression which will be checked. |
| constant | const ConstantT\& | expression which will be compared with left one. |

### Returvärde

true if type check is successful, false otherwise.

## System::Is(const E\&, const A\&) funktion

Top-nivå matchningsfunktion. Applicerar ett mönster på ett värde.

```cpp
template<typename A,typename E> std::enable_if_t<std::is_base_of<Details::Pattern, A>::value, bool> System::Is(const E &e, const A &a)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| A | Pattern type (must inherit from Details::Pattern). |
| E | Type of the value to match. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| e | const E\& | Value to match against. |
| a | const A\& | Pattern to apply. |

### Returvärde

true if the pattern matches the value.

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)