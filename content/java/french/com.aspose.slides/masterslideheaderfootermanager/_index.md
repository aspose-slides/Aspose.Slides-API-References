---
title: MasterSlideHeaderFooterManager
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente le gestionnaire qui détient le comportement des espaces réservés du pied de page, de la date-heure, du numéro de page de la diapositive maîtresse et de tous les espaces réservés enfants.
type: docs
url: /fr/com.aspose.slides/masterslideheaderfootermanager/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
```
public final class MasterSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IMasterSlideHeaderFooterManager
```

Représente le gestionnaire qui contient le comportement des espaces réservés du pied de page de la diapositive maître, de la date-heure, du numéro de page et de tous les espaces réservés enfants. Les espaces réservés enfants désignent les espaces réservés contenus dans les diapositives de mise en page dépendantes et les diapositives dépendantes. Les diapositives de mise en page dépendantes et les diapositives utilisent et dépendent de la diapositive maître.
## Méthodes

| Méthode | Description |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Modifie la visibilité de l'espace réservé du pied de page de la diapositive maître et de tous les espaces réservés du pied de page enfants. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Modifie la visibilité de l'espace réservé du numéro de page de la diapositive maître et de tous les espaces réservés du numéro de page enfants. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Modifie la visibilité de l'espace réservé de la date-heure de la diapositive maître et de tous les espaces réservés de la date-heure enfants. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Définit le texte de l'espace réservé du pied de page de la diapositive maître et de tous les espaces réservés du pied de page enfants. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Définit le texte de l'espace réservé de la date-heure de la diapositive maître et de tous les espaces réservés de la date-heure enfants. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

Modifie la visibilité de l'espace réservé du pied de page de la diapositive maître et de tous les espaces réservés du pied de page enfants. Les espaces réservés enfants désignent les espaces réservés contenus dans les diapositives de mise en page dépendantes et les diapositives dépendantes. Les diapositives de mise en page dépendantes et les diapositives utilisent et dépendent de la diapositive maître.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend les espaces réservés du pied de page visibles, sinon les masque. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Modifie la visibilité de l'espace réservé du numéro de page de la diapositive maître et de tous les espaces réservés du numéro de page enfants. Les espaces réservés enfants désignent les espaces réservés contenus dans les diapositives de mise en page dépendantes et les diapositives dépendantes. Les diapositives de mise en page dépendantes et les diapositives utilisent et dépendent de la diapositive maître.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend les espaces réservés du numéro de page visibles, sinon les masque. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Modifie la visibilité de l'espace réservé de la date-heure de la diapositive maître et de tous les espaces réservés de la date-heure enfants. Les espaces réservés enfants désignent les espaces réservés contenus dans les diapositives de mise en page dépendantes et les diapositives dépendantes. Les diapositives de mise en page dépendantes et les diapositives utilisent et dépendent de la diapositive maître.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend les espaces réservés de la date-heure visibles, sinon les masque. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

Définit le texte de l'espace réservé du pied de page de la diapositive maître et de tous les espaces réservés du pied de page enfants. Les espaces réservés enfants désignent les espaces réservés contenus dans les diapositives de mise en page dépendantes et les diapositives dépendantes. Les diapositives de mise en page dépendantes et les diapositives utilisent et dépendent de la diapositive maître.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte à définir. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

Définit le texte de l'espace réservé de la date-heure de la diapositive maître et de tous les espaces réservés de la date-heure enfants. Les espaces réservés enfants désignent les espaces réservés contenus dans les diapositives de mise en page dépendantes et les diapositives dépendantes. Les diapositives de mise en page dépendantes et les diapositives utilisent et dépendent de la diapositive maître.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte à définir. |