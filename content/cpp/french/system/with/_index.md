---
title: With()
second_title: Référence de l'API Aspose.Slides pour C++
description: Clone l'enregistrement de référence et applique le foncteur d'initialisation à celui-ci.
type: docs
weight: 2575
url: /fr/system/with/
---
## System::With(const SharedPtr\<T\>\&, const A\&) fonction

Clone l'enregistrement de référence et applique le foncteur d'initialisation à celui-ci.

```cpp
template<typename T,typename A> SharedPtr<T> System::With(const SharedPtr<T> &record, const A &initializer)
```

### Paramètres de modèle

| Parameter | Description |
| --- | --- |
| T | Type d'enregistrement à cloner. |
| A | Type de foncteur d'initialisation. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| record | const [SharedPtr](../sharedptr/)\<T\>\& | Pointeur partagé vers l'objet à cloner et initialiser. |
| initializer | const A\& | Foncteur d'initialisation appliqué au clone de l'enregistrement. |

### Valeur de retour

Pointeur partagé vers l'enregistrement cloné.

## System::With(const T\&, const A\&) fonction

Copie l'enregistrement de structure et applique le foncteur d'initialisation à celui-ci.

```cpp
template<typename T,typename A> T System::With(const T &record, const A &initializer)
```

### Paramètres de modèle

| Parameter | Description |
| --- | --- |
| T | Type d'enregistrement à copier. |
| A | Type de foncteur d'initialisation. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| record | const T\& | Enregistrement à copier et initialiser. |
| initializer | const A\& | Foncteur d'initialisation appliqué à la copie de l'enregistrement. |

### Valeur de retour

Enregistrement copié.

## Voir aussi

* Typedef [SharedPtr](../sharedptr/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)