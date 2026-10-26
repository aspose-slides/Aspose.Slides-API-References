---
title: "System::BoxedValueDetail"
second_title: Aspose.Slides per il riferimento API C++
description: 
type: docs
weight: 287
url: /it/system.boxedvaluedetail/
---
## Classi

| Classe | Descrizione |
| --- | --- |
| [Comparable](./comparable/) | Implementazione semplice di IComparable<> |
| [NonComparable](./noncomparable/) | Tipo base fittizio per tipi boxed che non implementano IComparable<> |
## Strutture

| Struttura | Descrizione |
| --- | --- |
| [ImplementsInterface](./implementsinterface/) | Predicato template che verifica se l'oggetto boxed deve implementare l'interfaccia data da solo. |
| [ImplementsInterface< String, IComparable< String > >](./implementsinterface_tmpl_string__icomparable_tmpl_string__end_tmpl__end_tmpl/) | [String](../system/string/) implements [IComparable](../system/icomparable/). |
| [ImplementsInterface< T, IComparable< T > >](./implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/) | Predicato template che verifica se l'oggetto boxed deve implementare l'interfaccia [IComparable](../system/icomparable/) da solo. |
## Funzioni

| Funzione | Descrizione |
| --- | --- |
| std::enable_if\<detail::has_operator_equal\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | Determina l'uguaglianza del valore specificato usando [operator==()](../system/operator_equal_equal/). |
| std::enable_if\<detail::has_only_method_equals\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | Determina l'uguaglianza del valore specificato usando il metodo [System::Object::Equals()](../system/object/equals/). |
| **bool** [Equals< float >](./equals_less_float__greater/)(**float**, **float**) | Confronta due valori a virgola mobile a precisione singola. |
| **bool** [Equals< double >](./equals_less_double__greater/)(**double**, **double**) | Confronta due valori a doppia precisione. |