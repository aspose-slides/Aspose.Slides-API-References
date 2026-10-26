---
title: IBaseSlideHeaderFooterManager
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente le gestionnaire qui maintient le comportement des espaces réservés du pied de page, de la date-heure et du numéro de page pour tous les types de diapositive.
type: docs
url: /fr/com.aspose.slides/ibaseslideheaderfootermanager/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

Représente le gestionnaire qui maintient le comportement des espaces réservés du pied de page, de la date-heure et du numéro de page pour tous les types de diapositive.
## Méthodes

| Méthode | Description |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | Obtient la valeur indiquant qu'un espace réservé au pied de page est présent. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | Obtient la valeur indiquant qu'un espace réservé au numéro de page est présent. |
| [isDateTimeVisible()](#isDateTimeVisible--) | Obtient la valeur indiquant qu'un espace réservé à la date-heure est présent. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | Modifie la visibilité de l'espace réservé au pied de page de la diapositive. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | Modifie la visibilité de l'espace réservé au numéro de page de la diapositive. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | Modifie la visibilité de l'espace réservé à la date-heure de la diapositive. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | Définit le texte de l'espace réservé au pied de page de la diapositive. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | Définit le texte de l'espace réservé à la date-heure de la diapositive. |
### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```

Obtient la valeur indiquant qu'un espace réservé au pied de page est présent. Lecture booléenne.

**Renvoie :**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```

Obtient la valeur indiquant qu'un espace réservé au numéro de page est présent. Lecture booléenne.

**Renvoie :**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```

Obtient la valeur indiquant qu'un espace réservé à la date-heure est présent. Lecture booléenne.

**Renvoie :**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```

Modifie la visibilité de l'espace réservé au pied de page de la diapositive.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend un espace réservé au pied de page visible, sinon - le masque. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```

Modifie la visibilité de l'espace réservé au numéro de page de la diapositive.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend un espace réservé au numéro de page visible, sinon - le masque. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```

Modifie la visibilité de l'espace réservé à la date-heure de la diapositive.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend un espace réservé à la date-heure visible, sinon - le masque. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```

Définit le texte de l'espace réservé au pied de page de la diapositive.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte à définir. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```

Définit le texte de l'espace réservé à la date-heure de la diapositive.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte à définir. |