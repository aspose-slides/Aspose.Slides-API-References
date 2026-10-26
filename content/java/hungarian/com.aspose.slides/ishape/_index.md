---
title: IShape
second_title: Aspose.Slides Java API referencia
description: Egy shape-et ábrázol egy dián.
type: docs
url: /hu/com.aspose.slides/ishape/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IShape extends ISlideComponent, IHyperlinkContainer
```

Egy alakzatot képvisel egy dián.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Megállapítja, hogy a shape TextHolder-e. |
| [getPlaceholder()](#getPlaceholder--) | Visszaadja a placeholder-t egy shape számára. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Új placeholder-t ad hozzá, ha nincs, és a placeholder tulajdonságait egy megadottra állítja. |
| [removePlaceholder()](#removePlaceholder--) | Meghatározza, hogy ez a shape nem placeholder. |
| [getCustomData()](#getCustomData--) | Visszaadja a shape egyéni adatait. |
| [getRawFrame()](#getRawFrame--) | Visszaadja vagy beállítja a raw shape frame tulajdonságait. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Visszaadja vagy beállítja a raw shape frame tulajdonságait. |
| [getFrame()](#getFrame--) | Visszaadja vagy beállítja a shape frame tulajdonságait. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Visszaadja vagy beállítja a shape frame tulajdonságait. |
| [getLineFormat()](#getLineFormat--) | Visszaadja a LineFormat objektumot, amely a shape vonalformázási tulajdonságait tartalmazza. |
| [getThreeDFormat()](#getThreeDFormat--) | Visszaadja a ThreeDFormat objektumot, amely a shape vonalformázási tulajdonságait tartalmazza. |
| [getEffectFormat()](#getEffectFormat--) | Visszaadja az EffectFormat objektumot, amely a shape-re alkalmazott pixel effektusokat tartalmazza. |
| [getFillFormat()](#getFillFormat--) | Visszaadja a FillFormat objektumot, amely a shape kitöltési tulajdonságait tartalmazza. |
| [getImage()](#getImage--) | Visszaadja a shape bélyegképét. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Visszaadja a shape bélyegképét. |
| [getHidden()](#getHidden--) | Megállapítja, hogy a shape rejtett-e. |
| [setHidden(boolean value)](#setHidden-boolean-) | Megállapítja, hogy a shape rejtett-e. |
| [getZOrderPosition()](#getZOrderPosition--) | Visszaadja a shape pozícióját a z-sorrendben. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Visszaadja a shape csatlakozási pontjainak számát. |
| [getRotation()](#getRotation--) | Visszaadja vagy beállítja a megadott shape z-tengely körüli forgatásának fokszámát. |
| [setRotation(float value)](#setRotation-float-) | Visszaadja vagy beállítja a megadott shape z-tengely körüli forgatásának fokszámát. |
| [getX()](#getX--) | Lekéri vagy beállítja a shape bal felső sarkának x-koordinátáját pontokban. |
| [setX(float value)](#setX-float-) | Lekéri vagy beállítja a shape bal felső sarkának x-koordinátáját pontokban. |
| [getY()](#getY--) | Lekéri vagy beállítja a shape bal felső sarkának y-koordinátáját pontokban. |
| [setY(float value)](#setY-float-) | Lekéri vagy beállítja a shape bal felső sarkának y-koordinátáját pontokban. |
| [getWidth()](#getWidth--) | Lekéri vagy beállítja a shape szélességét pontokban. |
| [setWidth(float value)](#setWidth-float-) | Lekéri vagy beállítja a shape szélességét pontokban. |
| [getHeight()](#getHeight--) | Lekéri vagy beállítja a shape magasságát pontokban. |
| [setHeight(float value)](#setHeight-float-) | Lekéri vagy beállítja a shape magasságát pontokban. |
| [getAlternativeText()](#getAlternativeText--) | Visszaadja vagy beállítja a shape-hez társított alternatív szöveget. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Visszaadja vagy beállítja a shape-hez társított alternatív szöveget. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Visszaadja vagy beállítja a shape-hez társított alternatív szöveg címét. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Visszaadja vagy beállítja a shape-hez társított alternatív szöveg címét. |
| [getName()](#getName--) | Visszaadja vagy beállítja egy shape nevét. |
| [setName(String value)](#setName-java.lang.String-) | Visszaadja vagy beállítja egy shape nevét. |
| [isDecorative()](#isDecorative--) | Lekéri vagy beállítja a 'Mark as decorative' opciót Olvasás/írás boolean. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Lekéri vagy beállítja a 'Mark as decorative' opciót Olvasás/írás boolean. |
| [getShapeLock()](#getShapeLock--) | Visszaadja a shape zárolásait. |
| [getUniqueId()](#getUniqueId--) | Visszaad egy belső, prezentációra korlátozott azonosítót, amelyet kiegészítők vagy más kód használhat. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Visszaad egy dia-szintű egyedi azonosítót, amely a shape élettartama alatt állandó, és lehetővé teszi a PowerPoint vagy interop kód számára a shape megbízható hivatkozását a dokumentum bármely részéről. |
| [isGrouped()](#isGrouped--) | Megállapítja, hogy a shape csoportosított-e. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | A tulajdonság meghatározza, hogyan jelenik meg a shape fekete-fehér megjelenítési módban. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | A tulajdonság meghatározza, hogyan jelenik meg a shape fekete-fehér megjelenítési módban. |
| [getParentGroup()](#getParentGroup--) | Visszaadja a szülő GroupShape objektumot, ha a shape csoportosított. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Elmenti a Shape tartalmát SVG fájlként. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Elmenti a Shape tartalmát SVG fájlként. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Visszaad egy alap placeholder shape-et (a layoutból és/vagy master diából származó shape, amelyről a jelenlegi shape örököl). |

### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```

Megállapítja, hogy a shape TextHolder-e. Csak olvasható boolean.

**Visszatér:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public abstract IPlaceholder getPlaceholder()
```

Visszaadja a placeholder-t egy shape számára. Csak olvasható [IPlaceholder](../../com.aspose.slides/iplaceholder).

**Visszatér:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public abstract IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Új placeholder-t ad hozzá, ha nincs, és a placeholder tulajdonságait egy megadottra állítja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Placeholder, amelyből a tartalmat másolni kell. |

**Visszatér:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - Új [IPlaceholder](../../com.aspose.slides/iplaceholder).

### removePlaceholder() {#removePlaceholder--}
```
public abstract void removePlaceholder()
```

Meghatározza, hogy ez a shape nem placeholder.

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Visszaadja a shape egyéni adatait. Csak olvasható [ICustomData](../../com.aspose.slides/icustomdata).

**Visszatér:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public abstract IShapeFrame getRawFrame()
```

Visszaadja vagy beállítja a raw shape frame tulajdonságait. Olvasás/írás [IShapeFrame](../../com.aspose.slides/ishapeframe).

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
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // shape is linked to placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // now shape inherits x, y, height, flipH, flipV values form placeholder and overrides width=100 and rotationAngle=0.
> ```

**Visszatér:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
```

Visszaadja vagy beállítja a raw shape frame tulajdonságait. Olvasás/írás [IShapeFrame](../../com.aspose.slides/ishapeframe).

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
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // shape is linked to placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // now shape inherits x, y, height, flipH, flipV values form placeholder and overrides width=100 and rotationAngle=0.
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

Visszaadja vagy beállítja a shape frame tulajdonságait. Olvasás/írás [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Az IShapeFrame példány minden visszaadott tulajdonságának értéke definiált (nem NaN vagy NotDefined). A hozzárendelt IShapeFrame példány minden tulajdonságának értéke szintén definiált kell legyen (nem NaN vagy NotDefined). A RawFrame példány tulajdonságainak undefined értékeit nem lehet beállítani.

**Visszatér:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

Visszaadja vagy beállítja a shape frame tulajdonságait. Olvasás/írás [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Az IShapeFrame példány minden visszaadott tulajdonságának értéke definiált (nem NaN vagy NotDefined). A hozzárendelt IShapeFrame példány minden tulajdonságának értéke szintén definiált kell legyen (nem NaN vagy NotDefined). A RawFrame példány tulajdonságainak undefined értékeit nem lehet beállítani.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Visszaadja a LineFormat objektumot, amely a shape vonalformázási tulajdonságait tartalmazza. Csak olvasható [ILineFormat](../../com.aspose.slides/ilineformat).

**Visszatér:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

Visszaadja a ThreeDFormat objektumot, amely a shape vonalformázási tulajdonságait tartalmazza. Csak olvasható [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Visszatér:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Visszaadja az EffectFormat objektumot, amely a shape-re alkalmazott pixel effektusokat tartalmazza. Csak olvasható [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Visszatér:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Visszaadja a FillFormat objektumot, amely a shape kitöltési tulajdonságait tartalmazza. Csak olvasható [IFillFormat](../../com.aspose.slides/ifillformat).

**Visszatér:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Visszaadja a shape bélyegképét. ShapeThumbnailBounds.Shape shape thumbnail bounds type az alapértelmezett.

**Visszatér:**
[IImage](../../com.aspose.slides/iimage) – Shape bélyegkép.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public abstract IImage getImage(int bounds, float scaleX, float scaleY)
```

Visszaadja a shape bélyegképét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bounds | int | Shape thumbnail bounds típus. |
| scaleX | float | X skála |
| scaleY | float | Y skála |

**Visszatér:**
[IImage](../../com.aspose.slides/iimage) – Shape bélyegkép vagy null, ha a ShapeThumbnailBounds.Appearance van használva és a shape nem rendelkezik látható elemekkel.

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Megállapítja, hogy a shape rejtett-e. Olvasás/írás boolean.

**Visszatér:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Megállapítja, hogy a shape rejtett-e. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```

Visszaadja a shape pozícióját a z-sorrendben. A Shapes[0] a z-sorrend hátuljában lévő shape-t adja, a Shapes[Shapes.Count-1] pedig az elöl lévőt. Csak olvasható int.

**Visszatér:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```

Visszaadja a shape csatlakozási pontjainak számát. Csak olvasható int.

**Visszatér:**
int

### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

Visszaadja vagy beállítja a megadott shape z-tengely körüli forgatásának fokszámát. Pozitív érték óramutató járásával megegyező forgást jelez; negatív érték az ellenkező irányt. Olvasás/írás float.

--------------------

A visszaadott érték mindig definiált (nem Float.NaN). A hozzárendelt értéknek is definiáltnak kell lennie (nem Float.NaN). A RawFrame példány tulajdonságainak undefined értékei beállíthatók.

**Visszatér:**
float

### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```

Visszaadja vagy beállítja a megadott shape z-tengely körüli forgatásának fokszámát. Pozitív érték óramutató járásával megegyező forgást jelez; negatív érték az ellenkező irányt. Olvasás/írás float.

--------------------

A visszaadott érték mindig definiált (nem Float.NaN). A hozzárendelt értéknek is definiáltnak kell lennie (nem Float.NaN). A RawFrame példány tulajdonságainak undefined értékei beállíthatók.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public abstract float getX()
```

Lekéri vagy beállítja a shape bal felső sarkának x-koordinátáját pontokban. Olvasás/írás float.

--------------------

A visszaadott érték mindig definiált és soha nem Float.NaN. A hozzárendelt értéknek is definiáltnak kell lennie; Float.NaN-t csak RawFrame példányok tulajdonságainak állíthatja be.

**Visszatér:**
float

### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```

Lekéri vagy beállítja a shape bal felső sarkának x-koordinátáját pontokban. Olvasás/írás float.

--------------------

A visszaadott érték mindig definiált és soha nem Float.NaN. A hozzárendelt értéknek is definiáltnak kell lennie; Float.NaN-t csak RawFrame példányok tulajdonságainak állíthatja be.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public abstract float getY()
```

Lekéri vagy beállítja a shape bal felső sarkának y-koordinátáját pontokban. Olvasás/írás float.

--------------------

A visszaadott érték mindig definiált és soha nem Float.NaN. A hozzárendelt értéknek is definiáltnak kell lennie; Float.NaN-t csak RawFrame példányok tulajdonságainak állíthatja be.

**Visszatér:**
float

### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```

Lekéri vagy beállítja a shape bal felső sarkának y-koordinátáját pontokban. Olvasás/írás float.

--------------------

A visszaadott érték mindig definiált és soha nem Float.NaN. A hozzárendelt értéknek is definiáltnak kell lennie; Float.NaN-t csak RawFrame példányok tulajdonságainak állíthatja be.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

Lekéri vagy beállítja a shape szélességét pontokban. Olvasás/írás float.

--------------------

A visszaadott érték mindig definiált és soha nem Float.NaN. A hozzárendelt értéknek is definiáltnak kell lennie; Float.NaN-t csak RawFrame példányok tulajdonságainak állíthatja be.

**Visszatér:**
float

### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```

Lekéri vagy beállítja a shape szélességét pontokban. Olvasás/írás float.

--------------------

A visszaadott érték mindig definiált és soha nem Float.NaN. A hozzárendelt értéknek is definiáltnak kell lennie; Float.NaN-t csak RawFrame példányok tulajdonságainak állíthatja be.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Lekéri vagy beállítja a shape magasságát pontokban. Olvasás/írás float.

--------------------

A visszaadott érték mindig definiált és soha nem Float.NaN. A hozzárendelt értéknek is definiáltnak kell lennie; Float.NaN-t csak RawFrame példányok tulajdonságainak állíthatja be.

**Visszatér:**
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Lekéri vagy beállítja a shape magasságát pontokban. Olvasás/írás float.

--------------------

A visszaadott érték mindig definiált és soha nem Float.NaN. A hozzárendelt értéknek is definiáltnak kell lennie; Float.NaN-t csak RawFrame példányok tulajdonságainak állíthatja be.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getAlternativeText() {#getAlternativeText--}
```
public abstract String getAlternativeText()
```

Visszaadja vagy beállítja a shape-hez társított alternatív szöveget. Olvasás/írás String.

**Visszatér:**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public abstract void setAlternativeText(String value)
```

Visszaadja vagy beállítja a shape-hez társított alternatív szöveget. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public abstract String getAlternativeTextTitle()
```

Visszaadja vagy beállítja a shape-hez társított alternatív szöveg címét. Olvasás/írás String.

**Visszatér:**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public abstract void setAlternativeTextTitle(String value)
```

Visszaadja vagy beállítja a shape-hez társított alternatív szöveg címét. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public abstract String getName()
```

Visszaadja vagy beállítja egy shape nevét. Olvasás/írás String.

**Visszatér:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Visszaadja vagy beállítja egy shape nevét. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```

Lekéri vagy beállítja a 'Mark as decorative' opciót Olvasás/írás boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatér:**
boolean

### setDecorative(boolean value) {#setDecorative-boolean-}
```
public abstract void setDecorative(boolean value)
```

Lekéri vagy beállítja a 'Mark as decorative' opciót Olvasás/írás boolean.

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
public abstract IBaseShapeLock getShapeLock()
```

Visszaadja a shape zárolásait. Csak olvasható [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Visszatér:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### getUniqueId() {#getUniqueId--}
```
public abstract long getUniqueId()
```

Visszaad egy belső, prezentációra korlátozott azonosítót, amelyet kiegészítők vagy más kód használhat. Mivel ezt az értéket a felhasználó vagy programozottan felülírhatja, nem tekinthető állandó egyedi kulcsnak. Csak olvasható long. Lásd még \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Visszatér:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public abstract long getOfficeInteropShapeId()
```

Visszaad egy dia-szintű egyedi azonosítót, amely a shape élettartama alatt állandó, és lehetővé teszi a PowerPoint vagy interop kód számára a shape megbízható hivatkozását a dokumentum bármely részéről. Csak olvasható long. Lásd még \#getUniqueId.getUniqueId.

**Visszatér:**
long

### isGrouped() {#isGrouped--}
```
public abstract boolean isGrouped()
```

Megállapítja, hogy a shape csoportosított-e. Csak olvasható boolean.

--------------------

A \#getParentGroup.getParentGroup tulajdonság visszaadja a szülő GroupShape objektumot, ha a shape csoportosított.

**Visszatér:**
boolean

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public abstract byte getBlackWhiteMode()
```

A tulajdonság meghatározza, hogyan jelenik meg a shape fekete-fehér megjelenítési módban. Olvasás/írás [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Visszatér:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```

A tulajdonság meghatározza, hogyan jelenik meg a shape fekete-fehér megjelenítési módban. Olvasás/írás [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Visszaadja a szülő GroupShape objektumot, ha a shape csoportosított. Ellenkező esetben null. Csak olvasható [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

A \#isGrouped.isGrouped tulajdonság meghatározza, hogy a shape csoportosított-e.

**Visszatér:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

Elmenti a Shape tartalmát SVG fájlként.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Cél stream |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Elmenti a Shape tartalmát SVG fájlként.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Cél stream |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG generálási beállítások |

### getBasePlaceholder() {#getBasePlaceholder--}
```
public abstract IShape getBasePlaceholder()
```

Visszaad egy alap placeholder shape-et (a layoutból és/vagy master diából származó shape, amelyről a jelenlegi shape örököl).

--------------------

> ```
> // az összes (master/layout/slide) animált effektust a placeholder shape-hez lekérdezi
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

Ha a jelenlegi shape nem örököl, null érték kerül visszaadásra.

**Visszatér:**
[IShape](../../com.aspose.slides/ishape)