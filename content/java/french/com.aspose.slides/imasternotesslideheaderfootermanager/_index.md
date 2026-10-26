---
title: IMasterNotesSlideHeaderFooterManager
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente le gestionnaire qui maintient le comportement des espaces réservés du pied de page, de la date-heure et du numéro de page du diapo maître des notes ainsi que de tous les espaces réservés enfants.
type: docs
url: /fr/com.aspose.slides/imasternotesslideheaderfootermanager/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public interface IMasterNotesSlideHeaderFooterManager extends IBaseHandoutNotesSlideHeaderFooterManag
```

Représente le gestionnaire qui maintient le comportement du pied de page, de la date-heure et du numéro de page du diapo maître des notes, ainsi que de tous les espaces réservés enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus sur les diapos de notes dépendantes. Les diapos de notes dépendantes utilisent et dépendent du diapo maître des notes.
## Méthodes

| Méthode | Description |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | Changes master notes slide header placeholder and all child header placeholders visibility. |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | Sets text to master notes slide header placeholder and all child header placeholders. |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Changes master notes slide footer placeholder and all child footer placeholders visibility. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Changes master notes slide page number placeholder and all child page number placeholders visibility. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Changes master notes slide date-time placeholder and all child date-time placeholders visibility. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Sets text to master notes slide footer placeholder and all child footer placeholders. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Sets text to master notes slide date-time placeholder and all child date-time placeholders. |
### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public abstract void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

Modifie la visibilité de l'espace réservé d'en-tête du diapo maître des notes et de tous les espaces réservés d'en-tête enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus sur les diapos de notes dépendantes. Les diapos de notes dépendantes utilisent et dépendent du diapo maître des notes.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend les espaces réservés d'en-tête visibles, sinon - les masque. |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public abstract void setHeaderAndChildHeadersText(String text)
```

Définit le texte de l'espace réservé d'en-tête du diapo maître des notes et de tous les espaces réservés d'en-tête enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus sur les diapos de notes dépendantes. Les diapos de notes dépendantes utilisent et dépendent du diapo maître des notes.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte à définir. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Modifie la visibilité de l'espace réservé de pied de page du diapo maître des notes et de tous les espaces réservés de pied de page enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus sur les diapos de notes dépendantes. Les diapos de notes dépendantes utilisent et dépendent du diapo maître des notes.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend les espaces réservés de pied de page visibles, sinon - les masque. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Modifie la visibilité de l'espace réservé du numéro de page du diapo maître des notes et de tous les espaces réservés de numéro de page enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus sur les diapos de notes dépendantes. Les diapos de notes dépendantes utilisent et dépendent du diapo maître des notes.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend les espaces réservés de numéro de page visibles, sinon - les masque. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Modifie la visibilité de l'espace réservé de date-heure du diapo maître des notes et de tous les espaces réservés de date-heure enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus sur les diapos de notes dépendantes. Les diapos de notes dépendantes utilisent et dépendent du diapo maître des notes.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend les espaces réservés de date-heure visibles, sinon - les masque. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Définit le texte de l'espace réservé de pied de page du diapo maître des notes et de tous les espaces réservés de pied de page enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus sur les diapos de notes dépendantes. Les diapos de notes dépendantes utilisent et dépendent du diapo maître des notes.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte à définir. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Définit le texte de l'espace réservé de date-heure du diapo maître des notes et de tous les espaces réservés de date-heure enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus sur les diapos de notes dépendantes. Les diapos de notes dépendantes utilisent et dépendent du diapo maître des notes.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte à définir. |