---
title: IMasterSlide
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente une diapositive maître dans une présentation.
type: docs
url: /fr/com.aspose.slides/imasterslide/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

Représente une diapositive maître dans une présentation.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Renvoie le gestionnaire HeaderFooter de la diapositive maîtresse. |
| [getTitleStyle()](#getTitleStyle--) | Renvoie le style d'un texte de titre. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Crée une nouvelle diapositive maîtresse basée sur celle-ci, applique un thème externe et applique la diapositive maîtresse créée à toutes les diapositives dépendantes. |
| [getBodyStyle()](#getBodyStyle--) | Renvoie le style d'un texte de corps. |
| [getOtherStyle()](#getOtherStyle--) | Renvoie le style d'un autre texte. |
| [getLayoutSlides()](#getLayoutSlides--) | Renvoie la collection de diapositives de mise en page enfants pour cette diapositive maîtresse. |
| [getPreserve()](#getPreserve--) | Détermine si le maître correspondant est supprimé lorsque toutes les diapositives qui le suivent sont supprimées. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Détermine si le maître correspondant est supprimé lorsque toutes les diapositives qui le suivent sont supprimées. |
| [hasDependingSlides()](#hasDependingSlides--) | Renvoie true si au moins une diapositive dépend de cette diapositive maîtresse. |
| [getDependingSlides()](#getDependingSlides--) | Renvoie un tableau contenant toutes les diapositives qui dépendent de cette diapositive maîtresse. |
| [getDrawingGuides()](#getDrawingGuides--) | Renvoie une collection de guides de dessin pour la diapositive maîtresse. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```


Renvoie le gestionnaire HeaderFooter de la diapositive maîtresse. Lecture seule [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Retour :**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### getTitleStyle() {#getTitleStyle--}
```
public abstract ITextStyle getTitleStyle()
```


Renvoie le style d'un texte de titre. Lecture seule [ITextStyle](../../com.aspose.slides/itextstyle).

**Retour :**
[ITextStyle](../../com.aspose.slides/itextstyle)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public abstract IMasterSlide applyExternalThemeToDependingSlides(String fname)
```


Crée une nouvelle diapositive maîtresse basée sur celle-ci, applique un thème externe et applique la diapositive maîtresse créée à toutes les diapositives dépendantes.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Chemin du fichier de thème externe (.thmx). |

**Retour :**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Nouveau MasterSlide thématisé.
### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```


Renvoie le style d'un texte de corps. Lecture seule [ITextStyle](../../com.aspose.slides/itextstyle).

**Retour :**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public abstract ITextStyle getOtherStyle()
```


Renvoie le style d'un autre texte. Lecture seule [ITextStyle](../../com.aspose.slides/itextstyle).

**Retour :**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```


Renvoie la collection de diapositives de mise en page enfants pour cette diapositive maîtresse. Lecture seule [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Vous pouvez accéder à l'API alternative pour ajouter/insérer/supprimer/dupliquer des diapositives de mise en page en utilisant la propriété ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Retour :**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```


Détermine si le maître correspondant est supprimé lorsque toutes les diapositives qui le suivent sont supprimées. Remarque : Aspose.Slides ne supprimera jamais automatiquement un maître inutilisé ; pour réellement supprimer les maîtres inutilisés, appelez [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) Lecture/écriture booléen.

**Retour :**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```


Détermine si le maître correspondant est supprimé lorsque toutes les diapositives qui le suivent sont supprimées. Remarque : Aspose.Slides ne supprimera jamais automatiquement un maître inutilisé ; pour réellement supprimer les maîtres inutilisés, appelez [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```


Renvoie true si au moins une diapositive dépend de cette diapositive maîtresse. Lecture seule booléen.

**Retour :**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```


Renvoie un tableau contenant toutes les diapositives qui dépendent de cette diapositive maîtresse.

**Retour :**
com.aspose.slides.ISlide[] - Tableau de [ISlide](../../com.aspose.slides/islide), qui dépendent de cette diapositive maîtresse
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Renvoie une collection de guides de dessin pour la diapositive maîtresse. Lecture seule [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

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

**Retour :**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)