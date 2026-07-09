---
title: IShape
second_title: Référence de l'API Java d'Aspose.Slides pour Android
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
| [getPlaceholder()](#getPlaceholder--) | Renvoie l'espace réservé d'une forme. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Ajoute un nouvel espace réservé s'il n'existe pas et définit les propriétés de l'espace réservé à une valeur spécifiée. |
| [removePlaceholder()](#removePlaceholder--) | Indique que cette forme n'est pas un espace réservé. |
| [getCustomData()](#getCustomData--) | Renvoie les données personnalisées de la forme. |
| [getRawFrame()](#getRawFrame--) | Renvoie ou définit les propriétés brutes du cadre de la forme. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Renvoie ou définit les propriétés brutes du cadre de la forme. |
| [getFrame()](#getFrame--) | Renvoie ou définit les propriétés du cadre de la forme. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Renvoie ou définit les propriétés du cadre de la forme. |
| [getLineFormat()](#getLineFormat--) | Renvoie l'objet LineFormat qui contient les propriétés de formatage de ligne pour une forme. |
| [getThreeDFormat()](#getThreeDFormat--) | Renvoie l'objet ThreeDFormat qui contient les propriétés de formatage 3D pour une forme. |
| [getEffectFormat()](#getEffectFormat--) | Renvoie l'objet EffectFormat qui contient les effets pixel appliqués à une forme. |
| [getFillFormat()](#getFillFormat--) | Renvoie l'objet FillFormat qui contient les propriétés de formatage de remplissage pour une forme. |
| [getImage()](#getImage--) | Renvoie la vignette de la forme. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Renvoie la vignette de la forme. |
| [getHidden()](#getHidden--) | Détermine si la forme est cachée. |
| [setHidden(boolean value)](#setHidden-boolean-) | Détermine si la forme est cachée. |
| [getZOrderPosition()](#getZOrderPosition--) | Renvoie la position d'une forme dans l'ordre Z. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Renvoie le nombre de points de connexion sur la forme. |
| [getRotation()](#getRotation--) | Renvoie ou définit le nombre de degrés de rotation de la forme spécifiée autour de l'axe Z. |
| [setRotation(float value)](#setRotation-float-) | Renvoie ou définit le nombre de degrés de rotation de la forme spécifiée autour de l'axe Z. |
| [getX()](#getX--) | Obtient ou définit la coordonnée x du coin supérieur gauche de la forme, exprimée en points. |
| [setX(float value)](#setX-float-) | Obtient ou définit la coordonnée x du coin supérieur gauche de la forme, exprimée en points. |
| [getY()](#getY--) | Obtient ou définit la coordonnée y du coin supérieur gauche de la forme, exprimée en points. |
| [setY(float value)](#setY-float-) | Obtient ou définit la coordonnée y du coin supérieur gauche de la forme, exprimée en points. |
| [getWidth()](#getWidth--) | Obtient ou définit la largeur de la forme, exprimée en points. |
| [setWidth(float value)](#setWidth-float-) | Obtient ou définit la largeur de la forme, exprimée en points. |
| [getHeight()](#getHeight--) | Obtient ou définit la hauteur de la forme, exprimée en points. |
| [setHeight(float value)](#setHeight-float-) | Obtient ou définit la hauteur de la forme, exprimée en points. |
| [getAlternativeText()](#getAlternativeText--) | Renvoie ou définit le texte alternatif associé à une forme. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Renvoie ou définit le texte alternatif associé à une forme. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Renvoie ou définit le titre du texte alternatif associé à une forme. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Renvoie ou définit le titre du texte alternatif associé à une forme. |
| [getName()](#getName--) | Renvoie ou définit le nom d'une forme. |
| [setName(String value)](#setName-java.lang.String-) | Renvoie ou définit le nom d'une forme. |
| [isDecorative()](#isDecorative--) | Obtient ou définit l'option « Mark as decorative » en lecture/écriture booléen. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Obtient ou définit l'option « Mark as decorative » en lecture/écriture booléen. |
| [getShapeLock()](#getShapeLock--) | Renvoie les verrous de la forme. |
| [getUniqueId()](#getUniqueId--) | Renvoie un identifiant interne, limité à la présentation, destiné à être utilisé par les modules complémentaires ou autre code. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Renvoie un identifiant unique limité à la diapositive qui reste constant pendant toute la durée de vie de la forme et permet à PowerPoint ou au code interop de référencer la forme de manière fiable depuis n'importe où dans le document. |
| [isGrouped()](#isGrouped--) | Détermine si la forme est groupée. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | La propriété spécifie comment une forme sera rendue en mode d'affichage noir et blanc. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | La propriété spécifie comment une forme sera rendue en mode d'affichage noir et blanc. |
| [getParentGroup()](#getParentGroup--) | Renvoie l'objet GroupShape parent si la forme est groupée. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Enregistre le contenu de la forme en fichier SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Enregistre le contenu de la forme en fichier SVG. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Renvoie une forme d'espace réservé de base (forme provenant de la diapositive modèle et/ou principale dont la forme actuelle hérite). |
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

Renvoie l'espace réservé d'une forme. Lecture seule [IPlaceholder](../../com.aspose.slides/iplaceholder).

**Renvoie :**  
[IPlaceholder](../../com.aspose.slides/iplaceholder)
### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public abstract IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Ajoute un nouvel espace réservé s'il n'existe pas et définit les propriétés de l'espace réservé à une valeur spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Espace réservé dont le contenu doit être copié. |

**Renvoie :**  
[IPlaceholder](../../com.aspose.slides/iplaceholder) - Nouveau [IPlaceholder](../../com.aspose.slides/iplaceholder).
### removePlaceholder() {#removePlaceholder--}
```
public abstract void removePlaceholder()
```

Indique que cette forme n'est pas un espace réservé.
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

Renvoie ou définit les propriétés brutes du cadre de la forme. Lecture/écriture [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //or
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Such code can lead to unclear situations. So restrictions had been added for using undefined values for IShape.getFrame(). Values of x, y, width, height, flipH, flipV and rotationAngle must be defined (not Float.NaN or NullableBool.NotDefined). Example code above now throws ArgumentException exception.
>  //This applies to these use cases:
>  IShape shape = ...;
>  shape.setFrame(...); // cannot be undefined
>  IShapeCollection shapes = ...;
>  // x, y, width, height parameters cannot be Float.NaN:
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
>  IShape shape = ...; // shape is linked to placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // now shape inherits x, y, height, flipH, flipV values form placeholder and overrides width=100 and rotationAngle=0.
> ```

**Returns:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
```

Returns or sets the raw shape frame's properties. Read/write [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //ou
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Ce code peut entraîner des situations ambiguës. Ainsi, des restrictions ont été ajoutées pour l'utilisation de valeurs indéfinies pour IShape.getFrame(). Les valeurs de x, y, width, height, flipH, flipV et rotationAngle doivent être définies (pas Float.NaN ou NullableBool.NotDefined). Le code d'exemple ci-dessus lance maintenant une exception ArgumentException.
>  //Cela s'applique à ces cas d'utilisation :
>  IShape shape = ...;
>  shape.setFrame(...); // cannot be undefined
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
>  IShape shape = ...; // la forme est liée à un espace réservé
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // maintenant la forme hérite des valeurs x, y, height, flipH, flipV du placeholder et surcharge width=100 et rotationAngle=0.
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

Returns or sets the shape frame's properties. Read/write [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Value of each property of the returned IShapeFrame instance is not undefined (is not NaN or NotDefined). Value of each property of the assigned IShapeFrame instance must be not undefined (must be not NaN or NotDefined). You can set undefined values for RawFrame instance properties.

**Returns:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

Returns or sets the shape frame's properties. Read/write [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Value of each property of the returned IShapeFrame instance is not undefined (is not NaN or NotDefined). Value of each property of the assigned IShapeFrame instance must be not undefined (must be not NaN or NotDefined). You can set undefined values for RawFrame instance properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Returns the LineFormat object that contains line formatting properties for a shape. Read-only [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

Returns the ThreeDFormat object that contains line formatting properties for a shape. Read-only [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Returns:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Returns the EffectFormat object which contains pixel effects applied to a shape. Read-only [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Returns:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Returns the FillFormat object that contains fill formatting properties for a shape. Read-only [IFillFormat](../../com.aspose.slides/ifillformat).

**Returns:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Returns shape thumbnail. ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Shape thumbnail.
### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public abstract IImage getImage(int bounds, float scaleX, float scaleY)
```

Returns shape thumbnail.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bounds | int | Shape thumbnail bounds type. |
| scaleX | float | X scale |
| scaleY | float | Y scale |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Shape thumbnail or null in case when ShapeThumbnailBounds.Appearance is used and a shape doesn't have visible elements.
### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Determines whether the shape is hidden. Read/write boolean.

**Returns:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Determines whether the shape is hidden. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```

Returns the position of a shape in the z-order. Shapes[0] returns the shape at the back of the z-order, and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order. Read-only int.

**Returns:**
int
### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```

Renvoie le nombre de points de connexion sur la forme. Lecture seule int.

**Returns:**
int
### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

Returns or sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Read/write float.

--------------------

Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**Returns:**
float
### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```

Returns or sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Read/write float.

--------------------

Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public abstract float getX()
```

Gets or sets the x-coordinate of the shape's upper-left corner, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Returns:**
float
### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```

Gets or sets the x-coordinate of the shape's upper-left corner, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public abstract float getY()
```

Gets or sets the y-coordinate of the shape's upper-left corner, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Returns:**
float
### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```

Gets or sets the y-coordinate of the shape's upper-left corner, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

Gets or sets the width of the shape, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```

Gets or sets the width of the shape, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Gets or sets the height of the shape, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Returns:**
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```
Gets or sets the height of the shape, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getAlternativeText() {#getAlternativeText--}
```
public abstract String getAlternativeText()
```

Returns or sets the alternative text associated with a shape. Read/write String.

**Returns:**
java.lang.String
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public abstract void setAlternativeText(String value)
```

Returns or sets the alternative text associated with a shape. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public abstract String getAlternativeTextTitle()
```

Returns or sets the title of alternative text associated with a shape. Read/write String.

**Returns:**
java.lang.String
### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public abstract void setAlternativeTextTitle(String value)
```

Returns or sets the title of alternative text associated with a shape. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public abstract String getName()
```

Returns or sets the name of a shape. Read/write String.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Returns or sets the name of a shape. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```
Gets or sets 'Mark as decorative' option Reed/write boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
boolean
### setDecorative(boolean value) {#setDecorative-boolean-}
```
public abstract void setDecorative(boolean value)
```
Obtient ou définit l'option « Mark as decorative » en lecture/écriture booléen.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public abstract IBaseShapeLock getShapeLock()
```


Returns shape's locks. Read-only [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Returns:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
### getUniqueId() {#getUniqueId--}
```
public abstract long getUniqueId()
```
 
Returns an internal, presentation-scoped identifier intended for use by add-ins or other code. Because this value can be reassigned by the user or programmatically, it must not be treated as a persistent unique key. Read-only long. See also \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Returns:**
long
### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public abstract long getOfficeInteropShapeId()
```


Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and lets PowerPoint or interop code reliably reference the shape from anywhere in the document. Read-only long. See also \#getUniqueId.getUniqueId.

**Returns:**
long
### isGrouped() {#isGrouped--}
```
public abstract boolean isGrouped()
```

Determines whether the shape is grouped. Read-only boolean.

--------------------

Property \#getParentGroup.getParentGroup returns parent GroupShape object if shape is grouped.

**Returns:**
boolean
### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public abstract byte getBlackWhiteMode()
```

Property specifies how a shape will render in black-and-white display mode.. Read/write [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Returns:**
byte
### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```

Property specifies how a shape will render in black-and-white display mode.. Read/write [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Returns parent GroupShape object if shape is grouped. Otherwise returns null. Read-only [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

Property \#isGrouped.isGrouped determines whether the shape is grouped.

**Returns:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```
Saves content of Shape as SVG file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Saves content of Shape as SVG file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG generation options |

### getBasePlaceholder() {#getBasePlaceholder--}
```
public abstract IShape getBasePlaceholder()


Renvoie une forme d'espace réservé de base (forme provenant de la diapositive modèle et/ou principale dont la forme actuelle hérite).

--------------------

> ```
> // get all (master/layout/slide) animated effects of the placeholder shape
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

Une valeur null est renvoyée si la forme actuelle n'est pas héritée.

**Renvoie :**  
[IShape](../../com.aspose.slides/ishape)