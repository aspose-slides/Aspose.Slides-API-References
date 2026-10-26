---
title: Shape
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une forme sur une diapositive.
type: docs
url: /fr/com.aspose.slides/shape/
---
**Héritage:**  
java.lang.Object

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IShape](../../com.aspose.slides/ishape), com.aspose.slides.IDOMObject  
```
public class Shape implements IShape, IDOMObject
```

Représente une forme sur une diapositive.

## Méthodes

| Méthode | Description |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Détermine si la forme est TextHolder_PPT. |
| [getPlaceholder()](#getPlaceholder--) | Renvoie le placeholder d'une forme. |
| [removePlaceholder()](#removePlaceholder--) | Définit que cette forme n'est pas un placeholder. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Ajoute un nouveau placeholder s'il n'y en a pas et définit les propriétés du placeholder à celui spécifié. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Renvoie une forme de placeholder de base (forme provenant de la diapositive modèle ou du masque dont la forme actuelle hérite). |
| [getCustomData()](#getCustomData--) | Renvoie les données personnalisées de la forme. |
| [getRawFrame()](#getRawFrame--) | Renvoie ou définit les propriétés du cadre brut de la forme. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Renvoie ou définit les propriétés du cadre brut de la forme. |
| [getFrame()](#getFrame--) | Renvoie ou définit les propriétés du cadre de la forme. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Renvoie ou définit les propriétés du cadre de la forme. |
| [getLineFormat()](#getLineFormat--) | Renvoie l'objet LineFormat qui contient les propriétés de formatage de ligne d'une forme. |
| [getThreeDFormat()](#getThreeDFormat--) | Renvoie l'objet ThreeDFormat qui contient les propriétés d'effet 3D d'une forme. |
| [getEffectFormat()](#getEffectFormat--) | Renvoie l'objet EffectFormat qui contient les effets pixels appliqués à une forme. |
| [getFillFormat()](#getFillFormat--) | Renvoie l'objet FillFormat qui contient les propriétés de formatage de remplissage d'une forme. |
| [getImage()](#getImage--) | Renvoie la miniature de la forme. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Renvoie la miniature de la forme. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Enregistre le contenu de la forme en fichier SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Enregistre le contenu de la forme en fichier SVG. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Renvoie ou définit le lien hypertexte défini pour le clic de souris. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Renvoie ou définit le lien hypertexte défini pour le clic de souris. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Renvoie ou définit le lien hypertexte défini pour le survol de la souris. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Renvoie ou définit le lien hypertexte défini pour le survol de la souris. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Renvoie le gestionnaire de liens hypertexte. |
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
| [getBlackWhiteMode()](#getBlackWhiteMode--) | La propriété spécifie comment une forme sera rendue en mode d'affichage noir et blanc.. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | La propriété spécifie comment une forme sera rendue en mode d'affichage noir et blanc.. |
| [getUniqueId()](#getUniqueId--) | Renvoie un identifiant interne, limité à la présentation, destiné à être utilisé par des add-ins ou autre code. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Renvoie un identifiant unique limité à la diapositive qui reste constant pendant la durée de vie de la forme et permet à PowerPoint ou au code interop de référencer de manière fiable la forme depuis n'importe où dans le document. |
| [getAlternativeText()](#getAlternativeText--) | Renvoie ou définit le texte alternatif associé à une forme. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Renvoie ou définit le texte alternatif associé à une forme. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Renvoie ou définit le titre du texte alternatif associé à une forme. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Renvoie ou définit le titre du texte alternatif associé à une forme. |
| [getName()](#getName--) | Renvoie ou définit le nom d'une forme. |
| [setName(String value)](#setName-java.lang.String-) | Renvoie ou définit le nom d'une forme. |
| [isDecorative()](#isDecorative--) | Obtient ou définit l'option « Marquer comme décoratif » booléen lecture/écriture. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Obtient ou définit l'option « Marquer comme décoratif » booléen lecture/écriture. |
| [getShapeLock()](#getShapeLock--) | Renvoie les verrous de la forme. |
| [isGrouped()](#isGrouped--) | Détermine si la forme est groupée. |
| [getParentGroup()](#getParentGroup--) | Renvoie l'objet parent GroupShape si la forme est groupée. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVisualBounds()](#getVisualBounds--) | Obtient les limites visuelles de la forme calculées à partir de son rendu. |
| [getSlide()](#getSlide--) | Renvoie la diapositive parent d'une forme. |
| [getPresentation()](#getPresentation--) | Renvoie la présentation parent d'une diapositive. |

### isTextHolder() {#isTextHolder--}
```
public final boolean isTextHolder()
```

Détermine si la forme est TextHolder_PPT. Lecture seule booléen.

**Renvoie:**  
boolean

### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```

Renvoie le placeholder d'une forme. Renvoie null si la forme n'a pas de placeholder. Lecture seule [IPlaceholder](../../com.aspose.slides/iplaceholder).

--------------------

> ```
> The following example shows how to change Text in Placeholder.
>  
>  // Instancie une classe Presentation
>  Presentation pres = new Presentation("ReplacingText.pptx");
>  try {
>      // Accède à la première diapositive
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Parcourt les formes pour trouver le placeholder
>      for (IShape shp : sld.getShapes())
>          if (shp.getPlaceholder() != null)
>          {
>              // Modifie le texte de chaque placeholder
>              ((IAutoShape)shp).getTextFrame().setText("This is a Placeholder");
>          }
>      // Enregistre la présentation sur le disque
>      pres.save("output_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set Prompt Text in Placeholder.
>  
>  Presentation pres = new Presentation("Presentation2.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      for (IShape shape : slide.getSlide().getShapes()) // Parcourt la diapositive
>      {
>          if (shape.getPlaceholder() != null && shape instanceof AutoShape)
>          {
>              String text = "";
>              if (shape.getPlaceholder().getType() == PlaceholderType.CenteredTitle) // PowerPoint affiche "Click to add title"
>              {
>                  text = "Add Title";
>              }
>              else if (shape.getPlaceholder().getType() == PlaceholderType.Subtitle) // Ajoute un sous-titre
>              {
>                  text = "Add Subtitle";
>              }
>              ((IAutoShape)shape).getTextFrame().setText(text);
>              System.out.println("Placeholder with text: " + text);
>          }
>      }
>      pres.save("Placeholders_PromptText.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  ```
**Returns:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)
### removePlaceholder() {#removePlaceholder--}
```
public final void removePlaceholder()
```

Defines that this shape isn't a placeholder.

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public final IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Adds a new placeholder if there is no and sets placeholder properties to a specified one.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Placeholder to copy content from. |

**Returns:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - New \#getPlaceholder.getPlaceholder.
### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from).

--------------------

> ```
> // récupère tous les effets animés (master/layout/slide) de la forme placeholder
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

A null is returned if the current shape is not inherited.

**Returns:**
[IShape](../../com.aspose.slides/ishape)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Returns the shape's custom data. Read-only [ICustomData](../../com.aspose.slides/icustomdata).

**Returns:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getRawFrame() {#getRawFrame--}
```
public final IShapeFrame getRawFrame()
```

Returns or sets the raw shape frame's properties. Read/write [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> // Le code qui tente d'assigner un cadre indéfini à IShape.getFrame() n'a pas de sens dans le cas général (en particulier lorsque le GroupShape parent est imbriqué plusieurs fois dans d'autres GroupShape). Par exemple :
>  
> // IShape shape = ...;
> // shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
> //ou
> // slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
> // Un tel code peut entraîner des situations ambiguës. Ainsi, des restrictions ont été ajoutées pour l'utilisation de valeurs indéfinies avec IShape.getFrame(). Les valeurs de x, y, largeur, hauteur, flipH, flipV et rotationAngle doivent être définies (pas Float.NaN ou NullableBool.NotDefined). Le code d'exemple ci-dessus lève maintenant une exception ArgumentException.
> // Cela s'applique à ces cas d'utilisation :
> // IShape shape = ...;
> // shape.setFrame(...); // ne peut pas être indéfini
> // IShapeCollection shapes = ...;
> // // les paramètres x, y, largeur, hauteur ne peuvent pas être Float.NaN :
> // {
> //     shapes.addAudioFrameCD(...);
> //     shapes.addAudioFrameEmbedded(...);
> //     shapes.addAudioFrameLinked(...);
> //     shapes.addAutoShape(...);
> //     shapes.addChart(...);
> //     shapes.addConnector(...);
> //     shapes.addOleObjectFrame(...);
> //     shapes.addPictureFrame(...);
> //     shapes.addSmartArt(...);
> //     shapes.addTable(...);
> //     shapes.addVideoFrame(...);
> //     shapes.insertAudioFrameEmbedded(...);
> //     shapes.insertAudioFrameLinked(...);
> //     shapes.insertAutoShape(...);
> //     shapes.insertChart(...);
> //     shapes.insertConnector(...);
> //     shapes.insertOleObjectFrame(...);
> //     shapes.insertPictureFrame(...);
> //     shapes.insertTable(...);
> //     shapes.insertVideoFrame(...);
> // }
> // Mais les propriétés du cadre IShape.RawFrame peuvent être indéfinies. Cela a du sens lorsque la forme est liée à un placeholder. Alors les valeurs de cadre indéfinies sont remplacées par celles du placeholder parent. S'il n'existe aucun placeholder parent pour cette forme, alors la forme utilise des valeurs par défaut lorsqu'elle calcule le cadre effectif à partir de son IShape.RawFrame. Les valeurs par défaut sont 0 et NullableBool.False pour x, y, largeur, hauteur, flipH, flipV et rotationAngle. Par exemple :
> // IShape shape = ...; // la forme est liée à un placeholder
> // shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // maintenant la forme hérite des valeurs x, y, hauteur, flipH, flipV du placeholder et surcharge la largeur=100 et rotationAngle=0.{code}
> ```

**Returns:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
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
>  //Ce code peut conduire à des situations ambiguës. Ainsi, des restrictions ont été ajoutées pour l'utilisation de valeurs indéfinies pour IShape.getFrame(). Les valeurs de x, y, largeur, hauteur, flipH, flipV et rotationAngle doivent être définies (pas Float.NaN ou NullableBool.NotDefined). Le code d'exemple ci-dessus lève maintenant une exception ArgumentException.
>  //Cela s'applique à ces cas d'utilisation :
>  IShape shape = ...;
>  shape.setFrame(...); // ne peut pas être indéfini
>  IShapeCollection shapes = ...;
>  // les paramètres x, y, largeur, hauteur ne peuvent pas être Float.NaN :
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
>  //Mais les propriétés du cadre IShape.RawFrame peuvent être indéfinies. Cela a du sens lorsque la forme est liée à un placeholder. Alors les valeurs de cadre indéfinies sont remplacées par celles du placeholder parent. S'il n'existe aucun placeholder parent pour cette forme, alors la forme utilise des valeurs par défaut lors du calcul du cadre effectif à partir de son IShape.RawFrame. Les valeurs par défaut sont 0 et NullableBool.False pour x, y, largeur, hauteur, flipH, flipV et rotationAngle. Par exemple :
>  IShape shape = ...; // la forme est liée à un placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // maintenant la forme hérite des valeurs x, y, hauteur, flipH, flipV du placeholder et surcharge la largeur=100 et rotationAngle=0.{code}
>  ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```
Returns or sets the shape frame's properties. Read/write [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Value of each property of the returned IShapeFrame instance is not undefined (is not NaN or NotDefined). Value of each property of the assigned IShapeFrame instance must be not undefined (must be not NaN or NotDefined). You can set undefined values for RawFrame instance properties.

**Returns:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
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
public ILineFormat getLineFormat()
```

Returns the LineFormat object that contains line formatting properties for a shape. Note: can return null for certain types of shapes which don't have line properties. Read-only [ILineFormat](../../com.aspose.slides/ilineformat).

**Returns:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

Returns the ThreeDFormat object that 3d effect properties for a shape. Note: can return null for certain types of shapes which don't have 3d properties. Read-only [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Returns:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

Returns the EffectFormat object which contains pixel effects applied to a shape. Note: can return null for certain types of shapes which don't have effect properties. Read-only [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Returns:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Returns the FillFormat object that contains fill formatting properties for a shape. Note: can return null for certain types of shapes which don't have fill properties. Read-only [IFillFormat](../../com.aspose.slides/ifillformat).

--------------------

> ```
> The following example shows how to change the accent color for a theme of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      shape.getFillFormat().setFillType(FillType.Solid);
>      shape.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example demonstrates how to obtain palette colors from the main theme color and then used in shapes.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Accent 4
>      IShape shape1 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 50, 50);
>      shape1.getFillFormat().setFillType(FillType.Solid);
>      shape1.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      // Accent 4, Plus clair 80%
>      IShape shape2 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 70, 50, 50);
>      shape2.getFillFormat().setFillType(FillType.Solid);
>      shape2.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.2f);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.8f);
>      // Accent 4, Plus clair 60%
>      IShape shape3 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 130, 50, 50);
>      shape3.getFillFormat().setFillType(FillType.Solid);
>      shape3.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.4f);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.6f);
>      // Accent 4, Plus clair 40%
>      IShape shape4 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 190, 50, 50);
>      shape4.getFillFormat().setFillType(FillType.Solid);
>      shape4.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.6f);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.4f);
>      // Accent 4, Plus sombre 25%
>      IShape shape5 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 250, 50, 50);
>      shape5.getFillFormat().setFillType(FillType.Solid);
>      shape5.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape5.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.75f);
>      // Accent 4, Plus sombre 50%
>      IShape shape6 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 310, 50, 50);
>      shape6.getFillFormat().setFillType(FillType.Solid);
>      shape6.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape6.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.5f);
>      pres.save("example_accent4.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getImage() {#getImage--}
```
public final IImage getImage()
```

Returns shape thumbnail. ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Shape thumbnail.
### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IImage getImage(int bounds, float scaleX, float scaleY)
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
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```
Saves content of Shape as SVG file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```
Saves content of Shape as SVG file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG generation options |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

Returns or sets the hyperlink defined for mouse click. Read/write [IHyperlink](../../com.aspose.slides/ihyperlink).

**Returns:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```
Renvoie ou définit le lien hypertexte défini pour le clic de souris. Lecture/écriture [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

Returns or sets the hyperlink defined for mouse over. Read/write [IHyperlink](../../com.aspose.slides/ihyperlink).

**Returns:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

Returns or sets the hyperlink defined for mouse over. Read/write [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

Returns the hyperlink manager. Read-only [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Returns:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)
### getHidden() {#getHidden--}
```
public final boolean getHidden()
```
 
Determines whether the shape is hidden. Read/write  boolean .

**Returns:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```
Determines whether the shape is hidden. Read/write  boolean .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

Returns the position of a shape in the z-order. Shapes[0] returns the shape at the back of the z-order, and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order. Read-only  int .

**Returns:**
int
### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```
Returns the number of connection sites on the shape. Read-only  int .

**Returns:**
int
### getRotation() {#getRotation--}
```
public final float getRotation()
```

Returns or sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Read/write float.

--------------------

Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**Returns:**
float
### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```

```

public final float getX()
```
Gets or sets the x-coordinate of the shape's upper-left corner, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Returns:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
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
public final float getY()
```

Obtient ou définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points. Lecture/écriture float.

--------------------

La valeur renvoyée est toujours définie et n’est jamais Float.NaN. La valeur assignée doit également être définie ; n’affectez Float.NaN qu’aux propriétés d’une instance RawFrame.

**Returns:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
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
public final float getWidth()
```

Gets or sets the width of the shape, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
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
public final float getHeight()
```
Gets or sets the height of the shape, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Returns:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Gets or sets the height of the shape, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```

Property specifies how a shape will render in black-and-white display mode.. Read/write [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Returns:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```
Property specifies how a shape will render in black-and-white display mode.. Read/write [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Renvoie :**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final long getUniqueId()
```

Returns an internal, presentation-scoped identifier intended for use by add-ins or other code. Because this value can be reassigned by the user or programmatically, it must not be treated as a persistent unique key. Read-only long. See also \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Returns:**
long
### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```

Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and lets PowerPoint or interop code reliably reference the shape from anywhere in the document. Read-only long. See also \#getUniqueId.getUniqueId.

**Returns:**
long
### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```

Returns or sets the alternative text associated with a shape. Read/write String.

**Returns:**
java.lang.String
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```

Returns or sets the alternative text associated with a shape. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```

Returns or sets the title of alternative text associated with a shape. Read/write String.

**Returns:**
java.lang.String
### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```

Renvoie ou définit le titre du texte alternatif associé à une forme. Lecture/écriture String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```
Renvoie ou définit le nom d'une forme. Ne doit pas être nul. Utilisez une chaîne vide si nécessaire. Lecture/écriture String.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```
Renvoie ou définit le nom d'une forme. Ne doit pas être nul. Utilisez une chaîne vide si nécessaire. Lecture/écriture String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```

Obtient ou définit l'option « Marquer comme décoratif » en lecture/écriture booléen.

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
public final void setDecorative(boolean value)
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public IBaseShapeLock getShapeLock()
```

Returns shape's locks. Read-only [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Returns:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```

Determines whether the shape is grouped. Read-only boolean.

--------------------

Property \#getParentGroup.getParentGroup returns parent GroupShape object if shape is grouped.

**Returns:**
boolean
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Returns parent GroupShape object if shape is grouped. Otherwise returns null. Read-only [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

Property \#isGrouped.isGrouped determines whether the shape is grouped.

**Returns:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getVisualBounds() {#getVisualBounds--}
```
public final RectF getVisualBounds()
```

Gets the visual bounds of the shape calculated from its rendered content.

**Returns:**
android.graphics.RectF - Un android.graphics.RectF qui représente les limites visuelles de la forme en coordonnées de diapositive.

--------------------

Le rectangle retourné représente les limites alignées sur les axes de tout le contenu produit par la forme lors du rendu dans l'espace de coordonnées de la diapositive. Ces limites peuvent différer des limites du modèle de la forme \#getX.getX/\#setX(float).setX(float), \#getY.getY/\#setY(float).setY(float), \#getWidth.getWidth/\#setWidth(float).setWidth(float), \#getHeight.getHeight/\#setHeight(float).setHeight(float) et peuvent contenir des coordonnées négatives si le contenu rendu dépasse l'origine de la diapositive. Les limites visuelles prennent en compte les aspects liés au rendu tels que les transformations (par exemple, la rotation), la largeur et les jointures du trait, la mise en page du texte et le débordement, la géométrie SmartArt, ainsi que d'autres effets de mise en page qui influencent l'apparence finale rendue de la forme. Les limites retournées ne sont pas découpées selon le rectangle de la diapositive.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```
Renvoie la diapositive parent d'une forme. Lecture seule [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Renvoie :**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()


Renvoie la présentation parent d'une diapositive. Lecture seule [IPresentation](../../com.aspose.slides/ipresentation).

**Renvoie:**  
[IPresentation](../../com.aspose.slides/ipresentation)