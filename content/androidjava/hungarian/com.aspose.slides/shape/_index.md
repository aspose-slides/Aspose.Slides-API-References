---
title: Shape
second_title: Aspose.Slides Androidra a Java API-referenciával
description: Egy dián lévő alakzatot képvisel.
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

A dián egy alakzatot képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Meghatározza, hogy a forma TextHolder_PPT-e. |
| [getPlaceholder()](#getPlaceholder--) | Visszaadja az alakzat helyőrzőjét. |
| [removePlaceholder()](#removePlaceholder--) | Meghatározza, hogy ez az alakzat nem helyőrző. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Új helyőrzőt ad hozzá, ha nincs, és a helyőrző tulajdonságait egy megadottra állítja. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Visszaad egy alap helyőrző alakzatot (az elrendezésből és/vagy a mester diából származó alakzatot, amelyről a jelenlegi alakzat örököl). |
| [getCustomData()](#getCustomData--) | Visszaadja az alakzat egyéni adatait. |
| [getRawFrame()](#getRawFrame--) | Visszaadja vagy beállítja a nyers alakzatkeret tulajdonságait. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Visszaadja vagy beállítja a nyers alakzatkeret tulajdonságait. |
| [getFrame()](#getFrame--) | Visszaadja vagy beállítja a nyers alakzatkeret tulajdonságait. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Visszaadja vagy beállítja a nyers alakzatkeret tulajdonságait. |
| [getLineFormat()](#getLineFormat--) | Visszaadja a LineFormat objektumot, amely a forma vonalformázási tulajdonságait tartalmazza. |
| [getThreeDFormat()](#getThreeDFormat--) | Visszaadja a ThreeDFormat objektumot, amely a forma 3D hatásának tulajdonságait tartalmazza. |
| [getEffectFormat()](#getEffectFormat--) | Visszaadja az EffectFormat objektumot, amely a forma alkalmazott pixelhatásait tartalmazza. |
| [getFillFormat()](#getFillFormat--) | Visszaadja a FillFormat objektumot, amely a forma kitöltésének formázási tulajdonságait tartalmazza. |
| [getImage()](#getImage--) | Visszaadja a forma bélyegképét. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Visszaadja a forma bélyegképét. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | A Shape tartalmát SVG fájlként menti. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | A Shape tartalmát SVG fájlként menti. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Visszaadja vagy beállítja az egér fölé húzásra definiált hiperhivatkozást. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Visszaadja vagy beállítja az egér fölé húzásra definiált hiperhivatkozást. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Visszaadja a hiperhivatkozás kezelőt. |
| [getHidden()](#getHidden--) | Meghatározza, hogy a forma rejtett-e. |
| [setHidden(boolean value)](#setHidden-boolean-) | Meghatározza, hogy a forma rejtett-e. |
| [getZOrderPosition()](#getZOrderPosition--) | Visszaadja egy alakzat pozícióját a z-rendben. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Visszaadja a forma csatlakozási pontjainak számát. |
| [getRotation()](#getRotation--) | Visszaadja vagy beállítja, hogy a megadott forma hány fokban van elfordítva a z-tengely körül. |
| [setRotation(float value)](#setRotation-float-) | Visszaadja vagy beállítja, hogy a megadott forma hány fokban van elfordítva a z-tengely körül. |
| [getX()](#getX--) | Megkapja vagy beállítja az alakzat bal-felső sarkának x-koordinátáját pontban mérve. |
| [setX(float value)](#setX-float-) | Megkapja vagy beállítja az alakzat bal-felső sarkának x-koordinátáját pontban mérve. |
| [getY()](#getY--) | Megkapja vagy beállítja az alakzat bal-felső sarkának y-koordinátáját pontban mérve. |
| [setY(float value)](#setY-float-) | Megkapja vagy beállítja az alakzat bal-felső sarkának y-koordinátáját pontban mérve. |
| [getWidth()](#getWidth--) | Megkapja vagy beállítja az alakzat szélességét pontban mérve. |
| [setWidth(float value)](#setWidth-float-) | Megkapja vagy beállítja az alakzat szélességét pontban mérve. |
| [getHeight()](#getHeight--) | Megkapja vagy beállítja az alakzat magasságát pontban mérve. |
| [setHeight(float value)](#setHeight-float-) | Megkapja vagy beállítja az alakzat magasságát pontban mérve. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | A tulajdonság meghatározza, hogyan jelenik meg egy alakzat fekete-fehér megjelenítési módban. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | A tulajdonság meghatározza, hogyan jelenik meg egy alakzat fekete-fehér megjelenítési módban. |
| [getUniqueId()](#getUniqueId--) | Visszaad egy belső, a prezentációra korlátozott azonosítót, amelyet kiegészítők vagy egyéb kódok használhatnak. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Visszaad egy diára korlátozott egyedi azonosítót, amely állandó a forma élettartama alatt, és lehetővé teszi a PowerPoint vagy interop kód számára, hogy megbízhatóan hivatkozzon a formára a dokumentum bármely pontjáról. |
| [getAlternativeText()](#getAlternativeText--) | Visszaadja vagy beállítja a forma alternatív szövegét. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Visszaadja vagy beállítja a forma alternatív szövegét. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Visszaadja vagy beállítja a forma alternatív szövegének címét. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Visszaadja vagy beállítja a forma alternatív szövegének címét. |
| [getName()](#getName--) | Visszaadja vagy beállítja egy forma nevét. |
| [setName(String value)](#setName-java.lang.String-) | Visszaadja vagy beállítja egy forma nevét. |
| [isDecorative()](#isDecorative--) | Megkapja vagy beállítja a 'Megjelölés dekoratívként' opciót Olvasás/írás boolean. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Megkapja vagy beállítja a 'Megjelölés dekoratívként' opciót Olvasás/írás boolean. |
| [getShapeLock()](#getShapeLock--) | Visszaadja a forma zárolásait. |
| [isGrouped()](#isGrouped--) | Meghatározza, hogy a forma csoportosított-e. |
| [getParentGroup()](#getParentGroup--) | Visszaadja a szülő GroupShape objektumot, ha a forma csoportosított. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVisualBounds()](#getVisualBounds--) | Megkapja a forma vizuális határait, amelyeket a megjelenített tartalom alapján számítanak. |
| [getSlide()](#getSlide--) | Visszaadja a forma szülő diáját. |
| [getPresentation()](#getPresentation--) | Visszaadja a dia szülő prezentációját. |

### isTextHolder() {#isTextHolder--}
```
public final boolean isTextHolder()
```

Meghatározza, hogy a forma TextHolder_PPT-e. Csak olvasható boolean.

**Visszaad:**  
boolean

### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```

Visszaadja az alakzat helyőrzőjét. Null értéket ad vissza, ha az alakzatnak nincs helyőrzője. Csak olvasható [IPlaceholder](../../com.aspose.slides/iplaceholder).

--------------------

> ```
> The following example shows how to change Text in Placeholder.
>  
>  // Létrehozza a Presentation osztályt
>  Presentation pres = new Presentation("ReplacingText.pptx");
>  try {
>      // Eléri az első diát
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Végig iterál a formákon, hogy megtalálja a helyőrzőt
>      for (IShape shp : sld.getShapes())
>          if (shp.getPlaceholder() != null)
>          {
>              // Módosítja minden helyőrző szövegét
>              ((IAutoShape)shp).getTextFrame().setText("This is a Placeholder");
>          }
>      // Mentés a prezentációt lemezen
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
>      for (IShape shape : slide.getSlide().getShapes()) // Végig iterál a dián
>      {
>          if (shape.getPlaceholder() != null && shape instanceof AutoShape)
>          {
>              String text = "";
>              if (shape.getPlaceholder().getType() == PlaceholderType.CenteredTitle) // A PowerPoint a "Click to add title" feliratot jeleníti meg
>              {
>                  text = "Add Title";
>              }
>              else if (shape.getPlaceholder().getType() == PlaceholderType.Subtitle) // Hozzáad alcímet
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


**Visszaad:**  
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### removePlaceholder() {#removePlaceholder--}
```
public final void removePlaceholder()
```

Meghatározza, hogy ez az alakzat nem helyőrző.

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public final IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Új helyőrzőt ad hozzá, ha nincs, és a helyőrző tulajdonságait egy megadottra állítja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | A másolandó helyőrző tartalma. |

**Visszaad:**  
[IPlaceholder](../../com.aspose.slides/iplaceholder) - Új #getPlaceholder.getPlaceholder.

### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

Visszaad egy alap helyőrző alakzatot (az elrendezésből és/vagy a mester diából származó alakzatot, amelyről a jelenlegi alakzat örököl).

--------------------

> ```
> // lekéri a helyőrző alakzat összes (mester/elrendezés/diára) animált effektusát
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

Null értéket ad vissza, ha a jelenlegi alakzat nem örököl.

**Visszaad:**  
[IShape](../../com.aspose.slides/ishape)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Visszaadja az alakzat egyéni adatait. Csak olvasható [ICustomData](../../com.aspose.slides/icustomdata).

**Visszaad:**  
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public final IShapeFrame getRawFrame()
```

Visszaadja vagy beállítja a nyers alakzatkeret tulajdonságait. Olvasható/írható [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //vagy
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Az ilyen kód összezavaró helyzetekhez vezethet. Ezért korlátozások kerültek bevezetésre a nem definiált értékek IShape.getFrame() esetén történő használatára. Az x, y, szélesség, magasság, flipH, flipV és rotationAngle értékeknek definiáltnak kell lenniük (nem Float.NaN vagy NullableBool.NotDefined). A fenti példa kód most ArgumentException kivételt dob.
>  //Ez az alábbi felhasználási esetekre vonatkozik:
>  IShape shape = ...;
>  shape.setFrame(...); // nem lehet undefined
>  IShapeCollection shapes = ...;
>  // az x, y, szélesség, magasság paraméterek nem lehetnek Float.NaN:
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
>  //De az IShape.RawFrame keret tulajdonságai lehetnek undefined. Ez akkor értelmes, ha a forma egy helyőrzőhöz van kapcsolva. Ekkor a nem definiált forma keret értékek felülíródnak a szülő helyőrző alakzatból. Ha nincs szülő helyőrző alakzat ehhez a formához, akkor a forma alapértelmezett értékeket használ, amikor a hatékony keretet az IShape.RawFrame alapján számítja ki. Az alapértelmezett értékek 0 és NullableBool.False az x, y, szélesség, magasság, flipH, flipV és rotationAngle esetén. Például:
>  IShape shape = ...; // a forma egy helyőrzőhöz van kapcsolva
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // most a forma örökli az x, y, magasság, flipH, flipV értékeket a helyőrzőből, és felülírja a szélességet 100-ra és a rotationAngle-ot 0-ra.{code}
```

**Visszaad:**  
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
```

Visszaadja vagy beállítja a nyers alakzatkeret tulajdonságait. Olvasható/írható [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //vagy
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Az ilyen kód összezavaró helyzetekhez vezethet. Ezért korlátozások kerültek bevezetésre a nem definiált értékek IShape.getFrame() esetén történő használatára. Az x, y, szélesség, magasság, flipH, flipV és rotationAngle értékeknek definiáltnak kell lenniük (nem Float.NaN vagy NullableBool.NotDefined). A fenti példakód most ArgumentException kivételt dob.
>  //Ez a következő esetekre vonatkozik:
>  IShape shape = ...;
>  shape.setFrame(...); // nem lehet undefined
>  IShapeCollection shapes = ...;
>  // x, y, szélesség, magasság paraméterek nem lehetnek Float.NaN:
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
>  //Viszont az IShape.RawFrame keret tulajdonságai lehetnek undefined. Ez akkor értelmes, ha a forma egy helyőrzőhöz van kapcsolva. Ebben az esetben a nem definiált keretértékeket a szülő helyőrző alakzat felülírja. Ha nincs szülő helyőrző, akkor a forma alapértelmezett értékeket használ az IShape.RawFrame alapján a hatékony keret kiszámításához. Az alapértelmezett értékek 0 és NullableBool.False az x, y, szélesség, magasság, flipH, flipV és rotationAngle esetén. Például:
>  IShape shape = ...; // a forma egy helyőrzőhöz van kapcsolva
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // most a forma örökli az x, y, magasság, flipH, flipV értékeket a helyőrzőtől, és felülírja a szélességet 100-ra és a rotationAngle-ot 0.{code}
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Visszaadja vagy beállítja a forma keret tulajdonságait. Olvasható/írható [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

A visszaadott IShapeFrame példány minden tulajdonsága definiált (nem NaN vagy NotDefined). A hozzárendelt IShapeFrame példány minden tulajdonságának nem szabad undefined értéknek lennie (nem NaN vagy NotDefined). Az RawFrame példány tulajdonságaihoz undefined értékek beállítása lehetséges.

**Visszaad:**  
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Visszaadja vagy beállítja a forma keret tulajdonságait. Olvasható/írható [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

A visszaadott IShapeFrame példány minden tulajdonsága definiált (nem NaN vagy NotDefined). A hozzárendelt IShapeFrame példány minden tulajdonságának nem szabad undefined értéknek lennie (nem NaN vagy NotDefined). Az RawFrame példány tulajdonságaihoz undefined értékek beállítása lehetséges.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

Visszaadja a LineFormat objektumot, amely a forma vonalformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos formáktípusok esetén visszaadhat null értéket, ha nincs vonal tulajdonságuk. Csak olvasható [ILineFormat](../../com.aspose.slides/ilineformat).

**Visszaad:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

Visszaadja a ThreeDFormat objektumot, amely a forma 3D hatásának tulajdonságait tartalmazza. Megjegyzés: bizonyos formáktípusok esetén visszaadhat null értéket, ha nincs 3D tulajdonságuk. Csak olvasható [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Visszaad:**  
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

Visszaadja az EffectFormat objektumot, amely a forma alkalmazott pixelhatásait tartalmazza. Megjegyzés: bizonyos formáktípusok esetén visszaadhat null értéket, ha nincs effektusuk. Csak olvasható [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Visszaad:**  
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Visszaadja a FillFormat objektumot, amely a forma kitöltésének formázási tulajdonságait tartalmazza. Megjegyzés: bizonyos formáktípusok esetén visszaadhat null értéket, ha nincs kitöltési tulajdonságuk. Csak olvasható [IFillFormat](../../com.aspose.slides/ifillformat).

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
>      // Accent 4, világosabb 80%
>      IShape shape2 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 70, 50, 50);
>      shape2.getFillFormat().setFillType(FillType.Solid);
>      shape2.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.2f);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.8f);
>      // Accent 4, világosabb 60%
>      IShape shape3 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 130, 50, 50);
>      shape3.getFillFormat().setFillType(FillType.Solid);
>      shape3.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.4f);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.6f);
>      // Accent 4, világosabb 40%
>      IShape shape4 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 190, 50, 50);
>      shape4.getFillFormat().setFillType(FillType.Solid);
>      shape4.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.6f);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.4f);
>      // Accent 4, sötétebb 25%
>      IShape shape5 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 250, 50, 50);
>      shape5.getFillFormat().setFillType(FillType.Solid);
>      shape5.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape5.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.75f);
>      // Accent 4, sötétebb 50%
>      IShape shape6 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 310, 50, 50);
>      shape6.getFillFormat().setFillType(FillType.Solid);
>      shape6.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape6.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.5f);
>      pres.save("example_accent4.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszaad:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public final IImage getImage()
```

Visszaadja a forma bélyegképét. A ShapeThumbnailBounds.Shape forma bélyegkép határok típusa az alapértelmezett.

**Visszaad:**  
[IImage](../../com.aspose.slides/iimage) - Forma bélyegkép.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IImage getImage(int bounds, float scaleX, float scaleY)
```

Visszaadja a forma bélyegképét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bounds | int | A forma bélyegkép határok típusa. |
| scaleX | float | X méretezés |
| scaleY | float | Y méretezés |

**Visszaad:**  
[IImage](../../com.aspose.slides/iimage) - Forma bélyegkép vagy null, ha a ShapeThumbnailBounds.Appearance van használva és a forma nem tartalmaz látható elemeket.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

A Shape tartalmát SVG fájlként menti.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Cél adatfolyam |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

A Shape tartalmát SVG fájlként menti.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Cél adatfolyam |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG generálási beállítások |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást. Olvasható/írható [IHyperlink](../../com.aspose.slides/ihyperlink).

**Visszaad:**  
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást. Olvasható/írható [IHyperlink](../../com.aspose.slides/ihyperlink).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

Visszaadja vagy beállítja az egér fölé húzásra definiált hiperhivatkozást. Olvasható/írható [IHyperlink](../../com.aspose.slides/ihyperlink).

**Visszaad:**  
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

Visszaadja vagy beállítja az egér fölé húzásra definiált hiperhivatkozást. Olvasható/írható [IHyperlink](../../com.aspose.slides/ihyperlink).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

Visszaadja a hiperhivatkozás kezelőt. Csak olvasható [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Visszaad:**  
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Meghatározza, hogy a forma rejtett-e. Olvasható/írható boolean.

**Visszaad:**  
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Meghatározza, hogy a forma rejtett-e. Olvasható/írható boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

Visszaadja egy alakzat pozícióját a z-rendben. A Shapes[0] a legháttali, a Shapes[Shapes.Count - 1] a legelöl lévő alakzatot adja. Csak olvasható int.

**Visszaad:**  
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```

Visszaadja a forma csatlakozási pontjainak számát. Csak olvasható int.

**Visszaad:**  
int

### getRotation() {#getRotation--}
```
public final float getRotation()
```

Visszaadja vagy beállítja, hogy a megadott forma hány fokban van elfordítva a z-tengely körül. A pozitív érték az óramutató járásával megegyező forgást jelenti; a negatív érték az ellenkezőjét. Olvasható/írható float.

--------------------

A visszaadott érték mindig definiált (nem Float.NaN). A hozzárendelt értéknek is definiáltnak kell lennie (nem Float.NaN). Az RawFrame példány tulajdonságaihoz undefined értékek beállíthatók.

**Visszaad:**  
float

### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```

Visszaadja vagy beállítja, hogy a megadott forma hány fokban van elfordítva a z-tengely körül. A pozitív érték az óramutató járásával megegyező forgást jelenti; a negatív érték az ellenkezőjét. Olvasható/írható float.

--------------------

A visszaadott érték mindig definiált (nem Float.NaN). A hozzárendelt értéknek is definiáltnak kell lennie (nem Float.NaN). Az RawFrame példány tulajdonságaihoz undefined értékek beállíthatók.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public final float getX()
```

Megkapja vagy beállítja az alakzat bal-felső sarkának x-koordinátáját pontban mérve. Olvasható/írható float.

--------------------

A visszaadott érték mindig definiált és soha nem Float.NaN. A hozzárendelt értéknek is definiáltnak kell lennie; csak RawFrame példányok tulajdonságaihoz állítható be Float.NaN.

**Visszaad:**  
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Megkapja vagy beállítja az alakzat bal-felső sarkának x-koordinátáját pontban mérve. Olvasható/írható float.

--------------------

A visszaadott érték mindig definiált és soha nem Float.NaN. A hozzárendelt értéknek is definiáltnak kell lennie; csak RawFrame példányok tulajdonságaihoz állítható be Float.NaN.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

Megkapja vagy beállítja az alakzat bal-felső sarkának y-koordinátáját pontban mérve. Olvasható/írható float.

--------------------

A visszaadott érték mindig definiált és soha nem Float.NaN. A hozzárendelt értéknek is definiáltnak kell lennie; csak RawFrame példányok tulajdonságaihoz állítható be Float.NaN.

**Visszaad:**  
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Megkapja vagy beállítja az alakzat bal-felső sarkának y-koordinátáját pontban mérve. Olvasható/írható float.

--------------------

A visszaadott érték mindig definiált és soha nem Float.NaN. A hozzárendelt értéknek is definiáltnak kell lennie; csak RawFrame példányok tulajdonságaihoz állítható be Float.NaN.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Megkapja vagy beállítja az alakzat szélességét pontban mérve. Olvasható/írható float.

--------------------

A visszaadott érték mindig definiált és soha nem Float.NaN. A hozzárendelt értéknek is definiáltnak kell lennie; csak RawFrame példányok tulajdonságaihoz állítható be Float.NaN.

**Visszaad:**  
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Megkapja vagy beállítja az alakzat szélességét pontban mérve. Olvasható/írható float.

--------------------

A visszaadott érték mindig definiált és soha nem Float.NaN. A hozzárendelt értéknek is definiáltnak kell lennie; csak RawFrame példányok tulajdonságaihoz állítható be Float.NaN.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Megkapja vagy beállítja az alakzat magasságát pontban mérve. Olvasható/írható float.

--------------------

A visszaadott érték mindig definiált és soha nem Float.NaN. A hozzárendelt értéknek is definiáltnak kell lennie; csak RawFrame példányok tulajdonságaihoz állítható be Float.NaN.

**Visszaad:**  
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Megkapja vagy beállítja az alakzat magasságát pontban mérve. Olvasható/írható float.

--------------------

A visszaadott érték mindig definiált és soha nem Float.NaN. A hozzárendelt értéknek is definiáltnak kell lennie; csak RawFrame példányok tulajdonságaihoz állítható be Float.NaN.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```

A tulajdonság meghatározza, hogyan jelenik meg egy alakzat fekete-fehér megjelenítési módban. Olvasható/írható [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Visszaad:**  
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```

A tulajdonság meghatározza, hogyan jelenik meg egy alakzat fekete-fehér megjelenítési módban. Olvasható/írható [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```

Visszaad egy belső, a prezentációra korlátozott azonosítót, amelyet kiegészítők vagy egyéb kódok használhatnak. Mivel ezt az értéket a felhasználó vagy programkód módosíthatja, nem tekinthető állandó egyedi kulcsnak. Csak olvasható long. Lásd még #getOfficeInteropShapeId.getOfficeInteropShapeId.

**Visszaad:**  
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```

Visszaad egy diára korlátozott egyedi azonosítót, amely állandó a forma élettartama alatt, és lehetővé teszi a PowerPoint vagy interop kód számára, hogy megbízhatóan hivatkozzon a formára a dokumentum bármely pontjáról. Csak olvasható long. Lásd még #getUniqueId.getUniqueId.

**Visszaad:**  
long

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```

Visszaadja vagy beállítja a forma alternatív szövegét. Olvasható/írható String.

**Visszaad:**  
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```

Visszaadja vagy beállítja a forma alternatív szövegét. Olvasható/írható String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```

Visszaadja vagy beállítja a forma alternatív szövegének címét. Olvasható/írható String.

**Visszaad:**  
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```

Visszaadja vagy beállítja a forma alternatív szövegének címét. Olvasható/írható String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```

Visszaadja vagy beállítja egy forma nevét. Nem lehet null; ha szükséges, használjon üres karakterláncot. Olvasható/írható String.

**Visszaad:**  
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Visszaadja vagy beállítja egy forma nevét. Nem lehet null; ha szükséges, használjon üres karakterláncot. Olvasható/írható String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```

Megkapja vagy beállítja a 'Megjelölés dekoratívként' opciót Olvasás/írás boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszaad:**  
boolean

### setDecorative(boolean value) {#setDecorative-boolean-}
```
public final void setDecorative(boolean value)
```

Megkapja vagy beállítja a 'Megjelölés dekoratívként' opciót Olvasás/írás boolean.

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

Visszaadja a forma zárolásait. Csak olvasható [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Visszaad:**  
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```

Meghatározza, hogy a forma csoportosított-e. Csak olvasható boolean.

--------------------

A #getParentGroup.getParentGroup tulajdonság visszaadja a szülő GroupShape objektumot, ha a forma csoportosított.

**Visszaad:**  
boolean

### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Visszaadja a szülő GroupShape objektumot, ha a forma csoportosított. Egyébként null. Csak olvasható [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

A #isGrouped.isGrouped meghatározza, hogy a forma csoportosított-e.

**Visszaad:**  
[IGroupShape](../../com.aspose.slides/igroupshape)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaadja a Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszaad:**  
com.aspose.slides.IDOMObject

### getVisualBounds() {#getVisualBounds--}
```
public final RectF getVisualBounds()
```

Megkapja a forma vizuális határait, amelyeket a megjelenített tartalom alapján számítanak.

**Visszaad:**  
android.graphics.RectF - Egy android.graphics.RectF, amely a forma vizuális határait slide koordinátákban reprezentálja.

--------------------

A visszaadott téglalap a forma által a megjelenítés során előállított összes tartalom tengely-alapú határait tartalmazza slide koordináta-térben. Ezek a határok eltérhetnek a forma modell-határaitól (#getX.getX/#setX(float).setX(float), #getY.getY/#setY(float).setY(float), #getWidth.getWidth/#setWidth(float).setWidth(float), #getHeight.getHeight/#setHeight(float).setHeight(float)) és negatív koordinátákat is tartalmazhatnak, ha a megjelenített tartalom túlnyúlik a dia eredetén. A vizuális határok figyelembe veszik a megjelenítéssel kapcsolatos tényezőket, például a transzformációkat (pl. forgás), a vonalvastagságot és illesztéseket, a szöveg elrendezését és túlcsordulását, a SmartArt geometriai alakját, valamint egyéb elrendezési hatásokat, amelyek befolyásolják a forma végső megjelenését. A visszaadott határok nincsenek levágva a dia téglalapjára.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Visszaadja a forma szülő diáját. Csak olvasható [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Visszaad:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Visszaadja a dia szülő prezentációját. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszaad:**  
[IPresentation](../../com.aspose.slides/ipresentation)