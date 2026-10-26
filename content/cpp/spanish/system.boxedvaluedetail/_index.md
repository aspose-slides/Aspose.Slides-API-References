---
title: "System::BoxedValueDetail"
second_title: Referencia de la API de Aspose.Slides para C++
description: 
type: docs
weight: 287
url: /es/system.boxedvaluedetail/
---
## Clases

| Clase | Descripción |
| --- | --- |
| [Comparable](./comparable/) | Implementación simple de IComparable<> |
| [NonComparable](./noncomparable/) | Tipo base ficticio para tipos empaquetados que no implementan IComparable<> |
## Estructuras

| Estructura | Descripción |
| --- | --- |
| [ImplementsInterface](./implementsinterface/) | Predicado de plantilla que verifica si el objeto empaquetado debe implementar la interfaz proporcionada por sí mismo. |
| [ImplementsInterface< String, IComparable< String > >](./implementsinterface_tmpl_string__icomparable_tmpl_string__end_tmpl__end_tmpl/) | [String](../system/string/) implementa [IComparable](../system/icomparable/). |
| [ImplementsInterface< T, IComparable< T > >](./implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/) | Predicado de plantilla que verifica si el objeto empaquetado debe implementar la interfaz [IComparable](../system/icomparable/) por sí mismo. |
## Funciones

| Función | Descripción |
| --- | --- |
| std::enable_if\<detail::has_operator_equal\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | Determina la igualdad del valor especificado usando [operator==()](../system/operator_equal_equal/). |
| std::enable_if\<detail::has_only_method_equals\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | Determina la igualdad del valor especificado usando el método [System::Object::Equals()](../system/object/equals/). |
| **bool** [Equals< float >](./equals_less_float__greater/)(**float**, **float**) | Compara dos valores de punto flotante de precisión simple. |
| **bool** [Equals< double >](./equals_less_double__greater/)(**double**, **double**) | Compara dos valores de punto flotante de doble precisión. |