---
title: Shape
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt eine Form auf einer Folie dar.
type: docs
url: /de/com.aspose.slides/shape/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape), com.aspose.slides.IDOMObject
```
public class Shape implements IShape, IDOMObject
```

Stellt eine Form auf einer Folie dar.
## Methoden

| Method | Description |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Bestimmt, ob die Form TextHolder_PPT ist. |
| [getPlaceholder()](#getPlaceholder--) | Gibt den Platzhalter für eine Form zurück. |
| [removePlaceholder()](#removePlaceholder--) | Definiert, dass diese Form kein Platzhalter ist. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf den angegebenen. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Gibt eine Basis-Platzhalter-Form zurück (Form aus dem Layout- und/oder Master-Slide, von dem die aktuelle Form ererbt wird). |
| [getCustomData()](#getCustomData--) | Gibt die benutzerdefinierten Daten der Form zurück. |
| [getRawFrame()](#getRawFrame--) | Gibt die rohen Frame-Eigenschaften der Form zurück oder setzt sie. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Gibt die rohen Frame-Eigenschaften der Form zurück oder setzt sie. |
| [getFrame()](#getFrame--) | Gibt die Frame-Eigenschaften der Form zurück oder setzt sie. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Gibt die Frame-Eigenschaften der Form zurück oder setzt sie. |
| [getLineFormat()](#getLineFormat--) | Gibt das LineFormat-Objekt zurück, das die Linienformat-Eigenschaften einer Form enthält. |
| [getThreeDFormat()](#getThreeDFormat--) | Gibt das ThreeDFormat-Objekt zurück, das die 3-D-Effekt-Eigenschaften einer Form enthält. |
| [getEffectFormat()](#getEffectFormat--) | Gibt das EffectFormat-Objekt zurück, das die Pixel-Effekte einer Form enthält. |
| [getFillFormat()](#getFillFormat--) | Gibt das FillFormat-Objekt zurück, das die Füll-Formatierung einer Form enthält. |
| [getImage()](#getImage--) | Gibt die Miniaturansicht der Form zurück. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Gibt die Miniaturansicht der Form zurück. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Speichert den Inhalt der Form als SVG-Datei. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Speichert den Inhalt der Form als SVG-Datei. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Gibt den für Mausklick definierten Hyperlink zurück oder setzt ihn. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Gibt den für Mausklick definierten Hyperlink zurück oder setzt ihn. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Gibt den für Maus-Over definierten Hyperlink zurück oder setzt ihn. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Gibt den für Maus-Over definierten Hyperlink zurück oder setzt ihn. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Gibt den Hyperlink-Manager zurück. |
| [getHidden()](#getHidden--) | Bestimmt, ob die Form ausgeblendet ist. |
| [setHidden(boolean value)](#setHidden-boolean-) | Bestimmt, ob die Form ausgeblendet ist. |
| [getZOrderPosition()](#getZOrderPosition--) | Gibt die Position einer Form in der Z-Reihenfolge zurück. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Gibt die Anzahl der Verbindungsstellen der Form zurück. |
| [getRotation()](#getRotation--) | Gibt die Drehung der angegebenen Form um die Z-Achse in Grad zurück oder setzt sie. |
| [setRotation(float value)](#setRotation-float-) | Gibt die Drehung der angegebenen Form um die Z-Achse in Grad zurück oder setzt sie. |
| [getX()](#getX--) | Gibt die X-Koordinate der linken oberen Ecke der Form in Punkten zurück oder setzt sie. |
| [setX(float value)](#setX-float-) | Gibt die X-Koordinate der linken oberen Ecke der Form in Punkten zurück oder setzt sie. |
| [getY()](#getY--) | Gibt die Y-Koordinate der linken oberen Ecke der Form in Punkten zurück oder setzt sie. |
| [setY(float value)](#setY-float-) | Gibt die Y-Koordinate der linken oberen Ecke der Form in Punkten zurück oder setzt sie. |
| [getWidth()](#getWidth--) | Gibt die Breite der Form in Punkten zurück oder setzt sie. |
| [setWidth(float value)](#setWidth-float-) | Gibt die Breite der Form in Punkten zurück oder setzt sie. |
| [getHeight()](#getHeight--) | Gibt die Höhe der Form in Punkten zurück oder setzt sie. |
| [setHeight(float value)](#setHeight-float-) | Gibt die Höhe der Form in Punkten zurück oder setzt sie. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Eigenschaft gibt an, wie eine Form im Schwarz-Weiß-Darstellungsmodus gerendert wird. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Eigenschaft gibt an, wie eine Form im Schwarz-Weiß-Darstellungsmodus gerendert wird. |
| [getUniqueId()](#getUniqueId--) | Gibt einen internen, präsentationsbezogenen Bezeichner zurück, der für Add-Ins oder anderen Code vorgesehen ist. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Gibt einen folienbezogenen eindeutigen Bezeichner zurück, der über die Lebensdauer der Form konstant bleibt und PowerPoint bzw. Interop-Code ein zuverlässiges Referenzieren der Form ermöglicht. |
| [getAlternativeText()](#getAlternativeText--) | Gibt den alternativen Text einer Form zurück oder setzt ihn. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Gibt den alternativen Text einer Form zurück oder setzt ihn. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Gibt den Titel des alternativen Textes einer Form zurück oder setzt ihn. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Gibt den Titel des alternativen Textes einer Form zurück oder setzt ihn. |
| [getName()](#getName--) | Gibt den Namen einer Form zurück oder setzt ihn. |
| [setName(String value)](#setName-java.lang.String-) | Gibt den Namen einer Form zurück oder setzt ihn. |
| [isDecorative()](#isDecorative--) | Gibt die Option „Als dekorativ markieren“ zurück oder setzt sie. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Gibt die Option „Als dekorativ markieren“ zurück oder setzt sie. |
| [getShapeLock()](#getShapeLock--) | Gibt die Sperren der Form zurück. |
| [isGrouped()](#isGrouped--) | Bestimmt, ob die Form gruppiert ist. |
| [getParentGroup()](#getParentGroup--) | Gibt das übergeordnete GroupShape-Objekt zurück, falls die Form gruppiert ist. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVisualBounds()](#getVisualBounds--) | Gibt die visuellen Grenzen der Form zurück, berechnet aus ihrem gerenderten Inhalt. |
| [getSlide()](#getSlide--) | Gibt die übergeordnete Folie einer Form zurück. |
| [getPresentation()](#getPresentation--) | Gibt die übergeordnete Präsentation einer Folie zurück. |

### isTextHolder() {#isTextHolder--}
```
public final boolean isTextHolder()
```

Bestimmt, ob die Form TextHolder_PPT ist. Nur lesbar  boolean .

**Rückgabe:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```

Gibt den Platzhalter für eine Form zurück. Gibt null zurück, wenn die Form keinen Platzhalter hat. Nur lesbar [IPlaceholder](../../com.aspose.slides/iplaceholder).

--------------------

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
>      // Speichert die Präsentation auf dem Datenträger
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
>              if (shape.getPlaceholder().getType() == PlaceholderType.CenteredTitle) // PowerPoint zeigt „Klicken Sie, um den Titel hinzuzufügen“ an
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


**Rückgabe:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### removePlaceholder() {#removePlaceholder--}
```
public final void removePlaceholder()
```

Definiert, dass diese Form kein Platzhalter ist.

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public final IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf den angegebenen.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Platzhalter, von dem der Inhalt kopiert werden soll. |

**Rückgabe:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - New #getPlaceholder.getPlaceholder.

### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

Gibt eine Basis-Platzhalter-Form zurück (Form aus dem Layout- und/oder Master-Slide, von dem die aktuelle Form ererbt wird).

--------------------

> ```
> // Alle (master/layout/slide) animierten Effekte der Platzhalterform abrufen
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

Ein null wird zurückgegeben, wenn die aktuelle Form nicht ererbt wird.

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

Gibt die rohen Frame-Eigenschaften der Form zurück oder setzt sie. Lesen/Schreiben [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //oder
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Ein solcher Code kann zu unklaren Situationen führen. Daher wurden Einschränkungen für die Verwendung undefinierter Werte bei IShape.getFrame() hinzugefügt. Werte für x, y, width, height, flipH, flipV und rotationAngle müssen definiert sein (nicht Float.NaN oder NullableBool.NotDefined). Der obige Beispielcode wirft jetzt eine ArgumentException.
>  //Dies gilt für die folgenden Anwendungsfälle:
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
>  //Aber IShape.RawFrame-Frame-Eigenschaften können undefiniert sein. Das ist sinnvoll, wenn die Form mit einem Platzhalter verknüpft ist. Dann werden undefinierte Frame-Werte vom übergeordneten Platzhalter-Form überschrieben. Gibt es keinen übergeordneten Platzhalter, verwendet die Form Standardwerte, wenn sie den effektiven Frame basierend auf ihrem IShape.RawFrame berechnet. Standardwerte sind 0 und NullableBool.False für x, y, width, height, flipH, flipV und rotationAngle. Zum Beispiel:
>  IShape shape = ...; // Form ist mit einem Platzhalter verknüpft
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // jetzt erbt die Form x, y, height, flipH, flipV Werte vom Platzhalter und überschreibt width=100 und rotationAngle=0.{code}
> ```


**Rückgabe:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
```

Gibt die rohen Frame-Eigenschaften der Form zurück oder setzt sie. Lesen/Schreiben [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //oder
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Solcher Code kann zu unklaren Situationen führen. Daher wurden Einschränkungen für die Verwendung undefinierter Werte bei IShape.getFrame() hinzugefügt. Werte für x, y, width, height, flipH, flipV und rotationAngle müssen definiert sein (nicht Float.NaN oder NullableBool.NotDefined). Der obige Beispielcode wirft jetzt eine ArgumentException.
>  //Dies gilt für die folgenden Anwendungsfälle:
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
>  //Aber IShape.RawFrame Frame-Eigenschaften können undefiniert sein. Das macht Sinn, wenn die Form mit einem Platzhalter verknüpft ist. Dann werden undefinierte Frame-Werte vom übergeordneten Platzhalter-Form überschrieben. Gibt es keinen übergeordneten Platzhalter für diese Form, verwendet die Form Standardwerte, wenn sie den effektiven Frame basierend auf ihrem IShape.RawFrame auswertet. Standardwerte sind 0 und NullableBool.False für x, y, width, height, flipH, flipV und rotationAngle. Zum Beispiel:
>  IShape shape = ...; // Form ist mit einem Platzhalter verknüpft
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // jetzt erbt die Form x, y, height, flipH, flipV Werte vom Platzhalter und überschreibt width=100 und rotationAngle=0.{code}
> ```


**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Gibt die Frame-Eigenschaften der Form zurück oder setzt sie. Lesen/Schreiben [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Der Wert jeder Eigenschaft des zurückgegebenen IShapeFrame-Objekts ist definiert (nicht Float.NaN oder NotDefined). Der zugewiesene Wert muss definiert sein (nicht Float.NaN oder NotDefined). Sie können undefinierte Werte für Eigenschaften einer RawFrame-Instanz setzen.

**Rückgabe:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Gibt die Frame-Eigenschaften der Form zurück oder setzt sie. Lesen/Schreiben [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Der Wert jeder Eigenschaft des zurückgegebenen IShapeFrame-Objekts ist definiert (nicht Float.NaN oder NotDefined). Der zugewiesene Wert muss definiert sein (nicht Float.NaN oder NotDefined). Sie können undefinierte Werte für Eigenschaften einer RawFrame-Instanz setzen.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

Gibt das LineFormat-Objekt zurück, das die Linienformat-Eigenschaften einer Form enthält. Hinweis: Für bestimmte Formtypen, die keine Linien-Eigenschaften besitzen, kann null zurückgegeben werden. Nur lesbar [ILineFormat](../../com.aspose.slides/ilineformat).

**Rückgabe:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

Gibt das ThreeDFormat-Objekt zurück, das die 3-D-Effekt-Eigenschaften einer Form enthält. Hinweis: Für bestimmte Formtypen, die keine 3-D-Eigenschaften besitzen, kann null zurückgegeben werden. Nur lesbar [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Rückgabe:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

Gibt das EffectFormat-Objekt zurück, das die Pixel-Effekte einer Form enthält. Hinweis: Für bestimmte Formtypen, die keine Effekt-Eigenschaften besitzen, kann null zurückgegeben werden. Nur lesbar [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Rückgabe:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Gibt das FillFormat-Objekt zurück, das die Füll-Formatierung einer Form enthält. Hinweis: Für bestimmte Formtypen, die keine Füll-Eigenschaften besitzen, kann null zurückgegeben werden. Nur lesbar [IFillFormat](../../com.aspose.slides/ifillformat).

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
>      // Akzent 4
>      IShape shape1 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 50, 50);
>      shape1.getFillFormat().setFillType(FillType.Solid);
>      shape1.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      // Akzent 4, Heller 80%
>      IShape shape2 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 70, 50, 50);
>      shape2.getFillFormat().setFillType(FillType.Solid);
>      shape2.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.2f);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.8f);
>      // Akzent 4, Heller 60%
>      IShape shape3 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 130, 50, 50);
>      shape3.getFillFormat().setFillType(FillType.Solid);
>      shape3.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.4f);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.6f);
>      // Akzent 4, Heller 40%
>      IShape shape4 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 190, 50, 50);
>      shape4.getFillFormat().setFillType(FillType.Solid);
>      shape4.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.6f);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.4f);
>      // Akzent 4, Dunkler 25%
>      IShape shape5 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 250, 50, 50);
>      shape5.getFillFormat().setFillType(FillType.Solid);
>      shape5.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape5.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.75f);
>      // Akzent 4, Dunkler 50%
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

Gibt die Miniaturansicht der Form zurück. ShapeThumbnailBounds.Shape-Miniatur-Grenztyp wird standardmäßig verwendet.

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) - Miniaturansicht der Form.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IImage getImage(int bounds, float scaleX, float scaleY)
```

Gibt die Miniaturansicht der Form zurück.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| bounds | int | Typ der Miniatur-Grenzen. |
| scaleX | float | X-Skalierung |
| scaleY | float | Y-Skalierung |

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) - Miniaturansicht der Form oder null, falls ShapeThumbnailBounds.Appearance verwendet wird und die Form keine sichtbaren Elemente besitzt.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

Speichert den Inhalt der Form als SVG-Datei.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Ziel-Stream |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Speichert den Inhalt der Form als SVG-Datei.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Ziel-Stream |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Optionen zur SVG-Erzeugung |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

Gibt den für Mausklick definierten Hyperlink zurück oder setzt ihn. Lesen/Schreiben [IHyperlink](../../com.aspose.slides/ihyperlink).

**Rückgabe:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

Gibt den für Mausklick definierten Hyperlink zurück oder setzt ihn. Lesen/Schreiben [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

Gibt den für Maus-Over definierten Hyperlink zurück oder setzt ihn. Lesen/Schreiben [IHyperlink](../../com.aspose.slides/ihyperlink).

**Rückgabe:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

Gibt den für Maus-Over definierten Hyperlink zurück oder setzt ihn. Lesen/Schreiben [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parameter:**
| Parameter | Type | Description |
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

Bestimmt, ob die Form ausgeblendet ist. Lesen/Schreiben  boolean .

**Rückgabe:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Bestimmt, ob die Form ausgeblendet ist. Lesen/Schreiben  boolean .

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

Gibt die Position einer Form in der Z-Reihenfolge zurück. Shapes[0] liefert die Form ganz hinten, Shapes[Shapes.Count - 1] die ganz vorne. Nur lesbar  int .

**Rückgabe:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```

Gibt die Anzahl der Verbindungsstellen der Form zurück. Nur lesbar  int .

**Rückgabe:**
int

### getRotation() {#getRotation--}
```
public final float getRotation()
```

Gibt die Drehung der angegebenen Form um die Z-Achse in Grad zurück oder setzt sie. Ein positiver Wert bedeutet Drehung im Uhrzeigersinn, ein negativer Wert Gegen-Uhrzeigersinn. Lesen/Schreiben float.

--------------------

Der zurückgegebene Wert ist immer definiert (nicht Float.NaN). Der zugewiesene Wert muss definiert sein (nicht Float.NaN). Sie können undefinierte Werte für Eigenschaften einer RawFrame-Instanz setzen.

**Rückgabe:**
float

### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```

Setzt die Drehung der angegebenen Form um die Z-Achse in Grad. Ein positiver Wert bedeutet Drehung im Uhrzeigersinn, ein negativer Wert Gegen-Uhrzeigersinn. Lesen/Schreiben float.

--------------------

Der zurückgegebene Wert ist immer definiert (nicht Float.NaN). Der zugewiesene Wert muss definiert sein (nicht Float.NaN). Sie können undefinierte Werte für Eigenschaften einer RawFrame-Instanz setzen.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public final float getX()
```

Gibt die X-Koordinate der linken oberen Ecke der Form in Punkten zurück oder setzt sie. Lesen/Schreiben float.

--------------------

Der zurückgegebene Wert ist immer definiert und nie Float.NaN. Der zugewiesene Wert muss ebenfalls definiert sein; Float.NaN darf nur für Eigenschaften einer RawFrame-Instanz zugewiesen werden.

**Rückgabe:**
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Setzt die X-Koordinate der linken oberen Ecke der Form in Punkten. Lesen/Schreiben float.

--------------------

Der zurückgegebene Wert ist immer definiert und nie Float.NaN. Der zugewiesene Wert muss ebenfalls definiert sein; Float.NaN darf nur für Eigenschaften einer RawFrame-Instanz zugewiesen werden.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

Gibt die Y-Koordinate der linken oberen Ecke der Form in Punkten zurück oder setzt sie. Lesen/Schreiben float.

--------------------

Der zurückgegebene Wert ist immer definiert und nie Float.NaN. Der zugewiesene Wert muss ebenfalls definiert sein; Float.NaN darf nur für Eigenschaften einer RawFrame-Instanz zugewiesen werden.

**Rückgabe:**
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Setzt die Y-Koordinate der linken oberen Ecke der Form in Punkten. Lesen/Schreiben float.

--------------------

Der zurückgegebene Wert ist immer definiert und nie Float.NaN. Der zugewiesene Wert muss ebenfalls definiert sein; Float.NaN darf nur für Eigenschaften einer RawFrame-Instanz zugewiesen werden.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Gibt die Breite der Form in Punkten zurück oder setzt sie. Lesen/Schreiben float.

--------------------

Der zurückgegebene Wert ist immer definiert und nie Float.NaN. Der zugewiesene Wert muss ebenfalls definiert sein; Float.NaN darf nur für Eigenschaften einer RawFrame-Instanz zugewiesen werden.

**Rückgabe:**
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Setzt die Breite der Form in Punkten. Lesen/Schreiben float.

--------------------

Der zurückgegebene Wert ist immer definiert und nie Float.NaN. Der zugewiesene Wert muss ebenfalls definiert sein; Float.NaN darf nur für Eigenschaften einer RawFrame-Instanz zugewiesen werden.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Gibt die Höhe der Form in Punkten zurück oder setzt sie. Lesen/Schreiben float.

--------------------

Der zurückgegebene Wert ist immer definiert und nie Float.NaN. Der zugewiesene Wert muss ebenfalls definiert sein; Float.NaN darf nur für Eigenschaften einer RawFrame-Instanz zugewiesen werden.

**Rückgabe:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Setzt die Höhe der Form in Punkten. Lesen/Schreiben float.

--------------------

Der zurückgegebene Wert ist immer definiert und nie Float.NaN. Der zugewiesene Wert muss ebenfalls definiert sein; Float.NaN darf nur für Eigenschaften einer RawFrame-Instanz zugewiesen werden.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```

Eigenschaft gibt an, wie eine Form im Schwarz-Weiß-Darstellungsmodus gerendert wird. Lesen/Schreiben [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Rückgabe:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```

Eigenschaft gibt an, wie eine Form im Schwarz-Weiß-Darstellungsmodus gerendert wird. Lesen/Schreiben [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```

Gibt einen internen, präsentationsbezogenen Bezeichner zurück, der für Add-Ins oder anderen Code gedacht ist. Da dieser Wert vom Benutzer oder programmatisch geändert werden kann, darf er nicht als dauerhaft eindeutiger Schlüssel verwendet werden. Nur lesbar long. Siehe auch #getOfficeInteropShapeId.getOfficeInteropShapeId.

**Rückgabe:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```

Gibt einen folienbezogenen eindeutigen Bezeichner zurück, der über die Lebensdauer der Form konstant bleibt und PowerPoint bzw. Interop-Code ein zuverlässiges Referenzieren der Form von überall im Dokument ermöglicht. Nur lesbar long. Siehe auch #getUniqueId.getUniqueId.

**Rückgabe:**
long

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```

Gibt den alternativen Text einer Form zurück oder setzt ihn. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```

Setzt den alternativen Text einer Form. Lesen/Schreiben String.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```

Gibt den Titel des alternativen Textes einer Form zurück oder setzt ihn. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```

Setzt den Titel des alternativen Textes einer Form. Lesen/Schreiben String.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```

Gibt den Namen einer Form zurück oder setzt ihn. Darf nicht null sein. Verwenden Sie bei Bedarf den leeren Zeichenkettenwert. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Setzt den Namen einer Form. Darf nicht null sein. Verwenden Sie bei Bedarf den leeren Zeichenkettenwert. Lesen/Schreiben String.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```

Gibt die Option „Als dekorativ markieren“ zurück oder setzt sie. Lesen/Schreiben boolean.

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

Setzt die Option „Als dekorativ markieren“. Lesen/Schreiben boolean.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public IBaseShapeLock getShapeLock()
```

Gibt die Sperren der Form zurück. Nur lesbar [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Rückgabe:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```

Bestimmt, ob die Form gruppiert ist. Nur lesbar boolean.

--------------------

Eigenschaft #getParentGroup.getParentGroup gibt das übergeordnete GroupShape-Objekt zurück, falls die Form gruppiert ist.

**Rückgabe:**
boolean

### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Gibt das übergeordnete GroupShape-Objekt zurück, falls die Form gruppiert ist. Andernfalls wird null zurückgegeben. Nur lesbar [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

Eigenschaft #isGrouped.isGrouped bestimmt, ob die Form gruppiert ist.

**Rückgabe:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt das Parent_Immediate-Objekt zurück. Nur lesbar IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject

### getVisualBounds() {#getVisualBounds--}
```
public final RectF getVisualBounds()
```

Gibt die visuellen Grenzen der Form zurück, berechnet aus ihrem gerenderten Inhalt.

**Rückgabe:**
android.graphics.RectF - Ein android.graphics.RectF, das die visuellen Grenzen der Form in Folien-Koordinaten darstellt.

--------------------

Das zurückgegebene Rechteck stellt die achsenausgerichteten Grenzen aller Inhalte dar, die die Form beim Rendern im Folien-Koordinatenraum erzeugt. Diese Grenzen können von den Modell-Grenzen der Form (#getX.getX/#setX(float), #getY.getY/#setY(float), #getWidth.getWidth/#setWidth(float), #getHeight.getHeight/#setHeight(float)) abweichen und negative Koordinaten enthalten, wenn der gerenderte Inhalt über den Ursprung der Folie hinausreicht. Die visuellen Grenzen berücksichtigen transformations-bezogene Aspekte wie Drehungen, Strichbreite und -verbindungen, Textlayout und Überlauf, SmartArt-Geometrie und weitere Layout-Effekte, die das endgültige Erscheinungsbild der Form beeinflussen. Die zurückgegebenen Grenzen werden nicht auf das Folienrechteck zugeschnitten.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Gibt die übergeordnete Folie einer Form zurück. Nur lesbar [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Rückgabe:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Gibt die übergeordnete Präsentation einer Folie zurück. Nur lesbar [IPresentation](../../com.aspose.slides/ipresentation).

**Rückgabe:**
[IPresentation](../../com.aspose.slides/ipresentation)