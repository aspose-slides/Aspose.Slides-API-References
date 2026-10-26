---
title: IShape
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente une forme sur une diapositive.
type: docs
url: /fr/com.aspose.slides/ishape/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IShape extends ISlideComponent, IHyperlinkContainer
```

Représente une forme sur une diapositive.
## Méthodes

| Méthode | Description |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Détermine si la forme est TextHolder. |
| [getPlaceholder()](#getPlaceholder--) | Renvoie le placeholder pour une forme. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Ajoute un nouveau placeholder s'il n'existe pas et définit les propriétés du placeholder sur celui spécifié. |
| [removePlaceholder()](#removePlaceholder--) | Définit que cette forme n'est pas un placeholder. |
| [getCustomData()](#getCustomData--) | Renvoie les données personnalisées de la forme. |
| [getRawFrame()](#getRawFrame--) | Renvoie ou définit les propriétés du cadre brut de la forme. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Renvoie ou définit les propriétés du cadre brut de la forme. |
| [getFrame()](#getFrame--) | Renvoie ou définit les propriétés du cadre de la forme. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Renvoie ou définit les propriétés du cadre de la forme. |
| [getLineFormat()](#getLineFormat--) | Renvoie l'objet LineFormat qui contient les propriétés de formatage de ligne pour une forme. |
| [getThreeDFormat()](#getThreeDFormat--) | Renvoie l'objet ThreeDFormat qui contient les propriétés de formatage de ligne pour une forme. |
| [getEffectFormat()](#getEffectFormat--) | Renvoie l'objet EffectFormat qui contient les effets pixélisés appliqués à une forme. |
| [getFillFormat()](#getFillFormat--) | Renvoie l'objet FillFormat qui contient les propriétés de formatage de remplissage pour une forme. |
| [getImage()](#getImage--) | Renvoie la miniature de la forme. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Renvoie la miniature de la forme. |
| [getHidden()](#getHidden--) | Détermine si la forme est masquée. |
| [setHidden(boolean value)](#setHidden-boolean-) | Détermine si la forme est masquée. |
| [getZOrderPosition()](#getZOrderPosition--) | Renvoie la position d'une forme dans l'ordre Z. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Renvoie le nombre de points de connexion sur la forme. |
| [getRotation()](#getRotation--) | Renvoie ou définit le nombre de degrés de rotation de la forme spécifiée autour de l'axe Z. |
| [setRotation(float value)](#setRotation-float-) | Renvoie ou définit le nombre de degrés de rotation de la forme spécifiée autour de l'axe Z. |
| [getX()](#getX--) | Obtient ou définit la coordonnée x du coin supérieur gauche de la forme, mesurée en points. |
| [setX(float value)](#setX-float-) | Obtient ou définit la coordonnée x du coin supérieur gauche de la forme, mesurée en points. |
| [getY()](#getY--) | Obtient ou définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points. |
| [setY(float value)](#setY-float-) | Obtient ou définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points. |
| [getWidth()](#getWidth--) | Obtient ou définit la largeur de la forme, mesurée en points. |
| [setWidth(float value)](#setWidth-float-) | Obtient ou définit la largeur de la forme, mesurée en points. |
| [getHeight()](#getHeight--) | Obtient ou définit la hauteur de la forme, mesurée en points. |
| [setHeight(float value)](#setHeight-float-) | Obtient ou définit la hauteur de la forme, mesurée en points. |
| [getAlternativeText()](#getAlternativeText--) | Renvoie ou définit le texte alternatif associé à une forme. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Renvoie ou définit le texte alternatif associé à une forme. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Renvoie ou définit le titre du texte alternatif associé à une forme. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Renvoie ou définit le titre du texte alternatif associé à une forme. |
| [getName()](#getName--) | Renvoie ou définit le nom d'une forme. |
| [setName(String value)](#setName-java.lang.String-) | Renvoie ou définit le nom d'une forme. |
| [isDecorative()](#isDecorative--) | Obtient ou définit l'option 'Marquer comme décoratif' booléen lecture/écriture. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Obtient ou définit l'option 'Marquer comme décoratif' booléen lecture/écriture. |
| [getShapeLock()](#getShapeLock--) | Renvoie les verrous de la forme. |
| [getUniqueId()](#getUniqueId--) | Renvoie un identifiant interne à portée de la présentation destiné à être utilisé par les modules complémentaires ou autre code. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Renvoie un identifiant unique à portée de la diapositive qui reste constant pendant la durée de vie de la forme et permet à PowerPoint ou au code d'interopérabilité de référencer solidement la forme depuis n'importe où dans le document. |
| [isGrouped()](#isGrouped--) | Détermine si la forme est groupée. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | La propriété spécifie comment une forme sera rendue en mode d'affichage noir et blanc. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | La propriété spécifie comment une forme sera rendue en mode d'affichage noir et blanc. |
| [getParentGroup()](#getParentGroup--) | Renvoie l'objet GroupShape parent si la forme est groupée. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Enregistre le contenu de Shape en tant que fichier SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Enregistre le contenu de Shape en tant que fichier SVG. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Renvoie une forme placeholder de base (forme provenant de la disposition et/ou de la diapositive maître dont la forme actuelle hérite). |

### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```


Détermine si la forme est TextHolder. Booléen en lecture seule.

**Renvoie :**
boolean
### getPlaceholder() {#getPlaceholder--}
```
public abstract IPlaceholder getPlaceholder()
```


Renvoie le placeholder pour une forme. Lecture seule [IPlaceholder](../../com.aspose.slides/iplaceholder).

**Renvoie :**
[IPlaceholder](../../com.aspose.slides/iplaceholder)
### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public abstract IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```


Ajoute un nouveau placeholder s'il n'existe pas et définit les propriétés du placeholder sur celui spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Placeholder dont le contenu doit être copié. |

**Renvoie :**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - Nouveau [IPlaceholder](../../com.aspose.slides/iplaceholder).
### removePlaceholder() {#removePlaceholder--}
```
public abstract void removePlaceholder()
```


Définit que cette forme n'est pas un placeholder.

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```


Renvoie les données personnalisées de la forme. Lecture seule [ICustomData](../../com.aspose.slides/icustomdata).

**Renvoie :**
[ICustomData](../../com.aspose.slides/icustomdata)
### getRawFrame() {#getRawFrame--}
```
public abstract IShapeFrame getRawFrame()
```


Renvoie ou définit les propriétés du cadre brut de la forme. Lecture/écriture [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //ou
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Ce code peut entraîner des situations ambiguës. Ainsi, des restrictions ont été ajoutées pour l'utilisation de valeurs indéfinies avec IShape.getFrame(). Les valeurs de x, y, width, height, flipH, flipV et rotationAngle doivent être définies (pas Float.NaN ou NullableBool.NotDefined). Le code d'exemple ci-dessus lève maintenant une exception ArgumentException.
>  //Cela s'applique à ces cas d'utilisation :
>  IShape shape = ...;
>  shape.setFrame(...); // ne peut pas être indéfini
>  IShapeCollection shapes = ...;
>  // les paramètres x, y, width, height ne peuvent pas être Float.NaN :
>  {
>      shapes.addAudioFrameCD(...);
>      shapes.addAudioFrameEmbedded(...);
>      shapes.addAudioFrameLinked(...);
>      shapes.addAutoShape(...);
>      shapes.addChart(...);
>      shapes.addConnector(...);
>      shapes.addOleObjectFrame(...);
>      shapes.addPictureFrame(...);
>      shapes.addSmartArt(...);
>      shapes.addTable(...);
>      shapes.addVideoFrame(...);
>      shapes.insertAudioFrameEmbedded(...);
>      shapes.insertAudioFrameLinked(...);
>      shapes.insertAutoShape(...);
>      shapes.insertChart(...);
>      shapes.insertConnector(...);
>      shapes.insertOleObjectFrame(...);
>      shapes.insertPictureFrame(...);
>      shapes.insertTable(...);
>      shapes.insertVideoFrame(...);
>  }
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // la forme est liée à un placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // maintenant la forme hérite des valeurs x, y, height, flipH, flipV du placeholder et remplace width=100 et rotationAngle=0.
```

**Renvoie :**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
```


Renvoie ou définit les propriétés du cadre brut de la forme. Lecture/écriture [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //ou
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Ce type de code peut entraîner des situations ambiguës. Ainsi, des restrictions ont été ajoutées pour l'utilisation de valeurs indéfinies avec IShape.getFrame(). Les valeurs de x, y, width, height, flipH, flipV et rotationAngle doivent être définies (pas Float.NaN ou NullableBool.NotDefined). Le code d'exemple ci-dessus lève maintenant une exception ArgumentException.
>  //Cela s'applique à ces cas d'utilisation :
>  IShape shape = ...;
>  shape.setFrame(...); // ne peut pas être indéfini
>  IShapeCollection shapes = ...;
>  // les paramètres x, y, width, height ne peuvent pas être Float.NaN :
>  {
>      shapes.addAudioFrameCD(...);
>      shapes.addAudioFrameEmbedded(...);
>      shapes.addAudioFrameLinked(...);
>      shapes.addAutoShape(...);
>      shapes.addChart(...);
>      shapes.addConnector(...);
>      shapes.addOleObjectFrame(...);
>      shapes.addPictureFrame(...);
>      shapes.addSmartArt(...);
>      shapes.addTable(...);
>      shapes.addVideoFrame(...);
>      shapes.insertAudioFrameEmbedded(...);
>      shapes.insertAudioFrameLinked(...);
>      shapes.insertAutoShape(...);
>      shapes.insertChart(...);
>      shapes.insertConnector(...);
>      shapes.insertOleObjectFrame(...);
>      shapes.insertPictureFrame(...);
>      shapes.insertTable(...);
>      shapes.insertVideoFrame(...);
>  }
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // la forme est liée à un placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // maintenant la forme hérite des valeurs x, y, height, flipH, flipV du placeholder et remplace width=100 et rotationAngle=0.
```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```


Renvoie ou définit les propriétés du cadre de la forme. Lecture/écriture [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

La valeur de chaque propriété de l'instance IShapeFrame retournée n'est pas indéfinie (n'est pas NaN ou NotDefined). La valeur de chaque propriété de l'instance IShapeFrame assignée doit être définie (ne doit pas être NaN ou NotDefined). Vous pouvez affecter des valeurs indéfinies aux propriétés d'une instance RawFrame.

**Renvoie :**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```


Renvoie ou définit les propriétés du cadre de la forme. Lecture/écriture [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

La valeur de chaque propriété de l'instance IShapeFrame retournée n'est pas indéfinie (n'est pas NaN ou NotDefined). La valeur de chaque propriété de l'instance IShapeFrame assignée doit être définie (ne doit pas être NaN ou NotDefined). Vous pouvez affecter des valeurs indéfinies aux propriétés d'une instance RawFrame.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```


Renvoie l'objet LineFormat qui contient les propriétés de formatage de ligne pour une forme. Lecture seule [ILineFormat](../../com.aspose.slides/ilineformat).

**Renvoie :**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```


Renvoie l'objet ThreeDFormat qui contient les propriétés de formatage de ligne pour une forme. Lecture seule [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Renvoie :**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```


Renvoie l'objet EffectFormat qui contient les effets pixélisés appliqués à une forme. Lecture seule [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Renvoie :**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Renvoie l'objet FillFormat qui contient les propriétés de formatage de remplissage pour une forme. Lecture seule [IFillFormat](../../com.aspose.slides/ifillformat).

**Renvoie :**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getImage() {#getImage--}
```
public abstract IImage getImage()
```


Renvoie la miniature de la forme. Le type de limites de vignette ShapeThumbnailBounds.Shape est utilisé par défaut.

**Renvoie :**
[IImage](../../com.aspose.slides/iimage) - Vignette de forme.
### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public abstract IImage getImage(int bounds, float scaleX, float scaleY)
```


Renvoie la miniature de la forme.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| bounds | int | Type de limites de la vignette de forme. |
| scaleX | float | Échelle X |
| scaleY | float | Échelle Y |

**Renvoie :**
[IImage](../../com.aspose.slides/iimage) - Vignette de forme ou null dans le cas où ShapeThumbnailBounds.Appearance est utilisé et qu'une forme ne possède aucun élément visible.
### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```


Détermine si la forme est masquée. Booléen lecture/écriture.

**Renvoie :**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```


Détermine si la forme est masquée. Booléen lecture/écriture.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```


Renvoie la position d'une forme dans l'ordre Z. Shapes[0] renvoie la forme à l'arrière de l'ordre Z, et Shapes[Shapes.Count - 1] renvoie la forme à l'avant de l'ordre Z. Int en lecture seule.

**Renvoie :**
int
### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```


Renvoie le nombre de points de connexion sur la forme. Int en lecture seule.

**Renvoie :**
int
### getRotation() {#getRotation--}
```
public abstract float getRotation()
```


Renvoie ou définit le nombre de degrés de rotation de la forme spécifiée autour de l'axe Z. Une valeur positive indique une rotation horaire ; une valeur négative indique une rotation antihoraire. Float en lecture/écriture.

--------------------

La valeur retournée est toujours définie (n'est pas Float.NaN). La valeur assignée doit être définie (pas Float.NaN). Vous pouvez affecter des valeurs indéfinies aux propriétés d'une instance RawFrame.

**Renvoie :**
float
### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```


Renvoie ou définit le nombre de degrés de rotation de la forme spécifiée autour de l'axe Z. Une valeur positive indique une rotation horaire ; une valeur négative indique une rotation antihoraire. Float en lecture/écriture.

--------------------

La valeur retournée est toujours définie (n'est pas Float.NaN). La valeur assignée doit être définie (pas Float.NaN). Vous pouvez affecter des valeurs indéfinies aux propriétés d'une instance RawFrame.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public abstract float getX()
```


Obtient ou définit la coordonnée x du coin supérieur gauche de la forme, mesurée en points. Float en lecture/écriture.

--------------------

La valeur retournée est toujours définie et ne sera jamais Float.NaN. La valeur assignée doit également être définie ; n'affectez Float.NaN qu'aux propriétés d'une instance RawFrame.

**Renvoie :**
float
### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```


Obtient ou définit la coordonnée x du coin supérieur gauche de la forme, mesurée en points. Float en lecture/écriture.

--------------------

La valeur retournée est toujours définie et ne sera jamais Float.NaN. La valeur assignée doit également être définie ; n'affectez Float.NaN qu'aux propriétés d'une instance RawFrame.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public abstract float getY()
```


Obtient ou définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points. Float en lecture/écriture.

--------------------

La valeur retournée est toujours définie et ne sera jamais Float.NaN. La valeur assignée doit également être définie ; n'affectez Float.NaN qu'aux propriétés d'une instance RawFrame.

**Renvoie :**
float
### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```


Obtient ou définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points. Float en lecture/écriture.

--------------------

La valeur retournée est toujours définie et ne sera jamais Float.NaN. La valeur assignée doit également être définie ; n'affectez Float.NaN qu'aux propriétés d'une instance RawFrame.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```


Obtient ou définit la largeur de la forme, mesurée en points. Float en lecture/écriture.

--------------------

La valeur retournée est toujours définie et ne sera jamais Float.NaN. La valeur assignée doit également être définie ; n'affectez Float.NaN qu'aux propriétés d'une instance RawFrame.

**Renvoie :**
float
### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```


Obtient ou définit la largeur de la forme, mesurée en points. Float en lecture/écriture.

--------------------

La valeur retournée est toujours définie et ne sera jamais Float.NaN. La valeur assignée doit également être définie ; n'affectez Float.NaN qu'aux propriétés d'une instance RawFrame.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


Obtient ou définit la hauteur de la forme, mesurée en points. Float en lecture/écriture.

--------------------

La valeur retournée est toujours définie et ne sera jamais Float.NaN. La valeur assignée doit également être définie ; n'affectez Float.NaN qu'aux propriétés d'une instance RawFrame.

**Renvoie :**
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```


Obtient ou définit la hauteur de la forme, mesurée en points. Float en lecture/écriture.

--------------------

La valeur retournée est toujours définie et ne sera jamais Float.NaN. La valeur assignée doit également être définie ; n'affectez Float.NaN qu'aux propriétés d'une instance RawFrame.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getAlternativeText() {#getAlternativeText--}
```
public abstract String getAlternativeText()
```


Renvoie ou définit le texte alternatif associé à une forme. String en lecture/écriture.

**Renvoie :**
java.lang.String
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public abstract void setAlternativeText(String value)
```


Renvoie ou définit le texte alternatif associé à une forme. String en lecture/écriture.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public abstract String getAlternativeTextTitle()
```


Renvoie ou définit le titre du texte alternatif associé à une forme. String en lecture/écriture.

**Renvoie :**
java.lang.String
### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public abstract void setAlternativeTextTitle(String value)
```


Renvoie ou définit le titre du texte alternatif associé à une forme. String en lecture/écriture.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public abstract String getName()
```


Renvoie ou définit le nom d'une forme. String en lecture/écriture.

**Renvoie :**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Renvoie ou définit le nom d'une forme. String en lecture/écriture.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```


Obtient ou définit l'option 'Marquer comme décoratif' booléen lecture/écriture.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Renvoie :**
boolean
### setDecorative(boolean value) {#setDecorative-boolean-}
```
public abstract void setDecorative(boolean value)
```


Obtient ou définit l'option 'Marquer comme décoratif' booléen lecture/écriture.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public abstract IBaseShapeLock getShapeLock()
```


Renvoie les verrous de la forme. Lecture seule [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Renvoie :**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
### getUniqueId() {#getUniqueId--}
```
public int ? ?? ???????
```


Renvoie un identifiant interne à portée de la présentation destiné à être utilisé par des modules complémentaires ou autre code. Comme cette valeur peut être réassignée par l'utilisateur ou programmatiquement, elle ne doit pas être considérée comme une clé unique persistante. Long en lecture seule. Voir aussi \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Renvoie :**
long
### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public abstract long getOfficeInteropShapeId()
```


Renvoie un identifiant unique à portée de la diapositive qui reste constant pendant la durée de vie de la forme et permet à PowerPoint ou au code d'interopérabilité de référencer solidement la forme depuis n'importe où dans le document. Long en lecture seule. Voir aussi \#getUniqueId.getUniqueId.

**Renvoie :**
long
### isGrouped() {#isGrouped--}
```
public abstract boolean isGrouped()
```


Détermine si la forme est groupée. Booléen en lecture seule.

--------------------

La propriété \#getParentGroup.getParentGroup renvoie l'objet GroupShape parent si la forme est groupée.

**Renvoie :**
boolean
### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public abstract byte getBlackWhiteMode()
```


La propriété spécifie comment une forme sera rendue en mode d'affichage noir et blanc. Lecture/écriture [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Renvoie :**
byte
### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```


La propriété spécifie comment une forme sera rendue en mode d'affichage noir et blanc. Lecture/écriture [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```


Renvoie l'objet GroupShape parent si la forme est groupée. Sinon renvoie null. Lecture seule [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

La propriété \#isGrouped.isGrouped détermine si la forme est groupée.

**Renvoie :**
[IGroupShape](../../com.aspose.slides/igroupshape)
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```


Enregistre le contenu de Shape en tant que fichier SVG.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Flux cible |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```


Enregistre le contenu de Shape en tant que fichier SVG.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Flux cible |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Options de génération SVG |

### getBasePlaceholder() {#getBasePlaceholder--}
```
public   …  ...  …  …  …
```


Renvoie une forme placeholder de base (forme provenant de la disposition et/ou de la diapositive maître dont la forme actuelle hérite).

--------------------

> ```
> // obtenir tous les effets animés (maître/disposition/diapositive) du placeholder shape
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IShape shape = slide.getShapes().get_Item(0);
>      IEffect[] shapeEffects = slide.getTimeline().getMainSequence().getEffectsByShape(shape);
>      IShape layoutShape = shape.getBasePlaceholder();
>      IEffect[] layoutShapeEffects = slide.getLayoutSlide().getTimeline().getMainSequence().getEffectsByShape(layoutShape);
>      IShape masterShape = layoutShape.getBasePlaceholder();
>      IEffect[] masterShapeEffects = slide.getLayoutSlide().getMasterSlide().getTimeline().getMainSequence().getEffectsByShape(masterShape);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Un null est renvoyé si la forme actuelle n'est pas héritée.

**Renvoie :**
[IShape](../../com.aspose.slides/ishape)