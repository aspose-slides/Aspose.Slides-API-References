---
title: Shape
second_title: Référence API Aspose.Slides pour Java
description: Représente une forme sur une diapositive.
type: docs
url: /fr/com.aspose.slides/shape/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape), com.aspose.slides.IDOMObject
```
public class Shape implements IShape, IDOMObject
```

Représente une forme sur une diapositive.
## Methods

| Méthode | Description |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Détermine si la forme est TextHolder_PPT. |
| [getPlaceholder()](#getPlaceholder--) | Renvoie l’espace réservé pour une forme. |
| [removePlaceholder()](#removePlaceholder--) | Définit que cette forme n’est pas un espace réservé. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Ajoute un nouvel espace réservé s’il n’en existe pas et définit les propriétés de l’espace réservé à un spécifié. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Renvoie une forme d’espace réservé de base (forme provenant de la disposition et/ou de la diapositive maître dont la forme actuelle hérite). |
| [getCustomData()](#getCustomData--) | Renvoie les données personnalisées de la forme. |
| [getRawFrame()](#getRawFrame--) | Renvoie ou définit les propriétés du cadre brut de la forme. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Renvoie ou définit les propriétés du cadre brut de la forme. |
| [getFrame()](#getFrame--) | Renvoie ou définit les propriétés du cadre de la forme. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Renvoie ou définit les propriétés du cadre de la forme. |
| [getLineFormat()](#getLineFormat--) | Renvoie l’objet LineFormat qui contient les propriétés de formatage de ligne pour une forme. |
| [getThreeDFormat()](#getThreeDFormat--) | Renvoie l’objet ThreeDFormat qui contient les propriétés d’effet 3D pour une forme. |
| [getEffectFormat()](#getEffectFormat--) | Renvoie l’objet EffectFormat qui contient les effets de pixel appliqués à une forme. |
| [getFillFormat()](#getFillFormat--) | Renvoie l’objet FillFormat qui contient les propriétés de formatage de remplissage pour une forme. |
| [getImage()](#getImage--) | Renvoie la miniature de la forme. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Renvoie la miniature de la forme. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Enregistre le contenu de Shape sous forme de fichier SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Enregistre le contenu de Shape sous forme de fichier SVG. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Renvoie ou définit le lien hypertexte défini pour le clic de la souris. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Renvoie ou définit le lien hypertexte défini pour le clic de la souris. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Renvoie ou définit le lien hypertexte défini pour le survol de la souris. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Renvoie ou définit le lien hypertexte défini pour le survol de la souris. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Renvoie le gestionnaire de liens hypertexte. |
| [getHidden()](#getHidden--) | Détermine si la forme est masquée. |
| [setHidden(boolean value)](#setHidden-boolean-) | Détermine si la forme est masquée. |
| [getZOrderPosition()](#getZOrderPosition--) | Renvoie la position d’une forme dans l’ordre Z. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Renvoie le nombre de sites de connexion sur la forme. |
| [getRotation()](#getRotation--) | Renvoie ou définit le nombre de degrés dont la forme spécifiée est pivotée autour de l’axe Z. |
| [setRotation(float value)](#setRotation-float-) | Renvoie ou définit le nombre de degrés dont la forme spécifiée est pivotée autour de l’axe Z. |
| [getX()](#getX--) | Obtient ou définit la coordonnée x du coin supérieur gauche de la forme, mesurée en points. |
| [setX(float value)](#setX-float-) | Obtient ou définit la coordonnée x du coin supérieur gauche de la forme, mesurée en points. |
| [getY()](#getY--) | Obtient ou définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points. |
| [setY(float value)](#setY-float-) | Obtient ou définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points. |
| [getWidth()](#getWidth--) | Obtient ou définit la largeur de la forme, mesurée en points. |
| [setWidth(float value)](#setWidth-float-) | Obtient ou définit la largeur de la forme, mesurée en points. |
| [getHeight()](#getHeight--) | Obtient ou définit la hauteur de la forme, mesurée en points. |
| [setHeight(float value)](#setHeight-float-) | Obtient ou définit la hauteur de la forme, mesurée en points. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Propriété spécifiant comment une forme sera rendue en mode affichage noir et blanc. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Propriété spécifiant comment une forme sera rendue en mode affichage noir et blanc. |
| [getUniqueId()](#getUniqueId--) | Renvoie un identifiant interne, limité à la présentation, destiné à être utilisé par des add-ins ou autre code. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Renvoie un identifiant unique limité à la diapositive qui reste constant pendant la durée de vie de la forme et permet à PowerPoint ou au code d’interop de référencer de manière fiable la forme depuis n’importe où dans le document. |
| [getAlternativeText()](#getAlternativeText--) | Renvoie ou définit le texte de remplacement associé à une forme. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Renvoie ou définit le texte de remplacement associé à une forme. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Renvoie ou définit le titre du texte de remplacement associé à une forme. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Renvoie ou définit le titre du texte de remplacement associé à une forme. |
| [getName()](#getName--) | Renvoie ou définit le nom d’une forme. |
| [setName(String value)](#setName-java.lang.String-) | Renvoie ou définit le nom d’une forme. |
| [isDecorative()](#isDecorative--) | Obtient ou définit l’option 'Marquer comme décoratif' booléen lecture/écriture. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Obtient ou définit l’option 'Marquer comme décoratif' booléen lecture/écriture. |
| [getShapeLock()](#getShapeLock--) | Renvoie les verrous de la forme. |
| [isGrouped()](#isGrouped--) | Détermine si la forme est groupée. |
| [getParentGroup()](#getParentGroup--) | Renvoie l’objet GroupShape parent si la forme est groupée. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVisualBounds()](#getVisualBounds--) | Obtient les limites visuelles de la forme calculées à partir de son contenu rendu. |
| [getSlide()](#getSlide--) | Renvoie la diapositive parente d’une forme. |
| [getPresentation()](#getPresentation--) | Renvoie la présentation parente d’une diapositive. |

### isTextHolder() {#isTextHolder--}
```
public final boolean isTextHolder()
```

Détermine si la forme est TextHolder_PPT. Lecture seule  booléen .

**Renvoie :**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```

Renvoie l’espace réservé pour une forme. Renvoie null si la forme n’a pas d’espace réservé. Lecture seule [IPlaceholder](../../com.aspose.slides/iplaceholder).

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
>              else if (shape.getPlaceholder().getType() == PlaceholderType.Subtitle) // Ajoute le sous-titre
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
> ```


**Renvoie :**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### removePlaceholder() {#removePlaceholder--}
```
public final void removePlaceholder()
```

Définit que cette forme n’est pas un espace réservé.

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public final IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Ajoute un nouvel espace réservé s’il n’en existe pas et définit les propriétés de l’espace réservé à un spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Espace réservé dont le contenu est copié. |

**Renvoie :**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - Nouveau \#getPlaceholder.getPlaceholder.

### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

Renvoie une forme d’espace réservé de base (forme provenant de la disposition et/ou de la diapositive maître dont la forme actuelle hérite).

--------------------

> ```
> // récupérer tous les effets animés (master/layout/slide) de la forme placeholder
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

Null est renvoyé si la forme actuelle n’est pas héritée.

**Renvoie :**
[IShape](../../com.aspose.slides/ishape)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Renvoie les données personnalisées de la forme. Lecture seule [ICustomData](../../com.aspose.slides/icustomdata).

**Renvoie :**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public final IShapeFrame getRawFrame()
```

Renvoie ou définit les propriétés du cadre brut de la forme. Lecture/écriture [IShapeFrame](../../com.aspose.slides/ishapeframe).

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
>  //But IShape.RawFrame frame properties can be undefined. This make sence when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // shape is linked to placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // now shape inherits x, y, height, flipH, flipV values form placeholder and overrides width=100 and rotationAngle=0.{code}
> ```

**Renvoie :**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
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
>  //Un tel code peut entraîner des situations ambiguës. Ainsi des restrictions ont été ajoutées pour interdire l’utilisation de valeurs non définies pour IShape.getFrame(). Les valeurs de x, y, width, height, flipH, flipV et rotationAngle doivent être définies (pas Float.NaN ou NullableBool.NotDefined). Le code ci-dessus lance maintenant une exception ArgumentException.
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
>  //Mais les propriétés du cadre IShape.RawFrame peuvent être indéfinies. Cela a du sens lorsque la forme est liée à un placeholder. Alors les valeurs de cadre indéfinies sont remplacées par celles du placeholder parent. S’il n’existe pas de placeholder parent pour cette forme, alors la forme utilise les valeurs par défaut lorsqu’elle calcule le cadre effectif à partir de son IShape.RawFrame. Les valeurs par défaut sont 0 et NullableBool.False pour x, y, width, height, flipH, flipV et rotationAngle. Par exemple :
>  IShape shape = ...; // la forme est liée au placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // maintenant la forme hérite des valeurs x, y, height, flipH, flipV du placeholder et remplace width=100 et rotationAngle=0.{code}
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Renvoie ou définit les propriétés du cadre de la forme. Lecture/écriture [IShapeFrame](../../com.aspose.slides/ishapeframe).

Valeur de chaque propriété de l’instance IShapeFrame retournée n’est pas indéfinie (n’est pas NaN ou NotDefined). Valeur de chaque propriété de l’instance IShapeFrame assignée doit être définie (ne doit pas être NaN ou NotDefined). Vous pouvez définir des valeurs indéfinies pour les propriétés de l’instance RawFrame.

**Renvoie :**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Renvoie ou définit les propriétés du cadre de la forme. Lecture/écriture [IShapeFrame](../../com.aspose.slides/ishapeframe).

Valeur de chaque propriété de l’instance IShapeFrame retournée n’est pas indéfinie (n’est pas NaN ou NotDefined). Valeur de chaque propriété de l’instance IShapeFrame assignée doit être définie (ne doit pas être NaN ou NotDefined). Vous pouvez définir des valeurs indéfinies pour les propriétés de l’instance RawFrame.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

Renvoie l’objet LineFormat qui contient les propriétés de formatage de ligne pour une forme. Remarque : peut renvoyer null pour certains types de formes qui n’ont pas de propriétés de ligne. Lecture seule [ILineFormat](../../com.aspose.slides/ilineformat).

**Renvoie :**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

Renvoie l’objet ThreeDFormat qui contient les propriétés d’effet 3D pour une forme. Remarque : peut renvoyer null pour certains types de formes qui n’ont pas de propriétés 3D. Lecture seule [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Renvoie :**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

Renvoie l’objet EffectFormat qui contient les effets pixels appliqués à une forme. Remarque : peut renvoyer null pour certains types de formes qui n’ont pas de propriétés d’effet. Lecture seule [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Renvoie :**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Renvoie l’objet FillFormat qui contient les propriétés de formatage de remplissage pour une forme. Remarque : peut renvoyer null pour certains types de formes qui n’ont pas de propriétés de remplissage. Lecture seule [IFillFormat](../../com.aspose.slides/ifillformat).

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
>      // Accent 4, plus clair 80%
>      IShape shape2 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 70, 50, 50);
>      shape2.getFillFormat().setFillType(FillType.Solid);
>      shape2.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.2f);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.8f);
>      // Accent 4, plus clair 60%
>      IShape shape3 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 130, 50, 50);
>      shape3.getFillFormat().setFillType(FillType.Solid);
>      shape3.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.4f);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.6f);
>      // Accent 4, plus clair 40%
>      IShape shape4 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 190, 50, 50);
>      shape4.getFillFormat().setFillType(FillType.Solid);
>      shape4.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.6f);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.4f);
>      // Accent 4, plus foncé 25%
>      IShape shape5 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 250, 50, 50);
>      shape5.getFillFormat().setFillType(FillType.Solid);
>      shape5.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape5.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.75f);
>      // Accent 4, plus foncé 50%
>      IShape shape6 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 310, 50, 50);
>      shape6.getFillFormat().setFillType(FillType.Solid);
>      shape6.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape6.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.5f);
>      pres.save("example_accent4.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Renvoie :**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public final IImage getImage()
```

Renvoie la miniature de la forme. Le type ShapeThumbnailBounds.Shape des limites de la miniature de forme est utilisé par défaut.

**Renvoie :**
[IImage](../../com.aspose.slides/iimage) - miniature de forme.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IImage getImage(int bounds, float scaleX, float scaleY)
```

Renvoie la miniature de la forme.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| bounds | int | Type de limites de la miniature de forme. |
| scaleX | float | Échelle X |
| scaleY | float | Échelle Y |

**Renvoie :**
[IImage](../../com.aspose.slides/iimage) - miniature de forme ou null dans le cas où ShapeThumbnailBounds.Appearance est utilisé et qu’une forme n’a pas d’éléments visibles.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

Enregistre le contenu de Shape sous forme de fichier SVG.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Flux cible |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Enregistre le contenu de Shape sous forme de fichier SVG.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Flux cible |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Options de génération SVG |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

Renvoie ou définit le lien hypertexte défini pour le clic de la souris. Lecture/écriture [IHyperlink](../../com.aspose.slides/ihyperlink).

**Renvoie :**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

Renvoie ou définit le lien hypertexte défini pour le clic de la souris. Lecture/écriture [IHyperlink](../../com.aspose.slides/ihyperlink).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

Renvoie ou définit le lien hypertexte défini pour le survol de la souris. Lecture/écriture [IHyperlink](../../com.aspose.slides/ihyperlink).

**Renvoie :**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

Renvoie ou définit le lien hypertexte défini pour le survol de la souris. Lecture/écriture [IHyperlink](../../com.aspose.slides/ihyperlink).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

Renvoie le gestionnaire de liens hypertexte. Lecture seule [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Renvoie :**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Détermine si la forme est masquée. Lecture/écriture  booléen .

**Renvoie :**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Détermine si la forme est masquée. Lecture/écriture  booléen .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

Renvoie la position d’une forme dans l’ordre Z. Shapes[0] renvoie la forme à l’arrière de l’ordre Z, et Shapes[Shapes.Count - 1] renvoie la forme à l’avant de l’ordre Z. Lecture seule  int .

**Renvoie :**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```

Renvoie le nombre de sites de connexion sur la forme. Lecture seule  int .

**Renvoie :**
int

### getRotation() {#getRotation--}
```
public final float getRotation()
```

Renvoie ou définit le nombre de degrés dont la forme spécifiée est pivotée autour de l’axe Z. Une valeur positive indique une rotation horaire ; une valeur négative indique une rotation antihoraire. Lecture/écriture float.

--------------------

Valeur retournée est toujours définie (n’est pas Float.NaN). La valeur assignée doit être définie (pas Float.NaN). Vous pouvez définir des valeurs indéfinies pour les propriétés de l’instance RawFrame.

**Renvoie :**
float

### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```
Renvoie ou définit le nombre de degrés selon lesquels la forme spécifiée est pivotée autour de l'axe z. Une valeur positive indique une rotation dans le sens horaire ; une valeur négative indique une rotation dans le sens antihoraire. Lecture/écriture float.

--------------------

La valeur renvoyée est toujours définie (n’est pas Float.NaN). La valeur assignée doit être définie (pas Float.NaN). Vous pouvez définir des valeurs indéfinies pour les propriétés d’instance RawFrame.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public final float getX()
```

Obtient ou définit la coordonnée x du coin supérieur gauche de la forme, mesurée en points. Lecture/écriture float.

--------------------

La valeur renvoyée est toujours définie et n’est jamais Float.NaN. La valeur assignée doit également être définie ; n’affectez Float.NaN qu’aux propriétés d’une instance RawFrame.

**Retour :**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Obtient ou définit la coordonnée x du coin supérieur gauche de la forme, mesurée en points. Lecture/écriture float.

--------------------

La valeur renvoyée est toujours définie et n’est jamais Float.NaN. La valeur assignée doit également être définie ; n’affectez Float.NaN qu’aux propriétés d’une instance RawFrame.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

Obtient ou définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points. Lecture/écriture float.

--------------------

La valeur renvoyée est toujours définie et n’est jamais Float.NaN. La valeur assignée doit également être définie ; n’affectez Float.NaN qu’aux propriétés d’une instance RawFrame.

**Retour :**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Obtient ou définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points. Lecture/écriture float.

--------------------

La valeur renvoyée est toujours définie et n’est jamais Float.NaN. La valeur assignée doit également être définie ; n’affectez Float.NaN qu’aux propriétés d’une instance RawFrame.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Obtient ou définit la largeur de la forme, mesurée en points. Lecture/écriture float.

--------------------

La valeur renvoyée est toujours définie et n’est jamais Float.NaN. La valeur assignée doit également être définie ; n’affectez Float.NaN qu’aux propriétés d’une instance RawFrame.

**Retour :**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Obtient ou définit la largeur de la forme, mesurée en points. Lecture/écriture float.

--------------------

La valeur renvoyée est toujours définie et n’est jamais Float.NaN. La valeur assignée doit également être définie ; n’affectez Float.NaN qu’aux propriétés d’une instance RawFrame.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Obtient ou définit la hauteur de la forme, mesurée en points. Lecture/écriture float.

--------------------

La valeur renvoyée est toujours définie et n’est jamais Float.NaN. La valeur assignée doit également être définie ; n’affectez Float.NaN qu’aux propriétés d’une instance RawFrame.

**Retour :**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Obtient ou définit la hauteur de la forme, mesurée en points. Lecture/écriture float.

--------------------

La valeur renvoyée est toujours définie et n’est jamais Float.NaN. La valeur assignée doit également être définie ; n’affectez Float.NaN qu’aux propriétés d’une instance RawFrame.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```

La propriété spécifie comment une forme sera rendue en mode d’affichage noir et blanc. Lecture/écriture [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Retour :**
byte
### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```

La propriété spécifie comment une forme sera rendue en mode d’affichage noir et blanc. Lecture/écriture [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```

Renvoie un identifiant interne, limité à la présentation, destiné à être utilisé par les compléments ou autre code. Étant donné que cette valeur peut être réassignée par l’utilisateur ou programmatiquement, elle ne doit pas être traitée comme une clé unique persistante. Lecture seule long. Voir aussi \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Retour :**
long
### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```

Renvoie un identifiant unique limité à la diapositive qui reste constant pendant la durée de vie de la forme et permet à PowerPoint ou au code interop de référencer la forme de manière fiable depuis n’importe où dans le document. Lecture seule long. Voir aussi \#getUniqueId.getUniqueId.

**Retour :**
long
### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```

Renvoie ou définit le texte alternatif associé à une forme. Lecture/écriture String.

**Retour :**
java.lang.String
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```

Renvoie ou définit le texte alternatif associé à une forme. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```

Renvoie ou définit le titre du texte alternatif associé à une forme. Lecture/écriture String.

**Retour :**
java.lang.String
### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```

Renvoie ou définit le titre du texte alternatif associé à une forme. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```

Renvoie ou définit le nom d’une forme. Doit être non nul. Utilisez une chaîne vide si nécessaire. Lecture/écriture String.

**Retour :**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Renvoie ou définit le nom d’une forme. Doit être non nul. Utilisez une chaîne vide si nécessaire. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```

Obtient ou définit l’option « Marquer comme décoratif ». Lecture/écriture boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retour :**
boolean
### setDecorative(boolean value) {#setDecorative-boolean-}
```
public final void setDecorative(boolean value)
```

Obtient ou définit l’option « Marquer comme décoratif ». Lecture/écriture boolean.

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
public IBaseShapeLock getShapeLock()
```

Renvoie les verrous de la forme. Lecture seule [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Retour :**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```

Détermine si la forme est groupée. Lecture seule boolean.

--------------------

La propriété \#getParentGroup.getParentGroup renvoie l’objet GroupShape parent si la forme est groupée.

**Retour :**
boolean
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Renvoie l’objet GroupShape parent si la forme est groupée. Sinon, renvoie null. Lecture seule [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

La propriété \#isGrouped.isGrouped détermine si la forme est groupée.

**Retour :**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Renvoie l’objet Parent_Immediate. Lecture seule IDOMObject.

**Retour :**
com.aspose.slides.IDOMObject
### getVisualBounds() {#getVisualBounds--}
```
public final Rectangle2D.Float getVisualBounds()
```

Obtient les limites visuelles de la forme calculées à partir de son contenu rendu.

**Retour :**
java.awt.geom.Rectangle2D.Float - Un java.awt.geom.Rectangle2D.Float qui représente les limites visuelles de la forme dans les coordonnées de la diapositive.

--------------------

Le rectangle renvoyé représente les limites alignées sur les axes de tout le contenu produit par la forme lors du rendu dans l’espace de coordonnées de la diapositive. Ces limites peuvent différer des limites du modèle de la forme \#getX.getX/\#setX(float).setX(float), \#getY.getY/\#setY(float).setY(float), \#getWidth.getWidth/\#setWidth(float).setWidth(float), \#getHeight.getHeight/\#setHeight(float).setHeight(float) et peuvent contenir des coordonnées négatives si le contenu rendu dépasse l’origine de la diapositive. Les limites visuelles tiennent compte d’aspects liés au rendu tels que les transformations (par exemple, la rotation), la largeur et les jointures du trait, la mise en page et le débordement du texte, la géométrie SmartArt et d’autres effets de mise en page qui influencent l’apparence finale rendue de la forme. Les limites renvoyées ne sont pas découpées selon le rectangle de la diapositive.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Renvoie la diapositive parent d’une forme. Lecture seule [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Retour :**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Renvoie la présentation parent d’une diapositive. Lecture seule [IPresentation](../../com.aspose.slides/ipresentation).

**Retour :**
[IPresentation](../../com.aspose.slides/ipresentation)