---
title: operator<<()
second_title: Référence de l'API Aspose.Slides pour C++
description: Insérer des données dans le flux en utilisant le codage UTF-8.
type: docs
weight: 716
url: /fr/system.collections.generic/operator_less_less/
---
## System::Collections::Generic::operator<<(std::ostream\&, const KeyValuePair\<TKey, TValue\>\&) fonction


Insérer les données dans le flux en utilisant le codage UTF-8.

```cpp
template<typename TKey,typename TValue> std::ostream & System::Collections::Generic::operator<<(std::ostream &stream, const KeyValuePair<TKey, TValue> &pair)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TKey | Type de clé. |
| TValue | Type de valeur. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | std::ostream\& | Flux de sortie dans lequel insérer les données. |
| pair | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | [Data](../../system.data/) à insérer. |

### Valeur de retour

**stream**.

## System::Collections::Generic::operator<<(std::wostream\&, const KeyValuePair\<TKey, TValue\>\&) fonction


Insérer les données dans le flux.

```cpp
template<typename TKey,typename TValue> std::wostream & System::Collections::Generic::operator<<(std::wostream &stream, const KeyValuePair<TKey, TValue> &pair)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TKey | Type de clé. |
| TValue | Type de valeur. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | std::wostream\& | Flux de sortie dans lequel insérer les données. |
| pair | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | [Data](../../system.data/) à insérer. |

### Valeur de retour

**stream**.

## Voir aussi

* Classe [KeyValuePair](../keyvaluepair/)
* Espace de noms [System::Collections::Generic](../)
* Bibliothèque [Aspose.Slides](../../)