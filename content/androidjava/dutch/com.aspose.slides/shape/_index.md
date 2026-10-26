---
title: Shape
second_title: Aspose.Slides voor Android via Java API-referentie
description: Representeert een vorm op een dia.
type: docs
url: /nl/com.aspose.slides/shape/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape), com.aspose.slides.IDOMObject
```
public class Shape implements IShape, IDOMObject
```

Stelt een vorm op een dia voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Bepaalt of de vorm TextHolder_PPT is. |
| [getPlaceholder()](#getPlaceholder--) | Retourneert de placeholder voor een vorm. |
| [removePlaceholder()](#removePlaceholder--) | Definieert dat deze vorm geen placeholder is. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Voegt een nieuwe placeholder toe als er geen is en stelt placeholder-eigenschappen in op een opgegeven. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Retourneert een basis-placeholder vorm (vorm van de lay-out en/of masterdia waarvan de huidige vorm is geërfd). |
| [getCustomData()](#getCustomData--) | Retourneert de aangepaste gegevens van de vorm. |
| [getRawFrame()](#getRawFrame--) | Retourneert of stelt de eigenschappen van het ruwe vormframe in. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Retourneert of stelt de eigenschappen van het ruwe vormframe in. |
| [getFrame()](#getFrame--) | Retourneert of stelt de eigenschappen van het vormframe in. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Retourneert of stelt de eigenschappen van het vormframe in. |
| [getLineFormat()](#getLineFormat--) | Retourneert het LineFormat-object dat lijnopmaak-eigenschappen bevat voor een vorm. |
| [getThreeDFormat()](#getThreeDFormat--) | Retourneert het ThreeDFormat-object dat 3D-effecteigenschappen bevat voor een vorm. |
| [getEffectFormat()](#getEffectFormat--) | Retourneert het EffectFormat-object dat pixel-effecten bevat die op een vorm worden toegepast. |
| [getFillFormat()](#getFillFormat--) | Retourneert het FillFormat-object dat vulopmaak-eigenschappen bevat voor een vorm. |
| [getImage()](#getImage--) | Retourneert een miniatuur van de vorm. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Retourneert een miniatuur van de vorm. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Slaat de inhoud van Shape op als SVG-bestand. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Slaat de inhoud van Shape op als SVG-bestand. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Retourneert of stelt de hyperlink in die is gedefinieerd voor muisklik. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Retourneert of stelt de hyperlink in die is gedefinieerd voor muisklik. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Retourneert of stelt de hyperlink in die is gedefinieerd voor muisover. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Retourneert of stelt de hyperlink in die is gedefinieerd voor muisover. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Retourneert de hyperlink-manager. |
| [getHidden()](#getHidden--) | Bepaalt of de vorm verborgen is. |
| [setHidden(boolean value)](#setHidden-boolean-) | Bepaalt of de vorm verborgen is. |
| [getZOrderPosition()](#getZOrderPosition--) | Retourneert de positie van een vorm in de Z-volgorde. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Retourneert het aantal aansluitpunten op de vorm. |
| [getRotation()](#getRotation--) | Retourneert of stelt het aantal graden in waarmee de opgegeven vorm om de Z-as is gedraaid. |
| [setRotation(float value)](#setRotation-float-) | Retourneert of stelt het aantal graden in waarmee de opgegeven vorm om de Z-as is gedraaid. |
| [getX()](#getX--) | Haalt of stelt de x-coördinaat van de linkerbovenhoek van de vorm, gemeten in points, in. |
| [setX(float value)](#setX-float-) | Haalt of stelt de x-coördinaat van de linkerbovenhoek van de vorm, gemeten in points, in. |
| [getY()](#getY--) | Haalt of stelt de y-coördinaat van de linkerbovenhoek van de vorm, gemeten in points, in. |
| [setY(float value)](#setY-float-) | Haalt of stelt de y-coördinaat van de linkerbovenhoek van de vorm, gemeten in points, in. |
| [getWidth()](#getWidth--) | Haalt of stelt de breedte van de vorm, gemeten in points, in. |
| [setWidth(float value)](#setWidth-float-) | Haalt of stelt de breedte van de vorm, gemeten in points, in. |
| [getHeight()](#getHeight--) | Haalt of stelt de hoogte van de vorm, gemeten in points, in. |
| [setHeight(float value)](#setHeight-float-) | Haalt of stelt de hoogte van de vorm, gemeten in points, in. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Eigenschap specificeert hoe een vorm wordt weergegeven in zwart-wit weergavemodus. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Eigenschap specificeert hoe een vorm wordt weergegeven in zwart-wit weergavemodus. |
| [getUniqueId()](#getUniqueId--) | Retourneert een interne, presentatie-scoped identifier bedoeld voor gebruik door add-ins of andere code. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Retourneert een dia-scoped unieke identifier die constant blijft gedurende de levensduur van de vorm en PowerPoint of interop-code in staat stelt de vorm betrouwbaar te refereren vanuit elk deel van het document. |
| [getAlternativeText()](#getAlternativeText--) | Retourneert of stelt de alternatieve tekst in die aan een vorm is gekoppeld. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Retourneert of stelt de alternatieve tekst in die aan een vorm is gekoppeld. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Retourneert of stelt de titel van de alternatieve tekst in die aan een vorm is gekoppeld. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Retourneert of stelt de titel van de alternatieve tekst in die aan een vorm is gekoppeld. |
| [getName()](#getName--) | Retourneert of stelt de naam van een vorm in. |
| [setName(String value)](#setName-java.lang.String-) | Retourneert of stelt de naam van een vorm in. |
| [isDecorative()](#isDecorative--) | Haalt of stelt de 'Mark as decorative' optie in. Lezen/Schrijven boolean. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Haalt of stelt de 'Mark as decorative' optie in. Lezen/Schrijven boolean. |
| [getShapeLock()](#getShapeLock--) | Retourneert de vergrendelingen van de vorm. |
| [isGrouped()](#isGrouped--) | Bepaalt of de vorm gegroepeerd is. |
| [getParentGroup()](#getParentGroup--) | Retourneert het bovenliggende GroupShape-object als de vorm gegroepeerd is. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVisualBounds()](#getVisualBounds--) | Haalt de visuele grenzen van de vorm op, berekend vanaf de gerenderde inhoud. |
| [getSlide()](#getSlide--) | Retourneert de bovenliggende dia van een vorm. |
| [getPresentation()](#getPresentation--) | Retourneert de bovenliggende presentatie van een dia. |

### isTextHolder() {#isTextHolder--}
```
public final boolean isTextHolder()
```

Bepaalt of de vorm TextHolder_PPT is. Alleen-lezen boolean.

**Retourneert:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```

Retourneert de placeholder voor een vorm. Retourneert null als de vorm geen placeholder heeft. Alleen-lezen [IPlaceholder](../../com.aspose.slides/iplaceholder).

--------------------
> ```
> Het volgende voorbeeld toont hoe tekst in een placeholder te wijzigen.
>  
>  // Initialiseert een Presentation-klasse
>  Presentation pres = new Presentation("ReplacingText.pptx");
>  try {
>      // Toegang tot de eerste dia
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Doorloopt vormen om de placeholder te vinden
>      for (IShape shp : sld.getShapes())
>          if (shp.getPlaceholder() != null)
>          {
>              // Wijzigt de tekst in elke placeholder
>              ((IAutoShape)shp).getTextFrame().setText("This is a Placeholder");
>          }
>      // Slaat de presentatie op schijf op
>      pres.save("output_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  Het volgende voorbeeld toont hoe Prompt-tekst in een placeholder in te stellen.
>  
>  Presentation pres = new Presentation("Presentation2.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      for (IShape shape : slide.getSlide().getShapes()) // Doorloopt de dia
>      {
>          if (shape.getPlaceholder() != null && shape instanceof AutoShape)
>          {
>              String text = "";
>              if (shape.getPlaceholder().getType() == PlaceholderType.CenteredTitle) // PowerPoint toont "Click to add title"
>              {
>                  text = "Add Title";
>              }
>              else if (shape.getPlaceholder().getType() == PlaceholderType.Subtitle) // Voegt ondertitel toe
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
```

**Retourneert:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### removePlaceholder() {#removePlaceholder--}
```
public final void removePlaceholder()
```

Definieert dat deze vorm geen placeholder is.

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public final IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Voegt een nieuwe placeholder toe als er geen is en stelt placeholder-eigenschappen in op een opgegeven.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Placeholder om inhoud van te kopiëren. |

**Retourneert:** [IPlaceholder](../../com.aspose.slides/iplaceholder) - Nieuw #getPlaceholder.getPlaceholder.

### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

Retourneert een basis-placeholder vorm (vorm van de lay-out en/of masterdia waarvan de huidige vorm is geërfd).

--------------------
> ```
> // haal alle (master/layout/slide) geanimeerde effecten van de placeholder vorm op
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


Er wordt null geretourneerd als de huidige vorm niet is geërfd.

**Retourneert:**
[IShape](../../com.aspose.slides/ishape)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Retourneert de aangepaste gegevens van de vorm. Alleen-lezen [ICustomData](../../com.aspose.slides/icustomdata).

**Retourneert:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public final IShapeFrame getRawFrame()
```

Retourneert of stelt de eigenschappen van het ruwe vormframe in. Lezen/Schrijven [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------
> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //of
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Dergelijke code kan tot onduidelijke situaties leiden. Daarom zijn er beperkingen toegevoegd voor het gebruik van ongedefinieerde waarden voor IShape.getFrame(). Waarden van x, y, width, height, flipH, flipV en rotationAngle moeten gedefinieerd zijn (niet Float.NaN of NullableBool.NotDefined). Bovenstaand voorbeeldcode gooit nu een ArgumentException.
>  //Dit geldt voor deze use-cases:
>  IShape shape = ...;
>  shape.setFrame(...); //mag niet ongedefinieerd zijn
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
>  //Maar IShape.RawFrame frame-eigenschappen kunnen ongedefinieerd zijn. Dit heeft zin wanneer een vorm is gekoppeld aan een placeholder. Dan worden ongedefinieerde frame-waarden van de vorm overschreven door de bovenliggende placeholder-vorm. Als er geen bovenliggende placeholder-vorm voor die vorm bestaat, gebruikt die vorm standaardwaarden bij het bepalen van het effectieve frame op basis van zijn IShape.RawFrame. Standaardwaarden zijn 0 en NullableBool.False voor x, y, width, height, flipH, flipV en rotationAngle. Bijvoorbeeld:
>  IShape shape = ...; //vorm is gekoppeld aan placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); //nu erft de vorm x, y, height, flipH, flipV waarden van de placeholder en overschrijft width=100 en rotationAngle=0.{code}
> ```


**Retourneert:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
```

Retourneert of stelt de eigenschappen van het ruwe vormframe in. Lezen/Schrijven [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------
> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //of
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Dergelijke code kan tot onduidelijke situaties leiden. Daarom zijn er beperkingen toegevoegd voor het gebruik van ongedefinieerde waarden voor IShape.getFrame(). Waarden van x, y, width, height, flipH, flipV en rotationAngle moeten gedefinieerd zijn (niet Float.NaN of NullableBool.NotDefined). Bovenstaande voorbeeldcode werpt nu een ArgumentException.
>  //Dit geldt voor deze use-cases:
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
>  //Maar IShape.RawFrame frame-eigenschappen kunnen ongedefinieerd zijn. Dit heeft zin wanneer een vorm is gekoppeld aan een placeholder. Dan worden ongedefinieerde frame-waarden van de vorm overschreven door de bovenliggende placeholder-vorm. Als er geen bovenliggende placeholder-vorm voor die vorm bestaat, gebruikt die vorm standaardwaarden bij het bepalen van het effectieve frame op basis van zijn IShape.RawFrame. Standaardwaarden zijn 0 en NullableBool.False voor x, y, width, height, flipH, flipV en rotationAngle. Bijvoorbeeld:
>  IShape shape = ...; // vorm is gekoppeld aan placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // nu erft de vorm x, y, height, flipH, flipV waarden van de placeholder en overschrijft width=100 en rotationAngle=0.{code}
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Retourneert of stelt de eigenschappen van het vormframe in. Lezen/Schrijven [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------
De waarde van elke eigenschap van de geretourneerde IShapeFrame-instance is niet undefined (is niet NaN of NotDefined). De waarde van elke eigenschap van de toegewezen IShapeFrame-instance moet niet undefined zijn (moet niet NaN of NotDefined zijn). Je kunt undefined-waarden instellen voor RawFrame-instance-eigenschappen.

**Retourneert:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Retourneert of stelt de eigenschappen van het vormframe in. Lezen/Schrijven [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------
De waarde van elke eigenschap van de geretourneerde IShapeFrame-instance is niet undefined (is niet NaN of NotDefined). De waarde van elke eigenschap van de toegewezen IShapeFrame-instance moet niet undefined zijn (moet niet NaN of NotDefined zijn). Je kunt undefined-waarden instellen voor RawFrame-instance-eigenschappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

Retourneert het LineFormat-object dat lijnopmaak-eigenschappen bevat voor een vorm. Opmerking: kan null retourneren voor bepaalde soorten vormen die geen lijn-eigenschappen hebben. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

**Retourneert:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

Retourneert het ThreeDFormat-object dat 3D-effecteigenschappen bevat voor een vorm. Opmerking: kan null retourneren voor bepaalde soorten vormen die geen 3D-eigenschappen hebben. Alleen-lezen [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Retourneert:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

Retourneert het EffectFormat-object dat pixel-effecten bevat die op een vorm worden toegepast. Opmerking: kan null retourneren voor bepaalde soorten vormen die geen effect-eigenschappen hebben. Alleen-lezen [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Retourneert:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Retourneert het FillFormat-object dat vulopmaak-eigenschappen bevat voor een vorm. Opmerking: kan null retourneren voor bepaalde soorten vormen die geen vul-eigenschappen hebben. Alleen-lezen [IFillFormat](../../com.aspose.slides/ifillformat).

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
>      // Accent 4, Lichter 80%
>      IShape shape2 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 70, 50, 50);
>      shape2.getFillFormat().setFillType(FillType.Solid);
>      shape2.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.2f);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.8f);
>      // Accent 4, Lichter 60%
>      IShape shape3 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 130, 50, 50);
>      shape3.getFillFormat().setFillType(FillType.Solid);
>      shape3.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.4f);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.6f);
>      // Accent 4, Lichter 40%
>      IShape shape4 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 190, 50, 50);
>      shape4.getFillFormat().setFillType(FillType.Solid);
>      shape4.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.6f);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.4f);
>      // Accent 4, Donkerder 25%
>      IShape shape5 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 250, 50, 50);
>      shape5.getFillFormat().setFillType(FillType.Solid);
>      shape5.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape5.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.75f);
>      // Accent 4, Donkerder 50%
>      IShape shape6 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 310, 50, 50);
>      shape6.getFillFormat().setFillType(FillType.Solid);
>      shape6.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape6.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.5f);
>      pres.save("example_accent4.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retourneert:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public final IImage getImage()
```

Retourneert een miniatuur van de vorm. ShapeThumbnailBounds.Shape vorm miniatuurbounds-type wordt standaard gebruikt.

**Retourneert:**
[IImage](../../com.aspose.slides/iimage) - Vorm miniatuur.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IImage getImage(int bounds, float scaleX, float scaleY)
```

Retourneert een miniatuur van de vorm.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bounds | int | Vorm miniatuur bounds type. |
| scaleX | float | X-schaal |
| scaleY | float | Y-schaal |

**Retourneert:**
[IImage](../../com.aspose.slides/iimage) - Vorm miniatuur of null in het geval dat ShapeThumbnailBounds.Appearance wordt gebruikt en een vorm geen zichtbare elementen heeft.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

Slaat de inhoud van Shape op als SVG-bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Doelstream |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Slaat de inhoud van Shape op als SVG-bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Doelstream |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG-generatie-opties |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

Retourneert of stelt de hyperlink in die is gedefinieerd voor muisklik. Lezen/Schrijven [IHyperlink](../../com.aspose.slides/ihyperlink).

**Retourneert:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

Retourneert of stelt de hyperlink in die is gedefinieerd voor muisklik. Lezen/Schrijven [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

Retourneert of stelt de hyperlink in die is gedefinieerd voor muisover. Lezen/Schrijven [IHyperlink](../../com.aspose.slides/ihyperlink).

**Retourneert:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

Retourneert of stelt de hyperlink in die is gedefinieerd voor muisover. Lezen/Schrijven [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

Retourneert de hyperlink-manager. Alleen-lezen [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Retourneert:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Bepaalt of de vorm verborgen is. Lezen/Schrijven boolean.

**Retourneert:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Bepaalt of de vorm verborgen is. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

Retourneert de positie van een vorm in de Z-volgorde. Shapes[0] retourneert de vorm aan de achterkant van de Z-volgorde, en Shapes[Shapes.Count - 1] retourneert de vorm aan de voorkant van de Z-volgorde. Alleen-lezen int.

**Retourneert:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```

Retourneert het aantal aansluitpunten op de vorm. Alleen-lezen int.

**Retourneert:**
int

### getRotation() {#getRotation--}
```
public final float getRotation()
```

Retourneert of stelt het aantal graden in waarmee de opgegeven vorm om de Z-as is gedraaid. Een positieve waarde geeft wijzerzinrotatie aan; een negatieve waarde geeft tegenwijzerzinrotatie aan. Lezen/Schrijven float.

--------------------
Geretourneerde waarde is altijd gedefinieerd (is niet Float.NaN). Toegewezen waarde moet gedefinieerd zijn (niet Float.NaN). Je kunt undefined-waarden instellen voor RawFrame-instance-eigenschappen.

**Retourneert:**
float

### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```

Retourneert of stelt het aantal graden in waarmee de opgegeven vorm om de Z-as is gedraaid. Een positieve waarde geeft wijzerzinrotatie aan; een negatieve waarde geeft tegenwijzerzinrotatie aan. Lezen/Schrijven float.

--------------------
Geretourneerde waarde is altijd gedefinieerd (is niet Float.NaN). Toegewezen waarde moet gedefinieerd zijn (niet Float.NaN). Je kunt undefined-waarden instellen voor RawFrame-instance-eigenschappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public final float getX()
```

Haalt of stelt de x-coördinaat van de linkerbovenhoek van de vorm, gemeten in points, in. Lezen/Schrijven float.

De geretourneerde waarde is altijd gedefinieerd en nooit Float.NaN. De toegewezen waarde moet ook gedefinieerd zijn; wijs Float.NaN alleen toe aan eigenschappen van een RawFrame-instance.

**Retourneert:**
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Haalt of stelt de x-coördinaat van de linkerbovenhoek van de vorm, gemeten in points, in. Lezen/Schrijven float.

De geretourneerde waarde is altijd gedefinieerd en nooit Float.NaN. De toegewezen waarde moet ook gedefinieerd zijn; wijs Float.NaN alleen toe aan eigenschappen van een RawFrame-instance.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

Haalt of stelt de y-coördinaat van de linkerbovenhoek van de vorm, gemeten in points, in. Lezen/Schrijven float.

De geretourneerde waarde is altijd gedefinieerd en nooit Float.NaN. De toegewezen waarde moet ook gedefinieerd zijn; wijs Float.NaN alleen toe aan eigenschappen van een RawFrame-instance.

**Retourneert:**
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Haalt of stelt de y-coördinaat van de linkerbovenhoek van de vorm, gemeten in points, in. Lezen/Schrijven float.

De geretourneerde waarde is altijd gedefinieerd en nooit Float.NaN. De toegewezen waarde moet ook gedefinieerd zijn; wijs Float.NaN alleen toe aan eigenschappen van een RawFrame-instance.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Haalt of stelt de breedte van de vorm, gemeten in points, in. Lezen/Schrijven float.

De geretourneerde waarde is altijd gedefinieerd en nooit Float.NaN. De toegewezen waarde moet ook gedefinieerd zijn; wijs Float.NaN alleen toe aan eigenschappen van een RawFrame-instance.

**Retourneert:**
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Haalt of stelt de breedte van de vorm, gemeten in points, in. Lezen/Schrijven float.

De geretourneerde waarde is altijd gedefinieerd en nooit Float.NaN. De toegewezen waarde moet ook gedefinieerd zijn; wijs Float.NaN alleen toe aan eigenschappen van een RawFrame-instance.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Haalt of stelt de hoogte van de vorm, gemeten in points, in. Lezen/Schrijven float.

De geretourneerde waarde is altijd gedefinieerd en nooit Float.NaN. De toegewezen waarde moet ook gedefinieerd zijn; wijs Float.NaN alleen toe aan eigenschappen van een RawFrame-instance.

**Retourneert:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Haalt of stelt de hoogte van de vorm, gemeten in points, in. Lezen/Schrijven float.

De geretourneerde waarde is altijd gedefinieerd en nooit Float.NaN. De toegewezen waarde moet ook gedefinieerd zijn; wijs Float.NaN alleen toe aan eigenschappen van een RawFrame-instance.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```

Eigenschap specificeert hoe een vorm wordt weergegeven in zwart-wit weergavemodus. Lezen/Schrijven [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Retourneert:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```

Eigenschap specificeert hoe een vorm wordt weergegeven in zwart-wit weergavemodus. Lezen/Schrijven [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```

Retourneert een interne, presentatie-scoped identifier bedoeld voor gebruik door add-ins of andere code. Omdat deze waarde opnieuw kan worden toegewezen door de gebruiker of programmatisch, mag deze niet worden beschouwd als een permanente unieke sleutel. Alleen-lezen long. Zie ook #getOfficeInteropShapeId.getOfficeInteropShapeId.

**Retourneert:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```

Retourneert een dia-scoped unieke identifier die constant blijft gedurende de levensduur van de vorm en PowerPoint of interop-code in staat stelt de vorm betrouwbaar te refereren vanuit elk deel van het document. Alleen-lezen long. Zie ook #getUniqueId.getUniqueId.

**Retourneert:**
long

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```

Retourneert of stelt de alternatieve tekst in die aan een vorm is gekoppeld. Lezen/Schrijven String.

**Retourneert:**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```

Retourneert of stelt de alternatieve tekst in die aan een vorm is gekoppeld. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```

Retourneert of stelt de titel van de alternatieve tekst in die aan een vorm is gekoppeld. Lezen/Schrijven String.

**Retourneert:**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```

Retourneert of stelt de titel van de alternatieve tekst in die aan een vorm is gekoppeld. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```

Retourneert of stelt de naam van een vorm in. Mag niet null zijn. Gebruik een lege tekenreeks indien nodig. Lezen/Schrijven String.

**Retourneert:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Retourneert of stelt de naam van een vorm in. Mag niet null zijn. Gebruik een lege tekenreeks indien nodig. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```

Haalt of stelt de 'Mark as decorative' optie in. Lezen/Schrijven boolean.

--------------------
> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourneert:**
boolean

### setDecorative(boolean value) {#setDecorative-boolean-}
```
public final void setDecorative(boolean value)
```

Haalt of stelt de 'Mark as decorative' optie in. Lezen/Schrijven boolean.

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
public IBaseShapeLock getShapeLock()
```

Retourneert de vergrendelingen van de vorm. Alleen-lezen [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Retourneert:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```

Bepaalt of de vorm gegroepeerd is. Alleen-lezen boolean.

--------------------
Eigenschap #getParentGroup.getParentGroup retourneert het bovenliggende GroupShape-object als de vorm gegroepeerd is.

**Retourneert:**
boolean

### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Retourneert het bovenliggende GroupShape-object als de vorm gegroepeerd is. Retourneert anders null. Alleen-lezen [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------
Eigenschap #isGrouped.isGrouped bepaalt of de vorm gegroepeerd is.

**Retourneert:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retourneert Parent_Immediate-object. Alleen-lezen IDOMObject.

**Retourneert:**
com.aspose.slides.IDOMObject

### getVisualBounds() {#getVisualBounds--}
```
public final RectF getVisualBounds()
```

Haalt de visuele grenzen van de vorm op, berekend vanuit de gerenderde inhoud.

**Retourneert:**
android.graphics.RectF - Een android.graphics.RectF die de visuele grenzen van de vorm in dia-coördinaten weergeeft.

--------------------
Het geretourneerde rechthoek vertegenwoordigt de as-uitgelijnde grenzen van alle inhoud die door de vorm tijdens het renderen in dia-coördinatenruimte is geproduceerd. Deze grenzen kunnen afwijken van de modelgrenzen van de vorm #getX.getX/#setX(float).setX(float), #getY.getY/#setY(float).setY(float), #getWidth.getWidth/#setWidth(float).setWidth(float), #getHeight.getHeight/#setHeight(float).setHeight(float) en kunnen negatieve coördinaten bevatten als de gerenderde inhoud voorbij de beginpositie van de dia reikt. De visuele grenzen houden rekening met render-gerelateerde aspecten zoals transformaties (bijvoorbeeld rotatie), lijndikte en hoeken, tekstindeling en overlopen, SmartArt-geometrie, en andere lay-outeffecten die de uiteindelijke weergave van de vorm beïnvloeden. De geretourneerde grenzen worden niet bijgesneden tot de dia-rechthoek.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Retourneert de bovenliggende dia van een vorm. Alleen-lezen [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Retourneert:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retourneert de bovenliggende presentatie van een dia. Alleen-lezen [IPresentation](../../com.aspose.slides/ipresentation).

**Retourneert:**
[IPresentation](../../com.aspose.slides/ipresentation)