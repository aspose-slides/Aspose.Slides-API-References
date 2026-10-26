---
title: LayoutSlideHeaderFooterManager
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente le gestionnaire qui détient le comportement des espaces réservés du pied de page, de la date-heure et du numéro de page de la diapositive de mise en page, ainsi que de tous les espaces réservés enfants.
type: docs
url: /fr/com.aspose.slides/layoutslideheaderfootermanager/
---
**Héritage:** 
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Toutes les interfaces implémentées**:
[com.aspose.slides.ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
```
public final class LayoutSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements ILayoutSlideHeaderFooterManager
```

Représente le gestionnaire qui contient le comportement du pied de page de la diapositive de mise en page, des espaces réservés date-heure, numéro de page et de tous les espaces réservés enfants. Les espaces réservés enfants sont des espaces réservés contenus dans les diapositives dépendantes. Les diapositives dépendantes utilisent et dépendent de la diapositive de mise en page.
## Méthodes

| Méthode | Description |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Modifie la visibilité du pied de page de la diapositive de mise en page et de tous les pieds de page enfants. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Modifie la visibilité du numéro de page de la diapositive de mise en page et de tous les numéros de page enfants. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Modifie la visibilité de l’espace réservé date-heure de la diapositive de mise en page et de tous les espaces réservés date-heure enfants. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Définit le texte du pied de page de la diapositive de mise en page et de tous les pieds de page enfants. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Définit le texte de l’espace réservé date-heure de la diapositive de mise en page et de tous les espaces réservés date-heure enfants. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

Modifie la visibilité du pied de page de la diapositive de mise en page et de tous les pieds de page enfants. Les espaces réservés enfants sont des espaces réservés contenus dans les diapositives dépendantes. Les diapositives dépendantes utilisent et dépendent de la diapositive maîtresse.

**Paramètres**:
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend les pieds de page visibles, sinon les masque. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Modifie la visibilité du numéro de page de la diapositive de mise en page et de tous les numéros de page enfants. Les espaces réservés enfants sont des espaces réservés contenus dans les diapositives dépendantes. Les diapositives dépendantes utilisent et dépendent de la diapositive de mise en page.

**Paramètres**:
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend les numéros de page visibles, sinon les masque. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Modifie la visibilité de l’espace réservé date-heure de la diapositive de mise en page et de tous les espaces réservés date-heure enfants. Les espaces réservés enfants sont des espaces réservés contenus dans les diapositives dépendantes. Les diapositives dépendantes utilisent et dépendent de la diapositive de mise en page.

**Paramètres**:
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend les espaces réservés date-heure visibles, sinon les masque. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

Définit le texte du pied de page de la diapositive de mise en page et de tous les pieds de page enfants. Les espaces réservés enfants sont des espaces réservés contenus dans les diapositives dépendantes. Les diapositives dépendantes utilisent et dépendent de la diapositive de mise en page.

**Paramètres**:
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte à définir. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

Définit le texte de l’espace réservé date-heure de la diapositive de mise en page et de tous les espaces réservés date-heure enfants. Les espaces réservés enfants sont des espaces réservés contenus dans les diapositives dépendantes. Les diapositives dépendantes utilisent et dépendent de la diapositive de mise en page.

**Paramètres**:
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte à définir. |