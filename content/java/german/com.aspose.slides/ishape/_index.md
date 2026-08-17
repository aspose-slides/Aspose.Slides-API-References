---
title: IShape
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Form auf einer Folie dar.
type: docs
url: /de/com.aspose.slides/ishape/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IShape extends ISlideComponent, IHyperlinkContainer
```

Stellt eine Form auf einer Folie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Bestimmt, ob die Form ein TextHolder ist. |
| [getPlaceholder()](#getPlaceholder--) | Gibt den Platzhalter für eine Form zurück. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf einen angegebenen. |
| [removePlaceholder()](#removePlaceholder--) | Definiert, dass diese Form kein Platzhalter ist. |
| [getCustomData()](#getCustomData--) | Gibt die benutzerdefinierten Daten der Form zurück. |
| [getRawFrame()](#getRawFrame--) | Gibt die rohen Frame-Eigenschaften der Form zurück oder setzt sie. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Gibt die rohen Frame-Eigenschaften der Form zurück oder setzt sie. |
| [getFrame()](#getFrame--) | Gibt die Frame-Eigenschaften der Form zurück oder setzt sie. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Gibt die Frame-Eigenschaften der Form zurück oder setzt sie. |
| [getLineFormat()](#getLineFormat--) | Gibt das LineFormat-Objekt zurück, das die Linienformatierungseigenschaften für eine Form enthält. |
| [getThreeDFormat()](#getThreeDFormat--) | Gibt das ThreeDFormat-Objekt zurück, das die Linienformatierungseigenschaften für eine Form enthält. |
| [getEffectFormat()](#getEffectFormat--) | Gibt das EffectFormat-Objekt zurück, das Pixel-Effekte enthält, die auf eine Form angewendet werden. |
| [getFillFormat()](#getFillFormat--) | Gibt das FillFormat-Objekt zurück, das die Füllformatierungseigenschaften für eine Form enthält. |
| [getImage()](#getImage--) | Gibt das Miniaturbild der Form zurück. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Gibt das Miniaturbild der Form zurück. |
| [getHidden()](#getHidden--) | Bestimmt, ob die Form ausgeblendet ist. |
| [setHidden(boolean value)](#setHidden-boolean-) | Bestimmt, ob die Form ausgeblendet ist. |
| [getZOrderPosition()](#getZOrderPosition--) | Gibt die Position einer Form in der Z-Reihenfolge zurück. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Gibt die Anzahl der Verbindungsstellen an der Form zurück. |
| [getRotation()](#getRotation--) | Gibt die Anzahl der Grad zurück, um die die angegebene Form um die Z-Achse gedreht ist, oder setzt sie. |
| [setRotation(float value)](#setRotation-float-) | Gibt die Anzahl der Grad zurück, um die die angegebene Form um die Z-Achse gedreht ist, oder setzt sie. |
| [getX()](#getX--) | Liest oder setzt die x-Koordinate der linken oberen Ecke der Form, gemessen in Punkten. |
| [setX(float value)](#setX-float-) | Liest oder setzt die x-Koordinate der linken oberen Ecke der Form, gemessen in Punkten. |
| [getY()](#getY--) | Liest oder setzt die y-Koordinate der linken oberen Ecke der Form, gemessen in Punkten. |
| [setY(float value)](#setY-float-) | Liest oder setzt die y-Koordinate der linken oberen Ecke der Form, gemessen in Punkten. |
| [getWidth()](#getWidth--) | Liest oder setzt die Breite der Form, gemessen in Punkten. |
| [setWidth(float value)](#setWidth-float-) | Liest oder setzt die Breite der Form, gemessen in Punkten. |
| [getHeight()](#getHeight--) | Liest oder setzt die Höhe der Form, gemessen in Punkten. |
| [setHeight(float value)](#setHeight-float-) | Liest oder setzt die Höhe der Form, gemessen in Punkten. |
| [getAlternativeText()](#getAlternativeText--) | Gibt den alternativen Text, der mit einer Form verknüpft ist, zurück oder setzt ihn. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Gibt den alternativen Text, der mit einer Form verknüpft ist, zurück oder setzt ihn. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Gibt den Titel des alternativen Textes, der mit einer Form verknüpft ist, zurück oder setzt ihn. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Gibt den Titel des alternativen Textes, der mit einer Form verknüpft ist, zurück oder setzt ihn. |
| [getName()](#getName--) | Gibt den Namen einer Form zurück oder setzt ihn. |
| [setName(String value)](#setName-java.lang.String-) | Gibt den Namen einer Form zurück oder setzt ihn. |
| [isDecorative()](#isDecorative--) | Liest oder setzt die Option „Als dekorativ markieren“, Lesen/Schreiben boolesch. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Liest oder setzt die Option „Als dekorativ markieren“, Lesen/Schreiben boolesch. |
| [getShapeLock()](#getShapeLock--) | Gibt die Sperren der Form zurück. |
| [getUniqueId()](#getUniqueId--) | Gibt einen internen, präsentationsbezogenen Bezeichner zurück, der für die Verwendung durch Add-Ins oder anderen Code vorgesehen ist. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Gibt einen folienbezogenen eindeutigen Bezeichner zurück, der während der Lebensdauer der Form konstant bleibt und PowerPoint oder Interop-Code ermöglicht, die Form zuverlässig von überall im Dokument zu referenzieren. |
| [isGrouped()](#isGrouped--) | Bestimmt, ob die Form gruppiert ist. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Eigenschaft gibt an, wie eine Form im Schwarz-Weiß-Anzeigemodus gerendert wird. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Eigenschaft gibt an, wie eine Form im Schwarz-Weiß-Anzeigemodus gerendert wird. |
| [getParentGroup()](#getParentGroup--) | Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Speichert den Inhalt der Form als SVG-Datei. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Speichert den Inhalt der Form als SVG-Datei. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Gibt eine grundlegende Platzhalterform zurück (Form aus dem Layout und/oder der Masterfolie, von der die aktuelle Form geerbt wurde). |

### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```

Bestimmt, ob die Form ein TextHolder ist. Nur-Lesen boolesch.

**Rückgabe:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public abstract IPlaceholder getPlaceholder()
```

Gibt den Platzhalter für eine Form zurück. Nur-Lesen [IPlaceholder](../../com.aspose.slides/iplaceholder).

**Rückgabe:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public abstract IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und setzt die Platzhalter-Eigenschaften auf einen angegebenen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Platzhalter, von dem der Inhalt kopiert wird. |

**Rückgabe:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - Neu [IPlaceholder](../../com.aspose.slides/iplaceholder).

### removePlaceholder() {#removePlaceholder--}
```
public abstract void removePlaceholder()
```

Definiert, dass diese Form kein Platzhalter ist.

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Gibt die benutzerdefinierten Daten der Form zurück. Nur-Lesen [ICustomData](../../com.aspose.slides/icustomdata).

**Rückgabe:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public abstract IShapeFrame getRawFrame()
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
>  //Solcher Code kann zu unklaren Situationen führen. Deshalb wurden Beschränkungen für die Verwendung undefinierter Werte bei IShape.getFrame() hinzugefügt. Werte von x, y, width, height, flipH, flipV und rotationAngle müssen definiert sein (nicht Float.NaN oder NullableBool.NotDefined). Der obige Beispielcode wirft jetzt eine ArgumentException.
>  //Dies gilt für diese Anwendungsfälle:
>  IShape shape = ...;
>  shape.setFrame(...); // darf nicht undefiniert sein
>  IShapeCollection shapes = ...;
>  // x, y, width, height-Parameter dürfen nicht Float.NaN sein:
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
>  IShape shape = ...; // Form ist mit einem Platzhalter verknüpft
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // jetzt erbt die Form x, y, height, flipH, flipV-Werte vom Platzhalter und überschreibt width=100 und rotationAngle=0.
> ```

**Rückgabe:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
```

Gibt die rohen Frame-Eigenschaften der Form zurück oder setzt sie. Lesen/Schreiben [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code, der versucht, ein undefiniertes Frame an IShape.getFrame() zuzuweisen, ist im Allgemeinen nicht sinnvoll (insbesondere wenn das übergeordnete GroupShape mehrfach in andere GroupShape-s verschachtelt ist). Zum Beispiel:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //oder
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Solcher Code kann zu unklaren Situationen führen. Deshalb wurden Beschränkungen für die Verwendung undefinierter Werte bei IShape.getFrame() eingeführt. Werte von x, y, width, height, flipH, flipV und rotationAngle müssen definiert sein (nicht Float.NaN oder NullableBool.NotDefined). Der obige Beispielcode wirft jetzt eine ArgumentException.
>  //Dies gilt für die folgenden Anwendungsfälle:
>  IShape shape = ...;
>  shape.setFrame(...); // darf nicht undefiniert sein
>  IShapeCollection shapes = ...;
>  // x, y, width, height-Parameter dürfen nicht Float.NaN sein:
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
>  Aber IShape.RawFrame-Frame-Eigenschaften können undefiniert sein. Das ist sinnvoll, wenn die Form mit einem Platzhalter verknüpft ist. Dann werden undefinierte Frame-Werte vom übergeordneten Platzhalter überschrieben. Gibt es keinen übergeordneten Platzhalter für diese Form, verwendet die Form Standardwerte, wenn sie das effektive Frame basierend auf ihrem IShape.RawFrame berechnet. Standardwerte sind 0 und NullableBool.False für x, y, width, height, flipH, flipV und rotationAngle. Zum Beispiel:
>  IShape shape = ...; // Form ist mit einem Platzhalter verknüpft
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // jetzt erbt die Form x, y, height, flipH, flipV-Werte vom Platzhalter und überschreibt width=100 und rotationAngle=0.
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

Gibt die Frame-Eigenschaften der Form zurück oder setzt sie. Lesen/Schreiben [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Der Wert jeder Eigenschaft der zurückgegebenen IShapeFrame-Instanz ist nicht undefiniert (ist nicht NaN oder NotDefined). Der Wert jeder Eigenschaft der zugewiesenen IShapeFrame-Instanz muss nicht undefiniert sein (muss nicht NaN oder NotDefined sein). Sie können undefinierte Werte für Eigenschaften der RawFrame-Instanz festlegen.

**Rückgabe:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

Gibt die Frame-Eigenschaften der Form zurück oder setzt sie. Lesen/Schreiben [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Der Wert jeder Eigenschaft der zurückgegebenen IShapeFrame-Instanz ist nicht undefiniert (ist nicht NaN oder NotDefined). Der Wert jeder Eigenschaft der zugewiesenen IShapeFrame-Instanz muss nicht undefiniert sein (muss nicht NaN oder NotDefined sein). Sie können undefinierte Werte für Eigenschaften der RawFrame-Instanz festlegen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Gibt das LineFormat-Objekt zurück, das die Linienformatierungseigenschaften für eine Form enthält. Nur-Lesen [ILineFormat](../../com.aspose.slides/ilineformat).

**Rückgabe:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

Gibt das ThreeDFormat-Objekt zurück, das die Linienformatierungseigenschaften für eine Form enthält. Nur-Lesen [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Rückgabe:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Gibt das EffectFormat-Objekt zurück, das Pixel-Effekte enthält, die auf eine Form angewendet werden. Nur-Lesen [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Rückgabe:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Gibt das FillFormat-Objekt zurück, das die Füllformatierungseigenschaften für eine Form enthält. Nur-Lesen [IFillFormat](../../com.aspose.slides/ifillformat).

**Rückgabe:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Gibt das Miniaturbild der Form zurück. ShapeThumbnailBounds.Shape-Miniaturbild-Bounds-Typ wird standardmäßig verwendet.

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) - Miniaturbild der Form.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public abstract IImage getImage(int bounds, float scaleX, float scaleY)
```

Gibt das Miniaturbild der Form zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bounds | int | Miniaturbild-Bounds-Typ. |
| scaleX | float | X-Skalierung |
| scaleY | float | Y-Skalierung |

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) - Miniaturbild der Form oder null, falls ShapeThumbnailBounds.Appearance verwendet wird und die Form keine sichtbaren Elemente besitzt.

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Bestimmt, ob die Form ausgeblendet ist. Lesen/Schreiben boolesch.

**Rückgabe:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Bestimmt, ob die Form ausgeblendet ist. Lesen/Schreiben boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```

Gibt die Position einer Form in der Z-Reihenfolge zurück. Shapes[0] liefert die Form ganz hinten, Shapes[Shapes.Count - 1] die Form ganz vorne. Nur-Lesen int.

**Rückgabe:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```

Gibt die Anzahl der Verbindungsstellen an der Form zurück. Nur-Lesen int.

**Rückgabe:**
int

### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

Gibt die Anzahl der Grad zurück, um die die angegebene Form um die Z-Achse gedreht ist, oder setzt sie. Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Drehung gegen den Uhrzeigersinn. Lesen/Schreiben float.

--------------------

Der zurückgegebene Wert ist stets definiert (ist nicht Float.NaN). Der zugewiesene Wert muss ebenfalls definiert sein (nicht Float.NaN). Sie können undefinierte Werte für Eigenschaften einer RawFrame-Instanz festlegen.

**Rückgabe:**
float

### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```

Gibt die Anzahl der Grad zurück, um die die angegebene Form um die Z-Achse gedreht ist, oder setzt sie. Ein positiver Wert bedeutet Drehung im Uhrzeigersinn; ein negativer Wert bedeutet Drehung gegen den Uhrzeigersinn. Lesen/Schreiben float.

--------------------

Der zurückgegebene Wert ist stets definiert (ist nicht Float.NaN). Der zugewiesene Wert muss ebenfalls definiert sein (nicht Float.NaN). Sie können undefinierte Werte für Eigenschaften einer RawFrame-Instanz festlegen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public abstract float getX()
```

Liest oder setzt die x-Koordinate der linken oberen Ecke der Form, gemessen in Punkten. Lesen/Schreiben float.

--------------------

Der zurückgegebene Wert ist stets definiert und nie Float.NaN. Der zugewiesene Wert muss ebenfalls definiert sein; Float.NaN darf nur für Eigenschaften einer RawFrame-Instanz zugewiesen werden.

**Rückgabe:**
float

### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```

Liest oder setzt die x-Koordinate der linken oberen Ecke der Form, gemessen in Punkten. Lesen/Schreiben float.

--------------------

Der zurückgegebene Wert ist stets definiert und nie Float.NaN. Der zugewiesene Wert muss ebenfalls definiert sein; Float.NaN darf nur für Eigenschaften einer RawFrame-Instanz zugewiesen werden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public abstract float getY()
```

Liest oder setzt die y-Koordinate der linken oberen Ecke der Form, gemessen in Punkten. Lesen/Schreiben float.

--------------------

Der zurückgegebene Wert ist stets definiert und nie Float.NaN. Der zugewiesene Wert muss ebenfalls definiert sein; Float.NaN darf nur für Eigenschaften einer RawFrame-Instanz zugewiesen werden.

**Rückgabe:**
float

### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```

Liest oder setzt die y-Koordinate der linken oberen Ecke der Form, gemessen in Punkten. Lesen/Schreiben float.

--------------------

Der zurückgegebene Wert ist stets definiert und nie Float.NaN. Der zugewiesene Wert muss ebenfalls definiert sein; Float.NaN darf nur für Eigenschaften einer RawFrame-Instanz zugewiesen werden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

Liest oder setzt die Breite der Form, gemessen in Punkten. Lesen/Schreiben float.

--------------------

Der zurückgegebene Wert ist stets definiert und nie Float.NaN. Der zugewiesene Wert muss ebenfalls definiert sein; Float.NaN darf nur für Eigenschaften einer RawFrame-Instanz zugewiesen werden.

**Rückgabe:**
float

### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```

Liest oder setzt die Breite der Form, gemessen in Punkten. Lesen/Schreiben float.

--------------------

Der zurückgegebene Wert ist stets definiert und nie Float.NaN. Der zugewiesene Wert muss ebenfalls definiert sein; Float.NaN darf nur für Eigenschaften einer RawFrame-Instanz zugewiesen werden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Liest oder setzt die Höhe der Form, gemessen in Punkten. Lesen/Schreiben float.

--------------------

Der zurückgegebene Wert ist stets definiert und nie Float.NaN. Der zugewiesene Wert muss ebenfalls definiert sein; Float.NaN darf nur für Eigenschaften einer RawFrame-Instanz zugewiesen werden.

**Rückgabe:**
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Liest oder setzt die Höhe der Form, gemessen in Punkten. Lesen/Schreiben float.

--------------------

Der zurückgegebene Wert ist stets definiert und nie Float.NaN. Der zugewiesene Wert muss ebenfalls definiert sein; Float.NaN darf nur für Eigenschaften einer RawFrame-Instanz zugewiesen werden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getAlternativeText() {#getAlternativeText--}
```
public abstract String getAlternativeText()
```

Gibt den alternativen Text, der mit einer Form verknüpft ist, zurück oder setzt ihn. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public abstract void setAlternativeText(String value)
```

Gibt den alternativen Text, der mit einer Form verknüpft ist, zurück oder setzt ihn. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public abstract String getAlternativeTextTitle()
```

Gibt den Titel des alternativen Textes, der mit einer Form verknüpft ist, zurück oder setzt ihn. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public abstract void setAlternativeTextTitle(String value)
```

Gibt den Titel des alternativen Textes, der mit einer Form verknüpft ist, zurück oder setzt ihn. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public abstract String getName()
```

Gibt den Namen einer Form zurück oder setzt ihn. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Gibt den Namen einer Form zurück oder setzt ihn. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```

Liest oder setzt die Option „Als dekorativ markieren“, Lesen/Schreiben boolesch.

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
public abstract void setDecorative(boolean value)
```

Liest oder setzt die Option „Als dekorativ markieren“, Lesen/Schreiben boolesch.

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
public abstract IBaseShapeLock getShapeLock()
```

Gibt die Sperren der Form zurück. Nur-Lesen [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Rückgabe:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### getUniqueId() {#getUniqueId--}
```
public       
```

(Note: The provided answer seems incorrect.)

Gibt einen internen, präsentationsbezogenen Bezeichner zurück, der für die Verwendung durch Add-Ins oder anderen Code vorgesehen ist. Da dieser Wert vom Benutzer oder programmatisch neu zugewiesen werden kann, darf er nicht als dauerhaft eindeutiger Schlüssel behandelt werden. Nur-Lesen long. Siehe auch \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Rückgabe:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public abstract long getOfficeInteropShapeId()
```

Gibt einen folienbezogenen eindeutigen Bezeichner zurück, der während der Lebensdauer der Form konstant bleibt und PowerPoint oder Interop-Code ermöglicht, die Form zuverlässig von überall im Dokument zu referenzieren. Nur-Lesen long. Siehe auch \#getUniqueId.getUniqueId.

**Rückgabe:**
long

### isGrouped() {#isGrouped--}
```
public abstract boolean isGrouped()
```

Bestimmt, ob die Form gruppiert ist. Nur-Lesen boolean.

--------------------

Eigenschaft \#getParentGroup.getParentGroup gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist.

**Rückgabe:**
boolean

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public abstract byte getBlackWhiteMode()
```

Eigenschaft gibt an, wie eine Form im Schwarz-Weiß-Anzeigemodus gerendert wird. Lesen/Schreiben [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Rückgabe:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```

Eigenschaft gibt an, wie eine Form im Schwarz-Weiß-Anzeigemodus gerendert wird. Lesen/Schreiben [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Gibt das übergeordnete GroupShape-Objekt zurück, wenn die Form gruppiert ist. Andernfalls wird null zurückgegeben. Nur-Lesen [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

Eigenschaft \#isGrouped.isGrouped bestimmt, ob die Form gruppiert ist.

**Rückgabe:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

Speichert den Inhalt der Form als SVG-Datei.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Ziel-Stream |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Speichert den Inhalt der Form als SVG-Datei.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Ziel-Stream |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG-Erstellungs-Optionen |

### getBasePlaceholder() {#getBasePlaceholder--}
```
public abstract IShape getBasePlaceholder()
```

Gibt eine grundlegende Platzhalterform zurück (Form aus dem Layout und/oder der Masterfolie, von der die aktuelle Form geerbt wurde).

--------------------

> ```
> // alle (master/layout/slide) animierten Effekte der Platzhalterform erhalten
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

Ein null wird zurückgegeben, wenn die aktuelle Form nicht geerbt ist.

**Rückgabe:**
[IShape](../../com.aspose.slides/ishape)