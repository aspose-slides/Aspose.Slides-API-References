---
title: Is()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Implementuje tłumaczenie wzorca deklaracji 'is'.
type: docs
weight: 2302
url: /pl/system/is/
---
## System::Is(const ExpressionT\&, ResultT\&) funkcja


Implementuje tłumaczenie wzorca deklaracji 'is'.

```cpp
template<class PatternT,class ExpressionT,class ResultT> bool System::Is(const ExpressionT &left, ResultT &result)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| PatternT | typ do sprawdzenia. |
| ExpressionT | typ wyrażenia po lewej. |
| ResultT | typ wyrażenia wyniku. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| left | const ExpressionT\& | wyrażenie, które zostanie sprawdzone. |
| result | ResultT\& | zmienna, do której zostanie przypisany sprawdzony typ. |

### Wartość zwracana

true, jeśli sprawdzenie typu zakończy się powodzeniem, false w przeciwnym razie.

## System::Is(const ExpressionT\&, const ConstantT\&) funkcja


Implementuje tłumaczenie wzorca stałej 'is'.

```cpp
template<class ExpressionT,class ConstantT> std::enable_if_t<!std::is_base_of<Details::Pattern, ConstantT>::value, bool> System::Is(const ExpressionT &left, const ConstantT &constant)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| ExpressionT | typ wyrażenia po lewej. |
| ConstantT | typ wyrażenia stałej. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| left | const ExpressionT\& | wyrażenie, które zostanie sprawdzone. |
| constant | const ConstantT\& | wyrażenie, które zostanie porównane z wyrażeniem po lewej. |

### Wartość zwracana

true, jeśli sprawdzenie typu zakończy się powodzeniem, false w przeciwnym razie.

## System::Is(const E\&, const A\&) funkcja


Funkcja dopasowująca na najwyższym poziomie. Stosuje wzorzec do wartości.

```cpp
template<typename A,typename E> std::enable_if_t<std::is_base_of<Details::Pattern, A>::value, bool> System::Is(const E &e, const A &a)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| A | typ wzorca (musi dziedziczyć po Details::Pattern). |
| E | typ wartości do dopasowania. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| e | const E\& | Wartość, do której będzie dopasowywana. |
| a | const A\& | Wzorzec do zastosowania. |

### Wartość zwracana

true, jeśli wzorzec pasuje do wartości.

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)