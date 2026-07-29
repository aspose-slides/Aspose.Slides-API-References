---
title: "System::BoxedValueDetail"
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 287
url: /sv/system.boxedvaluedetail/
---
## Klasser

| Klass | Beskrivning |
| --- | --- |
| [Comparable](./comparable/) | Enkel implementation av IComparable<> |
| [NonComparable](./noncomparable/) | Dummy-bastyp för inlåsta typer som inte implementerar IComparable<> |
## Strukturer

| Struktur | Beskrivning |
| --- | --- |
| [ImplementsInterface](./implementsinterface/) | Mallpredikat som kontrollerar om ett inlåst objekt ska implementera det givna gränssnittet själv. |
| [ImplementsInterface< String, IComparable< String > >](./implementsinterface_tmpl_string__icomparable_tmpl_string__end_tmpl__end_tmpl/) | [String](../system/string/) implementerar [IComparable](../system/icomparable/). |
| [ImplementsInterface< T, IComparable< T > >](./implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/) | Mallpredikat som kontrollerar om ett inlåst objekt ska implementera [IComparable](../system/icomparable/)-gränssnittet själv. |
## Funktioner

| Funktion | Beskrivning |
| --- | --- |
| std::enable_if\<detail::has_operator_equal\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | Bestämmer likheten för det angivna värdet med hjälp av [operator==()](../system/operator_equal_equal/). |
| std::enable_if\<detail::has_only_method_equals\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | Bestämmer likheten för det angivna värdet med hjälp av metoden [System::Object::Equals()](../system/object/equals/). |
| **bool** [Equals< float >](./equals_less_float__greater/)(**float**, **float**) | Jämför två enkelprecisionsflyttal. |
| **bool** [Equals< double >](./equals_less_double__greater/)(**double**, **double**) | Jämför två dubbelprecisionsflyttal. |