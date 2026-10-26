---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Référence API Aspose.Slides pour Java
description: Représente le gestionnaire qui contient le comportement des espaces réservés, y compris l'espace réservé d'en-tête pour tous les types de diapositives de support et de notes.
type: docs
url: /fr/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

Représente le gestionnaire qui contient le comportement des espaces réservés, y compris l'espace réservé d'en-tête pour tous les types de diapositives de support et de notes.

--------------------

Le nom d'interface original "IBaseHandoutNotesSlideHeaderFooterManager" est tronqué en "IBaseHandoutNotesSlideHeaderFooterManag" pour la compatibilité COM (la longueur du nom de type ne doit pas dépasser 39).
## Méthodes

| Méthode | Description |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Obtient la valeur indiquant qu'un espace réservé d'en-tête est présent. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Modifie la visibilité de l'espace réservé d'en-tête de diapositive. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Définit le texte de l'espace réservé d'en-tête de diapositive. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```

Obtient la valeur indiquant qu'un espace réservé d'en-tête est présent. Lecture booléenne.

**Renvoie :**  
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```

Modifie la visibilité de l'espace réservé d'en-tête de diapositive.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend l'espace réservé d'en-tête visible, sinon - le masque. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```

Définit le texte de l'espace réservé d'en-tête de diapositive.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte à définir. |