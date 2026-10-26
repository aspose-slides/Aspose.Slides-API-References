---
title: TestTools
second_title: Référence de l'API Aspose.Slides pour C++
description: Fournit un ensemble de méthodes utiles qui vérifient certaines propriétés de base de différents types et fonctions.
type: docs
weight: 1899
url: /fr/system/testtools/
---
## TestTools struct

Fournit un ensemble de méthodes utiles qui vérifient certaines propriétés de base de différents types et fonctions.

```cpp
class TestTools
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static **bool** [AssertThrows](./assertthrows/)(const std::function\<void()>\&) | Vérifie si la fonction lève une exception de n'importe quel type. |
| static **bool** [IsEmpty](./isempty/)(const [System::String](../string/)\&) | Vérifie si la chaîne est vide. |
| static **bool** [IsEmpty](./isempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Vérifie si la collection est vide. |
| static std::enable_if\<std::is_arithmetic\<T\>::value||std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(T) | Vérifie si la valeur spécifique est nulle. [Version](../version/) pour les types arithmétiques et enum. |
| static std::enable_if<\!std::is_arithmetic\<T\>::value\&&\!std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(const T\&) | Vérifie si la valeur spécifique est nulle. [Version](../version/) pour les types non arithmétiques et non enum. |
| static **bool** [IsNull](./isnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Vérifie si la valeur spécifique est nulle. [Version](../version/) pour les types non arithmétiques. |
| static **bool** [IsNull](./isnull/)([System::Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<K, V\>\&) | Vérifie si la valeur spécifique est nulle. [Version](../version/) pour les paires clé-valeur. |
| static **bool** [IsNull](./isnull/)(const [System::String](../string/)\&) | Vérifie si la chaîne est nulle. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Vérifie si la collection est nulle ou vide. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [System::String](../string/)\&) | Vérifie si la chaîne est nulle ou vide. |
## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)