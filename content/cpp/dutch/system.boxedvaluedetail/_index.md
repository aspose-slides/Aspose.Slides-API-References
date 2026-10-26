---
title: "System::BoxedValueDetail"
second_title: Aspose.Slides voor C++ API-referentie
description: 
type: docs
weight: 287
url: /nl/system.boxedvaluedetail/
---
## Klassen

| Klasse | Beschrijving |
| --- | --- |
| [Comparable](./comparable/) | Eenvoudige implementatie van IComparable<> |
| [NonComparable](./noncomparable/) | Dummy-basistype voor verpakte types die IComparable<> niet implementeren |

## Structuren

| Struct | Beschrijving |
| --- | --- |
| [ImplementsInterface](./implementsinterface/) | Sjabloon-predicaat dat controleert of een verpakt object zelf de opgegeven interface moet implementeren. |
| [ImplementsInterface< String, IComparable< String > >](./implementsinterface_tmpl_string__icomparable_tmpl_string__end_tmpl__end_tmpl/) | [String](../system/string/) implementeert [IComparable](../system/icomparable/). |
| [ImplementsInterface< T, IComparable< T > >](./implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/) | Sjabloon-predicaat dat controleert of een verpakt object zelf de [IComparable](../system/icomparable/) interface moet implementeren. |

## Functies

| Functie | Beschrijving |
| --- | --- |
| std::enable_if\<detail::has_operator_equal\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | Bepaalt de gelijkheid van de opgegeven waarde met behulp van [operator==()](../system/operator_equal_equal/). |
| std::enable_if\<detail::has_only_method_equals\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | Bepaalt de gelijkheid van de opgegeven waarde met behulp van methode [System::Object::Equals()](../system/object/equals/). |
| **bool** [Equals< float >](./equals_less_float__greater/)(**float**, **float**) | Vergelijkt twee enkelprecisie floating-point waarden. |
| **bool** [Equals< double >](./equals_less_double__greater/)(**double**, **double**) | Vergelijkt twee dubbelprecisie floating-point waarden. |