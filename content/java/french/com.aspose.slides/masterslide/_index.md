---
title: MasterSlide
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente une diapositive maître dans une présentation.
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

Représente une diapositive maître dans une présentation.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Renvoie le gestionnaire HeaderFooter de la diapositive maître. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Crée une nouvelle diapositive maître basée sur celle actuelle, applique un thème externe et applique la diapositive maître créée à toutes les diapositives dépendantes. |
| [getTitleStyle()](#getTitleStyle--) | Renvoie le style d'un texte de titre. |
| [getBodyStyle()](#getBodyStyle--) | Renvoie le style d'un texte de corps. |
| [getOtherStyle()](#getOtherStyle--) | Renvoie le style d'un autre texte. |
| [getLayoutSlides()](#getLayoutSlides--) | Renvoie la collection de diapositives de mise en page enfant pour cette diapositive maître. |
| [getPreserve()](#getPreserve--) | Détermine si le maître correspondant est supprimé lorsque toutes les diapositives qui suivent ce maître sont supprimées. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Détermine si le maître correspondant est supprimé lorsque toutes les diapositives qui suivent ce maître sont supprimées. |
| [getDependingSlides()](#getDependingSlides--) | Renvoie un tableau contenant toutes les diapositives qui dépendent de cette diapositive maître. |
| [hasDependingSlides()](#hasDependingSlides--) | Renvoie true s'il existe au moins une diapositive qui dépend de cette diapositive maître. |
| [getThemeManager()](#getThemeManager--) | Renvoie le gestionnaire de thème. |
| [getName()](#getName--) | Renvoie ou définit le nom d'une diapositive maître. |
| [setName(String value)](#setName-java.lang.String-) | Renvoie ou définit le nom d'une diapositive maître. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Spécifie si les formes sur la diapositive maître doivent être affichées sur les diapositives ou non. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Spécifie si les formes sur la diapositive maître doivent être affichées sur les diapositives ou non. |
| [getDrawingGuides()](#getDrawingGuides--) | Renvoie une collection de guides de dessin pour la diapositive maître. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

Renvoie le gestionnaire HeaderFooter de la diapositive maître. Lecture seule [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Renvoie :**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

Crée une nouvelle diapositive maître basée sur celle actuelle, applique un thème externe et applique la diapositive maître créée à toutes les diapositives dépendantes.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Chemin du fichier de thème externe (.thmx). |

**Renvoie :**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Nouvelle MasterSlide thématisée.
### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```

Renvoie le style d'un texte de titre. Lecture seule [ITextStyle](../../com.aspose.slides/itextstyle).

**Renvoie :**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```

Renvoie le style d'un texte de corps. Lecture seule [ITextStyle](../../com.aspose.slides/itextstyle).

**Renvoie :**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```

Renvoie le style d'un autre texte. Lecture seule [ITextStyle](../../com.aspose.slides/itextstyle).

**Renvoie :**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```

Renvoie la collection de diapositives de mise en page enfant pour cette diapositive maître. Lecture seule [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Vous pouvez accéder à une API alternative pour ajouter/insérer/supprimer/dupliquer des diapositives de mise en page en utilisant la propriété ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Renvoie :**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```

Détermine si le maître correspondant est supprimé lorsque toutes les diapositives qui suivent ce maître sont supprimées. Remarque : Aspose.Slides ne supprimera jamais aucun maître inutilisé par lui-même ; pour réellement supprimer les maîtres inutilisés, appelez [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Lecture/écriture  boolean .

**Renvoie :**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```

Détermine si le maître correspondant est supprimé lorsque toutes les diapositives qui suivent ce maître sont supprimées. Remarque : Aspose.Slides ne supprimera jamais aucun maître inutilisé par lui-même ; pour réellement supprimer les maîtres inutilisés, appelez [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Lecture/écriture  boolean .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

Renvoie un tableau contenant toutes les diapositives qui dépendent de cette diapositive maître.

**Renvoie :**
com.aspose.slides.ISlide[] - Tableau de [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

Renvoie true s'il existe au moins une diapositive qui dépend de cette diapositive maître. Lecture seule  boolean .

**Renvoie :**
boolean
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Renvoie le gestionnaire de thème. Lecture seule [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Renvoie :**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getName() {#getName--}
```
public String getName()
```

Renvoie ou définit le nom d'une diapositive maître. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Renvoie ou définit le nom d'une diapositive maître. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Spécifie si les formes sur la diapositive maître doivent être affichées sur les diapositives ou non. Pour la diapositive maître elle-même, cette propriété renvoie toujours false. Lecture/écriture  boolean .

**Renvoie :**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Spécifie si les formes sur la diapositive maître doivent être affichées sur les diapositives ou non. Pour la diapositive maître elle-même, cette propriété renvoie toujours false. Lecture/écriture  boolean .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Renvoie une collection de guides de dessin pour la diapositive maître. Lecture seule [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Ajout du nouveau guide de dessin vertical à droite du centre de la diapositive
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Renvoie :**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)