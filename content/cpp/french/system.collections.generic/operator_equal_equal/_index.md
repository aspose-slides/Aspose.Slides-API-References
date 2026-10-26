---
title: operator==()
second_title: Référence de l'API Aspose.Slides pour C++
description: Compare deux paires clé-valeur en utilisant la sémantique « equals ». Utilise l’opérateur == ou la méthode EqualsTo pour les deux clés et valeurs, selon celle qui est définie.
type: docs
weight: 690
url: /fr/system.collections.generic/operator_equal_equal/
---
## System::Collections::Generic::operator==(const KeyValuePair\<TKey, TValue\>\&, const KeyValuePair\<TKey, TValue\>\&) fonction

Compare deux paires clé-valeur en utilisant la sémantique « equals ». Utilise l’opérateur == ou la méthode EqualsTo pour les deux clés et valeurs, selon celle qui est définie.

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator==(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TKey | Type de clé. |
| TValue | Type de valeur. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| left | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | Opérande gauche. |
| right | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | Opérande droite. |

### Valeur de retour

Vrai si les deux clés et valeurs correspondent, faux sinon.

## Voir aussi

* Classe [KeyValuePair](../keyvaluepair/)
* Espace de noms [System::Collections::Generic](../)
* Bibliothèque [Aspose.Slides](../../)