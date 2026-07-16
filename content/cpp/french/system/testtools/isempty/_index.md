---
title: IsEmpty()
second_title: Référence API Aspose.Slides pour C++
description: Vérifie si la chaîne est vide.
type: docs
weight: 14
url: /fr/system/testtools/isempty/
---
## TestTools::IsEmpty(const System::String\&) method


Vérifie si la chaîne est vide.

```cpp
static bool System::TestTools::IsEmpty(const System::String &str)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) à vérifier s'il est vide. |

### Valeur de retour

Vrai si la chaîne est vide (longueur nulle), faux sinon.

## TestTools::IsEmpty(const SharedPtr\<T\>\&) method


Vérifie si la collection est vide.

```cpp
template<typename T> static bool System::TestTools::IsEmpty(const SharedPtr<T> &collection)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type de collection. |

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | Collection à vérifier. |

### Valeur de retour

Vrai si la collection a un nombre d'éléments zéro, faux sinon.

## Voir aussi

* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Structure [TestTools](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)