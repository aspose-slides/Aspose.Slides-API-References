---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente le gestionnaire qui conserve le comportement des espaces réservés, y compris le placeholder d'en-tête pour tous les types de diapositives de support et de notes.
type: docs
url: /fr/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

Représente le gestionnaire qui maintient le comportement des espaces réservés, y compris le placeholder d’en-tête pour tous les types de diapositives de support et de notes.

--------------------

Le nom d’interface original « IBaseHandoutNotesSlideHeaderFooterManager » est tronqué en « IBaseHandoutNotesSlideHeaderFooterManag » pour la compatibilité COM (la longueur du nom de type ne doit pas dépasser 39).

## Méthodes

| Méthode | Description |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Obtient la valeur indiquant qu’un placeholder d’en-tête est présent. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Modifie la visibilité du placeholder d’en-tête de la diapositive. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Définit le texte du placeholder d’en-tête de la diapositive. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```

Obtient la valeur indiquant qu’un placeholder d’en-tête est présent. Lit un boolean.

**Retour :**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```

Modifie la visibilité du placeholder d’en-tête de la diapositive.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend le placeholder d’en-tête visible, sinon - le masque. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```

Définit le texte du placeholder d’en-tête de la diapositive.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte à définir. |