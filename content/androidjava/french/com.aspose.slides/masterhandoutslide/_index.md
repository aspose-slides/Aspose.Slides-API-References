---
title: MasterHandoutSlide
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente la diapositive maître pour les documents d'accompagnement.
type: docs
url: /fr/com.aspose.slides/masterhandoutslide/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
```
public class MasterHandoutSlide extends BaseSlide implements IMasterHandoutSlide
```

Représente la diapositive maître pour les documents d'accompagnement.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Spécifie si les formes sur la diapositive maître doivent être affichées sur les diapositives ou non. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Spécifie si les formes sur la diapositive maître doivent être affichées sur les diapositives ou non. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Renvoie le gestionnaire HeaderFooter de la diapositive maître d'annexe. |
| [getThemeManager()](#getThemeManager--) | Renvoie le gestionnaire de thème. |
| [getDrawingGuides()](#getDrawingGuides--) | Renvoie une collection de guides de dessin pour la diapositive maître d'annexe. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Spécifie si les formes sur la diapositive maître doivent être affichées sur les diapositives ou non. Pour la diapositive maître elle-même, cette propriété renvoie toujours false. Lecture/écriture booléen.

**Renvoie :**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Spécifie si les formes sur la diapositive maître doivent être affichées sur les diapositives ou non. Pour la diapositive maître elle-même, cette propriété renvoie toujours false. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```

Renvoie le gestionnaire HeaderFooter de la diapositive maître d'annexe. Lecture seule [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Renvoie :**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Renvoie le gestionnaire de thème. Lecture seule [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Renvoie :**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Renvoie une collection de guides de dessin pour la diapositive maître d'annexe. Lecture seule [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // Adding the new horizontal drawing guide above the slide center
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Renvoie :**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)