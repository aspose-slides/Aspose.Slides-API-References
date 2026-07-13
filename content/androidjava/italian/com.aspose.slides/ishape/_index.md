---
title: IShape
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Rappresenta una forma su una diapositiva.
type: docs
url: /it/com.aspose.slides/ishape/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IShape extends ISlideComponent, IHyperlinkContainer
```

Rappresenta una forma su una diapositiva.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Determina se la forma è TextHolder. |
| [getPlaceholder()](#getPlaceholder--) | Restituisce il segnaposto per una forma. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Aggiunge un nuovo segnaposto se non esiste e imposta le proprietà del segnaposto a quello specificato. |
| [removePlaceholder()](#removePlaceholder--) | Definisce che questa forma non è un segnaposto. |
| [getCustomData()](#getCustomData--) | Restituisce i dati personalizzati della forma. |
| [getRawFrame()](#getRawFrame--) | Restituisce o imposta le proprietà del raw shape frame. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Restituisce o imposta le proprietà del raw shape frame. |
| [getFrame()](#getFrame--) | Restituisce o imposta le proprietà del raw shape frame. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Restituisce o imposta le proprietà del raw shape frame. |
| [getLineFormat()](#getLineFormat--) | Restituisce l'oggetto LineFormat che contiene le proprietà di formattazione della linea per una forma. |
| [getThreeDFormat()](#getThreeDFormat--) | Restituisce l'oggetto ThreeDFormat che contiene le proprietà di formattazione della linea per una forma. |
| [getEffectFormat()](#getEffectFormat--) | Restituisce l'oggetto EffectFormat che contiene gli effetti pixel applicati a una forma. |
| [getFillFormat()](#getFillFormat--) | Restituisce l'oggetto FillFormat che contiene le proprietà di formattazione del riempimento per una forma. |
| [getImage()](#getImage--) | Restituisce la miniatura della forma. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Restituisce la miniatura della forma. |
| [getHidden()](#getHidden--) | Determina se la forma è nascosta. |
| [setHidden(boolean value)](#setHidden-boolean-) | Determina se la forma è nascosta. |
| [getZOrderPosition()](#getZOrderPosition--) | Restituisce la posizione di una forma nell'ordine Z. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Restituisce il numero di punti di connessione sulla forma. |
| [getRotation()](#getRotation--) | Restituisce o imposta il numero di gradi di rotazione della forma specificata attorno all'asse Z. |
| [setRotation(float value)](#setRotation-float-) | Restituisce o imposta il numero di gradi di rotazione della forma specificata attorno all'asse Z. |
| [getX()](#getX--) | Ottiene o imposta la coordinata x dell'angolo superiore sinistro della forma, misurata in punti. |
| [setX(float value)](#setX-float-) | Ottiene o imposta la coordinata x dell'angolo superiore sinistro della forma, misurata in punti. |
| [getY()](#getY--) | Ottiene o imposta la coordinata y dell'angolo superiore sinistro della forma, misurata in punti. |
| [setY(float value)](#setY-float-) | Ottiene o imposta la coordinata y dell'angolo superiore sinistro della forma, misurata in punti. |
| [getWidth()](#getWidth--) | Ottiene o imposta la larghezza della forma, misurata in punti. |
| [setWidth(float value)](#setWidth-float-) | Ottiene o imposta la larghezza della forma, misurata in punti. |
| [getHeight()](#getHeight--) | Ottiene o imposta l'altezza della forma, misurata in punti. |
| [setHeight(float value)](#setHeight-float-) | Ottiene o imposta l'altezza della forma, misurata in punti. |
| [getAlternativeText()](#getAlternativeText--) | Restituisce o imposta il testo alternativo associato a una forma. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Restituisce o imposta il testo alternativo associato a una forma. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Restituisce o imposta il titolo del testo alternativo associato a una forma. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Restituisce o imposta il titolo del testo alternativo associato a una forma. |
| [getName()](#getName--) | Restituisce o imposta il nome di una forma. |
| [setName(String value)](#setName-java.lang.String-) | Restituisce o imposta il nome di una forma. |
| [isDecorative()](#isDecorative--) | Ottiene o imposta l'opzione 'Segna come decorativo' booleano Lettura/Scrittura. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Ottiene o imposta l'opzione 'Segna come decorativo' booleano Lettura/Scrittura. |
| [getShapeLock()](#getShapeLock--) | Restituisce i blocchi della forma. |
| [getUniqueId()](#getUniqueId--) | Restituisce un identificatore interno a livello di presentazione destinato all'uso da parte di componenti aggiuntivi o altro codice. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Restituisce un identificatore unico a livello di diapositiva che rimane costante per la durata della forma e consente a PowerPoint o al codice interop di fare riferimento in modo affidabile alla forma da qualsiasi punto del documento. |
| [isGrouped()](#isGrouped--) | Determina se la forma è raggruppata. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | La proprietà specifica come una forma verrà visualizzata in modalità bianco e nero. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | La proprietà specifica come una forma verrà visualizzata in modalità bianco e nero. |
| [getParentGroup()](#getParentGroup--) | Restituisce l'oggetto GroupShape genitore se la forma è raggruppata. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Salva il contenuto della Forma come file SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Salva il contenuto della Forma come file SVG. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Restituisce una forma segnaposto di base (forma dal layout e/o dalla diapositiva master da cui la forma corrente è ereditata). |

### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```

Determina se la forma è TextHolder. Solo lettura boolean.

**Restituisce:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public abstract IPlaceholder getPlaceholder()
```

Restituisce il segnaposto per una forma. Solo lettura [IPlaceholder](../../com.aspose.slides/iplaceholder).

**Restituisce:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public abstract IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Aggiunge un nuovo segnaposto se non esiste e imposta le proprietà del segnaposto a quello specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Segnaposto da cui copiare il contenuto. |

**Restituisce:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - Nuovo [IPlaceholder](../../com.aspose.slides/iplaceholder).

### removePlaceholder() {#removePlaceholder--}
```
public abstract void removePlaceholder()
```

Definisce che questa forma non è un segnaposto.

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Restituisce i dati personalizzati della forma. Solo lettura [ICustomData](../../com.aspose.slides/icustomdata).

**Restituisce:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public abstract IShapeFrame getRawFrame()
```

Restituisce o imposta le proprietà del raw shape frame. Lettura/Scrittura [IShapeFrame](../../com.aspose.slides/ishapeframe).

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //oppure
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Tale codice può portare a situazioni ambigue. Pertanto sono state aggiunte restrizioni per l'uso di valori indefiniti per IShape.getFrame(). I valori di x, y, width, height, flipH, flipV e rotationAngle devono essere definiti (non Float.NaN o NullableBool.NotDefined). Il codice di esempio sopra ora genera un'eccezione ArgumentException.
>  //Questo vale per i seguenti casi d'uso:
>  IShape shape = ...;
>  shape.setFrame(...); // non può essere indefinito
>  IShapeCollection shapes = ...;
>  // i parametri x, y, width, height non possono essere Float.NaN:
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
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // ora la forma eredita i valori x, y, height, flipH, flipV dal segnaposto e sovrascrive width=100 e rotationAngle=0.
> ```

**Restituisce:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
```

Restituisce o imposta le proprietà del raw shape frame. Lettura/Scrittura [IShapeFrame](../../com.aspose.slides/ishapeframe).

> ```
> Il codice che tenta di assegnare un frame non definito a IShape.getFrame() non ha senso nel caso generale (in particolare quando il GroupShape genitore è annidato più volte in altri GroupShape). Per esempio:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //oppure
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Questo tipo di codice può portare a situazioni poco chiare. Perciò sono state aggiunte restrizioni per l'uso di valori non definiti in IShape.getFrame(). I valori di x, y, width, height, flipH, flipV e rotationAngle devono essere definiti (non Float.NaN o NullableBool.NotDefined). Il codice di esempio sopra ora genera un'eccezione ArgumentException.
>  //Questo vale per questi casi d'uso:
>  IShape shape = ...;
>  shape.setFrame(...); // non può essere indefinito
>  IShapeCollection shapes = ...;
>  // i parametri x, y, width, height non possono essere Float.NaN:
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
>  Ma le proprietà del frame di IShape.RawFrame possono essere non definite. Questo ha senso quando la forma è collegata a un segnaposto. Allora i valori del frame non definiti vengono sovrascritti dal segnaposto genitore. Se non esiste un segnaposto genitore per quella forma, allora la forma utilizza i valori predefiniti quando valuta il frame effettivo basandosi su IShape.RawFrame. I valori predefiniti sono 0 e NullableBool.False per x, y, width, height, flipH, flipV e rotationAngle. Per esempio:
>  IShape shape = ...; // la forma è collegata al segnaposto
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // ora la forma eredita i valori x, y, height, flipH, flipV dal segnaposto e sovrascrive width=100 e rotationAngle=0.
```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

Restituisce o imposta le proprietà del shape frame. Lettura/Scrittura [IShapeFrame](../../com.aspose.slides/ishapeframe).

Il valore di ogni proprietà dell'istanza IShapeFrame restituita non è indefinito (non è NaN o NotDefined). Il valore di ogni proprietà dell'istanza IShapeFrame assegnata deve essere definito (non NaN o NotDefined). È possibile impostare valori indefiniti per le proprietà dell'istanza RawFrame.

**Restituisce:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

Restituisce o imposta le proprietà del shape frame. Lettura/Scrittura [IShapeFrame](../../com.aspose.slides/ishapeframe).

Il valore di ogni proprietà dell'istanza IShapeFrame restituita non è indefinito (non è NaN o NotDefined). Il valore di ogni proprietà dell'istanza IShapeFrame assegnata deve essere definito (non NaN o NotDefined). È possibile impostare valori indefiniti per le proprietà dell'istanza RawFrame.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

Restituisce l'oggetto LineFormat che contiene le proprietà di formattazione della linea per una forma. Solo lettura [ILineFormat](../../com.aspose.slides/ilineformat).

**Restituisce:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

Restituisce l'oggetto ThreeDFormat che contiene le proprietà di formattazione della linea per una forma. Solo lettura [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Restituisce:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Restituisce l'oggetto EffectFormat che contiene gli effetti pixel applicati a una forma. Solo lettura [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Restituisce:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Restituisce l'oggetto FillFormat che contiene le proprietà di formattazione del riempimento per una forma. Solo lettura [IFillFormat](../../com.aspose.slides/ifillformat).

**Restituisce:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Restituisce la miniatura della forma. Il tipo ShapeThumbnailBounds.Shape per i limiti della miniatura della forma è usato per impostazione predefinita.

**Restituisce:**
[IImage](../../com.aspose.slides/iimage) - Miniatura della forma.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public abstract IImage getImage(int bounds, float scaleX, float scaleY)
```

Restituisce la miniatura della forma.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bounds | int | Tipo di limiti della miniatura della forma. |
| scaleX | float | Scala X |
| scaleY | float | Scala Y |

**Restituisce:**
[IImage](../../com.aspose.slides/iimage) - Miniatura della forma o null nel caso in cui venga usato ShapeThumbnailBounds.Appearance e la forma non abbia elementi visibili.

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Determina se la forma è nascosta. Lettura/Scrittura boolean.

**Restituisce:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Determina se la forma è nascosta. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```

Restituisce la posizione di una forma nell'ordine Z. Shapes[0] restituisce la forma in fondo all'ordine Z, e Shapes[Shapes.Count - 1] restituisce la forma in cima all'ordine Z. Solo lettura int.

**Restituisce:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```

Restituisce il numero di punti di connessione sulla forma. Solo lettura int.

**Restituisce:**
int

### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

Restituisce o imposta il numero di gradi di rotazione della forma specificata attorno all'asse Z. Un valore positivo indica rotazione in senso orario; un valore negativo indica rotazione in senso antiorario. Lettura/Scrittura float.

--------------------
Il valore restituito è sempre definito (non è Float.NaN). Il valore assegnato deve essere definito (non Float.NaN). È possibile impostare valori indefiniti per le proprietà dell'istanza RawFrame.

**Restituisce:**
float

### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```

Restituisce o imposta il numero di gradi di rotazione della forma specificata attorno all'asse Z. Un valore positivo indica rotazione in senso orario; un valore negativo indica rotazione in senso antiorario. Lettura/Scrittura float.

--------------------
Il valore restituito è sempre definito (non è Float.NaN). Il valore assegnato deve essere definito (non Float.NaN). È possibile impostare valori indefiniti per le proprietà dell'istanza RawFrame.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public abstract float getX()
```

Ottiene o imposta la coordinata x dell'angolo superiore sinistro della forma, misurata in punti. Lettura/Scrittura float.

--------------------
Il valore restituito è sempre definito e non è mai Float.NaN. Il valore assegnato deve anche essere definito; assegnare Float.NaN solo alle proprietà di un'istanza RawFrame.

**Restituisce:**
float

### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```

Ottiene o imposta la coordinata x dell'angolo superiore sinistro della forma, misurata in punti. Lettura/Scrittura float.

--------------------
Il valore restituito è sempre definito e non è mai Float.NaN. Il valore assegnato deve anche essere definito; assegnare Float.NaN solo alle proprietà di un'istanza RawFrame.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public abstract float getY()
```

Ottiene o imposta la coordinata y dell'angolo superiore sinistro della forma, misurata in punti. Lettura/Scrittura float.

--------------------
Il valore restituito è sempre definito e non è mai Float.NaN. Il valore assegnato deve anche essere definito; assegnare Float.NaN solo alle proprietà di un'istanza RawFrame.

**Restituisce:**
float

### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```

Ottiene o imposta la coordinata y dell'angolo superiore sinistro della forma, misurata in punti. Lettura/Scrittura float.

--------------------
Il valore restituito è sempre definito e non è mai Float.NaN. Il valore assegnato deve anche essere definito; assegnare Float.NaN solo alle proprietà di un'istanza RawFrame.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

Ottiene o imposta la larghezza della forma, misurata in punti. Lettura/Scrittura float.

--------------------
Il valore restituito è sempre definito e non è mai Float.NaN. Il valore assegnato deve anche essere definito; assegnare Float.NaN solo alle proprietà di un'istanza RawFrame.

**Restituisce:**
float

### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```

Ottiene o imposta la larghezza della forma, misurata in punti. Lettura/Scrittura float.

--------------------
Il valore restituito è sempre definito e non è mai Float.NaN. Il valore assegnato deve anche essere definito; assegnare Float.NaN solo alle proprietà di un'istanza RawFrame.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Ottiene o imposta l'altezza della forma, misurata in punti. Lettura/Scrittura float.

--------------------
Il valore restituito è sempre definito e non è mai Float.NaN. Il valore assegnato deve anche essere definito; assegnare Float.NaN solo alle proprietà di un'istanza RawFrame.

**Restituisce:**
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Ottiene o imposta l'altezza della forma, misurata in punti. Lettura/Scrittura float.

--------------------
Il valore restituito è sempre definito e non è mai Float.NaN. Il valore assegnato deve anche essere definito; assegnare Float.NaN solo alle proprietà di un'istanza RawFrame.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getAlternativeText() {#getAlternativeText--}
```
public abstract String getAlternativeText()
```

Restituisce o imposta il testo alternativo associato a una forma. Lettura/Scrittura String.

**Restituisce:**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public abstract void setAlternativeText(String value)
```

Restituisce o imposta il testo alternativo associato a una forma. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public abstract String getAlternativeTextTitle()
```

Restituisce o imposta il titolo del testo alternativo associato a una forma. Lettura/Scrittura String.

**Restituisce:**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public abstract void setAlternativeTextTitle(String value)
```

Restituisce o imposta il titolo del testo alternativo associato a una forma. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public abstract String getName()
```

Restituisce o imposta il nome di una forma. Lettura/Scrittura String.

**Restituisce:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Restituisce o imposta il nome di una forma. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```

Ottiene o imposta l'opzione 'Segna come decorativo' booleano Lettura/Scrittura.

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Restituisce:**
boolean

### setDecorative(boolean value) {#setDecorative-boolean-}
```
public abstract void setDecorative(boolean value)
```

Ottiene o imposta l'opzione 'Segna come decorativo' booleano Lettura/Scrittura.

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public abstract IBaseShapeLock getShapeLock()
```

Restituisce i blocchi della forma. Solo lettura [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Restituisce:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### getUniqueId() {#getUniqueId--}
```
public abstract long getUniqueId()
```

Restituisce un identificatore interno a livello di presentazione destinato all'uso da parte di componenti aggiuntivi o altro codice. Poiché questo valore può essere riassegnato dall'utente o programmaticamente, non deve essere considerato una chiave unica persistente. Solo lettura long. Vedi anche \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**Restituisce:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public abstract long getOfficeInteropShapeId()
```

Restituisce un identificatore unico a livello di diapositiva che rimane costante per la durata della forma e consente a PowerPoint o al codice interop di fare riferimento in modo affidabile alla forma da qualsiasi punto del documento. Solo lettura long. Vedi anche \#getUniqueId.getUniqueId.

**Restituisce:**
long

### isGrouped() {#isGrouped--}
```
public abstract boolean isGrouped()
```

Determina se la forma è raggruppata. Solo lettura boolean.

--------------------
La proprietà #getParentGroup.getParentGroup restituisce l'oggetto GroupShape genitore se la forma è raggruppata.

**Restituisce:**
boolean

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public abstract byte getBlackWhiteMode()
```

La proprietà specifica come una forma verrà visualizzata in modalità bianco e nero. Lettura/Scrittura [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Restituisce:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```

La proprietà specifica come una forma verrà visualizzata in modalità bianco e nero. Lettura/Scrittura [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Restituisce l'oggetto GroupShape genitore se la forma è raggruppata. Altrimenti restituisce null. Solo lettura [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------
La proprietà #isGrouped.isGrouped determina se la forma è raggruppata.

**Restituisce:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

Salva il contenuto della Forma come file SVG.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Flusso di destinazione |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Salva il contenuto della Forma come file SVG.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Flusso di destinazione |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Opzioni di generazione SVG |

### getBasePlaceholder() {#getBasePlaceholder--}
```
public abstract IShape getBasePlaceholder()
```

Restituisce una forma segnaposto di base (forma dal layout e/o dalla diapositiva master da cui la forma corrente è ereditata).

> ```
> // Recupera tutti gli effetti animati (master/layout/slide) del segnaposto della forma
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


A viene restituito null se la forma corrente non è ereditata.

**Restituisce:**
[IShape](../../com.aspose.slides/ishape)