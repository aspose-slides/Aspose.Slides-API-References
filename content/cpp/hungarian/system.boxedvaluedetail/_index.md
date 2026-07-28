---
title: "System::BoxedValueDetail"
second_title: Aspose.Slides C++ API referencia
description: 
type: docs
weight: 287
url: /hu/system.boxedvaluedetail/
---
## Classes

| Osztály | Leírás |
| --- | --- |
| [Comparable](./comparable/) | Az IComparable<> egyszerű megvalósítása |
| [NonComparable](./noncomparable/) | Dummy alap típus a dobozolt típusokhoz, amelyek nem valósítják meg az IComparable<>-t |
## Structures

| Struktúra | Leírás |
| --- | --- |
| [ImplementsInterface](./implementsinterface/) | Sablonfeltétel, amely ellenőrzi, hogy a dobozolt objektumnak önmagától kell-e megvalósítania a megadott interfészt. |
| [ImplementsInterface< String, IComparable< String > >](./implementsinterface_tmpl_string__icomparable_tmpl_string__end_tmpl__end_tmpl/) | [String](../system/string/) implements [IComparable](../system/icomparable/). |
| [ImplementsInterface< T, IComparable< T > >](./implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/) | Sablonfeltétel, amely ellenőrzi, hogy a dobozolt objektumnak önmagától kell-e megvalósítania a [IComparable](../system/icomparable/) interfészt. |
## Functions

| Függvény | Leírás |
| --- | --- |
| std::enable_if\<detail::has_operator_equal\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | Meghatározza a megadott érték egyenlőségét a [operator==()](../system/operator_equal_equal/) használatával. |
| std::enable_if\<detail::has_only_method_equals\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | Meghatározza a megadott érték egyenlőségét a [System::Object::Equals()](../system/object/equals/) metódus használatával. |
| **bool** [Equals< float >](./equals_less_float__greater/)(**float**, **float**) | Összehasonlít két egyszeres pontosságú lebegőpontos értéket. |
| **bool** [Equals< double >](./equals_less_double__greater/)(**double**, **double**) | Összehasonlít két dupla pontosságú lebegőpontos értéket. |