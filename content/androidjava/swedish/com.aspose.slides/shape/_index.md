---
title: Shape
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en form på en bild.
type: docs
url: /sv/com.aspose.slides/shape/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape), com.aspose.slides.IDOMObject
```
public class Shape implements IShape, IDOMObject
```

Representerar en form på en bild.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Bestämmer om formen är TextHolder_PPT. |
| [getPlaceholder()](#getPlaceholder--) | Returnerar platshållaren för en form. |
| [removePlaceholder()](#removePlaceholder--) | Definierar att denna form inte är en platshållare. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Lägger till en ny platshållare om det inte finns någon och sätter platshållarens egenskaper till en specificerad. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Returnerar en grundläggande platshållarform (form från layouten och/eller huvudbilden som den aktuella formen ärvs från). |
| [getCustomData()](#getCustomData--) | Returnerar formens anpassade data. |
| [getRawFrame()](#getRawFrame--) | Returnerar eller anger de råa egenskaperna för formens ram. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Returnerar eller anger de råa egenskaperna för formens ram. |
| [getFrame()](#getFrame--) | Returnerar eller anger formens ramegenskaper. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Returnerar eller anger formens ramegenskaper. |
| [getLineFormat()](#getLineFormat--) | Returnerar LineFormat-objektet som innehåller linjeformateringsegenskaper för en form. |
| [getThreeDFormat()](#getThreeDFormat--) | Returnerar ThreeDFormat-objektet som innehåller 3D-effektegenskaper för en form. |
| [getEffectFormat()](#getEffectFormat--) | Returnerar EffectFormat-objektet som innehåller pixel-effekter som appliceras på en form. |
| [getFillFormat()](#getFillFormat--) | Returnerar FillFormat-objektet som innehåller fyllningsformateringsegenskaper för en form. |
| [getImage()](#getImage--) | Returnerar formens miniatyrbild. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Returnerar formens miniatyrbild. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Sparar innehållet i en form som SVG-fil. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Sparar innehållet i en form som SVG-fil. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Returnerar eller anger hyperlänken som definierats för musklick. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Returnerar eller anger hyperlänken som definierats för musklick. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Returnerar eller anger hyperlänken som definierats för muspekning. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Returnerar eller anger hyperlänken som definierats för muspekning. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Returnerar hyperlänkshanteraren. |
| [getHidden()](#getHidden--) | Bestämmer om formen är dold. |
| [setHidden(boolean value)](#setHidden-boolean-) | Bestämmer om formen är dold. |
| [getZOrderPosition()](#getZOrderPosition--) | Returnerar positionen för en form i z-ordningen. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Returnerar antalet anslutningspunkter på formen. |
| [getRotation()](#getRotation--) | Returnerar eller anger antalet grader som den specifika formen är roterad kring z-axeln. |
| [setRotation(float value)](#setRotation-float-) | Returnerar eller anger antalet grader som den specifika formen är roterad kring z-axeln. |
| [getX()](#getX--) | Hämtar eller anger x-koordinaten för formens övre vänstra hörn, mätt i punkter. |
| [setX(float value)](#setX-float-) | Hämtar eller anger x-koordinaten för formens övre vänstra hörn, mätt i punkter. |
| [getY()](#getY--) | Hämtar eller anger y-koordinaten för formens övre vänstra hörn, mätt i punkter. |
| [setY(float value)](#setY-float-) | Hämtar eller anger y-koordinaten för formens övre vänstra hörn, mätt i punkter. |
| [getWidth()](#getWidth--) | Hämtar eller anger bredden på formen, mätt i punkter. |
| [setWidth(float value)](#setWidth-float-) | Hämtar eller anger bredden på formen, mätt i punkter. |
| [getHeight()](#getHeight--) | Hämtar eller anger höjden på formen, mätt i punkter. |
| [setHeight(float value)](#setHeight-float-) | Hämtar eller anger höjden på formen, mätt i punkter. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Egenskapen anger hur en form ska renderas i svart-vitt visningsläge. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Egenskapen anger hur en form ska renderas i svart-vitt visningsläge. |
| [getUniqueId()](#getUniqueId--) | Returnerar en intern, presentation-omfattande identifierare avsedd för användning av tillägg eller annan kod. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Returnerar en bild-omfattande unik identifierare som förblir konstant under formens livstid och låter PowerPoint eller interop-kod på ett tillförlitligt sätt referera till formen från vilken plats som helst i dokumentet. |
| [getAlternativeText()](#getAlternativeText--) | Returnerar eller anger alternativ text som är associerad med en form. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Returnerar eller anger alternativ text som är associerad med en form. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Returnerar eller anger titeln för den alternativa texten som är associerad med en form. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Returnerar eller anger titeln för den alternativa texten som är associerad med en form. |
| [getName()](#getName--) | Returnerar eller anger namnet på en form. |
| [setName(String value)](#setName-java.lang.String-) | Returnerar eller anger namnet på en form. |
| [isDecorative()](#isDecorative--) | Hämtar eller anger alternativet 'Markera som dekorativ' Läs/skriv boolesk. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Hämtar eller anger alternativet 'Markera som dekorativ' Läs/skriv boolesk. |
| [getShapeLock()](#getShapeLock--) | Returnerar formens lås. |
| [isGrouped()](#isGrouped--) | Bestämmer om formen är grupperad. |
| [getParentGroup()](#getParentGroup--) | Returnerar förälder-GroupShape-objektet om formen är grupperad. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVisualBounds()](#getVisualBounds--) | Hämtar de visuella gränserna för formen beräknade från dess renderade innehåll. |
| [getSlide()](#getSlide--) | Returnerar föräldrabilden för en form. |
| [getPresentation()](#getPresentation--) | Returnerar föräldrapresentationen för en bild. |

### isTextHolder() {#isTextHolder--}
```
public final boolean isTextHolder()
```

Bestämmer om formen är TextHolder_PPT. Skrivskyddad boolean .

**Returnerar:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```

Returnerar platshållaren för en form. Returnerar null om formen inte har någon platshållare. Skrivskyddad [IPlaceholder](../../com.aspose.slides/iplaceholder).

--------------------

> ```
> The following example shows how to change Text in Placeholder.
>  
>  // Instansierar en Presentation-klass
>  Presentation pres = new Presentation("ReplacingText.pptx");
>  try {
>      // Åtkomst till den första bilden
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Itererar genom former för att hitta platshållaren
>      for (IShape shp : sld.getShapes())
>          if (shp.getPlaceholder() != null)
>          {
>              // Ändrar texten i varje platshållare
>              ((IAutoShape)shp).getTextFrame().setText("This is a Placeholder");
>          }
>      // Sparar presentationen till disk
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
>      for (IShape shape : slide.getSlide().getShapes()) // Itererar genom bilden
>      {
>          if (shape.getPlaceholder() != null && shape instanceof AutoShape)
>          {
>              String text = "";
>              if (shape.getPlaceholder().getType() == PlaceholderType.CenteredTitle) // PowerPoint visar "Click to add title"
>              {
>                  text = "Add Title";
>              }
>              else if (shape.getPlaceholder().getType() == PlaceholderType.Subtitle) // Lägger till undertext
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


**Returnerar:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### removePlaceholder() {#removePlaceholder--}
```
public final void removePlaceholder()
```

Definierar att denna form inte är en platshållare.

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public final IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Lägger till en ny platshållare om det inte finns någon och sätter platshållarens egenskaper till en specificerad.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Platshållare att kopiera innehåll från. |

**Returnerar:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - Ny \#getPlaceholder.getPlaceholder.

### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

Returnerar en grundläggande platshållarform (form från layouten och/eller huvudbilden som den aktuella formen ärvs från).

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

En null returneras om den aktuella formen inte ärvs.

**Returnerar:**
[IShape](../../com.aspose.slides/ishape)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Returnerar formens anpassade data. Skrivskyddad [ICustomData](../../com.aspose.slides/icustomdata).

**Returnerar:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public final IShapeFrame getRawFrame()
```

Returnerar eller anger de råa egenskaperna för formens ram. Läs/skriv [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Kod som försöker tilldela en odefinierad ram till IShape.getFrame() är inte meningsfull i allmänna fallet (särskilt när föräldra-GroupShape är flera nivåer inbäddad i andra GroupShape-s). Till exempel:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //eller
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  // Sådan kod kan leda till oklara situationer. Så har restriktioner lagts till för att använda odefinierade värden för IShape.getFrame(). Värdena x, y, width, height, flipH, flipV och rotationAngle måste vara definierade (inte Float.NaN eller NullableBool.NotDefined). Exempelkoden ovan kastar nu ett ArgumentException-undantag.
>  // Detta gäller för följande användningsfall:
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
>  // Men IShape.RawFrame-ramegenskaper kan vara odefinierade. Detta är meningsfullt när formen är länkad till en platshållare. Då överskrids odefinierade ramvärden av föräldraplatshållarformen. Om det inte finns någon föräldraplatshållarform för den formen använder den standardvärden när den beräknar effektiv ram baserat på sin IShape.RawFrame. Standardvärden är 0 och NullableBool.False för x, y, width, height, flipH, flipV och rotationAngle. Till exempel:
>  IShape shape = ...; // formen är länkad till platshållare
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // nu ärver formen x, y, height, flipH, flipV-värden från platshållaren och överskrider width=100 och rotationAngle=0.{code}
```

**Returnerar:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
```

Returnerar eller anger de råa egenskaperna för formens ram. Läs/skriv [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //eller
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Sådan kod kan leda till oklara situationer. Så har restriktioner lagts till för att använda odefinierade värden för IShape.getFrame(). Värdena x, y, width, height, flipH, flipV och rotationAngle måste vara definierade (inte Float.NaN eller NullableBool.NotDefined). Exempelkoden ovan kastar nu ett ArgumentException-undantag.
>  //Detta gäller för följande användningsfall:
>  IShape shape = ...;
>  shape.setFrame(...); //kan inte vara odefinierad
>  IShapeCollection shapes = ...;
>  //x, y, width, height-parametrar kan inte vara Float.NaN:
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
>  //Men IShape.RawFrame-rameegenskaper kan vara odefinierade. Detta är meningsfullt när formen är länkad till en platshållare. Då blir odefinierade ramvärden överskrivna av föräldraplatshållarformen. Om det inte finns någon föräldraplatshållarform för den formen använder den standardvärden när den beräknar effektiv ram baserat på sin IShape.RawFrame. Standardvärden är 0 och NullableBool.False för x, y, width, height, flipH, flipV och rotationAngle.
>  IShape shape = ...; // shape is linked to placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); //nu ärver formen x, y, height, flipH, flipV-värden från platshållaren och överskrider width=100 och rotationAngle=0.{code}
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Returnerar eller anger formens ramegenskaper. Läs/skriv [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Värdet för varje egenskap i den returnerade IShapeFrame-instansen är alltid definierat (är inte NaN eller NotDefined). Värdet för varje egenskap i den tilldelade IShapeFrame-instansen måste vara definierat (inte NaN eller NotDefined). Du kan ange odefinierade värden för RawFrame-instansens egenskaper.

**Returnerar:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Returnerar eller anger formens ramegenskaper. Läs/skriv [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Värdet för varje egenskap i den returnerade IShapeFrame-instansen är alltid definierat (är inte NaN eller NotDefined). Värdet för varje egendom i den tilldelade IShapeFrame-instansen måste vara definierat (inte NaN eller NotDefined). Du kan ange odefinierade värden för RawFrame-instansens egenskaper.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

Returnerar LineFormat-objektet som innehåller linjeformateringsegenskaper för en form. Obs: kan returnera null för vissa typer av former som inte har linjeegenskaper. Skrivskyddad [ILineFormat](../../com.aspose.slides/ilineformat).

**Returnerar:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

Returnerar ThreeDFormat-objektet som 3d-effektegenskaper för en form. Obs: kan returnera null för vissa typer av former som inte har 3d-egenskaper. Skrivskyddad [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Returnerar:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

Returnerar EffectFormat-objektet som innehåller pixel-effekter som appliceras på en form. Obs: kan returnera null för vissa typer av former som inte har effekt-egenskaper. Skrivskyddad [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Returnerar:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Returnerar FillFormat-objektet som innehåller fyllningsformateringsegenskaper för en form. Obs: kan returnera null för vissa typer av former som inte har fyllnings-egenskaper. Skrivskyddad [IFillFormat](../../com.aspose.slides/ifillformat).

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
>      // Accent 4, Ljusare 80%
>      IShape shape2 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 70, 50, 50);
>      shape2.getFillFormat().setFillType(FillType.Solid);
>      shape2.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.2f);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.8f);
>      // Accent 4, Ljusare 60%
>      IShape shape3 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 130, 50, 50);
>      shape3.getFillFormat().setFillType(FillType.Solid);
>      shape3.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.4f);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.6f);
>      // Accent 4, Ljusare 40%
>      IShape shape4 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 190, 50, 50);
>      shape4.getFillFormat().setFillType(FillType.Solid);
>      shape4.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.6f);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.4f);
>      // Accent 4, Mörkare 25%
>      IShape shape5 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 250, 50, 50);
>      shape5.getFillFormat().setFillType(FillType.Solid);
>      shape5.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape5.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.75f);
>      // Accent 4, Mörkare 50%
>      IShape shape6 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 310, 50, 50);
>      shape6.getFillFormat().setFillType(FillType.Solid);
>      shape6.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape6.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.5f);
>      pres.save("example_accent4.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returnerar:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public final IImage getImage()
```

Returnerar formens miniatyrbild. ShapeThumbnailBounds.Shape form miniatyrgränser-typ används som standard.

**Returnerar:**
[IImage](../../com.aspose.slides/iimage) - Formens miniatyrbild.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IImage getImage(int bounds, float scaleX, float scaleY)
```

Returnerar formens miniatyrbild.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bounds | int | Formens miniatyrgränser-typ. |
| scaleX | float | X-skala |
| scaleY | float | Y-skala |

**Returnerar:**
[IImage](../../com.aspose.slides/iimage) - Formens miniatyrbild eller null om ShapeThumbnailBounds.Appearance används och en form saknar synliga element.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

Sparar innehållet i en form som SVG-fil.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Målstyrda strömmen |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Sparar innehållet i en form som SVG-fil.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Målstyrda strömmen |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG-genereringsalternativ |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

Returnerar eller anger hyperlänken som definierats för musklick. Läs/skriv [IHyperlink](../../com.aspose.slides/ihyperlink).

**Returnerar:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

Returnerar eller anger hyperlänken som definierats för musklick. Läs/skriv [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

Returnerar eller anger hyperlänken som definierats för muspekning. Läs/skriv [IHyperlink](../../com.aspose.slides/ihyperlink).

**Returnerar:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

Returnerar eller anger hyperlänken som definierats för muspekning. Läs/skriv [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

Returnerar hyperlänkshanteraren. Skrivskyddad [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Returnerar:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Bestämmer om formen är dold. Läs/skriv  boolean .

**Returnerar:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Bestämmer om formen är dold. Läs/skriv  boolean .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

Returnerar positionen för en form i z-ordningen. Shapes[0] returnerar formen längst bak i z-ordningen, och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen. Skrivskyddad  int .

**Returnerar:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```

Returnerar antalet anslutningspunkter på formen. Skrivskyddad  int .

**Returnerar:**
int

### getRotation() {#getRotation--}
```
public final float getRotation()
```

Returnerar eller anger antalet grader som den specificerade formen är roterad kring z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Läs/skriv float.

--------------------

Det returnerade värdet är alltid definierat (är inte Float.NaN). Tilldelat värde måste vara definierat (inte Float.NaN). Du kan ange odefinierade värden för RawFrame-instansens egenskaper.

**Returnerar:**
float

### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```

Returnerar eller anger antalet grader som den specificerade formen är roterad kring z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Läs/skriv float.

--------------------

Det returnerade värdet är alltid definierat (är inte Float.NaN). Tilldelat värde måste vara definierat (inte Float.NaN). Du kan ange odefinierade värden för RawFrame-instansens egenskaper.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public final float getX()
```

Hämtar eller anger x-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs/skriv float.

--------------------

Det returnerade värdet är alltid definierat och aldrig Float.NaN. Det tilldelade värdet måste också vara definierat; tilldela Float.NaN endast till egenskaper i en RawFrame-instans.

**Returnerar:**
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Hämtar eller anger x-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs/skriv float.

--------------------

Det returnerade värdet är alltid definierat och aldrig Float.NaN. Det tilldelade värdet måste också vara definierat; tilldela Float.NaN endast till egenskaper i en RawFrame-instans.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

Hämtar eller anger y-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs/skriv float.

--------------------

Det returnerade värdet är alltid definierat och aldrig Float.NaN. Det tilldelade värdet måste också vara definierat; tilldela Float.NaN endast till egenskaper i en RawFrame-instans.

**Returnerar:**
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Hämtar eller anger y-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs/skriv float.

--------------------

Det returnerade värdet är alltid definierat och aldrig Float.NaN. Det tilldelade värdet måste också vara definierat; tilldela Float.NaN endast till egenskaper i en RawFrame-instans.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Hämtar eller anger bredden på formen, mätt i punkter. Läs/skriv float.

--------------------

Det är alltid definierat och aldrig Float.NaN. Det tilldelade värdet måste också vara definierat; tilldela Float.NaN endast till egenskaper i en RawFrame-instans.

**Returnerar:**
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Hämtar eller anger bredden på formen, mätt i punkter. Läs/skriv float.

--------------------

Det är alltid definierat och aldrig Float.NaN. Det tilldelade värdet måste också vara definierat; tilldela Float.NaN endast till egenskaper i en RawFrame-instans.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Hämtar eller anger höjden på formen, mätt i punkter. Läs/skriv float.

--------------------

Det är alltid definierat och aldrig Float.NaN. Det tilldelade värdet måste också vara definierat; tilldela Float.NaN endast till egenskaper i en RawFrame-instans.

**Returnerar:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Hämtar eller anger höjden på formen, mätt i punkter. Läs/skriv float.

--------------------

Det är alltid definierat och aldrig Float.NaN. Det tilldelade värdet måste också vara definierat; tilldela Float.NaN endast till egenskaper i en RawFrame-instans.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```

Egenskapen anger hur en form ska renderas i svart-vitt visningsläge. Läs/skriv [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Returnerar:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```

Egenskapen anger hur en form ska renderas i svart-vitt visningsläge. Läs/skriv [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```

Returnerar en intern, presentation-omfattande identifierare avsedd för användning av tillägg eller annan kod. Eftersom detta värde kan omdefinieras av användaren eller programmässigt, bör det inte behandlas som en beständig unik nyckel. Skrivskyddad long. Se även \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Returnerar:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```

Returnerar en bild-omfattande unik identifierare som förblir konstant under formens livstid och låter PowerPoint eller interop-kod på ett tillförlitligt sätt referera till formen från vilken plats som helst i dokumentet. Skrivskyddad long. Se även \#getUniqueId.getUniqueId.

**Returnerar:**
long

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```

Returnerar eller anger alternativ text associerad med en form. Läs/skriv String.

**Returnerar:**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final String getAlternativeText()
```

Returnerar eller anger alternativ text associerad med en form. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```

Returnerar eller anger titeln för alternativ text associerad med en form. Läs/skriv String.

**Returnerar:**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```

Returnerar eller anger titeln för alternativ text associerad med en form. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```

Returnerar eller anger namnet på en form. Måste vara icke-null. Använd tom sträng om behövs. Läs/skriv String.

**Returnerar:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Returnerar eller anger namnet på en form. Måste vara icke-null. Använd tom sträng om behövs. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```

Hämtar eller anger 'Markera som dekorativ' alternativet Läs/skriv boolesk.

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
public final void setDecorative(boolean value)
```

Hämtar eller anger 'Markera som dekorativ' alternativet Läs/skriv boolesk.

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
public IBaseShapeLock getShapeLock()
```

Returnerar formens lås. Skrivskyddad [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Returnerar:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```

Bestämmer om formen är grupperad. Skrivskyddad boolean.

--------------------

Egenskap \#getParentGroup.getParentGroup returnerar förälder-GroupShape-objektet om formen är grupperad.

**Returnerar:**
boolean

### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Returnerar förälder-GroupShape-objektet om formen är grupperad. Annars returnerar null. Skrivskyddad [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

Egenskap \#isGrouped.isGrouped bestämmer om formen är grupperad.

**Returnerar:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returnerar Parent\_Immediate-objektet. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject

### getVisualBounds() {#getVisualBounds--}
```
public final RectF getVisualBounds()
```

Hämtar de visuella gränserna för formen beräknade från dess renderade innehåll.

**Returnerar:**
android.graphics.RectF - En android.graphics.RectF som representerar de visuella gränserna för formen i bildkoordinater.

--------------------

Den returnerade rektangeln representerar de axel-inriktade gränserna för allt innehåll som formen producerar under rendering i bildkoordinatrummet. Dessa gränser kan skilja sig från modellgränserna \#getX.getX/\#setX(float).setX(float), \#getY.getY/\#setY(float).setY(float), \#getWidth.getWidth/\#setWidth(float).setWidth(float), \#getHeight.getHeight/\#setHeight(float).setHeight(float) och kan innehålla negativa koordinater om det renderade innehållet sträcker sig bortom bildens origo. De visuella gränserna tar hänsyn till transformations-faktorer som rotation, linjebredd och hörn, textlayout och översvämning, SmartArt-geometri och andra layout-effekter som påverkar det slutliga renderade utseendet på formen. Den återvända gränsen är inte lagrad till bildrektangeln.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returnerar föräldrabilden för en form. Skrivskyddad [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Returnerar:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Returnerar föräldrapresentationen för en bild. Skrivskyddad [IPresentation](../../com.aspose.slides/ipresentation).

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation)