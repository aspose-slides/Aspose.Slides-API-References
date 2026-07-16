---
title: IsNullOrEmpty()
second_title: Référence de l'API Aspose.Slides pour C++
description: Vérifie si la collection est nulle ou vide.
type: docs
weight: 27
url: /fr/system/testtools/isnullorempty/
---
## TestTools::IsNullOrEmpty(const SharedPtr\<T\>\&) méthode

Vérifie si la collection est nulle ou vide.

```cpp
template<typename T> static bool System::TestTools::IsNullOrEmpty(const SharedPtr<T> &collection)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type de collection. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | Collection à vérifier. |

### Valeur de retour

True si la collection est nulle ou a un nombre d'éléments égal à zéro, false sinon.

## TestTools::IsNullOrEmpty(const System::String\&) méthode

Vérifie si la chaîne est nulle ou vide.

```cpp
static bool System::TestTools::IsNullOrEmpty(const System::String &str)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) à vérifier. |

### Valeur de retour

True si la chaîne est nulle ou a une longueur de zéro, false sinon.

## Voir aussi

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Struct [TestTools](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)