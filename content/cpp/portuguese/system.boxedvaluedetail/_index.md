---
title: "System::BoxedValueDetail"
second_title: Referência da API C++ do Aspose.Slides
description: 
type: docs
weight: 287
url: /pt/system.boxedvaluedetail/
---
## Classes

| Classe | Descrição |
| --- | --- |
| [Comparable](./comparable/) | Implementação simples de IComparable<> |
| [NonComparable](./noncomparable/) | Tipo base fictício para tipos boxed que não implementam IComparable<> |
## Estruturas

| Estrutura | Descrição |
| --- | --- |
| [ImplementsInterface](./implementsinterface/) | Predicado de modelo que verifica se o objeto boxed deve implementar a interface fornecida por conta própria. |
| [ImplementsInterface< String, IComparable< String > >](./implementsinterface_tmpl_string__icomparable_tmpl_string__end_tmpl__end_tmpl/) | [String](../system/string/) implementa [IComparable](../system/icomparable/). |
| [ImplementsInterface< T, IComparable< T > >](./implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/) | Predicado de modelo que verifica se o objeto boxed deve implementar a interface [IComparable](../system/icomparable/) por conta própria. |
## Funções

| Função | Descrição |
| --- | --- |
| std::enable_if\<detail::has_operator_equal\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | Determina a igualdade do valor especificado usando [operator==()](../system/operator_equal_equal/). |
| std::enable_if\<detail::has_only_method_equals\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | Determina a igualdade do valor especificado usando o método [System::Object::Equals()](../system/object/equals/). |
| **bool** [Equals< float >](./equals_less_float__greater/)(**float**, **float**) | Compara dois valores de ponto flutuante de precisão simples. |
| **bool** [Equals< double >](./equals_less_double__greater/)(**double**, **double**) | Compara dois valores de ponto flutuante de precisão dupla. |