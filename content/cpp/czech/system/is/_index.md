---
title: Is()
second_title: Aspose.Slides pro C++ referenční příručka
description: Implementuje překlad vzoru deklarace 'is'.
type: docs
weight: 2302
url: /cs/system/is/
---
## System::Is(const ExpressionT\&, ResultT\&) funkce


Implementuje překlad vzoru deklarace 'is'.

```cpp
template<class PatternT,class ExpressionT,class ResultT> bool System::Is(const ExpressionT &left, ResultT &result)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| PatternT | typ k ověření. |
| ExpressionT | typ levého výrazu. |
| ResultT | typ výsledného výrazu. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| left | const ExpressionT\& | výraz, který bude ověřen. |
| result | ResultT\& | proměnná, do které bude přiřazen ověřený typ. |

### Návratová hodnota

true pokud je kontrola typu úspěšná, false jinak.

## System::Is(const ExpressionT\&, const ConstantT\&) funkce


Implementuje překlad konstantního vzoru 'is'.

```cpp
template<class ExpressionT,class ConstantT> std::enable_if_t<!std::is_base_of<Details::Pattern, ConstantT>::value, bool> System::Is(const ExpressionT &left, const ConstantT &constant)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| ExpressionT | typ levého výrazu. |
| ConstantT | typ konstantního výrazu. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| left | const ExpressionT\& | výraz, který bude ověřen. |
| constant | const ConstantT\& | výraz, který bude porovnán s levým. |

### Návratová hodnota

true pokud je kontrola typu úspěšná, false jinak.

## System::Is(const E\&, const A\&) funkce


Funkce porovnání na nejvyšší úrovni. Použije vzor na hodnotu.

```cpp
template<typename A,typename E> std::enable_if_t<std::is_base_of<Details::Pattern, A>::value, bool> System::Is(const E &e, const A &a)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| A | typ vzoru (musí dědit z Details::Pattern). |
| E | typ hodnoty k porovnání. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| e | const E\& | hodnota, proti které se porovnává. |
| a | const A\& | vzor, který se použije. |

### Návratová hodnota

true pokud vzor odpovídá hodnotě, false jinak.

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)