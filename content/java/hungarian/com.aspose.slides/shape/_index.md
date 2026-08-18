---
title: Shape
second_title: Aspose.Slides for Java API referencia
description: Egy alakzatot képvisel egy dián.
type: docs
url: /hu/com.aspose.slides/shape/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape), com.aspose.slides.IDOMObject
```
public class Shape implements IShape, IDOMObject
```

Egy dián lévő alakzatot képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Megállapítja, hogy az alakzat TextHolder_PPT-e. |
| [getPlaceholder()](#getPlaceholder--) | Visszaadja az alakzat helykitöltőjét. |
| [removePlaceholder()](#removePlaceholder--) | Megadja, hogy ez az alakzat nem helykitöltő. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Új helykitöltőt ad hozzá, ha nincs, és a megadott helykitöltő tulajdonságait állítja be. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Visszaad egy alap helykitöltő alakzatot (az elrendezésből és/vagy a mester diárról származó alakzatot, amelyből a jelenlegi alakzat örököl). |
| [getCustomData()](#getCustomData--) | Visszaadja az alakzat egyedi adatait. |
| [getRawFrame()](#getRawFrame--) | Visszaadja vagy beállítja a nyers alakzatrám tulajdonságait. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Visszaadja vagy beállítja a nyers alakzatrám tulajdonságait. |
| [getFrame()](#getFrame--) | Visszaadja vagy beállítja a shape frame tulajdonságait. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Visszaadja vagy beállítja a shape frame tulajdonságait. |
| [getLineFormat()](#getLineFormat--) | Visszaadja a LineFormat objektumot, amely a shape vonalformázási tulajdonságait tartalmazza. |
| [getThreeDFormat()](#getThreeDFormat--) | Visszaadja a ThreeDFormat objektumot, amely a shape 3D hatás tulajdonságait tartalmazza. |
| [getEffectFormat()](#getEffectFormat--) | Visszaadja az EffectFormat objektumot, amely a shape-re alkalmazott pixelhatásokat tartalmaz. |
| [getFillFormat()](#getFillFormat--) | Visszaadja a FillFormat objektumot, amely a shape kitöltésformázási tulajdonságait tartalmazza. |
| [getImage()](#getImage--) | Visszaadja az alakzat miniatűrjét. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Visszaadja az alakzat miniatűrjét. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Elmenti a Shape tartalmát SVG fájlként. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Elmenti a Shape tartalmát SVG fájlként. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Visszaadja vagy beállítja az egérkattintáshoz definiált hiperlinket. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Visszaadja vagy beállítja az egérkattintáshoz definiált hiperlinket. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Visszaadja vagy beállítja az egér fölé húzásakor definiált hiperlinket. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Visszaadja vagy beállítja az egér fölé húzásakor definiált hiperlinket. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Visszaadja a hiperlink kezelőt. |
| [getHidden()](#getHidden--) | Megállapítja, hogy az alakzat rejtett-e. |
| [setHidden(boolean value)](#setHidden-boolean-) | Megállapítja, hogy az alakzat rejtett-e. |
| [getZOrderPosition()](#getZOrderPosition--) | Visszaadja az alakzat pozícióját a z-sorrendben. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Visszaadja az alakzaton lévő csatlakozási pontok számát. |
| [getRotation()](#getRotation--) | Visszaadja vagy beállítja a megadott alakzat z-tengely körüli forgatási fokszámát. |
| [setRotation(float value)](#setRotation-float-) | Visszaadja vagy beállítja a megadott alakzat z-tengely körüli forgatási fokszámát. |
| [getX()](#getX--) | Lekéri vagy beállítja az alakzat bal felső sarkának X koordinátáját pontban mérve. |
| [setX(float value)](#setX-float-) | Lekéri vagy beállítja az alakzat bal felső sarkának X koordinátáját pontban mérve. |
| [getY()](#getY--) | Lekéri vagy beállítja az alakzat bal felső sarkának Y koordinátáját pontban mérve. |
| [setY(float value)](#setY-float-) | Lekéri vagy beállítja az alakzat bal felső sarkának Y koordinátáját pontban mérve. |
| [getWidth()](#getWidth--) | Lekéri vagy beállítja az alakzat szélességét pontban mérve. |
| [setWidth(float value)](#setWidth-float-) | Lekéri vagy beállítja az alakzat szélességét pontban mérve. |
| [getHeight()](#getHeight--) | Lekéri vagy beállítja az alakzat magasságát pontban mérve. |
| [setHeight(float value)](#setHeight-float-) | Lekéri vagy beállítja az alakzat magasságát pontban mérve. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | A tulajdonság meghatározza, hogyan jelenik meg az alakzat fekete-fehér módon.. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | A tulajdonság meghatározza, hogyan jelenik meg az alakzat fekete-fehér módon.. |
| [getUniqueId()](#getUniqueId--) | Visszaad egy belső, prezentációra vonatkozó azonosítót, amely a kiegészítők vagy más kódok számára készült. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Visszaad egy dia-alapú egyedi azonosítót, amely a shape életciklusa során állandó, és lehetővé teszi a PowerPoint vagy az interop kód számára, hogy megbízhatóan hivatkozzon az alakzatra a dokumentum bármely pontjáról. |
| [getAlternativeText()](#getAlternativeText--) | Visszaadja vagy beállítja az alakzathoz tartozó alternatív szöveget. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Visszaadja vagy beállítja az alakzathoz tartozó alternatív szöveget. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Visszaadja vagy beállítja az alakzathoz tartozó alternatív szöveg címét. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Visszaadja vagy beállítja az alakzathoz tartozó alternatív szöveg címét. |
| [getName()](#getName--) | Visszaadja vagy beállítja az alakzat nevét. |
| [setName(String value)](#setName-java.lang.String-) | Visszaadja vagy beállítja az alakzat nevét. |
| [isDecorative()](#isDecorative--) | Bekapcsolja vagy kikapcsolja a 'Mark as decorative' opciót. Olvasás/írás boolean. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Bekapcsolja vagy kikapcsolja a 'Mark as decorative' opciót. Olvasás/írás boolean. |
| [getShapeLock()](#getShapeLock--) | Visszaadja az alakzat zárjait. |
| [isGrouped()](#isGrouped--) | Megállapítja, hogy az alakzat csoportosított-e. |
| [getParentGroup()](#getParentGroup--) | Visszaadja a szülő GroupShape objektumot, ha az alakzat csoportosított. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVisualBounds()](#getVisualBounds--) | Lekéri az alakzat vizuális határait, amelyeket a renderelt tartalom alapján számoltak. |
| [getSlide()](#getSlide--) | Visszaadja az alakzat szülő diáját. |
| [getPresentation()](#getPresentation--) | Visszaadja a dia szülő prezentációját. |

### isTextHolder() {#isTextHolder--}
```
public final boolean isTextHolder()
```

Megállapítja, hogy az alakzat TextHolder_PPT-e. Csak olvasható boolean .

**Visszatér:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```

Visszaadja az alakzat helykitöltőjét. Visszaad null értéket, ha az alakzatnak nincs helykitöltője. Csak olvasható [IPlaceholder](../../com.aspose.slides/iplaceholder).

--------------------

> ```
> The following example shows how to change Text in Placeholder.
>  
>  // Létrehozza a Presentation osztályt
>  Presentation pres = new Presentation("ReplacingText.pptx");
>  try {
>      // Eléri az első diát
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Végigiterál a alakzatokon a helykitöltő megtalálásához
>      for (IShape shp : sld.getShapes())
>          if (shp.getPlaceholder() != null)
>          {
>              // Módosítja a szöveget minden helykitöltőben
>              ((IAutoShape)shp).getTextFrame().setText("This is a Placeholder");
>          }
>      // Mentés a lemezen
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
>      for (IShape shape : slide.getSlide().getShapes()) // Végigiterál a dián
>      {
>          if (shape.getPlaceholder() != null && shape instanceof AutoShape)
>          {
>              String text = "";
>              if (shape.getPlaceholder().getType() == PlaceholderType.CenteredTitle) // A PowerPoint a "Click to add title" feliratot jeleníti meg
>              {
>                  text = "Add Title";
>              }
>              else if (shape.getPlaceholder().getType() == PlaceholderType.Subtitle) // Alcímet ad hozzá
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


**Visszatér:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### removePlaceholder() {#removePlaceholder--}
```
public final void removePlaceholder()
```

Megadja, hogy ez az alakzat nem helykitöltő.

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public final IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Új helykitöltőt ad hozzá, ha nincs, és a megadott helykitöltő tulajdonságait állítja be.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | A helykitöltő, amelyből a tartalmat másolni kell. |

**Visszatér:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - Új #getPlaceholder.getPlaceholder.

### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

Visszaad egy alap helykitöltő alakzatot (az elrendezésből és/vagy a mester diárról származó alakzatot, amelyből a jelenlegi alakzat örököl).

--------------------

> ```
> // lekéri az összes (master/layout/slide) animált hatást a helykitöltő alakzattól
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


A null érték visszatér, ha a jelenlegi alakzat nem örökölt.

**Visszatér:**
[IShape](../../com.aspose.slides/ishape)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Visszaadja az alakzat egyedi adatait. Csak olvasható [ICustomData](../../com.aspose.slides/icustomdata).

**Visszatér:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public final IShapeFrame getRawFrame()
```

Visszaadja vagy beállítja a nyers alakzatrám tulajdonságait. Olvasás/írás [IShapeFrame](../../com.aspose.slides/ishapeframe).

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

**Visszatér:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
```

Visszaadja vagy beállítja a nyers alakzatrám tulajdonságait. Olvasás/írás [IShapeFrame](../../com.aspose.slides/ishapeframe).

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Visszaadja vagy beállítja a shape frame tulajdonságait. Olvasás/írás [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Az IShapeFrame példány visszaadott minden tulajdonsága meghatározott (nem NaN vagy NotDefined). A hozzárendelt IShapeFrame példány minden tulajdonsága szintén meghatározott (nem NaN vagy NotDefined). Undefined értékek beállíthatók a RawFrame példány tulajdonságaira.

**Visszatér:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Visszaadja vagy beállítja a shape frame tulajdonságait. Olvasás/írás [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Az IShapeFrame példány visszaadott minden tulajdonsága meghatározott (nem NaN vagy NotDefined). A hozzárendelt IShapeFrame példány minden tulajdonsága szintén meghatározott (nem NaN vagy NotDefined). Undefined értékek beállíthatók a RawFrame példány tulajdonságaira.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

Visszaadja a LineFormat objektumot, amely a shape vonalformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos típusú alakzatok esetén, amelyeknek nincs vonaltulajdonsága, null értéket adhat vissza. Csak olvasható [ILineFormat](../../com.aspose.slides/ilineformat).

**Visszatér:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

Visszaadja a ThreeDFormat objektumot, amely a shape 3D hatás tulajdonságait tartalmazza. Megjegyzés: bizonyos típusú alakzatok esetén, amelyeknek nincs 3D tulajdonsága, null értéket adhat vissza. Csak olvasható [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Visszatér:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

Visszaadja az EffectFormat objektumot, amely a shape-re alkalmazott pixelhatásokat tartalmaz. Megjegyzés: bizonyos típusú alakzatok esetén, amelyeknek nincs effektustulajdonsága, null értéket adhat vissza. Csak olvasható [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Visszatér:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Visszaadja a FillFormat objektumot, amely a shape kitöltésformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos típusú alakzatok esetén, amelyeknek nincs kitöltéstulajdonsága, null értéket adhat vissza. Csak olvasható [IFillFormat](../../com.aspose.slides/ifillformat).

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
>      // Accent 4, Lighter 80%
>      IShape shape2 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 70, 50, 50);
>      shape2.getFillFormat().setFillType(FillType.Solid);
>      shape2.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.2f);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.8f);
>      // Accent 4, Lighter 60%
>      IShape shape3 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 130, 50, 50);
>      shape3.getFillFormat().setFillType(FillType.Solid);
>      shape3.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.4f);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.6f);
>      // Accent 4, Lighter 40%
>      IShape shape4 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 190, 50, 50);
>      shape4.getFillFormat().setFillType(FillType.Solid);
>      shape4.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.6f);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.4f);
>      // Accent 4, Darker 25%
>      IShape shape5 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 250, 50, 50);
>      shape5.getFillFormat().setFillType(FillType.Solid);
>      shape5.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape5.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.75f);
>      // Accent 4, Darker 50%
>      IShape shape6 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 310, 50, 50);
>      shape6.getFillFormat().setFillType(FillType.Solid);
>      shape6.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape6.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.5f);
>      pres.save("example_accent4.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatér:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public final IImage getImage()
```

Visszaadja az alakzat miniatűrjét. Alapértelmezés szerint a ShapeThumbnailBounds.Shape típusú miniatűr határ használatos.

**Visszatér:**
[IImage](../../com.aspose.slides/iimage) - Shape thumbnail.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IImage getImage(int bounds, float scaleX, float scaleY)
```

Visszaadja az alakzat miniatűrjét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bounds | int | Alakzat miniatűr határ típusa. |
| scaleX | float | X méretezés |
| scaleY | float | Y méretezés |

**Visszatér:**
[IImage](../../com.aspose.slides/iimage) - Shape thumbnail vagy null, ha a ShapeThumbnailBounds.Appearance van használva és az alakzatnak nincsenek látható elemei.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

Elmenti a Shape tartalmát SVG fájlként.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Cél adatfolyam |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Elmenti a Shape tartalmát SVG fájlként.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Cél adatfolyam |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG generálási beállítások |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

Visszaadja vagy beállítja az egérkattintáshoz definiált hiperlinket. Olvasás/írás [IHyperlink](../../com.aspose.slides/ihyperlink).

**Visszatér:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

Visszaadja vagy beállítja az egérkattintáshoz definiált hiperlinket. Olvasás/írás [IHyperlink](../../com.aspose.slides/ihyperlink).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

Visszaadja vagy beállítja az egér fölé húzásakor definiált hiperlinket. Olvasás/írás [IHyperlink](../../com.aspose.slides/ihyperlink).

**Visszatér:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

Visszaadja vagy beállítja az egér fölé húzásakor definiált hiperlinket. Olvasás/írás [IHyperlink](../../com.aspose.slides/ihyperlink).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

Visszaadja a hiperlink kezelőt. Csak olvasható [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Visszatér:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Megállapítja, hogy az alakzat rejtett-e. Olvasás/írás boolean .

**Visszatér:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Megállapítja, hogy az alakzat rejtett-e. Olvasás/írás boolean .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

Visszaadja az alakzat pozícióját a z-sorrendben. A Shapes[0] visszaadja a hátul lévő alakzatot, a Shapes[Shapes.Count - 1] pedig az elöl lévő alakzatot. Csak olvasható int .

**Visszatér:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```

Visszaadja az alakzaton lévő csatlakozási pontok számát. Csak olvasható int .

**Visszatér:**
int

### getRotation() {#getRotation--}
```
public final float getRotation()
```

Visszaadja vagy beállítja a megadott alakzat z-tengely körüli forgatási fokszámát. A pozitív érték az óramutató járásával megegyező forgatást jelzi; a negatív érték az óramutatóval ellentétes forgatást. Olvasás/írás float.

--------------------

A visszaadott IShapeFrame példány minden tulajdonsága meghatározott (nem Float.NaN). A hozzárendelt IShapeFrame példány minden tulajdonságát meghatározottnak kell lennie (nem Float.NaN). Undefined értékek beállíthatók a RawFrame példány tulajdonságaira.

**Visszatér:**
float

### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```
A visszaadja vagy beállítja a meghatározott alakzat z-tengely körül történő elfordulásának fokszámát. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az óramutató járásával ellentétes forgást jelzi. Olvasás/írás float.

--------------------

A visszaadott érték mindig definiált (nem Float.NaN). A hozzárendelt értéknek definiáltnak kell lennie (nem Float.NaN). Nem definiált értékeket állíthat be a RawFrame példány tulajdonságainál.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public final float getX()
```

A forma bal felső sarkának x-koordinátáját adja vissza vagy állítja be, pontban mérve. Olvasás/írás float.

--------------------

A visszaadott érték mindig definiált és soha nem Float.NaN. A hozzárendelt értéknek szintén definiáltnak kell lennie; Float.NaN-t csak a RawFrame példány tulajdonságainak állíthatja be.

**Visszatérési érték:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

A forma bal felső sarkának x-koordinátáját adja vissza vagy állítja be, pontban mérve. Olvasás/írás float.

--------------------

A visszaadott érték mindig definiált és soha nem Float.NaN. A hozzárendelt értéknek szintén definiáltnak kell lennie; Float.NaN-t csak a RawFrame példány tulajdonságainak állíthatja be.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

A forma bal felső sarkának y-koordinátáját adja vissza vagy állítja be, pontban mérve. Olvasás/írás float.

--------------------

A visszaadott érték mindig definiált és soha nem Float.NaN. A hozzárendelt értéknek szintén definiáltnak kell lennie; Float.NaN-t csak a RawFrame példány tulajdonságainak állíthatja be.

**Visszatérési érték:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

A forma bal felső sarkának y-koordinátáját adja vissza vagy állítja be, pontban mérve. Olvasás/írás float.

--------------------

A visszaadott érték mindig definiált és soha nem Float.NaN. A hozzárendelt értéknek szintén definiáltnak kell lennie; Float.NaN-t csak a RawFrame példány tulajdonságainak állíthatja be.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Az alakzat szélességét adja vissza vagy állítja be, pontban mérve. Olvasás/írás float.

--------------------

A visszaadott érték mindig definiált és soha nem Float.NaN. A hozzárendelt értéknek szintén definiáltnak kell lennie; Float.NaN-t csak a RawFrame példány tulajdonságainak állíthatja be.

**Visszatérési érték:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Az alakzat szélességét adja vissza vagy állítja be, pontban mérve. Olvasás/írás float.

--------------------

A visszaadott érték mindig definiált és soha nem Float.NaN. A hozzárendelt értéknek szintén definiáltnak kell lennie; Float.NaN-t csak a RawFrame példány tulajdonságainak állíthatja be.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Az alakzat magasságát adja vissza vagy állítja be, pontban mérve. Olvasás/írás float.

--------------------

A visszaadott érték mindig definiált és soha nem Float.NaN. A hozzárendelt értéknek szintén definiáltnak kell lennie; Float.NaN-t csak a RawFrame példány tulajdonságainak állíthatja be.

**Visszatérési érték:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Az alakzat magasságát adja vissza vagy állítja be, pontban mérve. Olvasás/írás float.

--------------------

A visszaadott érték mindig definiált és soha nem Float.NaN. A hozzárendelt értéknek szintén definiáltnak kell lennie; Float.NaN-t csak a RawFrame példány tulajdonságainak állíthatja be.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```

A tulajdonság meghatározza, hogyan jelenik meg egy alakzat fekete-fehér megjelenítési módban. Olvasás/írás [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Visszatérési érték:**
byte
### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```

A tulajdonság meghatározza, hogyan jelenik meg egy alakzat fekete-fehér megjelenítési módban. Olvasás/írás [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```

Visszaad egy belső, a bemutatóhoz kötött azonosítót, amely bővítmények vagy egyéb kódok számára készült. Mivel ezt az értéket a felhasználó vagy programozott módon át lehet rendelni, nem szabad állandó egyedi kulcsként kezelni. Csak olvasható long. Lásd még \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Visszatérési érték:**
long
### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```

Visszaad egy dia-körülhatárolt egyedi azonosítót, amely az alakzat életciklusában állandó, és a PowerPoint vagy az interop kód megbízhatóan hivatkozhat rá a dokumentum bármely pontjáról. Csak olvasható long. Lásd még \#getUniqueId.getUniqueId.

**Visszatérési érték:**
long
### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```

Visszaadja vagy beállítja egy alakzat alternatív szövegét. Olvasás/írás String.

**Visszatérési érték:**
java.lang.String
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```

Visszaadja vagy beállítja egy alakzat alternatív szövegét. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```

Visszaadja vagy beállítja egy alakzat alternatív szövegének címét. Olvasás/írás String.

**Visszatérési érték:**
java.lang.String
### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```

Visszaadja vagy beállítja egy alakzat alternatív szövegének címét. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```

Visszaadja vagy beállítja egy alakzat nevét. Nem lehet null. Szükség esetén használjon üres karakterlánc értéket. Olvasás/írás String.

**Visszatérési érték:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Visszaadja vagy beállítja egy alakzat nevét. Nem lehet null. Szükség esetén használjon üres karakterlánc értéket. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```

Olvasás/írás boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatérési érték:**
boolean
### setDecorative(boolean value) {#setDecorative-boolean-}
```
public final void setDecorative(boolean value)
```

Olvasás/írás boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public IBaseShapeLock getShapeLock()
```

Visszaadja az alakzat zárolásait. Csak olvasható [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Visszatérési érték:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```

Megállapítja, hogy az alakzat csoportosítva van-e. Csak olvasható boolean.

--------------------

A \#getParentGroup.getParentGroup tulajdonság visszaadja a szülő GroupShape objektumot, ha az alakzat csoportosítva van.

**Visszatérési érték:**
boolean
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Visszaadja a szülő GroupShape objektumot, ha az alakzat csoportosítva van. Ellenkező esetben null-t ad vissza. Csak olvasható [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

A \#isGrouped.isGrouped tulajdonság meghatározza, hogy az alakzat csoportosítva van-e.

**Visszatérési érték:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaadja a Parent\_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatérési érték:**
com.aspose.slides.IDOMObject
### getVisualBounds() {#getVisualBounds--}
```
public final Rectangle2D.Float getVisualBounds()
```

Lekéri az alakzat vizuális határait, amelyek a renderelt tartalom alapján számítottak.

**Visszatérési érték:**
java.awt.geom.Rectangle2D.Float - Egy java.awt.geom.Rectangle2D.Float, amely az alakzat vizuális határait ábrázolja dia koordinátákban.

--------------------

A visszaadott téglalap a modell szélesség-magasságra vetített (axis-aligned) határokat tartalmazza, amelyet az alakzat a renderelés során a dia koordináta-térben előállít. Ezek a határok eltérhetnek az alakzat modellhatáraitól (\#getX.getX/\#setX(float).setX(float), \#getY.getY/\#setY(float).setY(float), \#getWidth.getWidth/\#setWidth(float).setWidth(float), \#getHeight.getHeight/\#setHeight(float).setHeight(float)) és negatív koordinátákat is tartalmazhatnak, ha a renderelt tartalom a dia origója mögé nyúlik. A vizuális határok figyelembe veszik a renderelésre ható tényezőket, például a transzformációkat (például forgást), a vonalvastagságot és illesztéseket, a szöveg elrendezését és túlfutását, a SmartArt geometriát, valamint egyéb elrendezési hatásokat, amelyek befolyásolják az alakzat végső megjelenését. A visszaadott határok nincsenek levágva a dia téglalapjára.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Visszaadja egy alakzat szülő diát. Csak olvasható [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Visszatérési érték:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Visszaadja egy dia szülő bemutatóját. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatérési érték:**
[IPresentation](../../com.aspose.slides/ipresentation)