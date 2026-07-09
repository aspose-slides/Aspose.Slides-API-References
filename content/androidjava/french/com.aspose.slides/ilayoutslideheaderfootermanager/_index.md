---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente le gestionnaire qui conserve le comportement des espaces réservés du pied de page, de la date-heure, du numéro de page de la diapositive de mise en page et de tous les espaces réservés enfants.
type: docs
url: /fr/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Représente le gestionnaire qui possède le comportement des espaces réservés du pied de page, de la date-heure et du numéro de page de la diapositive de mise en page, ainsi que de tous les espaces réservés enfants. Les espaces réservés enfants désignent les espaces réservés contenus dans les diapositives dépendantes. Les diapositives dépendantes utilisent et dépendent de la diapositive de mise en page.
## Méthodes

| Méthode | Description |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Modifie la visibilité de l’espace réservé du pied de page de la diapositive de mise en page et de tous les espaces réservés pieds de page enfants. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Modifie la visibilité de l’espace réservé du numéro de page de la diapositive de mise en page et de tous les espaces réservés numéros de page enfants. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Modifie la visibilité de l’espace réservé de la date-heure de la diapositive de mise en page et de tous les espaces réservés date-heure enfants. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Définit le texte de l’espace réservé du pied de page de la diapositive de mise en page et de tous les espaces réservés pieds de page enfants. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Définit le texte de l’espace réservé de la date-heure de la diapositive de mise en page et de tous les espaces réservés date-heure enfants. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Modifie la visibilité de l’espace réservé du pied de page de la diapositive de mise en page et de tous les espaces réservés pieds de page enfants. Les espaces réservés enfants désignent les espaces réservés contenus dans les diapositives dépendantes. Les diapositives dépendantes utilisent et dépendent de la diapositive maître.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend l’espace réservé du pied de page visible, sinon - le masque. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Modifie la visibilité de l’espace réservé du numéro de page de la diapositive de mise en page et de tous les espaces réservés numéros de page enfants. Les espaces réservés enfants désignent les espaces réservés contenus dans les diapositives dépendantes. Les diapositives dépendantes utilisent et dépendent de la diapositive de mise en page.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend les espaces réservés du numéro de page visibles, sinon - les masque. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Modifie la visibilité de l’espace réservé de la date-heure de la diapositive de mise en page et de tous les espaces réservés date-heure enfants. Les espaces réservés enfants désignent les espaces réservés contenus dans les diapositives dépendantes. Les diapositives dépendantes utilisent et dépendent de la diapositive de mise en page.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend les espaces réservés de date-heure visibles, sinon - les masque. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Définit le texte de l’espace réservé du pied de page de la diapositive de mise en page et de tous les espaces réservés pieds de page enfants. Les espaces réservés enfants désignent les espaces réservés contenus dans les diapositives dépendantes. Les diapositives dépendantes utilisent et dépendent de la diapositive de mise en page.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte à définir. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Définit le texte de l’espace réservé de la date-heure de la diapositive de mise en page et de tous les espaces réservés date-heure enfants. Les espaces réservés enfants désignent les espaces réservés contenus dans les diapositives dépendantes. Les diapositives dépendantes utilisent et dépendent de la diapositive de mise en page.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte à définir. |