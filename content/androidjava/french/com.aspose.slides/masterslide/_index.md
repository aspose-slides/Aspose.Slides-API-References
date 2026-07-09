---
title: MasterSlide
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une diapositive maîtresse dans une présentation.
type: docs
url: /fr/com.aspose.slides/masterslide/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IMasterSlide](../../com.aspose.slides/imasterslide)
```
public class MasterSlide extends BaseSlide implements IMasterSlide
```

Représente une diapositive maîtresse dans une présentation.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Renvoie le gestionnaire HeaderFooter de la diapositive maîtresse. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Crée une nouvelle diapositive maîtresse basée sur celle-ci, en appliquant un thème externe, puis applique la diapositive maîtresse créée à toutes les diapositives dépendantes. |
| [getTitleStyle()](#getTitleStyle--) | Renvoie le style d'un texte de titre. |
| [getBodyStyle()](#getBodyStyle--) | Renvoie le style d'un texte de corps. |
| [getOtherStyle()](#getOtherStyle--) | Renvoie le style d'un autre texte. |
| [getLayoutSlides()](#getLayoutSlides--) | Renvoie la collection des diapositives de mise en page enfants de cette diapositive maîtresse. |
| [getPreserve()](#getPreserve--) | Détermine si la diapositive maîtresse correspondante est supprimée lorsque toutes les diapositives qui la suivent sont supprimées. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Détermine si la diapositive maîtresse correspondante est supprimée lorsque toutes les diapositives qui la suivent sont supprimées. |
| [getDependingSlides()](#getDependingSlides--) | Renvoie un tableau contenant toutes les diapositives qui dépendent de cette diapositive maîtresse. |
| [hasDependingSlides()](#hasDependingSlides--) | Renvoie vrai s'il existe au moins une diapositive dépendant de cette diapositive maîtresse. |
| [getThemeManager()](#getThemeManager--) | Renvoie le gestionnaire de thème. |
| [getName()](#getName--) | Renvoie ou définit le nom d'une diapositive maîtresse. |
| [setName(String value)](#setName-java.lang.String-) | Renvoie ou définit le nom d'une diapositive maîtresse. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Spécifie si les formes sur la diapositive maîtresse doivent être affichées sur les diapositives ou non. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Spécifie si les formes sur la diapositive maîtresse doivent être affichées sur les diapositives ou non. |
| [getDrawingGuides()](#getDrawingGuides--) | Renvoie une collection de guides de dessin pour la diapositive maîtresse. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

Renvoie le gestionnaire HeaderFooter de la diapositive maîtresse. Lecture seule [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Retourne :**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)

### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

Crée une nouvelle diapositive maîtresse basée sur celle-ci, en appliquant un thème externe, puis applique la diapositive maîtresse créée à toutes les diapositives dépendantes.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Chemin vers le fichier de thème externe (.thmx). |

**Retourne :**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Nouvelle MasterSlide thématisée.

### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```

Renvoie le style d'un texte de titre. Lecture seule [ITextStyle](../../com.aspose.slides/itextstyle).

**Retourne :**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```

Renvoie le style d'un texte de corps. Lecture seule [ITextStyle](../../com.aspose.slides/itextstyle).

**Retourne :**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```

Renvoie le style d'un autre texte. Lecture seule [ITextStyle](../../com.aspose.slides/itextstyle).

**Retourne :**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```

Renvoie la collection des diapositives de mise en page enfants de cette diapositive maîtresse. Lecture seule [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Vous pouvez accéder à une API alternative pour ajouter/inserer/supprimer/dupliquer des diapositives de mise en page en utilisant la propriété ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Retourne :**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)

### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```

Détermine si la diapositive maîtresse correspondante est supprimée lorsque toutes les diapositives qui la suivent sont supprimées. Note : Aspose.Slides ne supprimera jamais automatiquement une maîtresse inutilisée ; pour réellement supprimer les maîtresses inutilisées, appelez [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Lecture/écriture  boolean .

**Retourne :**
boolean

### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```

Détermine si la diapositive maîtresse correspondante est supprimée lorsque toutes les diapositives qui la suivent sont supprimées. Note : Aspose.Slides ne supprimera jamais automatiquement une maîtresse inutilisée ; pour réellement supprimer les maîtresses inutilisées, appelez [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Lecture/écriture  boolean .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

Renvoie un tableau contenant toutes les diapositives qui dépendent de cette diapositive maîtresse.

**Retourne :**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)

### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

Renvoie vrai s'il existe au moins une diapositive qui dépend de cette diapositive maîtresse. Lecture seule  boolean .

**Retourne :**
boolean

### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Renvoie le gestionnaire de thème. Lecture seule [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Retourne :**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)

### getName() {#getName--}
```
public String getName()
```

Renvoie ou définit le nom d'une diapositive maîtresse. Lecture/écriture String.

**Retourne :**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Renvoie ou définit le nom d'une diapositive maîtresse. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Spécifie si les formes sur la diapositive maîtresse doivent être affichées sur les diapositives ou non. Pour la diapositive maîtresse elle-même, cette propriété renvoie toujours false. Lecture/écriture  boolean .

**Retourne :**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Spécifie si les formes sur la diapositive maîtresse doivent être affichées sur les diapositives ou non. Pour la diapositive maîtresse elle-même, cette propriété renvoie toujours false. Lecture/écriture  boolean .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Renvoie une collection de guides de dessin pour la diapositive maîtresse. Lecture seule [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Adding the new vertical drawing guide to the right of the slide center
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourne :**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)