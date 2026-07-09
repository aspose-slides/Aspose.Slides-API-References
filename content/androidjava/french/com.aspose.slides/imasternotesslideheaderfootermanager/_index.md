---
title: IMasterNotesSlideHeaderFooterManager
second_title: Référence API Java d'Aspose.Slides pour Android
description: Représente le gestionnaire qui contrôle le comportement des espaces réservés du pied de page, de la date-heure et du numéro de diapositive de la diapositive de notes maître ainsi que de tous les espaces réservés enfants.
type: docs
url: /fr/com.aspose.slides/imasternotesslideheaderfootermanager/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public interface IMasterNotesSlideHeaderFooterManager extends IBaseHandoutNotesSlideHeaderFooterManag
```

Représente le gestionnaire qui contrôle le comportement des espaces réservés du pied de page, de la date-heure et du numéro de diapositive de la diapositive de notes maître ainsi que de tous les espaces réservés enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus dans les diapositives de notes dépendantes. Les diapositives de notes dépendantes utilisent et dépendent de la diapositive de notes maître.

## Méthodes

| Méthode | Description |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | Modifie la visibilité de l'espace réservé d'en-tête de la diapositive de notes maître et de tous les espaces réservés d'en-tête enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus dans les diapositives de notes dépendantes. Les diapositives de notes dépendantes utilisent et dépendent de la diapositive de notes maître. |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | Définit le texte de l'espace réservé d'en-tête de la diapositive de notes maître et de tous les espaces réservés d'en-tête enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus dans les diapositives de notes dépendantes. Les diapositives de notes dépendantes utilisent et dépendent de la diapositive de notes maître. |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Modifie la visibilité de l'espace réservé du pied de page de la diapositive de notes maître et de tous les espaces réservés du pied de page enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus dans les diapositives de notes dépendantes. Les diapositives de notes dépendantes utilisent et dépendent de la diapositive de notes maître. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Modifie la visibilité de l'espace réservé du numéro de diapositive de la diapositive de notes maître et de tous les espaces réservés de numéro de diapositive enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus dans les diapositives de notes dépendantes. Les diapositives de notes dépendantes utilisent et dépendent de la diapositive de notes maître. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Modifie la visibilité de l'espace réservé de la date-heure de la diapositive de notes maître et de tous les espaces réservés de date-heure enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus dans les diapositives de notes dépendantes. Les diapositives de notes dépendantes utilisent et dépendent de la diapositive de notes maître. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Définit le texte de l'espace réservé du pied de page de la diapositive de notes maître et de tous les espaces réservés du pied de page enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus dans les diapositives de notes dépendantes. Les diapositives de notes dépendantes utilisent et dépendent de la diapositive de notes maître. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Définit le texte de l'espace réservé de la date-heure de la diapositive de notes maître et de tous les espaces réservés de date-heure enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus dans les diapositives de notes dépendantes. Les diapositives de notes dépendantes utilisent et dépendent de la diapositive de notes maître. |

### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public abstract void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

Modifie la visibilité de l'espace réservé d'en-tête de la diapositive de notes maître et de tous les espaces réservés d'en-tête enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus dans les diapositives de notes dépendantes. Les diapositives de notes dépendantes utilisent et dépendent de la diapositive de notes maître.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend les espaces réservés d'en-tête visibles, sinon - les masque. |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public abstract void setHeaderAndChildHeadersText(String text)
```

Définit le texte de l'espace réservé d'en-tête de la diapositive de notes maître et de tous les espaces réservés d'en-tête enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus dans les diapositives de notes dépendantes. Les diapositives de notes dépendantes utilisent et dépendent de la diapositive de notes maître.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte à définir. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Modifie la visibilité de l'espace réservé du pied de page de la diapositive de notes maître et de tous les espaces réservés du pied de page enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus dans les diapositives de notes dépendantes. Les diapositives de notes dépendantes utilisent et dépendent de la diapositive de notes maître.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend les espaces réservés du pied de page visibles, sinon - les masque. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Modifie la visibilité de l'espace réservé du numéro de diapositive de la diapositive de notes maître et de tous les espaces réservés de numéro de diapositive enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus dans les diapositives de notes dépendantes. Les diapositives de notes dépendantes utilisent et dépendent de la diapositive de notes maître.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend les espaces réservés de numéro de diapositive visibles, sinon - les masque. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Modifie la visibilité de l'espace réservé de la date-heure de la diapositive de notes maître et de tous les espaces réservés de date-heure enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus dans les diapositives de notes dépendantes. Les diapositives de notes dépendantes utilisent et dépendent de la diapositive de notes maître.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend les espaces réservés de date-heure visibles, sinon - les masque. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Définit le texte de l'espace réservé du pied de page de la diapositive de notes maître et de tous les espaces réservés du pied de page enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus dans les diapositives de notes dépendantes. Les diapositives de notes dépendantes utilisent et dépendent de la diapositive de notes maître.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte à définir. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Définit le texte de l'espace réservé de la date-heure de la diapositive de notes maître et de tous les espaces réservés de date-heure enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus dans les diapositives de notes dépendantes. Les diapositives de notes dépendantes utilisent et dépendent de la diapositive de notes maître.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte à définir. |