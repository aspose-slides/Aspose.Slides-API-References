---
title: Shape
second_title: Aspose.Slides for Java API-referentie
description: Stelt een vorm op een dia voor.
type: docs
url: /nl/com.aspose.slides/shape/
---
**Erfelijkheid:**
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
| [getBasePlaceholder()](#getBasePlaceholder--) | Retourneert een basis placeholder-vorm (vorm van de lay-out en/of masterdia waar de huidige vorm van erft). |
| [getCustomData()](#getCustomData--) | Retourneert de aangepaste gegevens van de vorm. |
| [getRawFrame()](#getRawFrame--) | Retourneert of stelt de ruwe vormframe-eigenschappen in. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Retourneert of stelt de ruwe vormframe-eigenschappen in. |
| [getFrame()](#getFrame--) | Retourneert of stelt de ruwe vormframe-eigenschappen in. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Retourneert of stelt de ruwe vormframe-eigenschappen in. |
| [getLineFormat()](#getLineFormat--) | Retourneert het LineFormat-object dat lijnopmaak-eigenschappen voor een vorm bevat. |
| [getThreeDFormat()](#getThreeDFormat--) | Retourneert het ThreeDFormat-object dat 3D-effecteigenschappen voor een vorm bevat. |
| [getEffectFormat()](#getEffectFormat--) | Retourneert het EffectFormat-object dat pixel-effecten op een vorm bevat. |
| [getFillFormat()](#getFillFormat--) | Retourneert het FillFormat-object dat opvulopmaak-eigenschappen voor een vorm bevat. |
| [getImage()](#getImage--) | Retourneert vormminiatuur. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Retourneert vormminiatuur. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Slaat de inhoud van Vorm op als SVG-bestand. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Slaat de inhoud van Vorm op als SVG-bestand. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Retourneert of stelt de hyperlink in die is gedefinieerd voor muisklik. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Retourneert of stelt de hyperlink in die is gedefinieerd voor muisklik. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Retourneert of stelt de hyperlink in die is gedefinieerd voor muis-over. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Retourneert of stelt de hyperlink in die is gedefinieerd voor muis-over. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Retourneert de hyperlink-beheerder. |
| [getHidden()](#getHidden--) | Bepaalt of de vorm verborgen is. |
| [setHidden(boolean value)](#setHidden-boolean-) | Bepaalt of de vorm verborgen is. |
| [getZOrderPosition()](#getZOrderPosition--) | Retourneert de positie van een vorm in de z-volgorde. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Retourneert het aantal verbindingspunten op de vorm. |
| [getRotation()](#getRotation--) | Retourneert of stelt het aantal graden in waarmee de opgegeven vorm rond de z-as is geroteerd. |
| [setRotation(float value)](#setRotation-float-) | Retourneert of stelt het aantal graden in waarmee de opgegeven vorm rond de z-as is geroteerd. |
| [getX()](#getX--) | Haalt of stelt de x-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten. |
| [setX(float value)](#setX-float-) | Haalt of stelt de x-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten. |
| [getY()](#getY--) | Haalt of stelt de y-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten. |
| [setY(float value)](#setY-float-) | Haalt of stelt de y-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten. |
| [getWidth()](#getWidth--) | Haalt of stelt de breedte van de vorm in, gemeten in punten. |
| [setWidth(float value)](#setWidth-float-) | Haalt of stelt de breedte van de vorm in, gemeten in punten. |
| [getHeight()](#getHeight--) | Haalt of stelt de hoogte van de vorm in, gemeten in punten. |
| [setHeight(float value)](#setHeight-float-) | Haalt of stelt de hoogte van de vorm in, gemeten in punten. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Eigenschap geeft aan hoe een vorm wordt gerenderd in zwart-wit weergavemodus.. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Eigenschap geeft aan hoe een vorm wordt gerenderd in zwart-wit weergavemodus.. |
| [getUniqueId()](#getUniqueId--) | Retourneert een interne, presentatie-gebonden identifier bedoeld voor gebruik door add-ins of andere code. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Retourneert een dia-gebonden unieke identifier die constant blijft gedurende de levensduur van de vorm en PowerPoint of interop-code betrouwbaar laat verwijzen naar de vorm vanuit elk deel van het document. |
| [getAlternativeText()](#getAlternativeText--) | Retourneert of stelt de alternatieve tekst in die aan een vorm is gekoppeld. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Retourneert of stelt de alternatieve tekst in die aan een vorm is gekoppeld. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Retourneert of stelt de titel van de alternatieve tekst in die aan een vorm is gekoppeld. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Retourneert of stelt de titel van de alternatieve tekst in die aan een vorm is gekoppeld. |
| [getName()](#getName--) | Retourneert of stelt de naam van een vorm in. |
| [setName(String value)](#setName-java.lang.String-) | Retourneert of stelt de naam van een vorm in. |
| [isDecorative()](#isDecorative--) | Haalt of stelt de optie ‘Mark as decorative’ in, Lezen/schrijven boolean. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Haalt of stelt de optie ‘Mark as decorative’ in, Lezen/schrijven boolean. |
| [getShapeLock()](#getShapeLock--) | Retourneert de vergrendelingen van de vorm. |
| [isGrouped()](#isGrouped--) | Bepaalt of de vorm gegroepeerd is. |
| [getParentGroup()](#getParentGroup--) | Retourneert het bovenliggende GroupShape-object als de vorm gegroepeerd is. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVisualBounds()](#getVisualBounds--) | Haalt de visuele grenzen van de vorm op, berekend uit de gerenderde inhoud. |
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

---

> ```
> The following example shows how to change Text in Placeholder.
>  
>  // Instantieert een Presentation-klasse
>  Presentation pres = new Presentation("ReplacingText.pptx");
>  try {
>      // Toegang tot de eerste dia
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Itereert door vormen om de placeholder te vinden
>      for (IShape shp : sld.getShapes())
>          if (shp.getPlaceholder() != null)
>          {
>              // Wijzigt de tekst in elke placeholder
>              ((IAutoShape)shp).getTextFrame().setText("This is a Placeholder");
>          }
>      // Slaat de presentatie op naar schijf
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
>      for (IShape shape : slide.getSlide().getShapes()) // Itereert door de dia
>      {
>          if (shape.getPlaceholder() != null && shape instanceof AutoShape)
>          {
>              String text = "";
>              if (shape.getPlaceholder().getType() == PlaceholderType.CenteredTitle) // PowerPoint toont "Klik om titel toe te voegen"
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
> ```


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

**Retourneert:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - Nieuwe #getPlaceholder.getPlaceholder.

### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

Retourneert een basis placeholder-vorm (vorm van de lay-out en/of masterdia waar de huidige vorm van erft).

---

> ```
> // haal alle (master/layout/slide) geanimeerde effecten van de placeholdervorm op
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


Een null wordt geretourneerd als de huidige vorm niet geërfd is.

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

Retourneert of stelt de ruwe vormframe-eigenschappen in. Lezen/schrijven [IShapeFrame](../../com.aspose.slides/ishapeframe).

---

> ```markdown
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //of
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Zo'n code kan tot onduidelijke situaties leiden. Daarom zijn er beperkingen toegevoegd voor het gebruik van ongedefinieerde waarden voor IShape.getFrame(). Waarden van x, y, breedte, hoogte, flipH, flipV en rotatiehoek moeten gedefinieerd zijn (niet Float.NaN of NullableBool.NotDefined). Voorbeeldcode hierboven veroorzaakt nu een ArgumentException.
>  //Dit is van toepassing op deze gebruikssituaties:
>  IShape shape = ...;
>  shape.setFrame(...); // mag niet ongedefinieerd zijn
>  IShapeCollection shapes = ...;
>  // x, y, breedte, hoogte parameters mogen geen Float.NaN zijn:
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
>  //Maar IShape.RawFrame frame-eigenschappen kunnen ongedefinieerd zijn. Dit heeft zin wanneer een shape is gekoppeld aan een placeholder. Dan worden ongedefinieerde shape-frame-waarden overschreven door de bovenliggende placeholder-shape. Als er geen bovenliggende placeholder-shape voor die shape bestaat, dan gebruikt die shape standaardwaarden bij het berekenen van het effectieve frame op basis van zijn IShape.RawFrame. Standaardwaarden zijn 0 en NullableBool.False voor x, y, breedte, hoogte, flipH, flipV en rotatiehoek. Bijvoorbeeld:
>  IShape shape = ...; // shape is gekoppeld aan placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // nu erft de shape x, y, hoogte, flipH, flipV waarden van de placeholder en overschrijft breedte=100 en rotatiehoek=0.{code}
```

**Retourneert:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
```

Retourneert of stelt de ruwe vormframe-eigenschappen in. Lezen/schrijven [IShapeFrame](../../com.aspose.slides/ishapeframe).

---

> ```markdown
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //of
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Zo'n code kan tot onduidelijke situaties leiden. Daarom zijn er beperkingen toegevoegd voor het gebruik van ongedefinieerde waarden voor IShape.getFrame(). Waarden van x, y, breedte, hoogte, flipH, flipV en rotatiehoek moeten gedefinieerd zijn (niet Float.NaN of NullableBool.NotDefined). Voorbeeldcode hierboven werpt nu een ArgumentException.
>  //Dit is van toepassing op deze gebruikssituaties:
>  IShape shape = ...;
>  shape.setFrame(...); // mag niet ongedefinieerd zijn
>  IShapeCollection shapes = ...;
>  // x, y, breedte, hoogte parameters mogen geen Float.NaN zijn:
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
>  //Maar IShape.RawFrame-frame-eigenschappen kunnen ongedefinieerd zijn. Dit heeft zin wanneer een shape is gekoppeld aan een placeholder. Dan worden ongedefinieerde shape-frame-waarden overschreven door de bovenliggende placeholder. Als er geen bovenliggende placeholder voor die shape bestaat, dan gebruikt die shape standaardwaarden bij het berekenen van het effectieve frame op basis van zijn IShape.RawFrame. Standaardwaarden zijn 0 en NullableBool.False voor x, y, breedte, hoogte, flipH, flipV en rotatiehoek. Bijvoorbeeld:
>  IShape shape = ...; // shape is gekoppeld aan placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // nu erft de shape x, y, hoogte, flipH, flipV waarden van de placeholder en overschrijft breedte=100 en rotatiehoek=0.{code}
```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Retourneert of stelt de vormframe-eigenschappen in. Lezen/schrijven [IShapeFrame](../../com.aspose.slides/ishapeframe).

---

Waarde van elke eigenschap van de geretourneerde IShapeFrame-instantie is gedefinieerd (is niet NaN of NotDefined). Waarde van elke eigenschap van de toegewezen IShapeFrame-instantie moet gedefinieerd zijn (mag niet NaN of NotDefined zijn). U kunt ongedefinieerde waarden instellen voor RawFrame-instantie-eigenschappen.

**Retourneert:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Retourneert of stelt de vormframe-eigenschappen in. Lezen/schrijven [IShapeFrame](../../com.aspose.slides/ishapeframe).

---

Waarde van elke eigenschap van de geretourneerde IShapeFrame-instantie is gedefinieerd (is niet NaN of NotDefined). Waarde van elke eigenschap van de toegewezen IShapeFrame-instantie moet gedefinieerd zijn (mag niet NaN of NotDefined zijn). U kunt ongedefinieerde waarden instellen voor RawFrame-instantie-eigenschappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

Retourneert het LineFormat-object dat lijnopmaak-eigenschappen voor een vorm bevat. Opmerking: kan null retourneren voor bepaalde vormtypen die geen lijn-eigenschappen hebben. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

**Retourneert:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

Retourneert het ThreeDFormat-object dat 3D-effecteigenschappen voor een vorm bevat. Opmerking: kan null retourneren voor bepaalde vormtypen die geen 3D-eigenschappen hebben. Alleen-lezen [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Retourneert:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

Retourneert het EffectFormat-object dat pixel-effecten op een vorm bevat. Opmerking: kan null retourneren voor bepaalde vormtypen die geen effect-eigenschappen hebben. Alleen-lezen [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Retourneert:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Retourneert het FillFormat-object dat opvulopmaak-eigenschappen voor een vorm bevat. Opmerking: kan null retourneren voor bepaalde vormtypen die geen vul-eigenschappen hebben. Alleen-lezen [IFillFormat](../../com.aspose.slides/ifillformat).

---

> ```markdown
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
>      // Accent 4, lichter 80%
>      IShape shape2 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 70, 50, 50);
>      shape2.getFillFormat().setFillType(FillType.Solid);
>      shape2.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.2f);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.8f);
>      // Accent 4, lichter 60%
>      IShape shape3 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 130, 50, 50);
>      shape3.getFillFormat().setFillType(FillType.Solid);
>      shape3.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.4f);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.6f);
>      // Accent 4, lichter 40%
>      IShape shape4 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 190, 50, 50);
>      shape4.getFillFormat().setFillType(FillType.Solid);
>      shape4.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.6f);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.4f);
>      // Accent 4, donkerder 25%
>      IShape shape5 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 250, 50, 50);
>      shape5.getFillFormat().setFillType(FillType.Solid);
>      shape5.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape5.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.75f);
>      // Accent 4, donkerder 50%
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

Retourneert vormminiatuur. ShapeThumbnailBounds.Shape vormminiatuur-grenzen-type wordt standaard gebruikt.

**Retourneert:**
[IImage](../../com.aspose.slides/iimage) - Vormminiatuur.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IImage getImage(int bounds, float scaleX, float scaleY)
```

Retourneert vormminiatuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bounds | int | Vormminiatuur-grenzen-type. |
| scaleX | float | X-schaal |
| scaleY | float | Y-schaal |

**Retourneert:**
[IImage](../../com.aspose.slides/iimage) - Vormminiatuur of null in het geval dat ShapeThumbnailBounds.Appearance wordt gebruikt en een vorm geen zichtbare elementen heeft.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

Slaat de inhoud van Vorm op als SVG-bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Doel-stream |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Slaat de inhoud van Vorm op als SVG-bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Doel-stream |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG-generatie-opties |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

Retourneert of stelt de hyperlink in die is gedefinieerd voor muisklik. Lezen/schrijven [IHyperlink](../../com.aspose.slides/ihyperlink).

**Retourneert:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

Retourneert of stelt de hyperlink in die is gedefinieerd voor muisklik. Lezen/schrijven [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

Retourneert of stelt de hyperlink in die is gedefinieerd voor muis-over. Lezen/schrijven [IHyperlink](../../com.aspose.slides/ihyperlink).

**Retourneert:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

Retourneert of stelt de hyperlink in die is gedefinieerd voor muis-over. Lezen/schrijven [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

Retourneert de hyperlink-beheerder. Alleen-lezen [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Retourneert:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Bepaalt of de vorm verborgen is. Lezen/schrijven boolean.

**Retourneert:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Bepaalt of de vorm verborgen is. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

Retourneert de positie van een vorm in de z-volgorde. Shapes[0] retourneert de vorm achterin de z-volgorde, en Shapes[Shapes.Count - 1] retourneert de vorm vooraan. Alleen-lezen int.

**Retourneert:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```

Retourneert het aantal verbindingspunten op de vorm. Alleen-lezen int.

**Retourneert:**
int

### getRotation() {#getRotation--}
```
public final float getRotation()
```

Retourneert of stelt het aantal graden in waarmee de opgegeven vorm rond de z-as is geroteerd. Een positieve waarde duidt op rotatie met de klok mee; een negatieve waarde duidt op rotatie tegen de klok in. Lezen/schrijven float.

---

Geretourneerde waarde is altijd gedefinieerd (is niet Float.NaN). Toegewezen waarde moet gedefinieerd zijn (niet Float.NaN). U kunt ongedefinieerde waarden instellen voor RawFrame-instantie-eigenschappen.

**Retourneert:**
float

### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```
Geeft het aantal graden terug of stelt het in waarmee de opgegeven shape wordt gedraaid rond de z-as. Een positieve waarde geeft een klokwijzerrotatie aan; een negatieve waarde geeft een tegen-de-klokrotatie aan. Lezen/schrijven float.

--------------------

De geretourneerde waarde is altijd gedefinieerd (is niet Float.NaN). De toegewezen waarde moet gedefinieerd zijn (niet Float.NaN). U kunt ongedefinieerde waarden instellen voor RawFrame-instance-eigenschappen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public final float getX()
```

Haal of stel de x-coördinaat van de linkerbovenhoek van de shape op, gemeten in points. Lezen/schrijven float.

--------------------

De geretourneerde waarde is altijd gedefinieerd en nooit Float.NaN. De toegewezen waarde moet ook gedefinieerd zijn; wijs Float.NaN alleen toe aan eigenschappen van een RawFrame-instance.

**Returns:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Haal of stel de x-coördinaat van de linkerbovenhoek van de shape op, gemeten in points. Lezen/schrijven float.

--------------------

De geretourneerde waarde is altijd gedefinieerd en nooit Float.NaN. De toegewezen waarde moet ook gedefinieerd zijn; wijs Float.NaN alleen toe aan eigenschappen van een RawFrame-instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

Haal of stel de y-coördinaat van de linkerbovenhoek van de shape op, gemeten in points. Lezen/schrijven float.

--------------------

De geretourneerde waarde is altijd gedefinieerd en nooit Float.NaN. De toegewezen waarde moet ook gedefinieerd zijn; wijs Float.NaN alleen toe aan eigenschappen van een RawFrame-instance.

**Returns:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Haal of stel de y-coördinaat van de linkerbovenhoek van de shape op, gemeten in points. Lezen/schrijven float.

--------------------

De geretourneerde waarde is altijd gedefinieerd en nooit Float.NaN. De toegewezen waarde moet ook gedefinieerd zijn; wijs Float.NaN alleen toe aan eigenschappen van een RawFrame-instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Haal of stel de breedte van de shape op, gemeten in points. Lezen/schrijven float.

--------------------

De geretourneerde waarde is altijd gedefinieerd en nooit Float.NaN. De toegewezen waarde moet ook gedefinieerd zijn; wijs Float.NaN alleen toe aan eigenschappen van een RawFrame-instance.

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Haal of stel de breedte van de shape op, gemeten in points. Lezen/schrijven float.

--------------------

De geretourneerde waarde is altijd gedefinieerd en nooit Float.NaN. De toegewezen waarde moet ook gedefinieerd zijn; wijs Float.NaN alleen toe aan eigenschappen van een RawFrame-instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Haal of stel de hoogte van de shape op, gemeten in points. Lezen/schrijven float.

--------------------

De geretourneerde waarde is altijd gedefinieerd en nooit Float.NaN. De toegewezen waarde moet ook gedefinieerd zijn; wijs Float.NaN alleen toe aan eigenschappen van een RawFrame-instance.

**Returns:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Haal of stel de hoogte van de shape op, gemeten in points. Lezen/schrijven float.

--------------------

De geretourneerde waarde is altijd gedefinieerd en nooit Float.NaN. De toegewezen waarde moet ook gedefinieerd zijn; wijs Float.NaN alleen toe aan eigenschappen van een RawFrame-instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```

Eigenschap specificeert hoe een shape wordt weergegeven in zwart-wit weergavemodus. Lezen/schrijven [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Returns:**
byte
### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```

Eigenschap specificeert hoe een shape wordt weergegeven in zwart-wit weergavemodus. Lezen/schrijven [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```

Geeft een interne, presentatie-gescopeerde identifier terug die bedoeld is voor gebruik door add-ins of andere code. Omdat deze waarde door de gebruiker of programmatisch kan worden hergebruikt, mag deze niet worden behandeld als een permanente unieke sleutel. Alleen-lezen long. Zie ook \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Returns:**
long
### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```

Geeft een slide-gescopeerde unieke identifier terug die constant blijft gedurende de levensduur van de shape en PowerPoint of interop-code in staat stelt de shape betrouwbaar te refereren vanuit elk deel van het document. Alleen-lezen long. Zie ook \#getUniqueId.getUniqueId.

**Returns:**
long
### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```

Geeft de alternatieve tekst van een shape terug of stelt deze in. Lezen/schrijven String.

**Returns:**
java.lang.String
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```

Geeft de alternatieve tekst van een shape terug of stelt deze in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```

Geeft de titel van de alternatieve tekst van een shape terug of stelt deze in. Lezen/schrijven String.

**Returns:**
java.lang.String
### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```

Geeft de titel van de alternatieve tekst van een shape terug of stelt deze in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```

Geeft de naam van een shape terug of stelt deze in. Mag niet null zijn. Gebruik een lege tekenreeks indien nodig. Lezen/schrijven String.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Geeft de naam van een shape terug of stelt deze in. Mag niet null zijn. Gebruik een lege tekenreeks indien nodig. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```

Haalt of stelt de optie ‘Mark as decorative’ in. Lezen/schrijven boolean.

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

Haalt of stelt de optie ‘Mark as decorative’ in. Lezen/schrijven boolean.

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

Geeft de locks van de shape terug. Alleen-lezen [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Returns:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```

Bepaalt of de shape gegroepeerd is. Alleen-lezen boolean.

--------------------

Eigenschap \#getParentGroup.getParentGroup geeft het bovenliggende GroupShape-object terug als de shape gegroepeerd is.

**Returns:**
boolean
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Geeft het bovenliggende GroupShape-object terug als de shape gegroepeerd is. Anders wordt null geretourneerd. Alleen-lezen [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

Eigenschap \#isGrouped.isGrouped bepaalt of de shape gegroepeerd is.

**Returns:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Geeft het Parent_Immediate-object terug. Alleen-lezen IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getVisualBounds() {#getVisualBounds--}
```
public final Rectangle2D.Float getVisualBounds()
```

Haalt de visuele grenzen van de shape op, berekend uit de gerenderde inhoud.

**Returns:**
java.awt.geom.Rectangle2D.Float - Een java.awt.geom.Rectangle2D.Float die de visuele grenzen van de shape in slide-coördinaten weergeeft.

--------------------

De geretourneerde rechthoek vertegenwoordigt de as-gealigneerde grenzen van alle inhoud die door de shape wordt geproduceerd tijdens het renderen in slide-coördinatenruimte. Deze grenzen kunnen afwijken van de model-grenzen van de shape \#getX.getX/\#setX(float).setX(float), \#getY.getY/\#setY(float).setY(float), \#getWidth.getWidth/\#setWidth(float).setWidth(float), \#getHeight.getHeight/\#setHeight(float).setHeight(float) en kunnen negatieve coördinaten bevatten als de gerenderde inhoud buiten de slide-oorsprong uitsteekt. De visuele grenzen houden rekening met render-gerelateerde aspecten zoals transformaties (bijvoorbeeld rotatie), lijnbreedte en verbindingen, tekstlayout en overloop, SmartArt-geometrie, en andere layouteffecten die de uiteindelijke weergave van de shape beïnvloeden. De geretourneerde grenzen worden niet bijgesneden tot de slide-rechthoek.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Geeft de bovenliggende slide van een shape terug. Alleen-lezen [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Geeft de bovenliggende presentatie van een slide terug. Alleen-lezen [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)