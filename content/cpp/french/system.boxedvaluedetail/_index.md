---
title: "System::BoxedValueDetail"
second_title: Référence de l'API Aspose.Slides pour C++
description: 
type: docs
weight: 287
url: /fr/system.boxedvaluedetail/
---
## Classes

| Class | Description |
| --- | --- |
| [Comparable](./comparable/) | Implémentation simple de IComparable<> |
| [NonComparable](./noncomparable/) | Type de base factice pour les types emballés qui n'implémentent pas IComparable<> |

## Structures

| Struct | Description |
| --- | --- |
| [ImplementsInterface](./implementsinterface/) | Prédicat de modèle qui vérifie si l'objet emballé doit implémenter l'interface donnée par lui-même. |
| [ImplementsInterface< String, IComparable< String > >](./implementsinterface_tmpl_string__icomparable_tmpl_string__end_tmpl__end_tmpl/) | [String](../system/string/) implémente [IComparable](../system/icomparable/). |
| [ImplementsInterface< T, IComparable< T > >](./implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/) | Prédicat de modèle qui vérifie si l'objet emballé doit implémenter l'interface [IComparable](../system/icomparable/) par lui-même. |

## Fonctions

| Function | Description |
| --- | --- |
| std::enable_if\<detail::has_operator_equal\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | Détermine l'égalité de la valeur spécifiée en utilisant [operator==()](../system/operator_equal_equal/). |
| std::enable_if\<detail::has_only_method_equals\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | Détermine l'égalité de la valeur spécifiée en utilisant la méthode [System::Object::Equals()](../system/object/equals/). |
| **bool** [Equals< float >](./equals_less_float__greater/)(**float**, **float**) | Compare deux valeurs à simple précision en virgule flottante. |
| **bool** [Equals< double >](./equals_less_double__greater/)(**double**, **double**) | Compare deux valeurs à double précision en virgule flottante. |