---
title: ILayoutSlideHeaderFooterManager
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente le gestionnaire qui maintient le comportement des espaces réservés du pied de page, de la date-heure, du numéro de page de la diapositive de mise en page et de tous les espaces réservés enfants.
type: docs
url: /fr/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**Toutes les interfaces implémentées:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Représente le gestionnaire qui maintient le comportement des espaces réservés du pied de page de la diapositive de mise en page, de la date-heure, du numéro de page et de tous les espaces réservés enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus dans les diapositives dépendantes. Les diapositives dépendantes utilisent et dépendent de la diapositive de mise en page.
## Méthodes

| Méthode | Description |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Modifie la visibilité de l’espace réservé du pied de page de la diapositive de mise en page et de tous les espaces réservés enfants du pied de page. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Modifie la visibilité de l’espace réservé du numéro de page de la diapositive de mise en page et de tous les espaces réservés enfants du numéro de page. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Modifie la visibilité de l’espace réservé de la date-heure de la diapositive de mise en page et de tous les espaces réservés enfants de la date-heure. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Définit le texte de l’espace réservé du pied de page de la diapositive de mise en page et de tous les espaces réservés enfants du pied de page. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Définit le texte de l’espace réservé de la date-heure de la diapositive de mise en page et de tous les espaces réservés enfants de la date-heure. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Modifie la visibilité de l’espace réservé du pied de page de la diapositive de mise en page et de tous les espaces réservés enfants du pied de page. Les espaces réservés enfants signifient que les espaces réservés sont contenus dans les diapositives dépendantes. Les diapositives dépendantes utilisent et dépendent de la diapositive maître.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend les espaces réservés du pied de page visibles, sinon les masque. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Modifie la visibilité de l’espace réservé du numéro de page de la diapositive de mise en page et de tous les espaces réservés enfants du numéro de page. Les espaces réservés enfants signifient que les espaces réservés sont contenus dans les diapositives dépendantes. Les diapositives dépendantes utilisent et dépendent de la diapositive de mise en page.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend les espaces réservés du numéro de page visibles, sinon les masque. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Modifie la visibilité de l’espace réservé de la date-heure de la diapositive de mise en page et de tous les espaces réservés enfants de la date-heure. Les espaces réservés enfants signifient que les espaces réservés sont contenus dans les diapositives dépendantes. Les diapositives dépendantes utilisent et dépendent de la diapositive de mise en page.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend les espaces réservés de la date-heure visibles, sinon les masque. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Définit le texte de l’espace réservé du pied de page de la diapositive de mise en page et de tous les espaces réservés enfants du pied de page. Les espaces réservés enfants signifient que les espaces réservés sont contenus dans les diapositives dépendantes. Les diapositives dépendantes utilisent et dépendent de la diapositive de mise en page.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte à définir. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Définit le texte de l’espace réservé de la date-heure de la diapositive de mise en page et de tous les espaces réservés enfants de la date-heure. Les espaces réservés enfants signifient que les espaces réservés sont contenus dans les diapositives dépendantes. Les diapositives dépendantes utilisent et dépendent de la diapositive de mise en page.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte à définir. |