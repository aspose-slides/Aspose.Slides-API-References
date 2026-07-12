---
title: IShape
second_title: Aspose.Slides für Android über Java API-Referenz
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
| [isTextHolder()](#isTextHolder--) | Ermittelt, ob die Form ein TextHolder ist. |
| [getPlaceholder()](#getPlaceholder--) | Gibt den Platzhalter für eine Form zurück. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und legt Platzhaltereigenschaften auf einen angegebenen fest. |
| [removePlaceholder()](#removePlaceholder--) | Definiert, dass diese Form kein Platzhalter ist. |
| [getCustomData()](#getCustomData--) | Gibt die benutzerdefinierten Daten der Form zurück. |
| [getRawFrame()](#getRawFrame--) | Gibt die Rohrahmeneigenschaften der Form zurück oder legt sie fest. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Gibt die Rohrahmeneigenschaften der Form zurück oder legt sie fest. |
| [getFrame()](#getFrame--) | Gibt die Formrahmeneigenschaften zurück oder legt sie fest. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Gibt die Formrahmeneigenschaften zurück oder legt sie fest. |
| [getLineFormat()](#getLineFormat--) | Gibt das LineFormat-Objekt zurück, das Linienformatierungs-Eigenschaften für eine Form enthält. |
| [getThreeDFormat()](#getThreeDFormat--) | Gibt das ThreeDFormat-Objekt zurück, das Linienformatierungs-Eigenschaften für eine Form enthält. |
| [getEffectFormat()](#getEffectFormat--) | Gibt das EffectFormat-Objekt zurück, das Pixel-Effekte auf eine Form anwendet. |
| [getFillFormat()](#getFillFormat--) | Gibt das FillFormat-Objekt zurück, das Füllungsformatierungs-Eigenschaften für eine Form enthält. |
| [getImage()](#getImage--) | Gibt das Form-Thumbnail zurück. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Gibt das Form-Thumbnail zurück. |
| [getHidden()](#getHidden--) | Ermittelt, ob die Form ausgeblendet ist. |
| [setHidden(boolean value)](#setHidden-boolean-) | Ermittelt, ob die Form ausgeblendet ist. |
| [getZOrderPosition()](#getZOrderPosition--) | Gibt die Position einer Form in der Z-Reihenfolge zurück. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Gibt die Anzahl der Verbindungsstellen an der Form zurück. |
| [getRotation()](#getRotation--) | Gibt den Drehwinkel der angegebenen Form um die Z-Achse zurück oder legt ihn fest. |
| [setRotation(float value)](#setRotation-float-) | Gibt den Drehwinkel der angegebenen Form um die Z-Achse zurück oder legt ihn fest. |
| [getX()](#getX--) | Gibt die X-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest (gemessen in Punkten). |
| [setX(float value)](#setX-float-) | Gibt die X-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest (gemessen in Punkten). |
| [getY()](#getY--) | Gibt die Y-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest (gemessen in Punkten). |
| [setY(float value)](#setY-float-) | Gibt die Y-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest (gemessen in Punkten). |
| [getWidth()](#getWidth--) | Gibt die Breite der Form zurück oder legt sie fest (gemessen in Punkten). |
| [setWidth(float value)](#setWidth-float-) | Gibt die Breite der Form zurück oder legt sie fest (gemessen in Punkten). |
| [getHeight()](#getHeight--) | Gibt die Höhe der Form zurück oder legt sie fest (gemessen in Punkten). |
| [setHeight(float value)](#setHeight-float-) | Gibt die Höhe der Form zurück oder legt sie fest (gemessen in Punkten). |
| [getAlternativeText()](#getAlternativeText--) | Gibt den Alternativtext einer Form zurück oder legt ihn fest. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Gibt den Alternativtext einer Form zurück oder legt ihn fest. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Gibt den Titel des Alternativtexts einer Form zurück oder legt ihn fest. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Gibt den Titel des Alternativtexts einer Form zurück oder legt ihn fest. |
| [getName()](#getName--) | Gibt den Namen einer Form zurück oder legt ihn fest. |
| [setName(String value)](#setName-java.lang.String-) | Gibt den Namen einer Form zurück oder legt ihn fest. |
| [isDecorative()](#isDecorative--) | Gibt die Option „Als dekorativ markieren“ zurück oder legt sie fest (Lese/Schreib-boolesch). |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Gibt die Option „Als dekorativ markieren“ zurück oder legt sie fest (Lese/Schreib-boolesch). |
| [getShapeLock()](#getShapeLock--) | Gibt die Sperren der Form zurück. |
| [getUniqueId()](#getUniqueId--) | Gibt eine interne, präsentationsbezogene Kennung zurück, die für Add-Ins oder anderen Code vorgesehen ist. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Gibt eine folienbezogene eindeutige Kennung zurück, die für die Lebensdauer der Form konstant bleibt und PowerPoint oder Interop-Code erlaubt, die Form zuverlässig zu referenzieren. |
| [isGrouped()](#isGrouped--) | Ermittelt, ob die Form gruppiert ist. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Gibt an, wie die Form im Schwarz-weiß-Anzeige-Modus gerendert wird. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Gibt an, wie die Form im Schwarz-weiß-Anzeige-Modus gerendert wird. |
| [getParentGroup()](#getParentGroup--) | Gibt das übergeordnete GroupShape-Objekt zurück, falls die Form gruppiert ist. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Speichert den Inhalt der Form als SVG-Datei. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Speichert den Inhalt der Form als SVG-Datei. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Gibt eine Basis-Platzhalter-Form zurück (Form aus Layout- und/oder Master-Folie, von der die aktuelle Form erbt). |

### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```

Ermittelt, ob die Form ein TextHolder ist. Nur-Lese boolesch.

**Rückgabe:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public abstract IPlaceholder getPlaceholder()
```

Gibt den Platzhalter für eine Form zurück. Nur-Lese [IPlaceholder](../../com.aspose.slides/iplaceholder).

**Rückgabe:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public abstract IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Fügt einen neuen Platzhalter hinzu, falls keiner vorhanden ist, und legt Platzhaltereigenschaften auf einen angegebenen fest.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Platzhalter, von dem der Inhalt kopiert werden soll. |

**Rückgabe:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) – neue [IPlaceholder](../../com.aspose.slides/iplaceholder).

### removePlaceholder() {#removePlaceholder--}
```
public abstract void removePlaceholder()
```

Definiert, dass diese Form kein Platzhalter ist.

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Gibt die benutzerdefinierten Daten der Form zurück. Nur-Lese [ICustomData](../../com.aspose.slides/icustomdata).

**Rückgabe:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public abstract IShapeFrame getRawFrame()
```

Gibt die Rohrahmeneigenschaften der Form zurück oder legt sie fest. Lese/Schreib [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code, der versucht, einen undefinierten Frame an IShape.getFrame() zuzuweisen, ergibt im allgemeinen Fall keinen Sinn (insbesondere wenn das übergeordnete GroupShape mehrfach in andere GroupShape(s) verschachtelt ist). Zum Beispiel:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //oder
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Solcher Code kann zu unklaren Situationen führen. Daher wurden Einschränkungen für die Verwendung undefinierter Werte bei IShape.getFrame() hinzugefügt. Werte von x, y, width, height, flipH, flipV und rotationAngle müssen definiert sein (nicht Float.NaN oder NullableBool.NotDefined). Das obige Beispielcode wirft jetzt eine ArgumentException.
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
>  Doch die Eigenschaften des IShape.RawFrame-Frames können undefiniert sein. Das ist sinnvoll, wenn die Form mit einem Platzhalter verknüpft ist. Dann werden die undefinierten Frame-Werte vom übergeordneten Platzhalter-Shape überschrieben. Gibt es keinen übergeordneten Platzhalter-Shape für diese Form, verwendet die Form Standardwerte, wenn sie den effektiven Frame basierend auf ihrem IShape.RawFrame berechnet. Standardwerte sind 0 und NullableBool.False für x, y, width, height, flipH, flipV und rotationAngle. Zum Beispiel:
>  IShape shape = ...; // Form ist mit einem Platzhalter verknüpft
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // Jetzt erbt die Form Werte für x, y, height, flipH, flipV vom Platzhalter und überschreibt width=100 und rotationAngle=0.
```

**Rückgabe:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
```

Gibt die Rohrahmeneigenschaften der Form zurück oder legt sie fest. Lese/Schreib [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //oder
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Solcher Code kann zu unklaren Situationen führen. Daher wurden Einschränkungen für die Verwendung undefinierter Werte bei IShape.getFrame() hinzugefügt. Werte von x, y, width, height, flipH, flipV und rotationAngle müssen definiert sein (nicht Float.NaN oder NullableBool.NotDefined). Der obige Beispielcode wirft jetzt eine ArgumentException.
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
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // Form ist mit einem Platzhalter verknüpft
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // jetzt erbt die Form x-, y-, height-, flipH-, flipV-Werte vom Platzhalter und überschreibt width=100 und rotationAngle=0.
```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

Gibt die Formrahmeneigenschaften zurück oder legt sie fest. Lese/Schreib [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Der Wert jeder Eigenschaft der zurückgegebenen IShapeFrame-Instanz ist definiert (ist nicht NaN oder NotDefined). Der Wert jeder Eigenschaft der zugewiesenen IShapeFrame-Instanz muss definiert sein (darf nicht NaN oder NotDefined sein). Sie können undefinierte Werte für Rohrahmen-Instanz-Eigenschaften setzen.

**Rückgabe:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

Gibt die Formrahmeneigenschaften zurück oder legt sie fest. Lese/Schreib [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Der Wert jeder Eigenschaft der zurückgegebenen IShapeFrame-Instanz ist definiert (ist nicht NaN oder NotDefined). Der Wert jeder Eigenschaft der zugewiesenen IShapeFrame-Instanz muss definiert sein (darf nicht NaN oder NotDefined sein). Sie können undefinierte Werte für Rohrahmen-Instanz-Eigenschaften setzen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Gibt das LineFormat-Objekt zurück, das Linienformatierungs-Eigenschaften für eine Form enthält. Nur-Lese [ILineFormat](../../com.aspose.slides/ilineformat).

**Rückgabe:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

Gibt das ThreeDFormat-Objekt zurück, das Linienformatierungs-Eigenschaften für eine Form enthält. Nur-Lese [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Rückgabe:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Gibt das EffectFormat-Objekt zurück, das Pixel-Effekte auf eine Form anwendet. Nur-Lese [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Rückgabe:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Gibt das FillFormat-Objekt zurück, das Füllungsformatierungs-Eigenschaften für eine Form enthält. Nur-Lese [IFillFormat](../../com.aspose.slides/ifillformat).

**Rückgabe:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Gibt das Form-Thumbnail zurück. ShapeThumbnailBounds.Shape-Form-Thumbnail-Bounds-Typ wird standardmäßig verwendet.

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) – Form-Thumbnail.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public abstract IImage getImage(int bounds, float scaleX, float scaleY)
```

Gibt das Form-Thumbnail zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bounds | int | Typ der Form-Thumbnail-Bounds. |
| scaleX | float | X-Skalierung |
| scaleY | float | Y-Skalierung |

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) – Form-Thumbnail oder null, falls ShapeThumbnailBounds.Appearance verwendet wird und die Form keine sichtbaren Elemente hat.

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Ermittelt, ob die Form ausgeblendet ist. Lese/Schreib boolesch.

**Rückgabe:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Ermittelt, ob die Form ausgeblendet ist. Lese/Schreib boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```

Gibt die Position einer Form in der Z-Reihenfolge zurück. Shapes[0] gibt die Form am hinteren Ende der Z-Reihenfolge zurück, Shapes[Shapes.Count - 1] die Form am vorderen Ende. Nur-Lese int.

**Rückgabe:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```

Gibt die Anzahl der Verbindungsstellen an der Form zurück. Nur-Lese int.

**Rückgabe:**
int

### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

Gibt den Drehwinkel der angegebenen Form um die Z-Achse zurück oder legt ihn fest. Ein positiver Wert bedeutet Drehen im Uhrzeigersinn; ein negativer Wert bedeutet Drehen gegen den Uhrzeigersinn. Lese/Schreib float.

--------------------

Der zurückgegebene Wert ist stets definiert (ist nicht Float.NaN). Der zugewiesene Wert muss definiert sein (nicht Float.NaN). Sie können undefinierte Werte für Rohrahmen-Instanz-Eigenschaften setzen.

**Rückgabe:**
float

### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```

Legt den Drehwinkel der angegebenen Form um die Z-Achse fest oder gibt ihn zurück. Ein positiver Wert bedeutet Drehen im Uhrzeigersinn; ein negativer Wert bedeutet Drehen gegen den Uhrzeigersinn. Lese/Schreib float.

--------------------

Der zurückgegebene Wert ist stets definiert (ist nicht Float.NaN). Der zugewiesene Wert muss definiert sein (nicht Float.NaN). Sie können undefinierte Werte für Rohrahmen-Instanz-Eigenschaften setzen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public abstract float getX()
```

Gibt die X-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest (gemessen in Punkten). Lese/Schreib float.

--------------------

Der zurückgegebene Wert ist stets definiert und nie Float.NaN. Der zugewiesene Wert muss ebenfalls definiert sein; Float.NaN darf nur bei Eigenschaften einer Rohrahmen-Instanz zugewiesen werden.

**Rückgabe:**
float

### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```

Setzt die X-Koordinate der oberen linken Ecke der Form (gemessen in Punkten) oder gibt sie zurück. Lese/Schreib float.

--------------------

Der zurückgegebene Wert ist stets definiert und nie Float.NaN. Der zugewiesene Wert muss ebenfalls definiert sein; Float.NaN darf nur bei Eigenschaften einer Rohrahmen-Instanz zugewiesen werden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public abstract float getY()
```

Gibt die Y-Koordinate der oberen linken Ecke der Form zurück oder legt sie fest (gemessen in Punkten). Lese/Schreib float.

--------------------

Der zurückgegebene Wert ist stets definiert und nie Float.NaN. Der zugewiesene Wert muss ebenfalls definiert sein; Float.NaN darf nur bei Eigenschaften einer Rohrahmen-Instanz zugewiesen werden.

**Rückgabe:**
float

### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```

Setzt die Y-Koordinate der oberen linken Ecke der Form (gemessen in Punkten) oder gibt sie zurück. Lese/Schreib float.

--------------------

Der zurückgegebene Wert ist stets definiert und nie Float.NaN. Der zugewiesene Wert muss ebenfalls definiert sein; Float.NaN darf nur bei Eigenschaften einer Rohrahmen-Instanz zugewiesen werden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

Gibt die Breite der Form zurück oder legt sie fest (gemessen in Punkten). Lese/Schreib float.

--------------------

Der zurückgegebene Wert ist stets definiert und nie Float.NaN. Der zugewiesene Wert muss ebenfalls definiert sein; Float.NaN darf nur bei Eigenschaften einer Rohrahmen-Instanz zugewiesen werden.

**Rückgabe:**
float

### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```

Setzt die Breite der Form (gemessen in Punkten) oder gibt sie zurück. Lese/Schreib float.

--------------------

Der zurückgegebene Wert ist stets definiert und nie Float.NaN. Der zugewiesene Wert muss ebenfalls definiert sein; Float.NaN darf nur bei Eigenschaften einer Rohrahmen-Instanz zugewiesen werden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Gibt die Höhe der Form zurück oder legt sie fest (gemessen in Punkten). Lese/Schreib float.

--------------------

Der zurückgegebene Wert ist stets definiert und nie Float.NaN. Der zugewiesene Wert muss ebenfalls definiert sein; Float.NaN darf nur bei Eigenschaften einer Rohrahmen-Instanz zugewiesen werden.

**Rückgabe:**
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Setzt die Höhe der Form (gemessen in Punkten) oder gibt sie zurück. Lese/Schreib float.

--------------------

Der zurückgegebene Wert ist stets definiert und nie Float.NaN. Der zugewiesene Wert muss ebenfalls definiert sein; Float.NaN darf nur bei Eigenschaften einer Rohrahmen-Instanz zugewiesen werden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getAlternativeText() {#getAlternativeText--}
```
public abstract String getAlternativeText()
```

Gibt den Alternativtext einer Form zurück oder legt ihn fest. Lese/Schreib String.

**Rückgabe:**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public abstract void setAlternativeText(String value)
```

Setzt den Alternativtext einer Form oder gibt ihn zurück. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public abstract String getAlternativeTextTitle()
```

Gibt den Titel des Alternativtexts einer Form zurück oder legt ihn fest. Lese/Schreib String.

**Rückgabe:**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public abstract void setAlternativeTextTitle(String value)
```

Setzt den Titel des Alternativtexts einer Form oder gibt ihn zurück. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public abstract String getName()
```

Gibt den Namen einer Form zurück oder legt ihn fest. Lese/Schreib String.

**Rückgabe:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Setzt den Namen einer Form oder gibt ihn zurück. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```

Gibt die Option „Als dekorativ markieren“ zurück oder legt sie fest. Lese/Schreib boolesch.

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

Setzt die Option „Als dekorativ markieren“ oder gibt sie zurück. Lese/Schreib boolesch.

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

Gibt die Sperren der Form zurück. Nur-Lese [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Rückgabe:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### getUniqueId() {#getUniqueId--}
```
public abstract long getUniqueId()
```

Gibt eine interne, präsentationsbezogene Kennung zurück, die für Add-Ins oder anderen Code vorgesehen ist. Da dieser Wert vom Benutzer oder programmatisch geändert werden kann, darf er nicht als persistenter eindeutiger Schlüssel verwendet werden. Nur-Lese long. Siehe auch \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Rückgabe:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public
```

Gibt eine folienbezogene eindeutige Kennung zurück, die für die Lebensdauer der Form konstant bleibt und PowerPoint oder Interop-Code erlaubt, die Form zuverlässig zu referenzieren. Nur-Lese long. Siehe auch \#getUniqueId.getUniqueId.

**Rückgabe:**
long

### isGrouped() {#isGrouped--}
```
public abstract boolean isGrouped()
```

Ermittelt, ob die Form gruppiert ist. Nur-Lese boolesch.

--------------------

Die Eigenschaft \#getParentGroup.getParentGroup gibt das übergeordnete GroupShape-Objekt zurück, falls die Form gruppiert ist.

**Rückgabe:**
boolean

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public abstract byte getBlackWhiteMode()
```

Die Eigenschaft gibt an, wie die Form im Schwarz-weiß-Anzeige-Modus gerendert wird. Lese/Schreib [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Rückgabe:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```

Die Eigenschaft gibt an, wie die Form im Schwarz-weiß-Anzeige-Modus gerendert wird. Lese/Schreib [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Gibt das übergeordnete GroupShape-Objekt zurück, falls die Form gruppiert ist. Andernfalls wird null zurückgegeben. Nur-Lese [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

Die Eigenschaft \#isGrouped.isGrouped bestimmt, ob die Form gruppiert ist.

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
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Optionen zur SVG-Erstellung |

### getBasePlaceholder() {#getBasePlaceholder--}
```
public abstract IShape getBasePlaceholder()
```

Gibt eine Basis-Platzhalter-Form zurück (Form aus Layout- und/oder Master-Folie, von der die aktuelle Form erbt).

--------------------

> ```
> // alle (master/layout/slide) animierten Effekte der Platzhalter-Form abrufen
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

Ein null wird zurückgegeben, wenn die aktuelle Form nicht geerbt wird.

**Rückgabe:**
[IShape](../../com.aspose.slides/ishape)