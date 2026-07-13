---
title: IShape
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een vorm op een dia voor.
type: docs
url: /nl/com.aspose.slides/ishape/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IShape extends ISlideComponent, IHyperlinkContainer
```

Stelt een vorm op een dia voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Bepaalt of de vorm een TextHolder is. |
| [getPlaceholder()](#getPlaceholder--) | Retourneert de placeholder voor een vorm. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Voegt een nieuwe placeholder toe als er geen is en stelt placeholder-eigenschappen in op een opgegeven. |
| [removePlaceholder()](#removePlaceholder--) | Definieert dat deze vorm geen placeholder is. |
| [getCustomData()](#getCustomData--) | Retourneert de aangepaste gegevens van de vorm. |
| [getRawFrame()](#getRawFrame--) | Retourneert of stelt de eigenschappen van het ruwe vormframe in. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Retourneert of stelt de eigenschappen van het ruwe vormframe in. |
| [getFrame()](#getFrame--) | Retourneert of stelt de eigenschappen van het vormframe in. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Retourneert of stelt de eigenschappen van het vormframe in. |
| [getLineFormat()](#getLineFormat--) | Retourneert het LineFormat-object dat lijnopmaak-eigenschappen voor een vorm bevat. |
| [getThreeDFormat()](#getThreeDFormat--) | Retourneert het ThreeDFormat-object dat lijnopmaak-eigenschappen voor een vorm bevat. |
| [getEffectFormat()](#getEffectFormat--) | Retourneert het EffectFormat-object dat pixel-effecten op een vorm bevat. |
| [getFillFormat()](#getFillFormat--) | Retourneert het FillFormat-object dat vulopmaak-eigenschappen voor een vorm bevat. |
| [getImage()](#getImage--) | Retourneert een miniatuur van de vorm. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Retourneert een miniatuur van de vorm. |
| [getHidden()](#getHidden--) | Bepaalt of de vorm verborgen is. |
| [setHidden(boolean value)](#setHidden-boolean-) | Bepaalt of de vorm verborgen is. |
| [getZOrderPosition()](#getZOrderPosition--) | Retourneert de positie van een vorm in de z-volgorde. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Retourneert het aantal aansluitpunten op de vorm. |
| [getRotation()](#getRotation--) | Retourneert of stelt het aantal graden in waarmee de opgegeven vorm rond de z-as wordt gedraaid. |
| [setRotation(float value)](#setRotation-float-) | Retourneert of stelt het aantal graden in waarmee de opgegeven vorm rond de z-as wordt gedraaid. |
| [getX()](#getX--) | Haalt of stelt de x-coördinaat van de linkerbovenhoek van de vorm op, gemeten in punten. |
| [setX(float value)](#setX-float-) | Haalt of stelt de x-coördinaat van de linkerbovenhoek van de vorm op, gemeten in punten. |
| [getY()](#getY--) | Haalt of stelt de y-coördinaat van de linkerbovenhoek van de vorm op, gemeten in punten. |
| [setY(float value)](#setY-float-) | Haalt of stelt de y-coördinaat van de linkerbovenhoek van de vorm op, gemeten in punten. |
| [getWidth()](#getWidth--) | Haalt of stelt de breedte van de vorm op, gemeten in punten. |
| [setWidth(float value)](#setWidth-float-) | Haalt of stelt de breedte van de vorm op, gemeten in punten. |
| [getHeight()](#getHeight--) | Haalt of stelt de hoogte van de vorm op, gemeten in punten. |
| [setHeight(float value)](#setHeight-float-) | Haalt of stelt de hoogte van de vorm op, gemeten in punten. |
| [getAlternativeText()](#getAlternativeText--) | Retourneert of stelt de alternatieve tekst in die aan een vorm is gekoppeld. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Retourneert of stelt de alternatieve tekst in die aan een vorm is gekoppeld. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Retourneert of stelt de titel van de alternatieve tekst in die aan een vorm is gekoppeld. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Retourneert of stelt de titel van de alternatieve tekst in die aan een vorm is gekoppeld. |
| [getName()](#getName--) | Retourneert of stelt de naam van een vorm in. |
| [setName(String value)](#setName-java.lang.String-) | Retourneert of stelt de naam van een vorm in. |
| [isDecorative()](#isDecorative--) | Haalt of stelt de optie 'Mark as decorative' in, Lezen/schrijven boolean. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Haalt of stelt de optie 'Mark as decorative' in, Lezen/schrijven boolean. |
| [getShapeLock()](#getShapeLock--) | Retourneert de vergrendelingen van de vorm. |
| [getUniqueId()](#getUniqueId--) | Retourneert een interne, presentatie-bereik identifier bedoeld voor gebruik door add-ins of andere code. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Retourneert een dia-bereik unieke identifier die constant blijft gedurende de levensduur van de vorm en PowerPoint of interop-code in staat stelt de vorm betrouwbaar te refereren vanaf elke plaats in het document. |
| [isGrouped()](#isGrouped--) | Bepaalt of de vorm gegroepeerd is. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Eigenschap specificeert hoe een vorm wordt weergegeven in zwart-wit weergavemodus. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Eigenschap specificeert hoe een vorm wordt weergegeven in zwart-wit weergavemodus. |
| [getParentGroup()](#getParentGroup--) | Retourneert het bovenliggende GroupShape-object als de vorm gegroepeerd is. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Slaat de inhoud van Shape op als SVG-bestand. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Slaat de inhoud van Shape op als SVG-bestand. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Retourneert een basis placeholder-vorm (vorm van de lay-out en/of master-dia waar de huidige vorm van is geërfd). |

### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```

Bepaalt of de vorm een TextHolder is. Alleen-lezen boolean.

**Retour:**  
boolean

### getPlaceholder() {#getPlaceholder--}
```
public abstract IPlaceholder getPlaceholder()
```

Retourneert de placeholder voor een vorm. Alleen-lezen [IPlaceholder](../../com.aspose.slides/iplaceholder).

**Retour:**  
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public abstract IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Voegt een nieuwe placeholder toe als er geen is en stelt placeholder-eigenschappen in op een opgegeven.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Placeholder om inhoud van te kopiëren. |

**Retour:**  
[IPlaceholder](../../com.aspose.slides/iplaceholder) - Nieuwe [IPlaceholder](../../com.aspose.slides/iplaceholder).

### removePlaceholder() {#removePlaceholder--}
```
public abstract void removePlaceholder()
```

Definieert dat deze vorm geen placeholder is.

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Retourneert de aangepaste gegevens van de vorm. Alleen-lezen [ICustomData](../../com.aspose.slides/icustomdata).

**Retour:**  
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public abstract IShapeFrame getRawFrame()
```

Retourneert of stelt de eigenschappen van het ruwe vormframe in. Lezen/schrijven [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //of
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Dergelijke code kan tot onduidelijke situaties leiden. Er zijn beperkingen toegevoegd voor het gebruik van ongedefinieerde waarden voor IShape.getFrame(). Waarden van x, y, width, height, flipH, flipV en rotationAngle moeten gedefinieerd zijn (niet Float.NaN of NullableBool.NotDefined). Voorbeeldcode hierboven werpt nu een ArgumentException.
>  //Dit geldt voor de volgende gebruikssituaties:
>  IShape shape = ...;
>  shape.setFrame(...); // mag niet ongedefinieerd zijn
>  IShapeCollection shapes = ...;
>  // x, y, width, height parameters mogen geen Float.NaN zijn:
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
>  IShape shape = ...; // vorm is gekoppeld aan placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // nu erft de vorm x, y, height, flipH, flipV waarden van de placeholder en overschrijft width=100 en rotationAngle=0.
```

**Retour:**  
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
```

Retourneert of stelt de eigenschappen van het ruwe vormframe in. Lezen/schrijven [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //of
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Dergelijke code kan tot onduidelijke situaties leiden. Er zijn beperkingen toegevoegd voor het gebruik van ongedefinieerde waarden voor IShape.getFrame(). Waarden van x, y, width, height, flipH, flipV en rotationAngle moeten gedefinieerd zijn (niet Float.NaN of NullableBool.NotDefined). De voorbeeldcode hierboven werpt nu een ArgumentException.
>  //Dit geldt voor deze gebruikssituaties:
>  IShape shape = ...;
>  shape.setFrame(...); // mag niet ongedefinieerd zijn
>  IShapeCollection shapes = ...;
>  // x, y, width, height parameters mogen geen Float.NaN zijn:
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
>  IShape shape = ...; // vorm is gekoppeld aan placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // nu erft de vorm x, y, height, flipH, flipV waarden van de placeholder en overschrijft width=100 en rotationAngle=0.
```

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

Retourneert of stelt de eigenschappen van het vormframe in. Lezen/schrijven [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

De waarde van elke eigenschap van de geretourneerde IShapeFrame-instantie is niet ongedefinieerd (is niet NaN of NotDefined). De waarde van elke eigenschap van de toegewezen IShapeFrame-instantie moet niet ongedefinieerd zijn (mag niet NaN of NotDefined zijn). U kunt ongedefinieerde waarden toewijzen aan RawFrame-instantie-eigenschappen.

**Retour:**  
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

Retourneert of stelt de eigenschappen van het vormframe in. Lezen/schrijven [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

De waarde van elke eigenschap van de geretourneerde IShapeFrame-instantie is niet ongedefinieerd (is niet NaN of NotDefined). De waarde van elke eigenschap van de toegewezen IShapeFrame-instantie moet niet ongedefinieerd zijn (mag niet NaN of NotDefined zijn). U kunt ongedefinieerde waarden toewijzen aan RawFrame-instantie-eigenschappen.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Retourneert het LineFormat-object dat lijnopmaak-eigenschappen voor een vorm bevat. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

**Retour:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

Retourneert het ThreeDFormat-object dat lijnopmaak-eigenschappen voor een vorm bevat. Alleen-lezen [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Retour:**  
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Retourneert het EffectFormat-object dat pixel-effecten op een vorm bevat. Alleen-lezen [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Retour:**  
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Retourneert het FillFormat-object dat vulopmaak-eigenschappen voor een vorm bevat. Alleen-lezen [IFillFormat](../../com.aspose.slides/ifillformat).

**Retour:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Retourneert een miniatuur van de vorm. ShapeThumbnailBounds.Shape-miniatuursectie wordt standaard gebruikt.

**Retour:**  
[IImage](../../com.aspose.slides/iimage) - Miniatuur van de vorm.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public abstract IImage getImage(int bounds, float scaleX, float scaleY)
```

Retourneert een miniatuur van de vorm.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bounds | int | Miniatuursectie-type. |
| scaleX | float | X-schaal |
| scaleY | float | Y-schaal |

**Retour:**  
[IImage](../../com.aspose.slides/iimage) - Miniatuur van de vorm of null wanneer ShapeThumbnailBounds.Appearance wordt gebruikt en een vorm geen zichtbare elementen heeft.

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Bepaalt of de vorm verborgen is. Lezen/schrijven boolean.

**Retour:**  
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Bepaalt of de vorm verborgen is. Lezen/schrijven boolean.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```

Retourneert de positie van een vorm in de z-volgorde. Shapes[0] geeft de vorm aan de onderkant van de z-volgorde, en Shapes[Shapes.Count - 1] geeft de vorm aan de voorkant van de z-volgorde. Alleen-lezen int.

**Retour:**  
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```

Retourneert het aantal aansluitpunten op de vorm. Alleen-lezen int.

**Retour:**  
int

### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

Retourneert of stelt het aantal graden in waarmee de opgegeven vorm rond de z-as wordt gedraaid. Een positieve waarde duidt op met de klok mee draaien; een negatieve waarde duidt op tegen de klok in draaien. Lezen/schrijven float.

--------------------

De geretourneerde waarde is altijd gedefinieerd (is niet Float.NaN). De toegewezen waarde moet gedefinieerd zijn (niet Float.NaN). U kunt ongedefinieerde waarden toewijzen aan RawFrame-instantie-eigenschappen.

**Retour:**  
float

### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```

Retourneert of stelt het aantal graden in waarmee de opgegeven vorm rond de z-as wordt gedraaid. Een positieve waarde duidt op met de klok mee draaien; een negatieve waarde duidt op tegen de klok in draaien. Lezen/schrijven float.

--------------------

De geretourneerde waarde is altijd gedefinieerd (is niet Float.NaN). De toegewezen waarde moet gedefinieerd zijn (niet Float.NaN). U kunt ongedefinieerde waarden toewijzen aan RawFrame-instantie-eigenschappen.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public abstract float getX()
```

Haalt of stelt de x-coördinaat van de linkerbovenhoek van de vorm op, gemeten in punten. Lezen/schrijven float.

--------------------

De geretourneerde waarde is altijd gedefinieerd en nooit Float.NaN. De toegewezen waarde moet ook gedefinieerd zijn; wijs Float.NaN alleen toe aan eigenschappen van een RawFrame-instantie.

**Retour:**  
float

### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```

Haalt of stelt de x-coördinaat van de linkerbovenhoek van de vorm op, gemeten in punten. Lezen/schrijven float.

--------------------

De geretourneerde waarde is altijd gedefinieerd en nooit Float.NaN. De toegewezen waarde moet ook gedefinieerd zijn; wijs Float.NaN alleen toe aan eigenschappen van een RawFrame-instantie.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public abstract float getY()
```

Haalt of stelt de y-coördinaat van de linkerbovenhoek van de vorm op, gemeten in punten. Lezen/schrijven float.

--------------------

De geretourneerde waarde is altijd gedefinieerd en nooit Float.NaN. De toegewezen waarde moet ook gedefinieerd zijn; wijs Float.NaN alleen toe aan eigenschappen van een RawFrame-instantie.

**Retour:**  
float

### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```

Haalt of stelt de y-coördinaat van de linkerbovenhoek van de vorm op, gemeten in punten. Lezen/schrijven float.

--------------------

De geretourneerde waarde is altijd gedefinieerd en nooit Float.NaN. De toegewezen waarde moet ook gedefinieerd zijn; wijs Float.NaN alleen toe aan eigenschappen van een RawFrame-instantie.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

Haalt of stelt de breedte van de vorm op, gemeten in punten. Lezen/schrijven float.

--------------------

De geretourneerde waarde is altijd gedefinieerd en nooit Float.NaN. De toegewezen waarde moet ook gedefinieerd zijn; wijs Float.NaN alleen toe aan eigenschappen van een RawFrame-instantie.

**Retour:**  
float

### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```

Haalt of stelt de breedte van de vorm op, gemeten in punten. Lezen/schrijven float.

--------------------

De geretourneerde waarde is altijd gedefinieerd en nooit Float.NaN. De toegewezen waarde moet ook gedefinieerd zijn; wijs Float.NaN alleen toe aan eigenschappen van een RawFrame-instantie.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Haalt of stelt de hoogte van de vorm op, gemeten in punten. Lezen/schrijven float.

--------------------

De geretourdeerde waarde is altijd gedefinieerd en nooit Float.NaN. De toegewezen waarde moet ook gedefinieerd zijn; wijs Float.NaN alleen toe aan eigenschappen van een RawFrame-instantie.

**Retour:**  
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Haalt of stelt de hoogte van de vorm op, gemeten in punten. Lezen/schrijven float.

--------------------

De geretourdeerde waarde is altijd gedefinieerd en nooit Float.NaN. De toegewezen waarde moet ook gedefinieerd zijn; wijs Float.NaN alleen toe aan eigenschappen van een RawFrame-instantie.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getAlternativeText() {#getAlternativeText--}
```
public abstract String getAlternativeText()
```

Retourneert of stelt de alternatieve tekst in die aan een vorm is gekoppeld. Lezen/schrijven String.

**Retour:**  
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public abstract void setAlternativeText(String value)
```

Retourneert of stelt de alternatieve tekst in die aan een vorm is gekoppeld. Lezen/schrijven String.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public abstract String getAlternativeTextTitle()
```

Retourneert of stelt de titel van de alternatieve tekst in die aan een vorm is gekoppeld. Lezen/schrijven String.

**Retour:**  
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public abstract void setAlternativeTextTitle(String value)
```

Retourneert of stelt de titel van de alternatieve tekst in die aan een vorm is gekoppeld. Lezen/schrijven String.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public abstract String getName()
```

Retourneert of stelt de naam van een vorm in. Lezen/schrijven String.

**Retour:**  
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Retourneert of stelt de naam van een vorm in. Lezen/schrijven String.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```

Haalt of stelt de optie 'Mark as decorative' in, Lezen/schrijven boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retour:**  
boolean

### setDecorative(boolean value) {#setDecorative-boolean-}
```
public abstract void setDecorative(boolean value)
```

Haalt of stelt de optie 'Mark as decorative' in, Lezen/schrijven boolean.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public abstract IBaseShapeLock getShapeLock()
```

Retourneert de vergrendelingen van de vorm. Alleen-lezen [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Retour:**  
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### getUniqueId() {#getUniqueId--}
```
public abstract long getUniqueId()
```

Retourneert een interne, presentatie-bereik identifier bedoeld voor gebruik door add-ins of andere code. Omdat deze waarde door de gebruiker of programmatisch kan worden herhaald, mag hij niet worden behandeld als een permanente unieke sleutel. Alleen-lezen long. Zie ook \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Retour:**  
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public abstract long getOfficeInteropShapeId()
```

Retourneert een dia-bereik unieke identifier die constant blijft gedurende de levensduur van de vorm en PowerPoint of interop-code in staat stelt de vorm betrouwbaar te refereren vanaf elke plaats in het document. Alleen-lezen long. Zie ook \#getUniqueId.getUniqueId.

**Retour:**  
long

### isGrouped() {#isGrouped--}
```
public abstract boolean isGrouped()
```

Bepaalt of de vorm gegroepeerd is. Alleen-lezen boolean.

--------------------

Eigenschap \#getParentGroup.getParentGroup retourneert het bovenliggende GroupShape-object als de vorm gegroepeerd is.

**Retour:**  
boolean

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public abstract byte getBlackWhiteMode()
```

Eigenschap specificeert hoe een vorm wordt weergegeven in zwart-wit weergavemodus. Lezen/schrijven [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Retour:**  
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```

Eigenschap specificeert hoe een vorm wordt weergegeven in zwart-wit weergavemodus. Lezen/schrijven [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Retourneert het bovenliggende GroupShape-object als de vorm gegroepeerd is. Anders retourneert null. Alleen-lezen [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

Eigenschap \#isGrouped.isGrouped bepaalt of de vorm gegroepeerd is.

**Retour:**  
[IGroupShape](../../com.aspose.slides/igroupshape)

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

Slaat de inhoud van Shape op als SVG-bestand.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Doel-stream |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Slaat de inhoud van Shape op als SVG-bestand.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Doel-stream |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG-generatie-opties |

### getBasePlaceholder() {#getBasePlaceholder--}
```
public abstract      I   Shape  get Base  Placeholder  ()
```

Retourneert een basis placeholder-vorm (vorm van de lay-out en/of master-dia waar de huidige vorm van is geërfd).

--------------------

> ```
> // haal alle (master/layout/slide) geanimeerde effecten van de placeholder-vorm op
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

Er wordt null geretourneerd als de huidige vorm niet is geërfd.

**Retour:**  
[IShape](../../com.aspose.slides/ishape)