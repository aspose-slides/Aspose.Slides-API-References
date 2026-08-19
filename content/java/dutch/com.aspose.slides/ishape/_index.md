---
title: IShape
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een shape op een dia voor.
type: docs
url: /nl/com.aspose.slides/ishape/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IShape extends ISlideComponent, IHyperlinkContainer
```

Stelt een shape op een slide voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Bepaalt of de shape TextHolder is. |
| [getPlaceholder()](#getPlaceholder--) | Retourneert de placeholder voor een shape. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Voegt een nieuwe placeholder toe als er geen is en stelt placeholder-eigenschappen in op een opgegeven. |
| [removePlaceholder()](#removePlaceholder--) | Definieert dat deze shape geen placeholder is. |
| [getCustomData()](#getCustomData--) | Retourneert de aangepaste gegevens van de shape. |
| [getRawFrame()](#getRawFrame--) | Retourneert of stelt de onbewerkte shape-frame-eigenschappen in. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Retourneert of stelt de onbewerkte shape-frame-eigenschappen in. |
| [getFrame()](#getFrame--) | Retourneert of stelt de onbewerkte shape-frame-eigenschappen in. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Retourneert of stelt de onbewerkte shape-frame-eigenschappen in. |
| [getLineFormat()](#getLineFormat--) | Retourneert het LineFormat-object dat lijnafdrukken bevat voor een shape. |
| [getThreeDFormat()](#getThreeDFormat--) | Retourneert het ThreeDFormat-object dat lijnafdrukken bevat voor een shape. |
| [getEffectFormat()](#getEffectFormat--) | Retourneert het EffectFormat-object dat pixel-effecten bevat die op een shape zijn toegepast. |
| [getFillFormat()](#getFillFormat--) | Retourneert het FillFormat-object dat opvulleigenschappen bevat voor een shape. |
| [getImage()](#getImage--) | Retourneert shape thumbnail. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Retourneert shape thumbnail. |
| [getHidden()](#getHidden--) | Bepaalt of de shape verborgen is. |
| [setHidden(boolean value)](#setHidden-boolean-) | Bepaalt of de shape verborgen is. |
| [getZOrderPosition()](#getZOrderPosition--) | Retourneert de positie van een shape in de z-volgorde. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Retourneert het aantal verbindingspunten op de shape. |
| [getRotation()](#getRotation--) | Retourneert of stelt het aantal graden in dat de opgegeven shape rond de z-as wordt gedraaid. |
| [setRotation(float value)](#setRotation-float-) | Retourneert of stelt het aantal graden in dat de opgegeven shape rond de z-as wordt gedraaid. |
| [getX()](#getX--) | Haalt of stelt de x-coördinaat van de linkerbovenhoek van de shape in, gemeten in punten. |
| [setX(float value)](#setX-float-) | Haalt of stelt de x-coördinaat van de linkerbovenhoek van de shape in, gemeten in punten. |
| [getY()](#getY--) | Haalt of stelt de y-coördinaat van de linkerbovenhoek van de shape in, gemeten in punten. |
| [setY(float value)](#setY-float-) | Haalt of stelt de y-coördinaat van de linkerbovenhoek van de shape in, gemeten in punten. |
| [getWidth()](#getWidth--) | Haalt of stelt de breedte van de shape in, gemeten in punten. |
| [setWidth(float value)](#setWidth-float-) | Haalt of stelt de breedte van de shape in, gemeten in punten. |
| [getHeight()](#getHeight--) | Haalt of stelt de hoogte van de shape in, gemeten in punten. |
| [setHeight(float value)](#setHeight-float-) | Haalt of stelt de hoogte van de shape in, gemeten in punten. |
| [getAlternativeText()](#getAlternativeText--) | Retourneert of stelt de alternatieve tekst in die aan een shape is gekoppeld. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Retourneert of stelt de alternatieve tekst in die aan een shape is gekoppeld. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Retourneert of stelt de titel van de alternatieve tekst in die aan een shape is gekoppeld. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Retourneert of stelt de titel van de alternatieve tekst in die aan een shape is gekoppeld. |
| [getName()](#getName--) | Retourneert of stelt de naam van een shape in. |
| [setName(String value)](#setName-java.lang.String-) | Retourneert of stelt de naam van een shape in. |
| [isDecorative()](#isDecorative--) | Haalt of stelt de optie ‘Mark as decorative’ in, Lezen/schrijven boolean. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Haalt of stelt de optie ‘Mark as decorative’ in, Lezen/schrijven boolean. |
| [getShapeLock()](#getShapeLock--) | Retourneert de vergrendelingen van de shape. |
| [getUniqueId()](#getUniqueId--) | Retourneert een interne, presentatiespecifieke identifier bedoeld voor gebruik door add-ins of andere code. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Retourneert een uniek identifier met slide-scope die constant blijft gedurende de levensduur van de shape en PowerPoint of interop-code in staat stelt de shape betrouwbaar te refereren vanaf elke plaats in het document. |
| [isGrouped()](#isGrouped--) | Bepaalt of de shape gegroepeerd is. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Eigenschap geeft aan hoe een shape wordt weergegeven in zwart-wit weergavemodus. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Eigenschap geeft aan hoe een shape wordt weergegeven in zwart-wit weergavemodus. |
| [getParentGroup()](#getParentGroup--) | Retourneert het bovenliggende GroupShape-object als de shape gegroepeerd is. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Slaat de inhoud van Shape op als SVG-bestand. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Slaat de inhoud van Shape op als SVG-bestand. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Retourneert een basis placeholder shape (shape van de lay-out en/of masterslide waarvan de huidige shape is geërfd). |

### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```

Bepaalt of de shape TextHolder is. Alleen-lezen boolean.

**Retourneert:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public abstract IPlaceholder getPlaceholder()
```

Retourneert de placeholder voor een shape. Alleen-lezen [IPlaceholder](../../com.aspose.slides/iplaceholder).

**Retourneert:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public abstract IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Voegt een nieuwe placeholder toe als er geen is en stelt placeholder-eigenschappen in op een opgegeven.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Placeholder om inhoud van te kopiëren. |

**Retourneert:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - New [IPlaceholder](../../com.aspose.slides/iplaceholder).

### removePlaceholder() {#removePlaceholder--}
```
public abstract void removePlaceholder()
```

Definieert dat deze shape geen placeholder is.

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Retourneert de aangepaste gegevens van de shape. Alleen-lezen [ICustomData](../../com.aspose.slides/icustomdata).

**Retourneert:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public abstract IShapeFrame getRawFrame()
```

Retourneert of stelt de onbewerkte shape-frame-eigenschappen in. Lezen/schrijven [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //of
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Dergelijke code kan tot onduidelijke situaties leiden. Daarom zijn beperkingen toegevoegd voor het gebruik van ongedefinieerde waarden voor IShape.getFrame(). De waarden van x, y, width, height, flipH, flipV en rotationAngle moeten gedefinieerd zijn (niet Float.NaN of NullableBool.NotDefined). In het voorbeeld wordt nu een ArgumentException gegooid.
>  //Dit geldt voor deze use cases:
>  IShape shape = ...;
>  shape.setFrame(...); // mag niet undefined zijn
>  IShapeCollection shapes = ...;
>  // x, y, breedte, hoogte parameters kunnen niet Float.NaN zijn:
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
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // nu erft de shape x, y, hoogte, flipH, flipV waarden van de placeholder en overschrijft width=100 en rotationAngle=0.
```

**Retourneert:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
```

Retourneert of stelt de onbewerkte shape-frame-eigenschappen in. Lezen/schrijven [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //of
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Zo'n code kan tot onduidelijke situaties leiden. Daarom zijn beperkingen toegevoegd voor het gebruik van ongedefinieerde waarden voor IShape.getFrame(). De waarden van x, y, width, height, flipH, flipV en rotationAngle moeten gedefinieerd zijn (niet Float.NaN of NullableBool.NotDefined). Bovenstaande voorbeeldcode werpt nu een ArgumentException.
>  //Dit geldt voor deze use cases:
>  IShape shape = ...;
>  shape.setFrame(...); // mag niet undefined zijn
>  IShapeCollection shapes = ...;
>  // x, y, width, height parameters kunnen niet Float.NaN zijn:
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
>  IShape shape = ...; // shape is gekoppeld aan placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // nu erft de shape x, y, height, flipH, flipV waarden van de placeholder en overschrijft width=100 en rotationAngle=0.
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

Retourneert of stelt de shape-frame-eigenschappen in. Lezen/schrijven [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

De waarde van elke eigenschap van de geretourneerde IShapeFrame-instantie is niet undefined (is niet Float.NaN). De waarde van elke eigenschap van de toegewezen IShapeFrame-instantie moet niet undefined zijn (mag niet Float.NaN). U kunt undefined-waarden instellen voor RawFrame-instantiëen.

**Retourneert:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

Retourneert of stelt de shape-frame-eigenschappen in. Lezen/schrijven [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

De waarde van elke eigenschap van de geretourneerde IShapeFrame-instantie is niet undefined (is niet Float.NaN). De waarde van elke eigenschap van de toegewezen IShapeFrame-instantie moet niet undefined zijn (mag niet Float.NaN). U kunt undefined-waarden instellen voor RawFrame-instantiëen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Retourneert het LineFormat-object dat lijnafdrukken bevat voor een shape. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

**Retourneert:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

Retourneert het ThreeDFormat-object dat lijnafdrukken bevat voor een shape. Alleen-lezen [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Retourneert:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Retourneert het EffectFormat-object dat pixel-effecten bevat die op een shape zijn toegepast. Alleen-lezen [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Retourneert:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Retourneert het FillFormat-object dat opvulleigenschappen bevat voor een shape. Alleen-lezen [IFillFormat](../../com.aspose.slides/ifillformat).

**Retourneert:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Retourneert shape thumbnail. ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

**Retourneert:**
[IImage](../../com.aspose.slides/iimage) - Shape thumbnail.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public abstract IImage getImage(int bounds, float scaleX, float scaleY)
```

Retourneert shape thumbnail.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bounds | int | Shape thumbnail bounds type. |
| scaleX | float | X scale |
| scaleY | float | Y scale |

**Retourneert:**
[IImage](../../com.aspose.slides/iimage) - Shape thumbnail or null in case when ShapeThumbnailBounds.Appearance is used and a shape doesn't have visible elements.

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Bepaalt of de shape verborgen is. Lezen/schrijven boolean.

**Retourneert:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Bepaalt of de shape verborgen is. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```

Retourneert de positie van een shape in de z-volgorde. Shapes[0] returns the shape at the back of the z-order, and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order. Alleen-lezen int.

**Retourneert:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```

Retourneert het aantal verbindingspunten op de shape. Alleen-lezen int.

**Retourneert:**
int

### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

Retourneert of stelt het aantal graden in dat de opgegeven shape rond de z-as wordt gedraaid. Een positieve waarde duidt op rotatie met de klok mee; een negatieve waarde duidt op tegen de klok in rotatie. Lezen/schrijven float.

--------------------

De geretourneerde waarde is altijd gedefinieerd (is niet Float.NaN). De toegewezen waarde moet gedefinieerd zijn (niet Float.NaN). U kunt undefined-waarden instellen voor RawFrame-instantiëen.

**Retourneert:**
float

### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```

Retourneert of stelt het aantal graden in dat de opgegeven shape rond de z-as wordt gedraaid. Een positieve waarde duidt op rotatie met de klok mee; een negatieve waarde duidt op tegen de klok in rotatie. Lezen/schrijven float.

--------------------

De geretourneerde waarde is altijd gedefinieerd (is niet Float.NaN). De toegewezen waarde moet gedefinieerd zijn (niet Float.NaN). U kunt undefined-waarden instellen voor RawFrame-instantiëen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public abstract float getX()
```

Haalt of stelt de x-coördinaat van de linkerbovenhoek van de shape in, gemeten in punten. Lezen/schrijven float.

--------------------

De geretourneerde waarde is altijd gedefinieerd en nooit Float.NaN. De toegewezen waarde moet ook gedefinieerd zijn; stel Float.NaN alleen in voor eigenschappen van een RawFrame-instantie.

**Retourneert:**
float

### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```

Haalt of stelt de x-coördinaat van de linkerbovenhoek van de shape in, gemeten in punten. Lezen/schrijven float.

--------------------

De geretourneerde waarde is altijd gedefinieerd en nooit Float.NaN. De toegewezen waarde moet ook gedefinieerd zijn; stel Float.NaN alleen in voor eigenschappen van een RawFrame-instantie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public abstract float getY()
```

Haalt of stelt de y-coördinaat van de linkerbovenhoek van de shape in, gemeten in punten. Lezen/schrijven float.

--------------------

De geretourneerde waarde is altijd gedefinieerd en nooit Float.NaN. De toegewezen waarde moet ook gedefinieerd zijn; stel Float.NaN alleen in voor eigenschappen van een RawFrame-instantie.

**Retourneert:**
float

### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```

Haalt of stelt de y-coördinaat van de linkerbovenhoek van de shape in, gemeten in punten. Lezen/schrijven float.

--------------------

De geretourneerde waarde is altijd gedefinieerd en nooit Float.NaN. De toegewezen waarde moet ook gedefinieerd zijn; stel Float.NaN alleen in voor eigenschappen van een RawFrame-instantie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

Haalt of stelt de breedte van de shape in, gemeten in punten. Lezen/schrijven float.

--------------------

De geretourneerde waarde is altijd gedefinieerd en nooit Float.NaN. De toegewezen waarde moet ook gedefinieerd zijn; stel Float.NaN alleen in voor eigenschappen van een RawFrame-instantie.

**Retourneert:**
float

### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```

Haalt of stelt de breedte van de shape in, gemeten in punten. Lezen/schrijven float.

--------------------

De geretourneerde waarde is altijd gedefinieerd en nooit Float.NaN. De toegewezen waarde moet ook gedefinieerd zijn; stel Float.NaN alleen in voor eigenschappen van een RawFrame-instantie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Haalt of stelt de hoogte van de shape in, gemeten in punten. Lezen/schrijven float.

--------------------

De geretourde waarde is altijd gedefinieerd en nooit Float.NaN. De toegewezen waarde moet ook gedefinieerd zijn; stel Float.NaN alleen in voor eigenschappen van een RawFrame-instantie.

**Retourneert:**
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Haalt of stelt de hoogte van de shape in, gemeten in punten. Lezen/schrijven float.

--------------------

De geretourde waarde is altijd gedefinieerd en nooit Float.NaN. De toegewezen waarde moet ook gedefinieerd zijn; stel Float.NaN alleen in voor eigenschappen van een RawFrame-instantie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getAlternativeText() {#getAlternativeText--}
```
public abstract String getAlternativeText()
```

Retourneert of stelt de alternatieve tekst in die aan een shape is gekoppeld. Lezen/schrijven String.

**Retourneert:**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public abstract void setAlternativeText(String value)
```

Retourneert of stelt de alternatieve tekst in die aan een shape is gekoppeld. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public abstract String getAlternativeTextTitle()
```

Retourneert of stelt de titel van de alternatieve tekst in die aan een shape is gekoppeld. Lezen/schrijven String.

**Retourneert:**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public abstract void setAlternativeTextTitle(String value)
```

Retourneert of stelt de titel van de alternatieve tekst in die aan een shape is gekoppeld. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public abstract String getName()
```

Retourneert of stelt de naam van een shape in. Lezen/schrijven String.

**Retourneert:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Retourneert of stelt de naam van een shape in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```

Haalt of stelt de optie ‘Mark as decorative’ in, Lezen/schrijven boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourneert:**
boolean

### setDecorative(boolean value) {#setDecorative-boolean-}
```
public abstract void setDecorative(boolean value)
```

Haalt of stelt de optie ‘Mark as decorative’ in, Lezen/schrijven boolean.

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
public abstract IBaseShapeLock getShapeLock()
```

Retourneert de vergrendelingen van de shape. Alleen-lezen [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Retourneert:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### getUniqueId() {#getUniqueId--}
```
public abstract long getUniqueId()
```

Retourneert een interne, presentatiespecifieke identifier bedoeld voor gebruik door add-ins of andere code. Omdat deze waarde door de gebruiker of programmatisch kan worden herkend, dient deze niet als een persistent unieke sleutel te worden beschouwd. Alleen-lezen long. Zie ook \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Retourneert:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public abstract long getOfficeInteropShapeId()
```

Retourneert een slide-scoped uniek identifier die constant blijft gedurende de levensduur van de shape en PowerPoint of interop-code in staat stelt de shape betrouwbaar te refereren vanaf elke plaats in het document. Alleen-lezen long. Zie ook \#getUniqueId.getUniqueId.

**Retourneert:**
long

### isGrouped() {#isGrouped--}
```
public abstract boolean isGrouped()
```

Bepaalt of de shape gegroepeerd is. Alleen-lezen boolean.

--------------------

Eigenschap \#getParentGroup.getParentGroup retourneert het bovenliggende GroupShape-object als de shape gegroepeerd is.

**Retourneert:**
boolean

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public abstract byte getBlackWhiteMode()
```

Eigenschap geeft aan hoe een shape wordt weergegeven in zwart-wit weergavemodus. Lezen/schrijven [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Retourneert:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```

Eigenschap geeft aan hoe een shape wordt weergegeven in zwart-wit weergavemodus. Lezen/schrijven [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Retourneert het bovenliggende GroupShape-object als de shape gegroepeerd is. Anders retourneert null. Alleen-lezen [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

Eigenschap \#isGrouped.isGrouped bepaalt of de shape gegroepeerd is.

**Retourneert:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

Slaat de inhoud van Shape op als SVG-bestand.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Doel-stream |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Slaat de inhoud van Shape op als SVG-bestand.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Doel-stream |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG-generatie-opties |

### getBasePlaceholder() {#getBasePlaceholder--}
```
public abstract IShape getBasePlaceholder()
```

Retourneert een basis placeholder shape (shape van de lay-out en/of masterslide waarvan de huidige shape is geërfd).

--------------------

> ```
> // verkrijg alle (master/layout/slide) geanimeerde effecten van de placeholder shape
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

Een null wordt geretourneerd als de huidige shape niet geërfd is.

**Retourneert:**
[IShape](../../com.aspose.slides/ishape)