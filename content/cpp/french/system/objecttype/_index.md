---
title: ObjectType
second_title: Aspose.Slides for C++ Référence API
description: Fournit des méthodes statiques qui implémentent les accesseurs de type d'objet. Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de celui-ci par quelque moyen que ce soit.
type: docs
weight: 1145
url: /fr/system/objecttype/
---
## ObjectType classe

Fournit des méthodes statiques qui implémentent les accesseurs de type d'objet. Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de celui-ci par quelque moyen que ce soit.

```cpp
class ObjectType
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Implémente la traduction de typeof(). Surcharge pour les pointeurs intelligents. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Implémente la traduction de typeof(). Surcharge pour les structures. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Implémente la traduction de typeof(). Surcharge pour les exceptions. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | Implémente la traduction de typeof(). Surcharge pour les types primitifs. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | Implémente la traduction de typeof(). Surcharge pour les types [Nullable](../nullable/). |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implémente la traduction de typeof(). Surcharge pour les types primitifs. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implémente la traduction de typeof(). Surcharge pour les types enum. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implémente la traduction de typeof(). Surcharge pour les structures et les pointeurs. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implémente la traduction de typeof(). Surcharge pour [Nullable](../nullable/). |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implémente la traduction de typeof(). Surcharge pour MutlicastDelegate. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Implémente la traduction de typeof(). Surcharge pour les structures et les pointeurs. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)(const [String](../string/)\&) | Implémente la traduction de typeof(). Surcharge pour le type string. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implémente la traduction de typeof(). Surcharge pour **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implémente la traduction de typeof(). Surcharge pour **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implémente la traduction de typeof(). Surcharge pour **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implémente la traduction de typeof(). Surcharge pour **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implémente la traduction de typeof(). Surcharge pour **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Implémente la traduction de typeof(). Surcharge pour **uint8_t**. |
## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)