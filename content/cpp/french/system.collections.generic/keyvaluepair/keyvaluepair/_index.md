---
title: KeyValuePair()
second_title: Référence de l'API Aspose.Slides pour C++
description: Initialisateur de paire clé-valeur nul.
type: docs
weight: 1
url: /fr/system.collections.generic/keyvaluepair/keyvaluepair/
---
## KeyValuePair::KeyValuePair() constructeur

Initialisateur de paire clé-valeur nul.

```cpp
System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair()
```

## KeyValuePair::KeyValuePair(const TKey\&, const TValue\&) constructeur

Constructeur.

```cpp
System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair(const TKey &key, const TValue &value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| key | const TKey\& | Clé. |
| value | const TValue\& | Valeur. |

## KeyValuePair::KeyValuePair(const std::pair\<OtherK, OtherV\>\&) constructeur

Constructeur de conversion de type.

```cpp
template<typename OtherK,typename OtherV> System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair(const std::pair<OtherK, OtherV> &pair)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| OtherK | Autre type de clé. |
| OtherV | Autre type de valeur. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| pair | const std::pair\<OtherK, OtherV\>\& | Valeur de la paire. |

## Voir aussi

* Classe [KeyValuePair](../)
* Espace de noms [System::Collections::Generic](../../)
* Bibliothèque [Aspose.Slides](../../../)