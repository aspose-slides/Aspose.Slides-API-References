---
title: Nullable
second_title: Référence de l'API Aspose.Slides for C++
description: Déclaration anticipée.
type: docs
weight: 1093
url: /fr/system/nullable/
---
## Classe Nullable

Déclaration anticipée.

```cpp
template<typename T>class Nullable
```

### Paramètres de modèle

| Parameter | Description |
| --- | --- |
| T | Le type de valeur sous-jacent qui est étendu par la classe [Nullable](./) |
## Méthodes

| Method | Description |
| --- | --- |
| std::enable_if\<[IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [Equals](./equals/)(const T1\&) const | Détermine si la valeur représentée par l'objet actuel est égale à la valeur représentée par l'objet [Nullable](./) spécifié. |
| **bool** [get_HasValue](./get_hasvalue/)() const | Détermine si l'objet actuel représente une valeur quelconque. |
| T [get_Value](./get_value/)() const | Retourne une copie de la valeur représentée par l'objet actuel. |
| int [GetHashCode](./gethashcode/)() const | Retourne un code de hachage pour l'objet actuel. |
| T [GetValueOrDefault](./getvalueordefault/)(T) | Retourne la valeur représentée par l'objet actuel ou la valeur spécifiée si la valeur représentée par l'objet actuel est nulle. |
| T [GetValueOrDefault](./getvalueordefault/)() |  |
| **bool** [IsNull](./isnull/)() const | Détermine si l'objet actuel représente une valeur nulle. |
| [Nullable](./nullable/)() | Construit une instance qui représente une valeur nulle. |
| [Nullable](./nullable/)(std::nullptr_t) | Construit une instance qui représente null. |
| [Nullable](./nullable/)(const T1\&) | Construit une instance de la classe [Nullable](./) qui représente la valeur spécifiée convertie (si nécessaire) au type sous-jacent T. |
| [Nullable](./nullable/)(const [Nullable](./)\<T1\>\&) | Construit une instance qui représente une valeur qui est représentée par l'objet [Nullable](./) spécifié. L'objet nullable spécifié peut représenter une valeur d'un type différent de celui du type sous-jacent de l'instance construite, auquel cas la valeur représentée est convertie en type T. |
| **bool** [NullableBoolHelper](./nullableboolhelper/)(const T1\&, const std::function\<**bool**()>\&, **bool**) const | Fonction d'assistance pour vérifier si cet objet et **other** ne sont pas nuls tous les deux et appeler une lambda le cas échéant. Utilisée dans implementation.s. |
| [operator const T &](./operator_const_t__and/)() const | Retourne une référence constante à la valeur représentée par l'objet actuel. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Détermine si la valeur représentée par l'objet actuel n'est pas nulle. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const T1\&) const | Détermine si la valeur représentée par l'objet actuel n'est pas égale à la valeur spécifiée. |
| **bool** [operator!=](./operator_not_equal/)(const [Nullable](./)\<T1\>\&) const | Détermine si la valeur représentée par l'objet actuel n'est pas égale à la valeur représentée par l'objet [Nullable](./) spécifié. |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator&=](./operator_and_equal/)(**bool**) | Applique [operator&=()](./operator_and_equal/) à la valeur représentée par l'objet actuel en utilisant la valeur spécifiée comme argument à droite. |
| [Nullable](./)\<T\> [operator+](./operator_plus/)(std::nullptr_t) const | Retourne une instance par défaut construite de la classe Nullable<T>. |
| auto [operator+](./operator_plus/)(const T1\&) const | Additionne les valeurs nullable et non-nullable. |
| auto [operator+](./operator_plus/)(const [Nullable](./)\<T1\>\&) const | Additionne les valeurs nullable. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(std::nullptr_t) | Réinitialise l'objet actuel afin qu'il représente une valeur nulle. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator+=](./operator_plus_equal/)(const T1\&) | Applique [operator+=()](./operator_plus_equal/) à la valeur représentée par l'objet actuel en utilisant la valeur spécifiée comme argument à droite. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(const [Nullable](./)\<T1\>\&) | Applique [operator+=()](./operator_plus_equal/) à la valeur représentée par l'objet actuel en utilisant la valeur représentée par l'objet [Nullable](./) spécifié comme argument à droite. |
| [Nullable](./)\<T\> [operator-](./operator_minus/)(T1) const | Soustrait les valeurs nullable et les valeurs pointées null. |
| auto [operator-](./operator_minus/)(const T1\&) const | Soustrait les valeurs nullable et non-nullable. |
| auto [operator-](./operator_minus/)(const [Nullable](./)\<T1\>\&) const | Soustrait les valeurs nullable. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(T1) | Retourne une instance de la classe [Nullable](./) qui représente une valeur nulle. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator-=](./operator_minus_equal/)(const T1\&) | Applique [operator-=()](./operator_minus_equal/) à la valeur représentée par l'objet actuel en utilisant la valeur spécifiée comme argument à droite. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(const [Nullable](./)\<T1\>\&) | Applique [operator-=()](./operator_minus_equal/) à la valeur représentée par l'objet actuel en utilisant la valeur représentée par l'objet [Nullable](./) spécifié comme argument à droite. |
| **bool** [operator<](./operator_less/)(std::nullptr_t) const | Retourne toujours false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<](./operator_less/)(const T1\&) const | Détermine si la valeur représentée par l'objet actuel est inférieure à la valeur spécifiée en appliquant [operator<()](./operator_less/) à ces valeurs. |
| **bool** [operator<](./operator_less/)(const [Nullable](./)\<T1\>\&) const | Détermine si la valeur représentée par l'objet actuel est inférieure à la valeur représentée par l'objet [Nullable](./) spécifié en appliquant [operator<()](./operator_less/) à ces valeurs. |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const | Retourne toujours false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<=](./operator_less_equal/)(const T1\&) const | Détermine si la valeur représentée par l'objet actuel est inférieure ou égale à la valeur spécifiée en appliquant [operator<=()](./operator_less_equal/) à ces valeurs. |
| **bool** [operator<=](./operator_less_equal/)(const [Nullable](./)\<T1\>\&) const | Détermine si la valeur représentée par l'objet actuel est inférieure ou égale à la valeur représentée par l'objet [Nullable](./) spécifié en appliquant [operator<=()](./operator_less_equal/) à ces valeurs. |
| [Nullable](./)\<T\> [operator=](./operator_equal/)(std::nullptr_t) | Assigne null à l'objet actuel. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value\&&\!std::is_null_pointer\<T1\>::value, [Nullable](./)\<T\>\&\>::type [operator=](./operator_equal/)(const T1\&) | Remplace la valeur actuellement représentée de l'objet par la valeur spécifiée. |
| [Nullable](./)\<T\>\& [operator=](./operator_equal/)(const [Nullable](./)\<T1\>\&) | Remplace la valeur actuellement représentée de l'objet par la valeur spécifiée. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Détermine si la valeur représentée par l'objet actuel est nulle. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const T1\&) const | Détermine si la valeur représentée par l'objet actuel est égale à la valeur spécifiée. |
| **bool** [operator==](./operator_equal_equal/)(const [Nullable](./)\<T1\>\&) const | Détermine si la valeur représentée par l'objet actuel est égale à la valeur représentée par l'objet [Nullable](./) spécifié. |
| **bool** [operator>](./operator_greater/)(std::nullptr_t) const | Retourne toujours false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>](./operator_greater/)(const T1\&) const | Détermine si la valeur représentée par l'objet actuel est supérieure à la valeur spécifiée en appliquant [operator>()](./operator_greater/) à ces valeurs. |
| **bool** [operator>](./operator_greater/)(const [Nullable](./)\<T1\>\&) const | Détermine si la valeur représentée par l'objet actuel est supérieure à la valeur représentée par l'objet [Nullable](./) spécifié en appliquant [operator>()](./operator_greater/) à ces valeurs. |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const | Retourne toujours false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>=](./operator_greater_equal/)(const T1\&) const | Détermine si la valeur représentée par l'objet actuel est supérieure ou égale à la valeur de l'objet spécifié en appliquant [operator>=()](./operator_greater_equal/) à ces valeurs. |
| **bool** [operator>=](./operator_greater_equal/)(const [Nullable](./)\<T1\>\&) const | Détermine si la valeur représentée par l'objet actuel est supérieure ou égale à la valeur de l'objet [Nullable](./) spécifié en appliquant [operator>=()](./operator_greater_equal/) à ces valeurs. |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator|=](./operator_or_equal/)(**bool**) | Applique [operator|=()](./operator_or_equal/) à la valeur représentée par l'objet actuel en utilisant la valeur spécifiée comme argument à droite. |
| void [reset](./reset/)() | Définit la valeur actuellement représentée sur null. |
| void [set_Value](./set_value/)(const T\&) | Définit une nouvelle valeur pour l'objet nullable. |
| [String](../string/) [ToString](./tostring/)() const | Convertit la valeur représentée par l'objet actuel en chaîne. |
## Alias de type

| Typedef | Description |
| --- | --- |
| [ValueType](./valuetype/) | Un alias pour le type de la valeur représentée par cette classe. |
## Remarques

Représente une valeur du type spécifié qui peut être assignée à null. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N'utilisez jamais la classe [System::SmartPtr](../smartptr/) pour gérer des objets de ce type.

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)