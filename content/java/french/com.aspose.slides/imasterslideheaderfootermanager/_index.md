---
title: IMasterSlideHeaderFooterManager
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente le gestionnaire qui maintient le comportement des espaces réservés du pied de page, de la date-heure, du numéro de page de la diapositive maîtresse et de tous les espaces réservés enfants.
type: docs
url: /fr/com.aspose.slides/imasterslideheaderfootermanager/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Représente le gestionnaire qui maintient le comportement des espaces réservés du pied de page de la diapositive maîtresse, des horodatages, des numéros de page et de tous les espaces réservés enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus dans les diapositives de mise en page dépendantes et les diapositives dépendantes. Les diapositives de mise en page dépendantes et les diapositives utilisent et dépendent de la diapositive maîtresse.
## Méthodes

| Méthode | Description |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Modifie la visibilité du master slide footer placeholder et de tous les child footer placeholders. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Modifie la visibilité du master slide page number placeholder et de tous les child page number placeholders. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Modifie la visibilité du master slide date-time placeholder et de tous les child date-time placeholders. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Définit le texte du master slide footer placeholder et de tous les child footer placeholders. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Définit le texte du master slide date-time placeholder et de tous les child date-time placeholders. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```


Modifie la visibilité du master slide footer placeholder et de tous les child footer placeholders. Les espaces réservés enfants signifient que les espaces réservés sont contenus dans les diapositives de mise en page dépendantes et les diapositives dépendantes. Les diapositives de mise en page dépendantes et les diapositives utilisent et dépendent de la diapositive maîtresse.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend les placeholders de pied de page visibles, sinon les masque. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```


Modifie la visibilité du master slide page number placeholder et de tous les child page number placeholders. Les espaces réservés enfants signifient que les espaces réservés sont contenus dans les diapositives de mise en page dépendantes et les diapositives dépendantes. Les diapositives de mise en page dépendantes et les diapositives utilisent et dépendent de la diapositive maîtresse.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend les placeholders de numéro de page visibles, sinon les masque. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```


Modifie la visibilité du master slide date-time placeholder et de tous les child date-time placeholders. Les espaces réservés enfants signifient que les espaces réservés sont contenus dans les diapositives de mise en page dépendantes et les diapositives dépendantes. Les diapositives de mise en page dépendantes et les diapositives utilisent et dépendent de la diapositive maîtresse.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend les placeholders de date-heure visibles, sinon les masque. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```


Définit le texte du master slide footer placeholder et de tous les child footer placeholders. Les espaces réservés enfants signifient que les espaces réservés sont contenus dans les diapositives de mise en page dépendantes et les diapositives dépendantes. Les diapositives de mise en page dépendantes et les diapositives utilisent et dépendent de la diapositive maîtresse.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte à définir. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```


Définit le texte du master slide date-time placeholder et de tous les child date-time placeholders. Les espaces réservés enfants signifient que les espaces réservés sont contenus dans les diapositives de mise en page dépendantes et les diapositives dépendantes. Les diapositives de mise en page dépendantes et les diapositives utilisent et dépendent de la diapositive maîtresse.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte à définir. |