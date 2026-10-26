---
title: KeyValuePair
second_title: Référence de l'API Aspose.Slides pour C++
description: "Paire de clé et de valeur. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N'utilisez jamais la classe System::SmartPtr pour gérer les objets de ce type."
type: docs
weight: 378
url: /fr/system.collections.generic/keyvaluepair/
---
## KeyValuePair classe

Paire de clé et de valeur. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N'utilisez jamais la classe [System::SmartPtr](../../system/smartptr/) pour gérer les objets de ce type.

```cpp
template<typename TKey,typename TValue>class KeyValuePair
```

## Méthodes

| Méthode | Description |
| --- | --- |
| const TKey\& [get_Key](./get_key/)() const | Obtient la clé. |
| const TValue\& [get_Value](./get_value/)() const | Obtient la valeur. |
| int [GetHashCode](./gethashcode/)() const | Calcule le hachage de la paire clé-valeur en xorant les hachages de la clé et de la valeur. |
| **bool** [IsNull](./isnull/)() const | Renvoie toujours false. |
|  [KeyValuePair](./keyvaluepair/)() | Initialiseur de paire clé-valeur nul. |
|  [KeyValuePair](./keyvaluepair/)(const TKey\&, const TValue\&) | Constructeur. |
|  [KeyValuePair](./keyvaluepair/)(const std::pair\<OtherK, OtherV\>\&) | Constructeur de conversion de type. |
| **bool** [operator<](./operator_less/)(const [KeyValuePair](./)\&) const | Correctif pour les classes héritées de IComparer<KeyValuePair<TKey, TValue>>, ne compare rien. |
| [String](../../system/string/) [ToString](./tostring/)() const | Convertit la paire clé-valeur en chaîne. |

## Voir aussi

* Espace de noms [System::Collections::Generic](../)
* Bibliothèque [Aspose.Slides](../../)