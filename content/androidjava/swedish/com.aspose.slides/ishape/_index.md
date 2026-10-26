---
title: IShape
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en form på en bild.
type: docs
url: /sv/com.aspose.slides/ishape/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IShape extends ISlideComponent, IHyperlinkContainer
```

Representerar en form på en bild.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Avgör om formen är TextHolder. |
| [getPlaceholder()](#getPlaceholder--) | Returnerar platshållaren för en form. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Lägger till en ny platshållare om ingen finns och sätter platshållarens egenskaper till en specificerad. |
| [removePlaceholder()](#removePlaceholder--) | Anger att denna form inte är en platshållare. |
| [getCustomData()](#getCustomData--) | Returnerar formens anpassade data. |
| [getRawFrame()](#getRawFrame--) | Returnerar eller anger de råa ramens egenskaper för formen. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Returnerar eller anger de råa ramens egenskaper för formen. |
| [getFrame()](#getFrame--) | Returnerar eller anger ramens egenskaper för formen. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Returnerar eller anger ramens egenskaper för formen. |
| [getLineFormat()](#getLineFormat--) | Returnerar LineFormat-objektet som innehåller linjeformateringsegenskaper för en form. |
| [getThreeDFormat()](#getThreeDFormat--) | Returnerar ThreeDFormat-objektet som innehåller linjeformateringsegenskaper för en form. |
| [getEffectFormat()](#getEffectFormat--) | Returnerar EffectFormat-objektet som innehåller pixeleffekter tillämpade på en form. |
| [getFillFormat()](#getFillFormat--) | Returnerar FillFormat-objektet som innehåller fyllningsformateringsegenskaper för en form. |
| [getImage()](#getImage--) | Returnerar formens miniatyrbild. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Returnerar formens miniatyrbild. |
| [getHidden()](#getHidden--) | Avgör om formen är dold. |
| [setHidden(boolean value)](#setHidden-boolean-) | Avgör om formen är dold. |
| [getZOrderPosition()](#getZOrderPosition--) | Returnerar formens position i z-ordningen. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Returnerar antalet anslutningsplatser på formen. |
| [getRotation()](#getRotation--) | Returnerar eller anger antalet grader som den specificerade formen roteras runt z-axeln. |
| [setRotation(float value)](#setRotation-float-) | Returnerar eller anger antalet grader som den specificerade formen roteras runt z-axeln. |
| [getX()](#getX--) | Hämtar eller anger x-koordinaten för formens övre vänstra hörn, mätt i punkter. |
| [setX(float value)](#setX-float-) | Hämtar eller anger x-koordinaten för formens övre vänstra hörn, mätt i punkter. |
| [getY()](#getY--) | Hämtar eller anger y-koordinaten för formens övre vänstra hörn, mätt i punkter. |
| [setY(float value)](#setY-float-) | Hämtar eller anger y-koordinaten för formens övre vänstra hörn, mätt i punkter. |
| [getWidth()](#getWidth--) | Hämtar eller anger bredden på formen, mätt i punkter. |
| [setWidth(float value)](#setWidth-float-) | Hämtar eller anger bredden på formen, mätt i punkter. |
| [getHeight()](#getHeight--) | Hämtar eller anger höjden på formen, mätt i punkter. |
| [setHeight(float value)](#setHeight-float-) | Hämtar eller anger höjden på formen, mätt i punkter. |
| [getAlternativeText()](#getAlternativeText--) | Returnerar eller anger den alternativa texten som är associerad med en form. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Returnerar eller anger den alternativa texten som är associerad med en form. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Returnerar eller anger titeln på den alternativa texten som är associerad med en form. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Returnerar eller anger titeln på den alternativa texten som är associerad med en form. |
| [getName()](#getName--) | Returnerar eller anger namnet på en form. |
| [setName(String value)](#setName-java.lang.String-) | Returnerar eller anger namnet på en form. |
| [isDecorative()](#isDecorative--) | Hämtar eller anger 'Mark as decorative'-alternativet Läs/skriv boolean. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Hämtar eller anger 'Mark as decorative'-alternativet Läs/skriv boolean. |
| [getShapeLock()](#getShapeLock--) | Returnerar formens lås. |
| [getUniqueId()](#getUniqueId--) | Returnerar en intern, presentationsavgränsad identifierare avsedd för användning av tillägg eller annan kod. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Returnerar en bildavgränsad unik identifierare som förblir konstant under formens livstid och låter PowerPoint eller interop-kod på ett pålitligt sätt referera till formen från var som helst i dokumentet. |
| [isGrouped()](#isGrouped--) | Avgör om formen är grupperad. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Egendomen anger hur en form renderas i svart-vit visningsläge. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Egendomen anger hur en form renderas i svart-vit visningsläge. |
| [getParentGroup()](#getParentGroup--) | Returnerar parent GroupShape-objekt om formen är grupperad. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Sparar innehållet i Shape som SVG-fil. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Sparar innehållet i Shape som SVG-fil. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Returnerar en grundläggande platshållarform (form från layouten och/eller mastersliden som den aktuella formen ärvs från). |

### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```

Avgör om formen är TextHolder. Endast läsning boolean.

**Returnerar:**
boolean
### getPlaceholder() {#getPlaceholder--}
```
public abstract IPlaceholder getPlaceholder()
```

Returnerar platshållaren för en form. Endast läsning [IPlaceholder](../../com.aspose.slides/iplaceholder).

**Returnerar:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)
### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public abstract IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Lägger till en ny platshållare om ingen finns och sätter platshållarens egenskaper till en specificerad.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Platshållare att kopiera innehåll från. |

**Returnerar:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - New [IPlaceholder](../../com.aspose.slides/iplaceholder).
### removePlaceholder() {#removePlaceholder--}
```
public abstract void removePlaceholder()
```

Anger att denna form inte är en platshållare.

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Returnerar formens anpassade data. Endast läsning [ICustomData](../../com.aspose.slides/icustomdata).

**Returnerar:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getRawFrame() {#getRawFrame--}
```
public abstract IShapeFrame getRawFrame()
```

Returnerar eller anger de råa formens ramens egenskaper. Läs/skriv [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //eller
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Sådan kod kan leda till oklara situationer. Så har begränsningar lagts till för att använda odefinierade värden för IShape.getFrame(). Värdena för x, y, width, height, flipH, flipV och rotationAngle måste vara definierade (inte Float.NaN eller NullableBool.NotDefined). Exempelkoden ovan kastar nu ArgumentException.
>  //Detta gäller för dessa användningsfall:
>  IShape shape = ...;
>  shape.setFrame(...); // kan inte vara odefinierad
>  IShapeCollection shapes = ...;
>  // x, y, width, height-parametrar kan inte vara Float.NaN:
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
>  IShape shape = ...; // formen är länkad till en platshållare
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // nu ärver formen x, y, height, flipH, flipV-värden från platshållaren och width=100 samt rotationAngle=0 åsidosätts.
```

**Returnerar:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
```

Returnerar eller anger de råa formens ramens egenskaper. Läs/skriv [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //eller
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Sådan kod kan leda till oklara situationer. Så har begränsningar lagts till för att använda odefinierade värden för IShape.getFrame(). Värdena för x, y, width, height, flipH, flipV och rotationAngle måste vara definierade (inte Float.NaN eller NullableBool.NotDefined). Exempelkoden ovan kastar nu ArgumentException.
>  //Detta gäller för dessa användningsfall:
>  IShape shape = ...;
>  shape.setFrame(...); // kan inte vara odefinierad
>  IShapeCollection shapes = ...;
>  // x, y, width, height parametrar kan inte vara Float.NaN:
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
>  IShape shape = ...; // formen är länkad till en platshållare
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // nu ärver formen x, y, height, flipH, flipV värden från platshållaren och överskriver width=100 och rotationAngle=0.
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

Returnerar eller anger ramens egenskaper för formen. Läs/skriv [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Värdet för varje egenskap i den returnerade IShapeFrame-instansen är inte odefinierat (är inte Float.NaN). Värdet för varje egenskap i den tilldelade IShapeFrame-instansen måste vara odefinierat (måste inte vara Float.NaN). Du kan sätta odefinierade värden för RawFrame-instansens egenskaper.

**Returnerar:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

Returnerar eller anger ramens egenskaper för formen. Läs/skriv [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Värdet för varje egenskap i den returnerade IShapeFrame-instansen är inte odefinierat (är inte Float.NaN). Värdet för varje egenskap i den tilldelade IShapeFrame-instansen måste vara odefinierat (måste inte vara Float.NaN). Du kan sätta odefinierade värden för RawFrame-instansens egenskaper.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Returnerar LineFormat-objektet som innehåller linjeformateringsegenskaper för en form. Endast läsning [ILineFormat](../../com.aspose.slides/ilineformat).

**Returnerar:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

Returnerar ThreeDFormat-objektet som innehåller linjeformateringsegenskaper för en form. Endast läsning [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Returnerar:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Returnerar EffectFormat-objektet som innehåller pixeleffekter tillämpade på en form. Endast läsning [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Returnerar:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Returnerar FillFormat-objektet som innehåller fyllningsformateringsegenskaper för en form. Endast läsning [IFillFormat](../../com.aspose.slides/ifillformat).

**Returnerar:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Returnerar miniatyrbild av formen. ShapeThumbnailBounds.Shape används som standard för miniatyrbildens gränstyp.

**Returnerar:**
[IImage](../../com.aspose.slides/iimage) - Miniatyrbild av formen.
### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public abstract IImage getImage(int bounds, float scaleX, float scaleY)
```

Returnerar miniatyrbild av formen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bounds | int | Formens miniatyrbildens gränstyp. |
| scaleX | float | X-skala |
| scaleY | float | Y-skala |

**Returnerar:**
[IImage](../../com.aspose.slides/iimage) - Miniatyrbild av formen eller null om ShapeThumbnailBounds.Appearance används och en form inte har synliga element.
### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Avgör om formen är dold. Läs/skriv boolean.

**Returnerar:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Avgör om formen är dold. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```

Returnerar positionen för en form i z-ordningen. Shapes[0] returnerar formen längst bak i z-ordningen, och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen. Endast läsning int.

**Returnerar:**
int
### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```

Returnerar antalet anslutningsplatser på formen. Endast läsning int.

**Returnerar:**
int
### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

Returnerar eller anger antalet grader som den specificerade formen roteras runt z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Läs/skriv float.

--------------------

Det returnerade värdet är alltid definierat (är inte Float.NaN). Tilldelat värde måste vara definierat (inte Float.NaN). Du kan sätta odefinierade värden för RawFrame-instansens egenskaper.

**Returnerar:**
float
### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```

Returnerar eller anger antalet grader som den specificerade formen roteras runt z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Läs/skriv float.

--------------------

Det returnerade värdet är alltid definierat (är inte Float.NaN). Tilldelat värde måste vara definierat (inte Float.NaN). Du kan sätta odefinierade värden för RawFrame-instansens egenskaper.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getX() {#getX--}
```
public abstract float getX()
```

Hämtar eller anger x-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs/skriv float.

--------------------

Det returnerade värdet är alltid definierat och aldrig Float.NaN. Det tilldelade värdet måste också vara definierat; sätt Float.NaN endast på egenskaper för en RawFrame-instans.

**Returnerar:**
float
### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```

Hämtar eller anger x-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs/skriv float.

--------------------

Det returnerade värdet är alltid definierat och aldrig Float.NaN. Det tilldelade värdet måste också vara definierat; sätt Float.NaN endast på egenskaper för en RawFrame-instans.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public abstract float getY()
```

Hämtar eller anger y-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs/skriv float.

--------------------

Det returnerade värdet är alltid definierat och aldrig Float.NaN. Det tilldelade värdet måste också vara definierat; sätt Float.NaN endast på egenskaper för en RawFrame-instans.

**Returnerar:**
float
### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```

Hämtar eller anger y-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs/skriv float.

--------------------

Det returnerade värdet är alltid definierat och aldrig Float.NaN. Det tilldelade värdet måste också vara definierat; sätt Float.NaN endast på egenskaper för en RawFrame-instans.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

Hämtar eller anger bredden på formen, mätt i punkter. Läs/skriv float.

--------------------

Det returnerade värdet är alltid definierat och aldrig Float.NaN. Det tilldelade värdet måste också vara definierat; sätt Float.NaN endast på egenskaper för en RawFrame-instans.

**Returnerar:**
float
### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```

Hämtar eller anger bredden på formen, mätt i punkter. Läs/skriv float.

--------------------

Det returnerade värdet är alltid definierat och aldrig Float.NaN. Det tilldelade värdet måste också vara definierat; sätt Float.NaN endast på egenskaper för en RawFrame-instans.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Hämtar eller anger höjden på formen, mätt i punkter. Läs/skriv float.

--------------------

Det returnerade värdet är alltid definierat och aldrig Float.NaN. Det tilldelade värdet måste också vara definierat; sätt Float.NaN endast på egenskaper för en RawFrame-instans.

**Returnerar:**
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Hämtar eller anger höjden på formen, mätt i punkter. Läs/skriv float.

--------------------

Det returnerade värdet är alltid definierat och aldrig Float.NaN. Det tilldelade värdet måste också vara definierat; sätt Float.NaN endast på egenskaper för en RawFrame-instans.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getAlternativeText() {#getAlternativeText--}
```
public abstract String getAlternativeText()
```

Returnerar eller anger den alternativa texten som är associerad med en form. Läs/skriv String.

**Returnerar:**
java.lang.String
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public abstract void setAlternativeText(String value)
```

Returnerar eller anger den alternativa texten som är associerad med en form. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public abstract String getAlternativeTextTitle()
```

Returnerar eller anger titeln på den alternativa texten som är associerad med en form. Läs/skriv String.

**Returnerar:**
java.lang.String
### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public                
//                           // (This appears to be a placeholder or malformed comment; no translation needed)
```

Returnerar eller anger titeln på den alternativa texten som är associerad med en form. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getName() {#getName--}
```
public abstract String getName()
```

Returnerar eller anger namnet på en form. Läs/skriv String.

**Returnerar:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Returnerar eller anger namnet på en form. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```

Hämtar eller anger 'Mark as decorative'-alternativet Läs/skriv boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returnerar:**
boolean
### setDecorative(boolean value) {#setDecorative-boolean-}
```
public abstract void setDecorative(boolean value)
```

Hämtar eller anger 'Mark as decorative'-alternativet Läs/skriv boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getShapeLock() {#getShapeLock--}
```
public abstract IBaseShapeLock getShapeLock()
```

Returnerar formens lås. Endast läsning [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Returnerar:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
### getUniqueId() {#getUniqueId--}
```
public                
//                           //                  …    …  …  INVALID     ...   ...  …
The      exact ...  ...  …

???   ??? …

  …

  …

0  NOTE… …  …

，  …

…

 …

  "))  ??   



Invoices … 

 




… 



  







  


… 



















…


```

Returnerar en intern, presentationsavgränsad identifierare avsedd för användning av tillägg eller annan kod. Eftersom detta värde kan omassigneras av användaren eller programmässigt, bör det inte behandlas som en bestående unik nyckel. Endast läsning long. See also \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Returnerar:**
long
### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public abstract long getOfficeInteropShapeId()
```

Returnerar en bildavgränsad unik identifierare som förblir konstant under formens livstid och låter PowerPoint eller interop-kod på ett pålitligt sätt referera till formen från var som helst i dokumentet. Endast läsning long. See also \#getUniqueId.getUniqueId.

**Returnerar:**
long
### isGrouped() {#isGrouped--}
```
public abstract boolean isGrouped()
```

Avgör om formen är grupperad. Endast läsning boolean.

--------------------

Egenskap #getParentGroup.getParentGroup returnerar parent GroupShape-objekt om formen är grupperad.

**Returnerar:**
boolean
### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public abstract byte getBlackWhiteMode()
```

Egenskap anger hur en form renderas i svart-vit visningsläge. Läs/skriv [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Returnerar:**
byte
### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```

Egenskap anger hur en form renderas i svart-vit visningsläge. Läs/skriv [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Returnerar parent GroupShape-objekt om formen är grupperad. Annars returneras null. Endast läsning [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

Egenskap #isGrouped.isGrouped avgör om formen är grupperad.

**Returnerar:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

Sparar innehållet i Shape som SVG-fil.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |
### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Sparar innehållet i Shape som SVG-fil.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG generation options |
### getBasePlaceholder() {#getBasePlaceholder--}
```
public abstract IShape getBasePlaceholder()
```

Returnerar en grundläggande platshållarform (form från layouten och/eller mastersliden som den aktuella formen ärvs från).

--------------------

> ```
> // hämta alla (master/layout/slide) animerade effekter för platshållarformen
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

Null returneras om den aktuella formen inte ärvs.

**Returnerar:**
[IShape](../../com.aspose.slides/ishape)