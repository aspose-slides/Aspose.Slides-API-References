---
title: IPresentationHeaderFooterManager
second_title: Référence API Aspose.Slides pour Android via Java
description: Représente le gestionnaire qui conserve le comportement de tous les espaces réservés aux pieds de page, aux dates-heures et aux numéros de page de la présentation.
type: docs
url: /fr/com.aspose.slides/ipresentationheaderfootermanager/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

Représente le gestionnaire qui conserve le comportement de tous les espaces réservés aux pieds de page, aux dates-heures et aux numéros de page de la présentation.

## Méthodes

| Méthode | Description |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | Modifie la visibilité de tous les espaces réservés d’en-tête, y compris le maître des notes, les diapositives de notes et le maître du fascicule. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | Modifie la visibilité de tous les espaces réservés de pied de page, y compris les diapositives maîtres, les diapositives de mise en page et les diapositives. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | Modifie la visibilité de tous les espaces réservés de numéro de page, y compris les diapositives maîtres, les diapositives de mise en page et les diapositives. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | Modifie la visibilité de tous les espaces réservés de date-heure, y compris les diapositives maîtres, les diapositives de mise en page et les diapositives. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | Définit le texte de tous les espaces réservés d’en-tête, y compris le maître des notes, les diapositives de notes et le maître du fascicule. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | Définit le texte de tous les espaces réservés de pied de page, y compris les diapositives maîtres, les diapositives de mise en page et les diapositives. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | Définit le texte de tous les espaces réservés de date-heure, y compris les diapositives maîtres, les diapositives de mise en page et les diapositives. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | Modifie la visibilité des espaces réservés de pied de page, de date-heure et de numéro de page pour toutes les diapositives de titre et pour la première diapositive de mise en page. |
### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

Modifie la visibilité de tous les espaces réservés d’en-tête, y compris le maître des notes, les diapositives de notes et le maître du fascicule.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend les espaces réservés d’en-tête visibles, sinon - les masque. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

Modifie la visibilité de tous les espaces réservés de pied de page, y compris les diapositives maîtres, les diapositives de mise en page et les diapositives.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend les espaces réservés de pied de page visibles, sinon - les masque. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

Modifie la visibilité de tous les espaces réservés de numéro de page, y compris les diapositives maîtres, les diapositives de mise en page et les diapositives.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend les espaces réservés de numéro de page visibles, sinon - les masque. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

Modifie la visibilité de tous les espaces réservés de date-heure, y compris les diapositives maîtres, les diapositives de mise en page et les diapositives.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend les espaces réservés de date-heure visibles, sinon - les masque. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

Définit le texte de tous les espaces réservés d’en-tête, y compris le maître des notes, les diapositives de notes et le maître du fascicule.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte à définir. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

Définit le texte de tous les espaces réservés de pied de page, y compris les diapositives maîtres, les diapositives de mise en page et les diapositives.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte à définir. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

Définit le texte de tous les espaces réservés de date-heure, y compris les diapositives maîtres, les diapositives de mise en page et les diapositives.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte à définir. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

Modifie la visibilité des espaces réservés de pied de page, de date-heure et de numéro de page pour toutes les diapositives de titre et pour la première diapositive de mise en page. Les diapositives de titre - diapositives basées sur la première mise en page (indépendamment du type de cette première mise en page).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true - rend les espaces réservés visibles, sinon - les masque. |