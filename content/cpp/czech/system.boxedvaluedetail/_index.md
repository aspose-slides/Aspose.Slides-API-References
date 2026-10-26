---
title: "System::BoxedValueDetail"
second_title: Aspose.Slides pro C++ API Reference
description: 
type: docs
weight: 287
url: /cs/system.boxedvaluedetail/
---
## Třídy

| Třída | Popis |
| --- | --- |
| [Comparable](./comparable/) | Jednoduchá implementace IComparable<> |
| [NonComparable](./noncomparable/) | Falešný základní typ pro zabalené typy, které neimplementují IComparable<> |
## Struktury

| Struktura | Popis |
| --- | --- |
| [ImplementsInterface](./implementsinterface/) | Predikát šablony, který kontroluje, zda by zabalený objekt měl sám implementovat dané rozhraní. |
| [ImplementsInterface< String, IComparable< String > >](./implementsinterface_tmpl_string__icomparable_tmpl_string__end_tmpl__end_tmpl/) | [String](../system/string/) implementuje [IComparable](../system/icomparable/). |
| [ImplementsInterface< T, IComparable< T > >](./implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/) | Predikát šablony, který kontroluje, zda by zabalený objekt měl sám implementovat rozhraní [IComparable](../system/icomparable/). |
## Funkce

| Funkce | Popis |
| --- | --- |
| std::enable_if\<detail::has_operator_equal\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | Určuje rovnost zadané hodnoty pomocí [operator==()](../system/operator_equal_equal/). |
| std::enable_if\<detail::has_only_method_equals\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | Určuje rovnost zadané hodnoty pomocí metody [System::Object::Equals()](../system/object/equals/). |
| **bool** [Equals< float >](./equals_less_float__greater/)(**float**, **float**) | Porovnává dvě hodnoty s jednoduchou přesností plovoucí desetinné čárky. |
| **bool** [Equals< double >](./equals_less_double__greater/)(**double**, **double**) | Porovnává dvě hodnoty s dvojitou přesností plovoucí desetinné čárky. |