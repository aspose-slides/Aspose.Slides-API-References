---
title: ObjectExt
second_title: Référence de l'API Aspose.Slides pour C++
description: Fournit des méthodes statiques qui émulent les méthodes C# Object appelées pour des types C++ non-Objet (chaînes, nombres, etc.). Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de celui-ci par quelque moyen que ce soit.
type: docs
weight: 1132
url: /fr/system/objectext/
---
## ObjectExt classe


Fournit des méthodes statiques qui émulent les méthodes C# [Object](../object/) appelées pour les types C++ non-Objet (chaînes, nombres, etc.). Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de celui-ci par quelque moyen que ce soit.

```cpp
class ObjectExt : public System::ObjectType
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static std::enable_if<(std::is_fundamental\<To\>::value), std::array\<To, sizeof...(From)>\>::type [ArrayInitializerCast](./arrayinitializercast/)(From ...) | Convertit les valeurs fondamentales d'un tableau (ce que C# fait implicitement mais que C++ ne fait apparemment pas). |
| static std::enable_if\<std::is_enum\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Boîte les types valeur pour la conversion en [Object](../object/). Implémentation pour les types enum. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Boîte les types valeur pour la conversion en [Object](../object/). Implémentation pour les types non-enum. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Boîte les types [Nullable](../nullable/) pour la conversion en [Object](../object/). |
| static [SmartPtr](../smartptr/)\<[Object](../object/)\> [Box](./box/)(const [String](../string/)\&) | Boîte les valeurs de chaîne. |
| static [SmartPtr](../smartptr/)\<[System::BoxedValueBase](../boxedvaluebase/)\> [BoxEnum](./boxenum/)(T) | Boîte les types enum pour être propagés en tant que [Object](../object/). |
| static [SmartPtr](../smartptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CastToIList](./casttoilist/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) |  |
| static auto [Coalesce](./coalesce/)(T0, T1) | Implémentation de la traduction de l'opérateur '??' pour les types non nullable. |
| static T0 [Coalesce](./coalesce/)([System::Nullable](../nullable/)\<T0\>, T1) | Implémentation de la traduction de l'opérateur '??' pour les types nullable. |
| static auto [CoalesceAssign](./coalesceassign/)(T0\&, T1) | Implémentation de la traduction de l'opérateur '??='. |
| static std::conditional\<std::is_convertible\<RT2, RT1\>::value, RT1, RT2\>::type [CoalesceInternal](./coalesceinternal/)(RT1, F) | Implémentation de la traduction de l'opérateur '??' pour les types non nullable. Surcharge pour le cas où RT2 est convertible en RT1. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) |  |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | Substitution des appels [Object.Equals](../object/equals/) de C# fonctionnant pour tout type en C++. Surcharge pour les types pointeur intelligent. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(T, const T2\&) | Substitution des appels [Object.Equals](../object/equals/) de C# fonctionnant pour tout type en C++. Surcharge pour les types structure. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | Substitution des appels [Object.Equals](../object/equals/) de C# fonctionnant pour tout type en C++. Surcharge pour les types scalaire. |
| static **bool** [Equals](./equals/)(const char_t(&), [String](../string/)) | Substitution des appels [Object.Equals](../object/equals/) de C# fonctionnant pour tout type en C++. Surcharge pour les littéraux de chaîne avec comparaison de chaînes. |
| static **bool** [Equals](./equals/)(const **float**\&, const **float**\&) | Émule la comparaison à virgule flottante de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](./equals/)(const **double**\&, const **double**\&) | Émule la comparaison à virgule flottante de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static std::enable_if\<[System::IsSmartPtr](../issmartptr/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static int [GetHashCode](./gethashcode/)(const T\&) | Implémente les appels [GetHashCode()](./gethashcode/) ; fonctionne à la fois sur les sous-classes [Object](../object/) et sur des types non liés. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Implémente la traduction de typeof(). Surcharge pour les pointeurs intelligents. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Implémente la traduction de typeof(). Surcharge pour les structures. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Implémente la traduction de typeof(). Surcharge pour les exceptions. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | Implémente la traduction de typeof(). Surcharge pour les types primitifs. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | Implémente la traduction de typeof(). Surcharge pour les types [Nullable](../nullable/). |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implémente la traduction de typeof(). Surcharge pour les types primitifs. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implémente la traduction de typeof(). Surcharge pour les types enum. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implémente la traduction de typeof(). Surcharge pour les structures et les pointeurs. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implémente la traduction de typeof(). Surcharge pour [Nullable](../nullable/). |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implémente la traduction de typeof(). Surcharge pour MutlicastDelegate. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Implémente la traduction de typeof(). Surcharge pour les structures et les pointeurs. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)(const [String](../string/)\&) | Implémente la traduction de typeof(). Surcharge pour le type chaîne. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implémente la traduction de typeof(). Surcharge pour **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implémente la traduction de typeof(). Surcharge pour **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implémente la traduction de typeof(). Surcharge pour **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implémente la traduction de typeof(). Surcharge pour **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implémente la traduction de typeof(). Surcharge pour **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Implémente la traduction de typeof(). Surcharge pour **uint8_t**. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, **bool**\>::type [Is](./is/)(const T\&) | Implémente la traduction de l'opérateur 'is'. Spécialisation pour les types booboxables (valeur) qui sont exactement cela. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | Implémente la traduction de l'opérateur 'is'. Spécialisation pour les types pointeur optimisés pour les classes 'final'. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&\!std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | Implémente la traduction de l'opérateur 'is'. Spécialisation pour les types pointeur. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | Implémente la traduction de l'opérateur 'is'. Spécialisation pour les types valeur. |
| static std::enable_if<\!std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | Implémente la traduction de l'opérateur 'is'. Spécialisation pour les types non convertibles. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | Implémente la traduction de l'opérateur 'is'. Spécialisation pour les types pointeur. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Is](./is/)(const [ExceptionWrapper](../exceptionwrapper/)\<U\>\&) | Implémente la traduction de l'opérateur 'is'. Spécialisation pour les types enveloppe d'exception. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Implémente la traduction de l'opérateur 'is'. Spécialisation pour les types nullable. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Implémente la traduction de l'opérateur 'is'. Spécialisation pour les types booboxables avec opérateur == défini. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Implémente la traduction de l'opérateur 'is'. Spécialisation pour les types booboxables sans opérateur == défini. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!std::is_same\<V, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<V\>\&) | Implémente la traduction de l'opérateur 'is'. Spécialisation des types valeur boxés vers les interfaces. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | Implémente la traduction de l'opérateur 'is'. Spécialisation pour les types enum. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [WeakPtr](../weakptr/)\<U\>\&) | Implémente la traduction de l'opérateur 'is'. Spécialisation pour les types enum contre les pointeurs faibles. |
| static **bool** [Is](./is/)(const [Nullable](../nullable/)\<U\>\&) | Implémente la traduction de l'opérateur 'is'. Spécialisation pour le type [Nullable](../nullable/). |
| static **bool** [Is](./is/)(const char16_t *) | Implémente la traduction de l'opérateur 'is'. Spécialisation pour le littéral chaîne. |
| static **bool** [Is](./is/)(**int32_t**) | Implémente la traduction de l'opérateur 'is'. Spécialisation pour le littéral entier. |
| static **bool** [IsBoxedValue](./isboxedvalue/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Vérifie si l'objet est une valeur boxée. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | Convertit [Object](../object/) en type inconnu, en gérant à la fois le type pointeur intelligent et les situations de valeur boxée. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | Convertit [Object](../object/) en type inconnu, en gérant à la fois le type pointeur intelligent et les situations de valeur boxée. |
| static [String](../string/) [ToString](./tostring/)(const char_t *) | Substitution pour la méthode C# ToString afin de fonctionner sur tout type C++. |
| static [String](../string/) [ToString](./tostring/)(const [Nullable](../nullable/)\<T\>\&) | Substitution pour la méthode C# ToString afin de fonctionner sur tout type C++. |
| static std::enable_if\<std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Substitution pour la méthode C# ToString afin de fonctionner sur tout type C++. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Substitution pour la méthode C# ToString afin de fonctionner sur tout type C++. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value||std::is_pointer\<T\>::value||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Substitution pour la méthode C# ToString afin de fonctionner sur tout type C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Substitution pour la méthode C# ToString afin de fonctionner sur tout type C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | Substitution pour la méthode C# ToString afin de fonctionner sur tout type C++. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Substitution pour la méthode C# ToString afin de fonctionner sur tout type C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Substitution pour la méthode C# ToString afin de fonctionner sur tout type C++. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_reference\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | Substitution pour la méthode C# ToString afin de fonctionner sur tout type C++. |
| static std::enable_if\<std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Déboxe les types valeur après conversion en [Object](../object/). Implémentation pour les types enum. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Déboxe les types valeur après conversion en [Object](../object/). Implémentation pour les types non-enum et non nullable. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Déboxe les types valeur après conversion en [Object](../object/). Implémentation pour les types non-enum et non nullable. |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::numeric_limits\<T\>::is_integer, T\>::type [Unbox](./unbox/)(E) | Déboxe les types enum en entier. |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(E) | Convertit les types enum. |
| static [String](../string/) [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Déboxe les valeurs de chaîne. |
| static [String](../string/) [UnboxStringSafe](./unboxstringsafe/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Déboxe la chaîne à partir d'une valeur boxée. |
| static [Nullable](../nullable/)\<T\> [UnboxToNullable](./unboxtonullable/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | Déboxe l'objet en type nullable. |
| static std::enable_if<\!std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | Vérifie si l'objet de type inconnu est nullptr. Surcharge pour les types non scalaire. |
| static std::enable_if\<std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | Vérifie si l'objet de type inconnu est nullptr. Surcharge pour les types scalaire. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(T) | Convertit le type inconnu en [Object](../object/), en gérant à la fois le type pointeur intelligent et le type valeur. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(const T\&) | Convertit le type inconnu en [Object](../object/), en gérant à la fois le type pointeur intelligent et le type valeur. |
## Voir aussi

* Classe [ObjectType](../objecttype/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)