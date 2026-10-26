---
title: MasterSlideHeaderFooterManager
second_title: Référence de l'API Aspose.Slides pour Android via Java
description: Représente le gestionnaire qui maintient le comportement des espaces réservés du pied de page, de la date-heure et du numéro de page de la diapositive maître ainsi que tous les espaces réservés enfants.
type: docs
url: /fr/com.aspose.slides/masterslideheaderfootermanager/
---
**Héritage:**  
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)  
```
public final class MasterSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IMasterSlideHeaderFooterManager
```

Représente le gestionnaire qui conserve le comportement des espaces réservés du pied de page, de la date-heure et du numéro de page de la diapositive maître ainsi que tous les espaces réservés enfants. Les espaces réservés enfants sont des espaces réservés contenus dans les diapositives de mise en page dépendantes et les diapositives dépendantes. Les diapositives de mise en page dépendantes et les diapositives utilisent et dépendent de la diapositive maître.

## Méthodes

| Méthode | Description |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Modifie la visibilité du placeholder du pied de page de la diapositive maître et de tous les placeholders du pied de page enfants. Les placeholders enfants sont des placeholders contenus sur les diapositives de mise en page dépendantes et les diapositives dépendantes. Les diapositives de mise en page dépendantes et les diapositives utilisent et dépendent de la diapositive maître. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Modifie la visibilité du placeholder du numéro de page de la diapositive maître et de tous les placeholders du numéro de page enfants. Les placeholders enfants sont des placeholders contenus sur les diapositives de mise en page dépendantes et les diapositives dépendantes. Les diapositives de mise en page dépendantes et les diapositives utilisent et dépendent de la diapositive maître. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Modifie la visibilité du placeholder de date-heure de la diapositive maître et de tous les placeholders de date-heure enfants. Les placeholders enfants sont des placeholders contenus sur les diapositives de mise en page dépendantes et les diapositives dépendantes. Les diapositives de mise en page dépendantes et les diapositives utilisent et dépendent de la diapositive maître. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Définit le texte du placeholder du pied de page de la diapositive maître et de tous les placeholders du pied de page enfants. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Définit le texte du placeholder de date-heure de la diapositive maître et de tous les placeholders de date-heure enfants. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

Modifie la visibilité du placeholder du pied de page de la diapositive maître et de tous les placeholders du pied de page enfants. Les placeholders enfants sont des placeholders contenus sur les diapositives de mise en page dépendantes et les diapositives dépendantes. Les diapositives de mise en page dépendantes et les diapositives utilisent et dépendent de la diapositive maître.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend les placeholders du pied de page visibles, sinon - les masque. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Modifie la visibilité du placeholder du numéro de page de la diapositive maître et de tous les placeholders du numéro de page enfants. Les placeholders enfants sont des placeholders contenus sur les diapositives de mise en page dépendantes et les diapositives dépendantes. Les diapositives de mise en page dépendantes et les diapositives utilisent et dépendent de la diapositive maître.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend les placeholders du numéro de page visibles, sinon - les masque. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Modifie la visibilité du placeholder de date-heure de la diapositive maître et de tous les placeholders de date-heure enfants. Les placeholders enfants sont des placeholders contenus sur les diapositives de mise en page dépendantes et les diapositives dépendantes. Les diapositives de mise en page dépendantes et les diapositives utilisent et dépendent de la diapositive maître.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend les placeholders de date-heure visibles, sinon - les masque. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

Définit le texte du placeholder du pied de page de la diapositive maître et de tous les placeholders du pied de page enfants. Les placeholders enfants sont des placeholders contenus sur les diapositives de mise en page dépendantes et les diapositives dépendantes. Les diapositives de mise en page dépendantes et les diapositives utilisent et dépendent de la diapositive maître.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte à définir. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

Définit le texte du placeholder de date-heure de la diapositive maître et de tous les placeholders de date-heure enfants. Les placeholders enfants sont des placeholders contenus sur les diapositives de mise en page dépendantes et les diapositives dépendantes. Les diapositives de mise en page dépendantes et les diapositives utilisent et dépendent de la diapositive maître.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte à définir. |