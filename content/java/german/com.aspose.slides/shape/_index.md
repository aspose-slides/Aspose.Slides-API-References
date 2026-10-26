---
title: Shape
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Form auf einer Folie dar.
type: docs
url: /de/com.aspose.slides/shape/
---
**Vererbung:**  
java.lang.Object

**Alle implementierten Schnittstellen:**  
[com.aspose.slides.IShape](../../com.aspose.slides/ishape), com.aspose.slides.IDOMObject  
```
public class Shape implements IShape, IDOMObject
```

Stellt eine Form auf einer Folie dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Bestimmt, ob die Form TextHolder_PPT ist. |
| [getPlaceholder()](#getPlaceholder--) | Gibt den Platzhalter für eine Form zurück. |
| [removePlaceholder()](#removePlaceholder--) | Definiert, dass diese Form kein Platzhalter ist. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und setzt die Platzhaltereigenschaften auf einen angegebenen. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Gibt eine einfache Platzhalterform zurück (Form aus dem Layout und/oder der Masterfolie, von der die aktuelle Form erbt). |
| [getCustomData()](#getCustomData--) | Gibt die benutzerdefinierten Daten der Form zurück. |
| [getRawFrame()](#getRawFrame--) | Gibt die Eigenschaften des Rohrahmens der Form zurück oder setzt sie. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Gibt die Eigenschaften des Rohrahmens der Form zurück oder setzt sie. |
| [getFrame()](#getFrame--) | Gibt die Eigenschaften des Rohrahmens der Form zurück oder setzt sie. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Gibt die Eigenschaften des Rohrahmens der Form zurück oder setzt sie. |
| [getLineFormat()](#getLineFormat--) | Gibt das LineFormat-Objekt zurück, das Linienformatierungseigenschaften für eine Form enthält. |
| [getThreeDFormat()](#getThreeDFormat--) | Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekteigenschaften für eine Form enthält. |
| [getEffectFormat()](#getEffectFormat--) | Gibt das EffectFormat-Objekt zurück, das Pixeleffekte auf eine Form anwendet. |
| [getFillFormat()](#getFillFormat--) | Gibt das FillFormat-Objekt zurück, das Füllformatierungseigenschaften für eine Form enthält. |
| [getImage()](#getImage--) | Gibt die Miniaturansicht der Form zurück. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Gibt die Miniaturansicht der Form zurück. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Speichert den Inhalt der Form als SVG-Datei. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Speichert den Inhalt der Form als SVG-Datei. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Gibt den für Mausklick definierten Hyperlink zurück oder setzt ihn. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Gibt den für Mausklick definierten Hyperlink zurück oder setzt ihn. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Gibt den für Mauszeiger-Überfahren definierten Hyperlink zurück oder setzt ihn. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Gibt den für Mauszeiger-Überfahren definierten Hyperlink zurück oder setzt ihn. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Gibt den Hyperlink-Manager zurück. |
| [getHidden()](#getHidden--) | Bestimmt, ob die Form ausgeblendet ist. |
| [setHidden(boolean value)](#setHidden-boolean-) | Bestimmt, ob die Form ausgeblendet ist. |
| [getZOrderPosition()](#getZOrderPosition--) | Gibt die Position einer Form in der Z-Ordnung zurück. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Gibt die Anzahl der Verbindungsstellen an der Form zurück. |
| [getRotation()](#getRotation--) | Gibt die Anzahl der Grad zurück, um die die angegebene Form um die Z-Achse gedreht ist, oder setzt sie. |
| [setRotation(float value)](#setRotation-float-) | Gibt die Anzahl der Grad zurück, um die die angegebene Form um die Z-Achse gedreht ist, oder setzt sie. |
| [getX()](#getX--) | Liest oder setzt die X-Koordinate der oberen linken Ecke der Form, gemessen in Punkten. |
| [setX(float value)](#setX-float-) | Liest oder setzt die X-Koordinate der oberen linken Ecke der Form, gemessen in Punkten. |
| [getY()](#getY--) | Liest oder setzt die Y-Koordinate der oberen linken Ecke der Form, gemessen in Punkten. |
| [setY(float value)](#setY-float-) | Liest oder setzt die Y-Koordinate der oberen linken Ecke der Form, gemessen in Punkten. |
| [getWidth()](#getWidth--) | Liest oder setzt die Breite der Form, gemessen in Punkten. |
| [setWidth(float value)](#setWidth-float-) | Liest oder setzt die Breite der Form, gemessen in Punkten. |
| [getHeight()](#getHeight--) | Liest oder setzt die Höhe der Form, gemessen in Punkten. |
| [setHeight(float value)](#setHeight-float-) | Liest oder setzt die Höhe der Form, gemessen in Punkten. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Eigenschaft gibt an, wie eine Form im Schwarz-Weiß-Anzeigemodus gerendert wird. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Eigenschaft gibt an, wie eine Form im Schwarz-Weiß-Anzeigemodus gerendert wird. |
| [getUniqueId()](#getUniqueId--) | Gibt einen internen, präsentationsbezogenen Bezeichner zurück, der für Add-Ins oder anderen Code gedacht ist. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Gibt einen eindeutigen Bezeichner zurück, der auf die Folie beschränkt ist, über die Lebensdauer der Form konstant bleibt und PowerPoint oder Interop-Code ermöglicht, zuverlässig von überall im Dokument auf die Form zu verweisen. |
| [getAlternativeText()](#getAlternativeText--) | Gibt den alternativen Text zurück, der mit einer Form verknüpft ist, oder setzt ihn. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Gibt den alternativen Text zurück, der mit einer Form verknüpft ist, oder setzt ihn. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Gibt den Titel des alternativen Textes zurück, der mit einer Form verknüpft ist, oder setzt ihn. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Gibt den Titel des alternativen Textes zurück, der mit einer Form verknüpft ist, oder setzt ihn. |
| [getName()](#getName--) | Gibt den Namen einer Form zurück oder setzt ihn. |
| [setName(String value)](#setName-java.lang.String-) | Gibt den Namen einer Form zurück oder setzt ihn. |
| [isDecorative()](#isDecorative--) | Liest oder setzt die Option 'Als dekorativ markieren' (Lese/Schreib bool). |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Liest oder setzt die Option 'Als dekorativ markieren' (Lese/Schreib bool). |
| [getShapeLock()](#getShapeLock--) | Gibt die Sperren der Form zurück. |
| [isGrouped()](#isGrouped--) | Bestimmt, ob die Form gruppiert ist. |
| [getParentGroup()](#getParentGroup--) | Gibt das übergeordnete GroupShape-Objekt zurück, falls die Form gruppiert ist. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVisualBounds()](#getVisualBounds--) | Liest die visuellen Grenzen der Form, berechnet aus ihrem gerenderten Inhalt. |
| [getSlide()](#getSlide--) | Gibt die übergeordnete Folie einer Form zurück. |
| [getPresentation()](#getPresentation--) | Gibt die übergeordnete Präsentation einer Folie zurück. |

### isTextHolder() {#isTextHolder--}
```
public final boolean isTextHolder()
```

Bestimmt, ob die Form TextHolder_PPT ist. Nur lesbar boolean .

**Rückgabe:**  
boolean

### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```

Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur lesbar [IPlaceholder](../../com.aspose.slides/iplaceholder).

**Rückgabe:**  
[IPlaceholder](../../com.aspose.slides/iplaceholder)

> ```
> The following example shows how to change Text in Placeholder.
>  
>  // Instanziiert eine Presentation-Klasse
>  Presentation pres = new Presentation("ReplacingText.pptx");
>  try {
>      // Greift auf die erste Folie zu
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Durchläuft die Shapes, um den Platzhalter zu finden
>      for (IShape shp : sld.getShapes())
>          if (shp.getPlaceholder() != null)
>          {
>              // Ändert den Text in jedem Platzhalter
>              ((IAutoShape)shp).getTextFrame().setText("This is a Placeholder");
>          }
>      // Speichert die Präsentation auf die Festplatte
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
>      for (IShape shape : slide.getSlide().getShapes()) // Durchläuft die Folie
>      {
>          if (shape.getPlaceholder() != null && shape instanceof AutoShape)
>          {
>              String text = "";
>              if (shape.getPlaceholder().getType() == PlaceholderType.CenteredTitle) // PowerPoint zeigt "Klicken Sie, um einen Titel hinzuzufügen"
>              {
>                  text = "Add Title";
>              }
>              else if (shape.getPlaceholder().getType() == PlaceholderType.Subtitle) // Fügt Untertitel hinzu
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


### removePlaceholder() {#removePlaceholder--}
```
public final void removePlaceholder()
```

Definiert, dass diese Form kein Platzhalter ist.

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public final IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und setzt die Platzhaltereigenschaften auf einen angegebenen.

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Platzhalter, von dem der Inhalt kopiert werden soll. |

**Rückgabe:**  
[IPlaceholder](../../com.aspose.slides/iplaceholder) - Neues #getPlaceholder.getPlaceholder.

### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

Gibt eine einfache Platzhalterform zurück (Form aus dem Layout und/oder der Masterfolie, von der die aktuelle Form erbt).

> ```
> // Alle (Master/Layout/Slide) animierten Effekte der Platzhalterform abrufen
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


Ein null wird zurückgegeben, wenn die aktuelle Form nicht geerbt wird.

**Rückgabe:**  
[IShape](../../com.aspose.slides/ishape)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Gibt die benutzerdefinierten Daten der Form zurück. Nur lesbar [ICustomData](../../com.aspose.slides/icustomdata).

**Rückgabe:**  
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public final IShapeFrame getRawFrame()
```

Gibt die Eigenschaften des Rohrahmens der Form zurück oder setzt sie. Lese/Schreib [IShapeFrame](../../com.aspose.slides/ishapeframe).

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

**Rückgabe:**  
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
```

Gibt die Eigenschaften des Rohrahmens der Form zurück oder setzt sie. Lese/Schreib [IShapeFrame](../../com.aspose.slides/ishapeframe).

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //oder
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Solcher Code kann zu unklaren Situationen führen. Daher wurden Beschränkungen für die Verwendung undefinierter Werte bei IShape.getFrame() hinzugefügt. Werte für x, y, width, height, flipH, flipV und rotationAngle müssen definiert sein (nicht Float.NaN oder NullableBool.NotDefined). Der obige Beispielcode wirft jetzt eine ArgumentException.
>  //Dies gilt für folgende Anwendungsfälle:
>  IShape shape = ...;
>  shape.setFrame(...); // darf nicht undefiniert sein
>  IShapeCollection shapes = ...;
>  // x, y, width, height Parameter dürfen nicht Float.NaN sein:
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
>  //Aber IShape.RawFrame Frame-Eigenschaften können undefiniert sein. Das macht Sinn, wenn die Form mit einem Platzhalter verknüpft ist. Dann werden undefinierte Frame-Werte vom übergeordneten Platzhalter überschrieben. Gibt es keinen übergeordneten Platzhalter, verwendet die Form Standardwerte, wenn sie den effektiven Frame basierend auf IShape.RawFrame berechnet. Standardwerte sind 0 und NullableBool.False für x, y, width, height, flipH, flipV und rotationAngle. Zum Beispiel:
>  IShape shape = ...; // Form ist mit einem Platzhalter verknüpft
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // jetzt erbt die Form x, y, height, flipH, flipV Werte vom Platzhalter und überschreibt width=100 und rotationAngle=0.{code}
> ```


**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Gibt die Eigenschaften des Formrahmens zurück oder setzt sie. Lese/Schreib [IShapeFrame](../../com.aspose.slides/ishapeframe).

> Der Wert jeder Eigenschaft der zurückgegebenen IShapeFrame-Instanz ist definiert (ist nicht NaN oder NotDefined). Der Wert jeder Eigenschaft der zugewiesenen IShapeFrame-Instanz muss definiert sein (darf nicht NaN oder NotDefined sein). Sie können undefinierte Werte für RawFrame-Instanz-Eigenschaften setzen.

**Rückgabe:**  
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Gibt die Eigenschaften des Formrahmens zurück oder setzt sie. Lese/Schreib [IShapeFrame](../../com.aspose.slides/ishapeframe).

> Der Wert jeder Eigenschaft der zurückgegebenen IShapeFrame-Instanz ist definiert (ist nicht NaN oder NotDefined). Der Wert jeder Eigenschaft der zugewiesenen IShapeFrame-Instanz muss definiert sein (darf nicht NaN oder NotDefined sein). Sie können undefinierte Werte für RawFrame-Instanz-Eigenschaften setzen.

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

Gibt das LineFormat-Objekt zurück, das Linienformatierungseigenschaften für eine Form enthält. Hinweis: kann null zurückgeben für bestimmte Formtypen, die keine Linieneigenschaften besitzen. Nur lesbar [ILineFormat](../../com.aspose.slides/ilineformat).

**Rückgabe:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

Gibt das ThreeDFormat-Objekt zurück, das 3D-Effekteigenschaften für eine Form enthält. Hinweis: kann null zurückgeben für bestimmte Formtypen, die keine 3D-Eigenschaften besitzen. Nur lesbar [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Rückgabe:**  
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

Gibt das EffectFormat-Objekt zurück, das Pixeleffekte auf eine Form anwendet. Hinweis: kann null zurückgeben für bestimmte Formtypen, die keine Effekteigenschaften besitzen. Nur lesbar [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Rückgabe:**  
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Gibt das FillFormat-Objekt zurück, das Füllformatierungseigenschaften für eine Form enthält. Hinweis: kann null zurückgeben für bestimmte Formtypen, die keine Fülleigenschaften besitzen. Nur lesbar [IFillFormat](../../com.aspose.slides/ifillformat).

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
>      // Akzent 4
>      IShape shape1 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 50, 50);
>      shape1.getFillFormat().setFillType(FillType.Solid);
>      shape1.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      // Akzent 4, 80% heller
>      IShape shape2 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 70, 50, 50);
>      shape2.getFillFormat().setFillType(FillType.Solid);
>      shape2.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.2f);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.8f);
>      // Akzent 4, 60% heller
>      IShape shape3 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 130, 50, 50);
>      shape3.getFillFormat().setFillType(FillType.Solid);
>      shape3.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.4f);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.6f);
>      // Akzent 4, 40% heller
>      IShape shape4 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 190, 50, 50);
>      shape4.getFillFormat().setFillType(FillType.Solid);
>      shape4.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.6f);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.4f);
>      // Akzent 4, 25% dunkler
>      IShape shape5 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 250, 50, 50);
>      shape5.getFillFormat().setFillType(FillType.Solid);
>      shape5.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape5.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.75f);
>      // Akzent 4, 50% dunkler
>      IShape shape6 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 310, 50, 50);
>      shape6.getFillFormat().setFillType(FillType.Solid);
>      shape6.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape6.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.5f);
>      pres.save("example_accent4.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public final IImage getImage()
```

Gibt die Miniaturansicht der Form zurück. ShapeThumbnailBounds.Shape-Miniaturansichts-Typ wird standardmäßig verwendet.

**Rückgabe:**  
[IImage](../../com.aspose.slides/iimage) - Miniaturansicht der Form.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IImage getImage(int bounds, float scaleX, float scaleY)
```

Gibt die Miniaturansicht der Form zurück.

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bounds | int | Typ der Miniaturansichts-Grenzen. |
| scaleX | float | X-Skalierung |
| scaleY | float | Y-Skalierung |

**Rückgabe:**  
[IImage](../../com.aspose.slides/iimage) - Miniaturansicht der Form oder null, wenn ShapeThumbnailBounds.Appearance verwendet wird und die Form keine sichtbaren Elemente besitzt.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

Speichert den Inhalt der Form als SVG-Datei.

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Ziel-Stream |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Speichert den Inhalt der Form als SVG-Datei.

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Ziel-Stream |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Optionen für die SVG-Erzeugung |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

Gibt den für Mausklick definierten Hyperlink zurück oder setzt ihn. Lese/Schreib [IHyperlink](../../com.aspose.slides/ihyperlink).

**Rückgabe:**  
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

Gibt den für Mausklick definierten Hyperlink zurück oder setzt ihn. Lese/Schreib [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

Gibt den für Mauszeiger-Überfahren definierten Hyperlink zurück oder setzt ihn. Lese/Schreib [IHyperlink](../../com.aspose.slides/ihyperlink).

**Rückgabe:**  
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

Gibt den für Mauszeiger-Überfahren definierten Hyperlink zurück oder setzt ihn. Lese/Schreib [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

Gibt den Hyperlink-Manager zurück. Nur lesbar [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Rückgabe:**  
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Bestimmt, ob die Form ausgeblendet ist. Lese/Schreib boolean .

**Rückgabe:**  
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Bestimmt, ob die Form ausgeblendet ist. Lese/Schreib boolean .

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

Gibt die Position einer Form in der Z-Ordnung zurück. Shapes[0] gibt die Form zurück, die sich ganz hinten in der Z-Ordnung befindet, und Shapes[Shapes.Count - 1] gibt die Form zurück, die ganz vorne steht. Nur lesbar int .

**Rückgabe:**  
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```

Gibt die Anzahl der Verbindungsstellen an der Form zurück. Nur lesbar int .

**Rückgabe:**  
int

### getRotation() {#getRotation--}
```
public final float getRotation()
```

Gibt die Anzahl der Grad zurück, um die die angegebene Form um die Z-Achse gedreht ist, oder setzt sie. Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Drehung gegen den Uhrzeigersinn. Lese/Schreib float.

> Der zurückgegebene Wert ist immer definiert (ist nicht Float.NaN). Zugewiesene Werte müssen definiert sein (nicht Float.NaN). Sie können undefinierte Werte für RawFrame-Instanz-Eigenschaften setzen.

**Rückgabe:**  
float

### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```
Returns or sets die Anzahl der Grad, um die das angegebene Shape um die z-Achse gedreht wird. Ein positiver Wert bedeutet eine Drehung im Uhrzeigersinn; ein negativer Wert bedeutet eine Drehung gegen den Uhrzeigersinn. Lese/Schreib float.

--------------------

Der zurückgegebene Wert ist immer definiert (ist nicht Float.NaN). Der zugewiesene Wert muss definiert sein (nicht Float.NaN). Sie können undefinierte Werte für Eigenschaften einer RawFrame-Instanz festlegen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public final float getX()
```

Liest oder schreibt die x-Koordinate der oberen linken Ecke des Shapes, gemessen in Punkten. Lese/Schreib float.

--------------------

Der zurückgegebene Wert ist immer definiert und niemals Float.NaN. Der zugewiesene Wert muss ebenfalls definiert sein; weisen Sie Float.NaN nur Eigenschaften einer RawFrame-Instanz zu.

**Rückgabe:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Liest oder schreibt die x-Koordinate der oberen linken Ecke des Shapes, gemessen in Punkten. Lese/Schreib float.

--------------------

Der zurückgegebene Wert ist immer definiert und niemals Float.NaN. Der zugewiesene Wert muss ebenfalls definiert sein; weisen Sie Float.NaN nur Eigenschaften einer RawFrame-Instanz zu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

Liest oder schreibt die y-Koordinate der oberen linken Ecke des Shapes, gemessen in Punkten. Lese/Schreib float.

--------------------

Der zurückgegebene Wert ist immer definiert und niemals Float.NaN. Der zugewiesene Wert muss ebenfalls definiert sein; weisen Sie Float.NaN nur Eigenschaften einer RawFrame-Instanz zu.

**Rückgabe:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Liest oder schreibt die y-Koordinate der oberen linken Ecke des Shapes, gemessen in Punkten. Lese/Schreib float.

--------------------

Der zurückgegebene Wert ist immer definiert und niemals Float.NaN. Der zugewiesene Wert muss ebenfalls definiert sein; weisen Sie Float.NaN nur Eigenschaften einer RawFrame-Instanz zu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Liest oder schreibt die Breite des Shapes, gemessen in Punkten. Lese/Schreib float.

--------------------

Der zurückgegebene Wert ist immer definiert und niemals Float.NaN. Der zugewiesene Wert muss ebenfalls definiert sein; weisen Sie Float.NaN nur Eigenschaften einer RawFrame-Instanz zu.

**Rückgabe:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Liest oder schreibt die Breite des Shapes, gemessen in Punkten. Lese/Schreib float.

--------------------

Der zurückgegebene Wert ist immer definiert und niemals Float.NaN. Der zugewiesene Wert muss ebenfalls definiert sein; weisen Sie Float.NaN nur Eigenschaften einer RawFrame-Instanz zu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Liest oder schreibt die Höhe des Shapes, gemessen in Punkten. Lese/Schreib float.

--------------------

Der zurückgegebene Wert ist immer definiert und niemals Float.NaN. Der zugewiesene Wert muss ebenfalls definiert sein; weisen Sie Float.NaN nur Eigenschaften einer RawFrame-Instanz zu.

**Rückgabe:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Liest oder schreibt die Höhe des Shapes, gemessen in Punkten. Lese/Schreib float.

--------------------

Der zurückgegebene Wert ist immer definiert und niemals Float.NaN. Der zugewiesene Wert muss ebenfalls definiert sein; weisen Sie Float.NaN nur Eigenschaften einer RawFrame-Instanz zu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```

Property specifies how a shape will render in black-and-white display mode.. Lese/Schreib [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Rückgabe:**
byte
### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```

Property specifies how a shape will render in black-and-white display mode.. Lese/Schreib [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```

Returns an internal, presentation-scoped identifier intended for use by add-ins or other code. Because this value can be reassigned by the user or programmatically, it must not be treated as a persistent unique key. Nur-lesen long. See also \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Rückgabe:**
long
### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```

Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and lets PowerPoint or interop code reliably reference the shape from anywhere in the document. Nur-lesen long. See also \#getUniqueId.getUniqueId.

**Rückgabe:**
long
### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```

Liest oder schreibt den alternativen Text, der einem Shape zugeordnet ist. Lese/Schreib String.

**Rückgabe:**
java.lang.String
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```

Liest oder schreibt den alternativen Text, der einem Shape zugeordnet ist. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```

Liest oder schreibt den Titel des alternativen Textes, der einem Shape zugeordnet ist. Lese/Schreib String.

**Rückgabe:**
java.lang.String
### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```

Liest oder schreibt den Titel des alternativen Textes, der einem Shape zugeordnet ist. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```

Liest oder schreibt den Namen eines Shapes. Darf nicht null sein. Verwenden Sie bei Bedarf einen leeren String. Lese/Schreib String.

**Rückgabe:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Liest oder schreibt den Namen eines Shapes. Darf nicht null sein. Verwenden Sie bei Bedarf einen leeren String. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```

Liest oder schreibt die Option „Mark as decorative“. Lese/Schreib boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
boolean
### setDecorative(boolean value) {#setDecorative-boolean-}
```
public final void setDecorative(boolean value)
```

Liest oder schreibt die Option „Mark as decorative“. Lese/Schreib boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public IBaseShapeLock getShapeLock()
```

Returns shape's locks. Nur-lesen [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Rückgabe:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```

Determines whether the shape is grouped. Nur-lesen boolean.

--------------------

Property \#getParentGroup.getParentGroup returns parent GroupShape object if shape is grouped.

**Rückgabe:**
boolean
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Returns parent GroupShape object if shape is grouped. Otherwise returns null. Nur-lesen [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

Property \#isGrouped.isGrouped determines whether the shape is grouped.

**Rückgabe:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returns Parent\_Immediate object. Nur-lesen IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject
### getVisualBounds() {#getVisualBounds--}
```
public final Rectangle2D.Float getVisualBounds()
```

Gets the visual bounds of the shape calculated from its rendered content.

**Rückgabe:**
java.awt.geom.Rectangle2D.Float - A java.awt.geom.Rectangle2D.Float that represents the visual bounds of the shape in slide coordinates.

--------------------

The returned rectangle represents the axis-aligned bounds of all content produced by the shape during rendering in slide coordinate space. These bounds may differ from the shape's model bounds \#getX.getX/\#setX(float).setX(float), \#getY.getY/\#setY(float).setY(float), \#getWidth.getWidth/\#setWidth(float).setWidth(float), \#getHeight.getHeight/\#setHeight(float).setHeight(float) and may contain negative coordinates if the rendered content extends beyond the slide origin. The visual bounds take into account rendering-related aspects such as transformations (for example, rotation), stroke width and joins, text layout and overflow, SmartArt geometry, and other layout effects that influence the final rendered appearance of the shape. The returned bounds are not clipped to the slide rectangle.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returns the parent slide of a shape. Nur-lesen [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Rückgabe:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Returns the parent presentation of a slide. Nur-lesen [IPresentation](../../com.aspose.slides/ipresentation).

**Rückgabe:**
[IPresentation](../../com.aspose.slides/ipresentation)