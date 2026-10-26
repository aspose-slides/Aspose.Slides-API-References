---
title: "System::BoxedValueDetail"
second_title: Aspose.Slides dla C++ - odniesienie API
description: 
type: docs
weight: 287
url: /pl/system.boxedvaluedetail/
---
## Klasy

| Klasa | Opis |
| --- | --- |
| [Comparable](./comparable/) | Prosta implementacja IComparable<> |
| [NonComparable](./noncomparable/) | Podstawowy typ zastępczy dla obiektów opakowanych, które nie implementują IComparable<> |
## Struktury

| Struktura | Opis |
| --- | --- |
| [ImplementsInterface](./implementsinterface/) | Predykat szablonu, który sprawdza, czy opakowany obiekt powinien samodzielnie implementować podany interfejs. |
| [ImplementsInterface< String, IComparable< String > >](./implementsinterface_tmpl_string__icomparable_tmpl_string__end_tmpl__end_tmpl/) | [String](../system/string/) implementuje [IComparable](../system/icomparable/). |
| [ImplementsInterface< T, IComparable< T > >](./implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/) | Predykat szablonu, który sprawdza, czy opakowany obiekt powinien samodzielnie implementować interfejs [IComparable](../system/icomparable/). |
## Funkcje

| Funkcja | Opis |
| --- | --- |
| std::enable_if\<detail::has_operator_equal\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | Określa równość podanej wartości przy użyciu [operator==()](../system/operator_equal_equal/). |
| std::enable_if\<detail::has_only_method_equals\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | Określa równość podanej wartości przy użyciu metody [System::Object::Equals()](../system/object/equals/). |
| **bool** [Equals< float >](./equals_less_float__greater/)(**float**, **float**) | Porównuje dwie wartości zmiennoprzecinkowe o pojedynczej precyzji. |
| **bool** [Equals< double >](./equals_less_double__greater/)(**double**, **double**) | Porównuje dwie wartości zmiennoprzecinkowe o podwójnej precyzji. |