---
title: MasterNotesSlide
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente la diapositive maîtresse pour les notes.
type: docs
url: /fr/com.aspose.slides/masternotesslide/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
```
public class MasterNotesSlide extends BaseSlide implements IMasterNotesSlide
```

Représente la diapositive maîtresse pour les notes.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Indique si les formes sur la diapositive maîtresse doivent être affichées sur les diapositives ou non. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Indique si les formes sur la diapositive maîtresse doivent être affichées sur les diapositives ou non. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Renvoie le gestionnaire HeaderFooter de la diapositive maîtresse de notes. |
| [getThemeManager()](#getThemeManager--) | Renvoie le gestionnaire de thème. |
| [getNotesStyle()](#getNotesStyle--) | Renvoie le style d'un texte de notes. |
| [getDrawingGuides()](#getDrawingGuides--) | Renvoie une collection de repères de dessin pour la diapositive maîtresse de notes. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Indique si les formes sur la diapositive maîtresse doivent être affichées sur les diapositives ou non. Pour la diapositive maîtresse elle-même, cette propriété renvoie toujours false. Lecture/écriture boolean.

**Renvoie :**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Indique si les formes sur la diapositive maîtresse doivent être affichées sur les diapositives ou non. Pour la diapositive maîtresse elle-même, cette propriété renvoie toujours false. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

Renvoie le gestionnaire HeaderFooter de la diapositive maîtresse de notes. Lecture seule [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Renvoie :**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Renvoie le gestionnaire de thème. Lecture seule [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Renvoie :**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getNotesStyle() {#getNotesStyle--}
```
public final ITextStyle getNotesStyle()
```

Renvoie le style d'un texte de notes. Lecture seule [ITextStyle](../../com.aspose.slides/itextstyle).

**Renvoie :**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Renvoie une collection de repères de dessin pour la diapositive maîtresse de notes. Lecture seule [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // Ajout du nouveau guide de dessin horizontal sous le centre de la diapositive
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Renvoie :**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)