---
title: IShape
second_title: Aspose.Slides för Java API-referens
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
| [isTextHolder()](#isTextHolder--) | Bestämmer om formen är TextHolder. |
| [getPlaceholder()](#getPlaceholder--) | Returnerar platshållaren för en form. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Lägger till en ny platshållare om ingen finns och sätter platshållarens egenskaper till en specificerad. |
| [removePlaceholder()](#removePlaceholder--) | Anger att den här formen inte är en platshållare. |
| [getCustomData()](#getCustomData--) | Returnerar formens anpassade data. |
| [getRawFrame()](#getRawFrame--) | Returnerar eller sätter de råa formramens egenskaper. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Returnerar eller sätter de råa formramens egenskaper. |
| [getFrame()](#getFrame--) | Returnerar eller sätter de råa formramens egenskaper. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Returnerar eller sätter de råa formramens egenskaper. |
| [getLineFormat()](#getLineFormat--) | Returnerar LineFormat-objektet som innehåller linjeformateringsegenskaper för en form. |
| [getThreeDFormat()](#getThreeDFormat--) | Returnerar ThreeDFormat-objektet som innehåller linjeformateringsegenskaper för en form. |
| [getEffectFormat()](#getEffectFormat--) | Returnerar EffectFormat-objektet som innehåller pixeleffekter som tillämpas på en form. |
| [getFillFormat()](#getFillFormat--) | Returnerar FillFormat-objektet som innehåller fyllningsformateringsegenskaper för en form. |
| [getImage()](#getImage--) | Returnerar formens miniatyrbild. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Returnerar formens miniatyrbild. |
| [getHidden()](#getHidden--) | Bestämmer om formen är dold. |
| [setHidden(boolean value)](#setHidden-boolean-) | Bestämmer om formen är dold. |
| [getZOrderPosition()](#getZOrderPosition--) | Returnerar formens position i z-ordningen. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Returnerar antalet anslutningspunkter på formen. |
| [getRotation()](#getRotation--) | Returnerar eller sätter antalet grader som den specificerade formen är roterad kring z-axeln. |
| [setRotation(float value)](#setRotation-float-) | Returnerar eller sätter antalet grader som den specificerade formen är roterad kring z-axeln. |
| [getX()](#getX--) | Hämtar eller sätter x-koordinaten för formens övre vänstra hörn, mätt i punkter. |
| [setX(float value)](#setX-float-) | Hämtar eller sätter x-koordinaten för formens övre vänstra hörn, mätt i punkter. |
| [getY()](#getY--) | Hämtar eller sätter y-koordinaten för formens övre vänstra hörn, mätt i punkter. |
| [setY(float value)](#setY-float-) | Hämtar eller sätter y-koordinaten för formens övre vänstra hörn, mätt i punkter. |
| [getWidth()](#getWidth--) | Hämtar eller sätter bredden på formen, mätt i punkter. |
| [setWidth(float value)](#setWidth-float-) | Hämtar eller sätter bredden på formen, mätt i punkter. |
| [getHeight()](#getHeight--) | Hämtar eller sätter höjden på formen, mätt i punkter. |
| [setHeight(float value)](#setHeight-float-) | Hämtar eller sätter höjden på formen, mätt i punkter. |
| [getAlternativeText()](#getAlternativeText--) | Returnerar eller sätter den alternativa texten som är associerad med en form. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Returnerar eller sätter den alternativa texten som är associerad med en form. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Returnerar eller sätter titeln för den alternativa texten som är associerad med en form. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Returnerar eller sätter titeln för den alternativa texten som är associerad med en form. |
| [getName()](#getName--) | Returnerar eller sätter namnet på en form. |
| [setName(String value)](#setName-java.lang.String-) | Returnerar eller sätter namnet på en form. |
| [isDecorative()](#isDecorative--) | Hämtar eller sätter 'Mark as decorative'-alternativet Läs/skriv boolesk. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Hämtar eller sätter 'Mark as decorative'-alternativet Läs/skriv boolesk. |
| [getShapeLock()](#getShapeLock--) | Returnerar formens lås. |
| [getUniqueId()](#getUniqueId--) | Returnerar en intern, presentationsomfattande identifierare avsedd för användning av tillägg eller annan kod. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Returnerar en bildomfattande unik identifierare som förblir konstant under formens livstid och låter PowerPoint eller interop-kod på ett pålitligt sätt referera till formen från vilken plats som helst i dokumentet. |
| [isGrouped()](#isGrouped--) | Bestämmer om formen är grupperad. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Egenskapen anger hur en form kommer att renderas i svartvit visningsläge. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Egenskapen anger hur en form kommer att renderas i svartvit visningsläge. |
| [getParentGroup()](#getParentGroup--) | Returnerar föräldra-GroupShape-objektet om formen är grupperad. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Sparar innehållet i Form som SVG-fil. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Sparar innehållet i Form som SVG-fil. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Returnerar en grundläggande platshållarform (form från layouten och/eller huvudyxeln som den aktuella formen ärvs från). |

### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```

Bestämmer om formen är TextHolder. Skrivskyddad boolean.

**Returnerar:**
boolean
### getPlaceholder() {#getPlaceholder--}
```
public abstract IPlaceholder getPlaceholder()
```

Returnerar platshållaren för en form. Skrivskyddad [IPlaceholder](../../com.aspose.slides/iplaceholder).

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
[IPlaceholder](../../com.aspose.slides/iplaceholder) - Ny [IPlaceholder](../../com.aspose.slides/iplaceholder).
### removePlaceholder() {#removePlaceholder--}
```
public abstract void removePlaceholder()
```

Anger att den här formen inte är en platshållare.

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Returnerar formens anpassade data. Skrivskyddad [ICustomData](../../com.aspose.slides/icustomdata).

**Returnerar:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getRawFrame() {#getRawFrame--}
```
public abstract IShapeFrame getRawFrame()
```

Returnerar eller sätter de råa formramens egenskaper. Läs/skriv [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Kod som försöker tilldela en odefinierad ram till IShape.getFrame() är inte meningsfull i allmänhet (särskilt när föräldra-GroupShape är flera gånger nästlad i andra GroupShape-objekt). Till exempel:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //eller
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Sådan kod kan leda till oklara situationer. Så begränsningar har lagts till för att använda odefinierade värden för IShape.getFrame(). Värdena x, y, width, height, flipH, flipV och rotationAngle måste vara definierade (inte Float.NaN eller NullableBool.NotDefined). Exempelkoden ovan kastar nu ett ArgumentException-undantag.
>  //Detta gäller för följande användningsfall:
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
>  // Men IShape.RawFrame-ramegenskaper kan vara odefinierade. Detta är logiskt när formen är länkad till en platshållare. Då åsidosätts odefinierade ramvärden av föräldraplatshållarformen. Om det inte finns någon föräldraplatshållarform för den formen använder den standardvärden när den beräknar effektiv ram baserat på sin IShape.RawFrame. Standardvärden är 0 och NullableBool.False för x, y, width, height, flipH, flipV och rotationAngle. Till exempel:
>  IShape shape = ...; // shape is linked to placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // nu ärver formen x, y, height, flipH, flipV-värden från platshållaren och åsidosätter width=100 och rotationAngle=0.
> ```

**Returnerar:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
```

Returnerar eller sätter de råa formramens egenskaper. Läs/skriv [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //eller
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Sådan kod kan leda till oklara situationer. Så har begränsningar lagts till för att använda odefinierade värden för IShape.getFrame(). Värdena x, y, width, height, flipH, flipV och rotationAngle måste vara definierade (inte Float.NaN eller NullableBool.NotDefined). Exempelkoden ovan kastar nu ett ArgumentException-undantag.
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
>  IShape shape = ...; // shape är länkad till en platshållare
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // nu ärver formen x, y, height, flipH, flipV-värden från platshållaren och åsidosätter width=100 och rotationAngle=0.
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

Returnerar eller sätter formramens egenskaper. Läs/skriv [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Värdet för varje egenskap i den returnerade IShapeFrame-instansen är inte odefinierat (inte NaN eller NotDefined). Värdet för varje egenskap i den tilldelade IShapeFrame-instansen får inte vara odefinierat (måste vara varken NaN eller NotDefined). Du kan sätta odefinierade värden för RawFrame-instansens egenskaper.

**Returnerar:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

Returnerar eller sätter formramens egenskaper. Läs/skriv [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Värdet för varje egenskap i den returnerade IShapeFrame-instansen är inte odefinierat (inte NaN eller NotDefined). Värdet för varje egenskap i den tilldelade IShapeFrame-instansen får inte vara odefinierat (måste vara varken NaN eller NotDefined). Du kan sätta odefinierade värden för RawFrame-instansens egenskaper.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |
### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Returnerar LineFormat-objektet som innehåller linjeformateringsegenskaper för en form. Skrivskyddad [ILineFormat](../../com.aspose.slides/ilineformat).

**Returnerar:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

Returnerar ThreeDFormat-objektet som innehåller linjeformateringsegenskaper för en form. Skrivskyddad [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Returnerar:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Returnerar EffectFormat-objektet som innehåller pixeleffekter som tillämpas på en form. Skrivskyddad [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Returnerar:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Returnerar FillFormat-objektet som innehåller fyllningsformateringsegenskaper för en form. Skrivskyddad [IFillFormat](../../com.aspose.slides/ifillformat).

**Returnerar:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Returnerar formens miniatyrbild. ShapeThumbnailBounds.Shape form miniatyrbilds-typ används som standard.

**Returnerar:**
[IImage](../../com.aspose.slides/iimage) - Formens miniatyrbild.
### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public abstract IImage getImage(int bounds, float scaleX, float scaleY)
```

Returnerar formens miniatyrbild.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bounds | int | Formens miniatyrbildstyp. |
| scaleX | float | X-skalning |
| scaleY | float | Y-skalning |

**Returnerar:**
[IImage](../../com.aspose.slides/iimage) - Formens miniatyrbild eller null om ShapeThumbnailBounds.Appearance används och formen saknar synliga element.
### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Bestämmer om formen är dold. Läs/skriv boolean.

**Returnerar:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Bestämmer om formen är dold. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```

Returnerar formens position i z-ordningen. Shapes[0] returnerar formen längst bak i z-ordningen, och Shapes[Shapes.Count - 1] returnerar formen längst fram. Skrivskyddad int.

**Returnerar:**
int
### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```

Returnerar antalet anslutningspunkter på formen. Skrivskyddad int.

**Returnerar:**
int
### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

Returnerar eller sätter antalet grader som den specificerade formen är roterad kring z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Läs/skriv float.

--------------------

Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**Returnerar:**
float
### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```

Returnerar eller sätter antalet grader som den specificerade formen är roterad kring z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Läs/skriv float.

--------------------

Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getX() {#getX--}
```
public abstract float getX()
```

Hämtar eller sätter x-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs/skriv float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Returnerar:**
float
### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```

Hämtar eller sätter x-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs/skriv float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public abstract float getY()
```

Hämtar eller sätter y-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs/skriv float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Returnerar:**
float
### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```

Hämtar eller sätter y-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs/skriv float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

Hämtar eller sätter bredden på formen, mätt i punkter. Läs/skriv float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Returnerar:**
float
### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```

Hämtar eller sätter bredden på formen, mätt i punkter. Läs/skriv float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Hämtar eller sätter höjden på formen, mätt i punkter. Läs/skriv float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Returnerar:**
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Hämtar eller sätter höjden på formen, mätt i punkter. Läs/skriv float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getAlternativeText() {#getAlternativeText--}
```
public abstract String getAlternativeText()
```

Returnerar eller sätter den alternativa texten som är associerad med en form. Läs/skriv String.

**Returnerar:**
java.lang.String
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public abstract void setAlternativeText(String value)
```

Returnerar eller sätter den alternativa texten som är associerad med en form. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public abstract String getAlternativeTextTitle()
```

Returnerar eller sätter titeln för den alternativa texten som är associerad med en form. Läs/skriv String.

**Returnerar:**
java.lang.String
### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public abstract void setAlternativeTextTitle(String value)
```

Returnerar eller sätter titeln för den alternativa texten som är associerad med en form. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getName() {#getName--}
```
public abstract String getName()
```

Returnerar eller sätter namnet på en form. Läs/skriv String.

**Returnerar:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Returnerar eller sätter namnet på en form. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```

Hämtar eller sätter 'Mark as decorative'-alternativet Läs/skriv boolesk.

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

Hämtar eller sätter 'Mark as decorative'-alternativet Läs/skriv boolesk.

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

Returnerar formens lås. Skrivskyddad [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Returnerar:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
### getUniqueId() {#getUniqueId--}
```
public abstract long getUniqueId()
```

Returnerar en intern, presentationsomfattande identifierare avsedd för användning av tillägg eller annan kod. Eftersom detta värde kan omassigneras av användaren eller programmässigt, får det inte behandlas som en bestående unik nyckel. Skrivskyddad long. Se även \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Returnerar:**
long
### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public int   ...  ...
Uh ...
```

Returnerar en bildomfattande unik identifierare som förblir konstant under formens livstid och låter PowerPoint eller interop-kod på ett pålitligt sätt referera till formen från vilken plats som helst i dokumentet. Skrivskyddad long. Se även \#getUniqueId.getUniqueId.

**Returnerar:**
long
### isGrouped() {#isGrouped--}
```
public abstract boolean isGrouped()
```

Bestämmer om formen är grupperad. Skrivskyddad boolean.

--------------------

Egenskapen \#getParentGroup.getParentGroup returnerar föräldra-GroupShape-objektet om formen är grupperad.

**Returnerar:**
boolean
### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public abstract byte getBlackWhiteMode()
```

Egenskapen anger hur en form kommer att renderas i svartvit visningsläge. Läs/skriv [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Returnerar:**
byte
### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```

Egenskapen anger hur en form kommer att renderas i svartvit visningsläge. Läs/skriv [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Returnerar föräldra-GroupShape-objektet om formen är grupperad. Annars returneras null. Skrivskyddad [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

Egenskapen \#isGrouped.isGrouped bestämmer om formen är grupperad.

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
| stream | java.io.OutputStream | Målsström |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Sparar innehållet i Shape som SVG-fil.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Målsström |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG-genereringsalternativ |

### getBasePlaceholder() {#getBasePlaceholder--}
```
public abstract IShape getBasePlaceholder()
```

Returnerar en grundläggande platshållarform (form från layouten och/eller huvudyxeln som den aktuella formen ärvs från).

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

Ett null returneras om den aktuella formen inte ärvs.

**Returnerar:**
[IShape](../../com.aspose.slides/ishape)