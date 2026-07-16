---
title: UnknownIsNull()
second_title: Référence de l'API Aspose.Slides pour C++
description: Vérifie si l'objet de type inconnu est nullptr. Surcharge pour les types non scalaires.
type: docs
weight: 144
url: /fr/system/objectext/unknownisnull/
---
## ObjectExt::UnknownIsNull(T) méthode

Vérifie si l'objet de type inconnu est nullptr. Surcharge pour les types non scalaires.

```cpp
template<typename T> static std::enable_if<!std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | [Object](../../object/) type. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | T | [Object](../../object/) à vérifier. |

### Valeur de retour

Vrai si 'obj == nullptr' est vrai, sinon faux.

## ObjectExt::UnknownIsNull(T) méthode

Vérifie si l'objet de type inconnu est nullptr. Surcharge pour les types scalaires.

```cpp
template<typename T> static std::enable_if<std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | [Object](../../object/) type. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | T | [Object](../../object/) à vérifier. |

### Valeur de retour

Retourne toujours faux.

## Voir aussi

* Classe [ObjectExt](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)