---
title: Shape
second_title: Riferimento API Java per Aspose.Slides per Android
description: Rappresenta una forma su una diapositiva.
type: docs
url: /it/com.aspose.slides/shape/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape), com.aspose.slides.IDOMObject
```
public class Shape implements IShape, IDOMObject
```

Rappresenta una forma su una diapositiva.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Determina se la forma è TextHolder_PPT. |
| [getPlaceholder()](#getPlaceholder--) | Restituisce il segnaposto per una forma. |
| [removePlaceholder()](#removePlaceholder--) | Definisce che questa forma non è un segnaposto. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Aggiunge un nuovo segnaposto se non ne esiste e imposta le proprietà del segnaposto su quello specificato. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Restituisce una forma segnaposto di base (forma dal layout e/o dalla diapositiva master da cui la forma corrente è ereditata). |
| [getCustomData()](#getCustomData--) | Restituisce i dati personalizzati della forma. |
| [getRawFrame()](#getRawFrame--) | Restituisce o imposta le proprietà grezze del frame della forma. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Restituisce o imposta le proprietà grezze del frame della forma. |
| [getFrame()](#getFrame--) | Restituisce o imposta le proprietà grezze del frame della forma. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Restituisce o imposta le proprietà grezze del frame della forma. |
| [getLineFormat()](#getLineFormat--) | Restituisce l'oggetto LineFormat che contiene le proprietà di formattazione delle linee per una forma. |
| [getThreeDFormat()](#getThreeDFormat--) | Restituisce l'oggetto ThreeDFormat che contiene le proprietà degli effetti 3d per una forma. |
| [getEffectFormat()](#getEffectFormat--) | Restituisce l'oggetto EffectFormat che contiene gli effetti pixel applicati a una forma. |
| [getFillFormat()](#getFillFormat--) | Restituisce l'oggetto FillFormat che contiene le proprietà di formattazione di riempimento per una forma. |
| [getImage()](#getImage--) | Restituisce la miniatura della forma. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Restituisce la miniatura della forma. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Salva il contenuto della Forma come file SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Salva il contenuto della Forma come file SVG. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Restituisce o imposta il collegamento ipertestuale definito per il clic del mouse. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Restituisce o imposta il collegamento ipertestuale definito per il clic del mouse. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Restituisce o imposta il collegamento ipertestuale definito per il passaggio del mouse. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Restituisce o imposta il collegamento ipertestuale definito per il passaggio del mouse. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Restituisce il gestore dei collegamenti ipertestuali. |
| [getHidden()](#getHidden--) | Determina se la forma è nascosta. |
| [setHidden(boolean value)](#setHidden-boolean-) | Determina se la forma è nascosta. |
| [getZOrderPosition()](#getZOrderPosition--) | Restituisce la posizione di una forma nell'ordine Z. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Restituisce il numero di punti di connessione sulla forma. |
| [getRotation()](#getRotation--) | Restituisce o imposta il numero di gradi di rotazione della forma specificata attorno all'asse Z. |
| [setRotation(float value)](#setRotation-float-) | Restituisce o imposta il numero di gradi di rotazione della forma specificata attorno all'asse Z. |
| [getX()](#getX--) | Ottiene o imposta la coordinata X dell'angolo superiore sinistro della forma, misurata in punti. |
| [setX(float value)](#setX-float-) | Ottiene o imposta la coordinata X dell'angolo superiore sinistro della forma, misurata in punti. |
| [getY()](#getY--) | Ottiene o imposta la coordinata Y dell'angolo superiore sinistro della forma, misurata in punti. |
| [setY(float value)](#setY-float-) | Ottiene o imposta la coordinata Y dell'angolo superiore sinistro della forma, misurata in punti. |
| [getWidth()](#getWidth--) | Ottiene o imposta la larghezza della forma, misurata in punti. |
| [setWidth(float value)](#setWidth-float-) | Ottiene o imposta la larghezza della forma, misurata in punti. |
| [getHeight()](#getHeight--) | Ottiene o imposta l'altezza della forma, misurata in punti. |
| [setHeight(float value)](#setHeight-float-) | Ottiene o imposta l'altezza della forma, misurata in punti. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | La proprietà specifica come una forma verrà renderizzata in modalità di visualizzazione in bianco e nero. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | La proprietà specifica come una forma verrà renderizzata in modalità di visualizzazione in bianco e nero. |
| [getUniqueId()](#getUniqueId--) | Restituisce un identificatore interno, a livello di presentazione, destinato all'uso da parte di componenti aggiuntivi o altro codice. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Restituisce un identificatore unico a livello di diapositiva che rimane costante per la durata della forma e consente a PowerPoint o al codice interop di fare riferimento in modo affidabile alla forma da qualsiasi punto del documento. |
| [getAlternativeText()](#getAlternativeText--) | Restituisce o imposta il testo alternativo associato a una forma. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Restituisce o imposta il testo alternativo associato a una forma. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Restituisce o imposta il titolo del testo alternativo associato a una forma. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Restituisce o imposta il titolo del testo alternativo associato a una forma. |
| [getName()](#getName--) | Restituisce o imposta il nome di una forma. |
| [setName(String value)](#setName-java.lang.String-) | Restituisce o imposta il nome di una forma. |
| [isDecorative()](#isDecorative--) | Ottiene o imposta l'opzione 'Contrassegna come decorativo' Lettura/Scrittura boolean. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Ottiene o imposta l'opzione 'Contrassegna come decorativo' Lettura/Scrittura boolean. |
| [getShapeLock()](#getShapeLock--) | Restituisce i blocchi della forma. |
| [isGrouped()](#isGrouped--) | Determina se la forma è raggruppata. |
| [getParentGroup()](#getParentGroup--) | Restituisce l'oggetto GroupShape genitore se la forma è raggruppata. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVisualBounds()](#getVisualBounds--) | Ottiene i limiti visivi della forma calcolati dal suo contenuto renderizzato. |
| [getSlide()](#getSlide--) | Restituisce la diapositiva genitore di una forma. |
| [getPresentation()](#getPresentation--) | Restituisce la presentazione genitore di una diapositiva. |

### isTextHolder() {#isTextHolder--}
```
public final boolean isTextHolder()
```

Determina se la forma è TextHolder_PPT. Solo lettura  boolean .

**Restituisce:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```

Restituisce il segnaposto per una forma. Restituisce null se la forma non ha un segnaposto. Solo lettura [IPlaceholder](../../com.aspose.slides/iplaceholder).

--------------------

> ```
> The following example shows how to change Text in Placeholder.
>  
>  // Istanzia una classe Presentation
>  Presentation pres = new Presentation("ReplacingText.pptx");
>  try {
>      // Accede alla prima diapositiva
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Itera le forme per trovare il segnaposto
>      for (IShape shp : sld.getShapes())
>          if (shp.getPlaceholder() != null)
>          {
>              // Modifica il testo in ogni segnaposto
>              ((IAutoShape)shp).getTextFrame().setText("This is a Placeholder");
>          }
>      // Salva la presentazione su disco
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
>      for (IShape shape : slide.getSlide().getShapes()) // Itera attraverso la diapositiva
>      {
>          if (shape.getPlaceholder() != null && shape instanceof AutoShape)
>          {
>              String text = "";
>              if (shape.getPlaceholder().getType() == PlaceholderType.CenteredTitle) // PowerPoint visualizza "Click to add title"
>              {
>                  text = "Add Title";
>              }
>              else if (shape.getPlaceholder().getType() == PlaceholderType.Subtitle) // Aggiunge il sottotitolo
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


**Restituisce:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### removePlaceholder() {#removePlaceholder--}
```
public final void removePlaceholder()
```

Definisce che questa forma non è un segnaposto.

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public final IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

Aggiunge un nuovo segnaposto se non ne esiste e imposta le proprietà del segnaposto su quello specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Segnaposto da cui copiare il contenuto. |

**Restituisce:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - New #getPlaceholder.getPlaceholder.

### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

Restituisce una forma segnaposto di base (forma dal layout e/o dalla diapositiva master da cui la forma corrente è ereditata).

--------------------

> ```
> // ottieni tutti gli effetti animati (master/layout/slide) della forma segnaposto
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

Viene restituito null se la forma corrente non è ereditata.

**Restituisce:**
[IShape](../../com.aspose.slides/ishape)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Restituisce i dati personalizzati della forma. Solo lettura [ICustomData](../../com.aspose.slides/icustomdata).

**Restituisce:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public final IShapeFrame getRawFrame()
```

Restituisce o imposta le proprietà grezze del frame della forma. Lettura/Scrittura [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //o
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Questo tipo di codice può portare a situazioni poco chiare. Pertanto sono state aggiunte restrizioni per l'uso di valori non definiti per IShape.getFrame(). I valori di x, y, width, height, flipH, flipV e rotationAngle devono essere definiti (non Float.NaN o NullableBool.NotDefined). Il codice di esempio sopra ora genera un'eccezione ArgumentException.
>  //Questo si applica a questi casi d'uso:
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
>  //Ma le proprietà del frame IShape.RawFrame possono essere non definite. Questo ha senso quando la forma è collegata a un segnaposto. In tal caso i valori non definiti del frame della forma vengono sovrascritti dal segnaposto genitore. Se non esiste un segnaposto genitore per quella forma, la forma utilizza i valori predefiniti quando valuta il frame efficace basandosi sul suo IShape.RawFrame. I valori predefiniti sono 0 e NullableBool.False per x, y, width, height, flipH, flipV e rotationAngle. Per esempio:
>  IShape shape = ...; // la forma è collegata a un segnaposto
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // ora la forma eredita i valori x, y, height, flipH, flipV dal segnaposto e sovrascrive width=100 e rotationAngle=0.{code}
```

**Restituisce:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
```

Restituisce o imposta le proprietà grezze del frame della forma. Lettura/Scrittura [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //o
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Questo tipo di codice può portare a situazioni poco chiare. Pertanto sono state aggiunte restrizioni per l'uso di valori non definiti per IShape.getFrame(). I valori di x, y, width, height, flipH, flipV e rotationAngle devono essere definiti (non Float.NaN o NullableBool.NotDefined). Il codice di esempio sopra ora genera un'eccezione ArgumentException.
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
>  //Ma le proprietà del frame IShape.RawFrame possono essere non definite. Questo ha senso quando la forma è collegata a un segnaposto. Allora i valori non definiti del frame della forma vengono sovrascritti dal segnaposto genitore. Se non esiste un segnaposto genitore per quella forma, la forma utilizza valori predefiniti quando valuta il frame efficace basandosi sul suo IShape.RawFrame. I valori predefiniti sono 0 e NullableBool.False per x, y, width, height, flipH, flipV e rotationAngle. Per esempio:
>  IShape shape = ...; // la forma è collegata a un segnaposto
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // ora la forma eredita i valori x, y, height, flipH, flipV dal segnaposto e sovrascrive width=100 e rotationAngle=0.{code}
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Restituisce o imposta le proprietà del frame della forma. Lettura/Scrittura [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Il valore di ciascuna proprietà dell'istanza IShapeFrame restituita non è undefined (non è NaN o NotDefined). Il valore di ciascuna proprietà dell'istanza IShapeFrame assegnata deve essere definito (non NaN o NotDefined). È possibile impostare valori undefined per le proprietà dell'istanza RawFrame.

**Restituisce:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Restituisce o imposta le proprietà del frame della forma. Lettura/Scrittura [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

Il valore di ciascuna proprietà dell'istanza IShapeFrame restituita non è undefined (non è NaN o NotDefined). Il valore di ciascuna proprietà dell'istanza IShapeFrame assegnata deve essere definito (non NaN o NotDefined). È possibile impostare valori undefined per le proprietà dell'istanza RawFrame.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

Restituisce l'oggetto LineFormat che contiene le proprietà di formattazione delle linee per una forma. Nota: può restituire null per alcuni tipi di forme che non possiedono proprietà di linea. Solo lettura [ILineFormat](../../com.aspose.slides/ilineformat).

**Restituisce:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

Restituisce l'oggetto ThreeDFormat che contiene le proprietà degli effetti 3D per una forma. Nota: può restituire null per alcuni tipi di forme che non possiedono proprietà 3D. Solo lettura [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Restituisce:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

Restituisce l'oggetto EffectFormat che contiene gli effetti pixel applicati a una forma. Nota: può restituire null per alcuni tipi di forme che non possiedono proprietà di effetto. Solo lettura [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Restituisce:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Restituisce l'oggetto FillFormat che contiene le proprietà di formattazione di riempimento per una forma. Nota: può restituire null per alcuni tipi di forme che non possiedono proprietà di riempimento. Solo lettura [IFillFormat](../../com.aspose.slides/ifillformat).

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
>      // Accento 4
>      IShape shape1 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 50, 50);
>      shape1.getFillFormat().setFillType(FillType.Solid);
>      shape1.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      // Accento 4, più chiaro 80%
>      IShape shape2 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 70, 50, 50);
>      shape2.getFillFormat().setFillType(FillType.Solid);
>      shape2.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.2f);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.8f);
>      // Accento 4, più chiaro 60%
>      IShape shape3 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 130, 50, 50);
>      shape3.getFillFormat().setFillType(FillType.Solid);
>      shape3.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.4f);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.6f);
>      // Accento 4, più chiaro 40%
>      IShape shape4 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 190, 50, 50);
>      shape4.getFillFormat().setFillType(FillType.Solid);
>      shape4.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.6f);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.4f);
>      // Accento 4, più scuro 25%
>      IShape shape5 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 250, 50, 50);
>      shape5.getFillFormat().setFillType(FillType.Solid);
>      shape5.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape5.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.75f);
>      // Accento 4, più scuro 50%
>      IShape shape6 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 310, 50, 50);
>      shape6.getFillFormat().setFillType(FillType.Solid);
>      shape6.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape6.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.5f);
>      pres.save("example_accent4.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public final IImage getImage()
```

Restituisce la miniatura della forma. ShapeThumbnailBounds.Shape shape thumbnail bounds type è usato per impostazione predefinita.

**Restituisce:**
[IImage](../../com.aspose.slides/iimage) - Miniatura della forma.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IImage getImage(int bounds, float scaleX, float scaleY)
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

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

Salva il contenuto della Forma come file SVG.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream di destinazione |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Salva il contenuto della Forma come file SVG.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream di destinazione |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Opzioni di generazione SVG |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

Restituisce o imposta il collegamento ipertestuale definito per il clic del mouse. Lettura/Scrittura [IHyperlink](../../com.aspose.slides/ihyperlink).

**Restituisce:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

Restituisce o imposta il collegamento ipertestuale definito per il clic del mouse. Lettura/Scrittura [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

Restituisce o imposta il collegamento ipertestuale definito per il passaggio del mouse. Lettura/Scrittura [IHyperlink](../../com.aspose.slides/ihyperlink).

**Restituisce:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

Restituisce o imposta il collegamento ipertestuale definito per il passaggio del mouse. Lettura/Scrittura [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

Restituisce il gestore dei collegamenti ipertestuali. Solo lettura [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Restituisce:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Determina se la forma è nascosta. Lettura/Scrittura  boolean .

**Restituisce:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Determina se la forma è nascosta. Lettura/Scrittura  boolean .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

Restituisce la posizione di una forma nell'ordine Z. Shapes[0] restituisce la forma più indietro nell'ordine Z, e Shapes[Shapes.Count - 1] restituisce la forma più in avanti nell'ordine Z. Solo lettura  int .

**Restituisce:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```

Restituisce il numero di punti di connessione sulla forma. Solo lettura  int .

**Restituisce:**
int

### getRotation() {#getRotation--}
```
public final float getRotation()
```

Restituisce o imposta il numero di gradi di rotazione della forma specificata attorno all'asse Z. Un valore positivo indica rotazione in senso orario; un valore negativo indica rotazione in senso antiorario. Lettura/Scrittura float.

--------------------

Il valore restituito è sempre definito (non è Float.NaN). Il valore assegnato deve essere definito (non Float.NaN). È possibile impostare valori undefined per le proprietà dell'istanza RawFrame.

**Restituisce:**
float

### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```

Restituisce o imposta il numero di gradi di rotazione della forma specificata attorno all'asse Z. Un valore positivo indica rotazione in senso orario; un valore negativo indica rotazione in senso antiorario. Lettura/Scrittura float.

--------------------

Il valore restituito è sempre definito (non è Float.NaN). Il valore assegnato deve essere definito (non Float.NaN). È possibile impostare valori undefined per le proprietà dell'istanza RawFrame.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public final float getX()
```

Ottiene o imposta la coordinata X dell'angolo superiore sinistro della forma, misurata in punti. Lettura/Scrittura float.

--------------------

Il valore restituito è sempre definito e non è Float.NaN. Il valore assegnato deve essere anch'esso definito; assegnare Float.NaN solo alle proprietà di un'istanza RawFrame.

**Restituisce:**
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Ottiene o imposta la coordinata X dell'angolo superiore sinistro della forma, misurata in punti. Lettura/Scrittura float.

--------------------

Il valore restituito è sempre definito e non è Float.NaN. Il valore assegnato deve essere anch'esso definito; assegnare Float.NaN solo alle proprietà di un'istanza RawFrame.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

Ottiene o imposta la coordinata Y dell'angolo superiore sinistro della forma, misurata in punti. Lettura/Scrittura float.

--------------------

Il valore restituito è sempre definito e non è Float.NaN. Il valore assegnato deve essere anch'esso definito; assegnare Float.NaN solo alle proprietà di un'istanza RawFrame.

**Restituisce:**
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Ottiene o imposta la coordinata Y dell'angolo superiore sinistro della forma, misurata in punti. Lettura/Scrittura float.

--------------------

Il valore restituito è sempre definito e non è Float.NaN. Il valore assegnato deve essere anch'esso definito; assegnare Float.NaN solo alle proprietà di un'istanza RawFrame.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Ottiene o imposta la larghezza della forma, misurata in punti. Lettura/Scrittura float.

--------------------

Il valore restituito è sempre definito e non è Float.NaN. Il valore assegnato deve essere anch'esso definito; assegnare Float.NaN solo alle proprietà di un'istanza RawFrame.

**Restituisce:**
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Ottiene o imposta la larghezza della forma, misurata in punti. Lettura/Scrittura float.

--------------------

Il valore restituito è sempre definito e non è Float.NaN. Il valore assegnato deve essere anch'esso definito; assegnare Float.NaN solo alle proprietà di un'istanza RawFrame.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Ottiene o imposta l'altezza della forma, misurata in punti. Lettura/Scrittura float.

--------------------

Il valore restituito è sempre definito e non è Float.NaN. Il valore assegnato deve essere anch'esso definito; assegnare Float.NaN solo alle proprietà di un'istanza RawFrame.

**Restituisce:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Ottiene o imposta l'altezza della forma, misurata in punti. Lettura/Scrittura float.

--------------------

Il valore restituito è sempre definito e non è Float.NaN. Il valore assegnato deve essere anch'esso definito; assegnare Float.NaN solo alle proprietà di un'istanza RawFrame.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```

La proprietà specifica come una forma verrà renderizzata in modalità di visualizzazione in bianco e nero. Lettura/Scrittura [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Restituisce:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```

La proprietà specifica come una forma verrà renderizzata in modalità di visualizzazione in bianco e nero. Lettura/Scrittura [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```

Restituisce un identificatore interno, a livello di presentazione, destinato all'uso da parte di componenti aggiuntivi o altro codice. Poiché questo valore può essere riassegnato dall'utente o programmaticamente, non deve essere trattato come chiave unica persistente. Solo lettura long. Vedi anche #getOfficeInteropShapeId.getOfficeInteropShapeId.

**Restituisce:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```

Restituisce un identificatore unico a livello di diapositiva che rimane costante per la durata della forma e consente a PowerPoint o al codice interop di fare riferimento in modo affidabile alla forma da qualsiasi punto del documento. Solo lettura long. Vedi anche #getUniqueId.getUniqueId.

**Restituisce:**
long

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```

Restituisce o imposta il testo alternativo associato a una forma. Lettura/Scrittura String.

**Restituisce:**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```

Restituisce o imposta il testo alternativo associato a una forma. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```

Restituisce o imposta il titolo del testo alternativo associato a una forma. Lettura/Scrittura String.

**Restituisce:**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```

Restituisce o imposta il titolo del testo alternativo associato a una forma. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```

Restituisce o imposta il nome di una forma. Deve essere non nullo. Usa una stringa vuota se necessario. Lettura/Scrittura String.

**Restituisce:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Restituisce o imposta il nome di una forma. Deve essere non nullo. Usa una stringa vuota se necessario. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```

Ottiene o imposta l'opzione 'Contrassegna come decorativo' Lettura/Scrittura boolean.

--------------------

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
public final void setDecorative(boolean value)
```

Ottiene o imposta l'opzione 'Contrassegna come decorativo' Lettura/Scrittura boolean.

--------------------

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
public IBaseShapeLock getShapeLock()
```

Restituisce i blocchi della forma. Solo lettura [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**Restituisce:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```

Determina se la forma è raggruppata. Solo lettura boolean.

--------------------

La proprietà #getParentGroup.getParentGroup restituisce l'oggetto GroupShape genitore se la forma è raggruppata.

**Restituisce:**
boolean

### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Restituisce l'oggetto GroupShape genitore se la forma è raggruppata. Altrimenti restituisce null. Solo lettura [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

La proprietà #isGrouped.isGrouped determina se la forma è raggruppata.

**Restituisce:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Restituisce l'oggetto Parent_Immediate. Solo lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject

### getVisualBounds() {#getVisualBounds--}
```
public        {
     // Oggi Finn  ..
```



Ottiene i limiti visivi della forma calcolati dal suo contenuto renderizzato.

**Restituisce:**
android.graphics.RectF - Un android.graphics.RectF che rappresenta i limiti visivi della forma nelle coordinate della diapositiva.

--------------------

Il rettangolo restituito rappresenta i limiti allineati all'asse di tutti i contenuti prodotti dalla forma durante il rendering nello spazio delle coordinate della diapositiva. Questi limiti possono differire dai limiti modello della forma #getX.getX/#setX(float).setX(float), #getY.getY/#setY(float).setY(float), #getWidth.getWidth/#setWidth(float).setWidth(float), #getHeight.getHeight/#setHeight(float).setHeight(float) e possono contenere coordinate negative se il contenuto renderizzato si estende oltre l'origine della diapositiva. I limiti visivi tengono conto di aspetti legati al rendering come trasformazioni (ad esempio, rotazione), larghezza e giunzioni del tratto, layout e overflow del testo, geometria SmartArt e altri effetti di layout che influenzano l'aspetto finale renderizzato della forma. I limiti restituiti non sono ritagliati al rettangolo della diapositiva.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Restituisce la diapositiva genitore di una forma. Solo lettura [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Restituisce:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Restituisce la presentazione genitore di una diapositiva. Solo lettura [IPresentation](../../com.aspose.slides/ipresentation).

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation)