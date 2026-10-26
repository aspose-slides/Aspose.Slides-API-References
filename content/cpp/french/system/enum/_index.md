---
title: Enum
second_title: Référence API Aspose.Slides pour C++
description: Fournit des méthodes qui effectuent certaines opérations sur des valeurs de type enum. Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de celui-ci par quelque moyen que ce soit.
type: docs
weight: 1561
url: /fr/system/enum/
---
## Structure d'énumération

Fournit des méthodes qui effectuent certaines opérations sur des valeurs de type enum. Il s'agit d'un type statique sans services d'instance. Vous ne devez jamais créer d'instances de celui-ci par quelque moyen que ce soit.

```cpp
template<class E,class Guard>class Enum
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| E | Le type d'énumération dont la classe gère les valeurs |
| Guard | Argument de type de service dont le but est de garantir que **E** est un type énumérable |

## Méthodes

| Méthode | Description |
| --- | --- |
| static int [Compare](./compare/)(E, T) | Effectue la comparaison arithmétique des valeurs des constantes d'énumération spécifiées. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetDescription](./getdescription/)(T) | Renvoie le nom de la constante d'énumération qui possède la valeur spécifiée. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetName](./getname/)(T) | Renvoie le nom de la constante d'énumération qui possède la valeur spécifiée. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() | Renvoie un tableau contenant les noms de tous les membres de l'énumération **E**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() | Renvoie le type sous-jacent de l'énumération. |
| static [ArrayPtr](../arrayptr/)\<E\> [GetValues](./getvalues/)() | Renvoie un tableau contenant tous les membres de l'énumération **E**. |
| static **bool** [HasFlag](./hasflag/)(E, E) | Détermine si les bits spécifiés sont définis dans une représentation binaire de la valeur d'énumération spécifiée. |
| static **bool** [IsDefined](./isdefined/)(E) | Détermine si la valeur spécifiée est un membre du type d'énumération **E**. |
| static std::enable_if\<std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, **bool**\>::type [IsDefined](./isdefined/)(T) | Détermine si la valeur spécifiée est un membre du type d'énumération **T**. |
| static **bool** [IsDefined](./isdefined/)(const [String](../string/)\&) | Détermine si la valeur portant le nom spécifié fait partie des membres de l'énumération **E**. |
| static E [Parse](./parse/)(const [String](../string/)\&, **bool**) | Convertit la chaîne spécifiée en constante d'énumération équivalente. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, E\&) | Essaie de convertir la chaîne spécifiée en constante d'énumération équivalente. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**, E\&) | Essaie de convertir la chaîne spécifiée en constante d'énumération équivalente. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [UnderlyingType](./underlyingtype/) | Alias pour le type sous-jacent de l'énumération. |

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)