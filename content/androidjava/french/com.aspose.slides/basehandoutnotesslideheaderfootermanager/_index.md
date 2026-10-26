---
title: BaseHandoutNotesSlideHeaderFooterManager
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente le gestionnaire qui conserve le comportement des espaces réservés, y compris l'espace réservé d'en-tête pour tous les types de supports et de notes de diapositives.
type: docs
url: /fr/com.aspose.slides/basehandoutnotesslideheaderfootermanager/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public abstract class BaseHandoutNotesSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IBaseHandoutNotesSlideHeaderFooterManag
```

Représente le gestionnaire qui contient le comportement des espaces réservés, y compris l'espace réservé d'en-tête pour tous les types de supports et de notes de diapositives.
## Méthodes

| Méthode | Description |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Obtient la valeur indiquant qu'un espace réservé d'en-tête est présent. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Modifie la visibilité de l'espace réservé d'en-tête de la diapositive. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Définit le texte de l'espace réservé d'en-tête de la diapositive. |
### isHeaderVisible() {#isHeaderVisible--}
```
public final boolean isHeaderVisible()
```

Obtient la valeur indiquant qu'un espace réservé d'en-tête est présent. Lecture booléenne.

**Renvoie :**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public final void setHeaderVisibility(boolean isVisible)
```

Modifie la visibilité de l'espace réservé d'en-tête de la diapositive.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend un espace réservé d'en-tête visible, sinon - le masque. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public final void setHeaderText(String text)
```

Définit le texte de l'espace réservé d'en-tête de la diapositive.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte à définir. |