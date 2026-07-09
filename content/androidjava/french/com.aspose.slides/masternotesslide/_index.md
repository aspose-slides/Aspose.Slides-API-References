---
title: MasterNotesSlide
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente la diapositive maître des notes.
type: docs
url: /fr/com.aspose.slides/masternotesslide/
---
**Héritage:**  
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)  
```
public class MasterNotesSlide extends BaseSlide implements IMasterNotesSlide
```

Représente la diapositive maître des notes.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Spécifie si les formes sur la diapositive maître doivent être affichées sur les diapositives ou non. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Spécifie si les formes sur la diapositive maître doivent être affichées sur les diapositives ou non. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Renvoie le gestionnaire HeaderFooter de la diapositive maître des notes. |
| [getThemeManager()](#getThemeManager--) | Renvoie le gestionnaire de thème. |
| [getNotesStyle()](#getNotesStyle--) | Renvoie le style d'un texte de notes. |
| [getDrawingGuides()](#getDrawingGuides--) | Renvoie une collection de guides de dessin pour la diapositive maître des notes. |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Spécifie si les formes sur la diapositive maître doivent être affichées sur les diapositives ou non. Pour la diapositive maître elle-même, cette propriété renvoie toujours false. Lecture/écriture boolean.

**Retourne :**  
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Spécifie si les formes sur la diapositive maître doivent être affichées sur les diapositives ou non. Pour la diapositive maître elle-même, cette propriété renvoie toujours false. Lecture/écriture boolean.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

Renvoie le gestionnaire HeaderFooter de la diapositive maître des notes. Lecture seule [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Retourne :**  
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)

### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Renvoie le gestionnaire de thème. Lecture seule [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Retourne :**  
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)

### getNotesStyle() {#getNotesStyle--}
```
public final ITextStyle getNotesStyle()
```

Renvoie le style d'un texte de notes. Lecture seule [ITextStyle](../../com.aspose.slides/itextstyle).

**Retourne :**  
[ITextStyle](../../com.aspose.slides/itextstyle)

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Renvoie une collection de guides de dessin pour la diapositive maître des notes. Lecture seule [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // Adding the new horizontal drawing guide below the slide center
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourne :**  
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)