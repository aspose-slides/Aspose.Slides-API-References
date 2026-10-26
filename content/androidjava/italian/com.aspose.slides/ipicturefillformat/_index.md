---
title: IPictureFillFormat
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Rappresenta uno stile di riempimento immagine.
type: docs
url: /it/com.aspose.slides/ipicturefillformat/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormat extends IFillParamSource
```

Rappresenta uno stile di riempimento immagine.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDpi()](#getDpi--) | Restituisce o imposta i dpi che sono usati per riempire un’immagine. |
| [setDpi(int value)](#setDpi-int-) | Restituisce o imposta i dpi che sono usati per riempire un’immagine. |
| [getPictureFillMode()](#getPictureFillMode--) | Restituisce o imposta la modalità di riempimento immagine. |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | Restituisce o imposta la modalità di riempimento immagine. |
| [getPicture()](#getPicture--) | Restituisce l’immagine. |
| [getCropLeft()](#getCropLeft--) | Restituisce o imposta la percentuale di larghezza reale dell’immagine che viene ritagliata a sinistra dell’immagine. |
| [setCropLeft(float value)](#setCropLeft-float-) | Restituisce o imposta la percentuale di larghezza reale dell’immagine che viene ritagliata a sinistra dell’immagine. |
| [getCropTop()](#getCropTop--) | Restituisce o imposta la percentuale di altezza reale dell’immagine che viene ritagliata in alto dell’immagine. |
| [setCropTop(float value)](#setCropTop-float-) | Restituisce o imposta la percentuale di altezza reale dell’immagine che viene ritagliata in alto dell’immagine. |
| [getCropRight()](#getCropRight--) | Restituisce o imposta la percentuale di larghezza reale dell’immagine che viene ritagliata a destra dell’immagine. |
| [setCropRight(float value)](#setCropRight-float-) | Restituisce o imposta la percentuale di larghezza reale dell’immagine che viene ritagliata a destra dell’immagine. |
| [getCropBottom()](#getCropBottom--) | Restituisce o imposta la percentuale di altezza reale dell’immagine che viene ritagliata in basso dell’immagine. |
| [setCropBottom(float value)](#setCropBottom-float-) | Restituisce o imposta la percentuale di altezza reale dell’immagine che viene ritagliata in basso dell’immagine. |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | Restituisce o imposta il bordo sinistro del rettangolo di riempimento definito da uno scostamento percentuale dal bordo sinistro della bounding box della forma. |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | Restituisce o imposta il bordo sinistro del rettangolo di riempimento definito da uno scostamento percentuale dal bordo sinistro della bounding box della forma. |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | Restituisce o imposta il bordo superiore del rettangolo di riempimento definito da uno scostamento percentuale dal bordo superiore della bounding box della forma. |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | Restituisce o imposta il bordo superiore del rettangolo di riempimento definito da uno scostamento percentuale dal bordo superiore della bounding box della forma. |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | Restituisce o imposta il bordo destro del rettangolo di riempimento definito da uno scostamento percentuale dal bordo destro della bounding box della forma. |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | Restituisce o imposta il bordo destro del rettangolo di riempimento definito da uno scostamento percentuale dal bordo destro della bounding box della forma. |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | Restituisce o imposta il bordo inferiore del rettangolo di riempimento definito da uno scostamento percentuale dal bordo inferiore della bounding box della forma. |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | Restituisce o imposta il bordo inferiore del rettangolo di riempimento definito da uno scostamento percentuale dal bordo inferiore della bounding box della forma. |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | Elimina le aree ritagliate dell’immagine di riempimento. |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | Comprimi l’immagine riducendone le dimensioni in base alle dimensioni della forma e alla risoluzione specificata. |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | Comprimi l’immagine riducandone le dimensioni in base alle dimensioni della forma e alla risoluzione specificata. |
| [getTileOffsetX()](#getTileOffsetX--) | Restituisce o imposta lo scostamento orizzontale della trama dall’origine della forma in punti. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Restituisce o imposta lo scostamento orizzontale della trama dall’origine della forma in punti. |
| [getTileOffsetY()](#getTileOffsetY--) | Restituisce o imposta lo scostamento verticale della trama dall’origine della forma in punti. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Restituisce o imposta lo scostamento verticale della trama dall’origine della forma in punti. |
| [getTileScaleX()](#getTileScaleX--) | Restituisce o imposta la scala orizzontale della trama di riempimento come percentuale. |
| [setTileScaleX(float value)](#setTileScaleX-float-) | Restituisce o imposta la scala orizzontale della trama di riempimento come percentuale. |
| [getTileScaleY()](#getTileScaleY--) | Restituisce o imposta la scala verticale della trama di riempimento come percentuale. |
| [setTileScaleY(float value)](#setTileScaleY-float-) | Restituisce o imposta la scala verticale della trama di riempimento come percentuale. |
| [getTileAlignment()](#getTileAlignment--) | Restituisce o imposta come la trama è allineata all’interno della forma. |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | Restituisce o imposta come la trama è allineata all’interno della forma. |
| [getTileFlip()](#getTileFlip--) | Capovolge la tessera della trama attorno al suo asse orizzontale, verticale o a entrambi gli assi. |
| [setTileFlip(int value)](#setTileFlip-int-) | Capovolge la tessera della trama attorno al suo asse orizzontale, verticale o a entrambi gli assi. |

### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

Restituisce o imposta i dpi che sono usati per riempire un’immagine. Lettura/Scrittura int.

**Restituisce:**
int

### setDpi(int value) {#setDpi-int-}
```
public abstract void setDpi(int value)
```

Restituisce o imposta i dpi che sono usati per riempire un’immagine. Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

Restituisce o imposta la modalità di riempimento immagine. Lettura/Scrittura [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Restituisce:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public abstract void setPictureFillMode(int value)
```

Restituisce o imposta la modalità di riempimento immagine. Lettura/Scrittura [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

Restituisce l’immagine. Solo lettura [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Restituisce:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

Restituisce o imposta la percentuale di larghezza reale dell’immagine che viene ritagliata a sinistra dell’immagine. Lettura/Scrittura float.

**Restituisce:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public abstract void setCropLeft(float value)
```

Restituisce o imposta la percentuale di larghezza reale dell’immagine che viene ritagliata a sinistra dell’immagine. Lettura/Scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

Restituisce o imposta la percentuale di altezza reale dell’immagine che viene ritagliata in alto dell’immagine. Lettura/Scrittura float.

**Restituisce:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public abstract void setCropTop(float value)
```

Restituisce o imposta la percentuale di altezza reale dell’immagine che viene ritagliata in alto dell’immagine. Lettura/Scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

Restituisce o imposta la percentuale di larghezza reale dell’immagine che viene ritagliata a destra dell’immagine. Lettura/Scrittura float.

**Restituisce:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public abstract void setCropRight(float value)
```

Restituisce o imposta la percentuale di larghezza reale dell’immagine che viene ritagliata a destra dell’immagine. Lettura/Scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

Restituisce o imposta la percentuale di altezza reale dell’immagine che viene ritagliata in basso dell’immagine. Lettura/Scrittura float.

**Restituisce:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public abstract void setCropBottom(float value)
```

Restituisce o imposta la percentuale di altezza reale dell’immagine che viene ritagliata in basso dell’immagine. Lettura/Scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public abstract float getStretchOffsetLeft()
```

Restituisce o imposta il bordo sinistro del rettangolo di riempimento definito da uno scostamento percentuale dal bordo sinistro della bounding box della forma. Una percentuale positiva specifica un rientro, mentre una percentuale negativa specifica un'estensione. Lettura/Scrittura float.

**Restituisce:**
float

### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public abstract void setStretchOffsetLeft(float value)
```

Restituisce o imposta il bordo sinistro del rettangolo di riempimento definito da uno scostamento percentuale dal bordo sinistro della bounding box della forma. Una percentuale positiva specifica un rientro, mentre una percentuale negativa specifica un'estensione. Lettura/Scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public abstract float getStretchOffsetTop()
```

Restituisce o imposta il bordo superiore del rettangolo di riempimento definito da uno scostamento percentuale dal bordo superiore della bounding box della forma. Una percentuale positiva specifica un rientro, mentre una percentuale negativa specifica un'estensione. Lettura/Scrittura float.

**Restituisce:**
float

### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public abstract void setStretchOffsetTop(float value)
```

Restituisce o imposta il bordo superiore del rettangolo di riempimento definito da uno scostamento percentuale dal bordo superiore della bounding box della forma. Una percentuale positiva specifica un rientro, mentre una percentuale negativa specifica un'estensione. Lettura/Scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public abstract float getStretchOffsetRight()
```

Restituisce o imposta il bordo destro del rettangolo di riempimento definito da uno scostamento percentuale dal bordo destro della bounding box della forma. Una percentuale positiva specifica un rientro, mentre una percentuale negativa specifica un'estensione. Lettura/Scrittura float.

**Restituisce:**
float

### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public abstract void setStretchOffsetRight(float value)
```

Restituisce o imposta il bordo destro del rettangolo di riempimento definito da uno scostamento percentuale dal bordo destro della bounding box della forma. Una percentuale positiva specifica un rientro, mentre una percentuale negativa specifica un'estensione. Lettura/Scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public abstract float getStretchOffsetBottom()
```

Restituisce o imposta il bordo inferiore del rettangolo di riempimento definito da uno scostamento percentuale dal bordo inferiore della bounding box della forma. Una percentuale positiva specifica un rientro, mentre una percentuale negativa specifica un'estensione. Lettura/Scrittura float.

**Restituisce:**
float

### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public abstract void setStretchOffsetBottom(float value)
```

Restituisce o imposta il bordo inferiore del rettangolo di riempimento definito da uno scostamento percentuale dal bordo inferiore della bounding box della forma. Una percentuale positiva specifica un rientro, mentre una percentuale negativa specifica un'estensione. Lettura/Scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public abstract IPPImage deletePictureCroppedAreas()
```

Elimina le aree ritagliate dell’immagine di riempimento.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Ottiene il PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Elimina le aree ritagliate dell'immagine del PictureFrame
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Restituisce:**
[IPPImage](../../com.aspose.slides/ippimage) - Immagine ritagliata o immagine di origine se il ritaglio non è necessario.

--------------------

Questo metodo converte i metafili WMF/EMF in un’immagine PNG rasterizzando e ritagliando.
### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

Comprime l’immagine riducendone le dimensioni in base alla dimensione della forma e alla risoluzione specificata. Facoltativamente, elimina anche le aree ritagliate.

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` metodo per ridurre le dimensioni di un’immagine in una presentazione impostando una risoluzione di destinazione e rimuovendo le aree ritagliate:
>  
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Compress the image with a target resolution of 150 DPI (Web resolution) and remove cropped areas
>      boolean result = picFrame.getPictureFormat().compressImage(true, PicturesCompression.Dpi150);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | Se true, il metodo rimuoverà le aree ritagliate dell'immagine, potenzialmente riducendone ulteriormente le dimensioni. |
| resolution | int | La risoluzione target per la compressione, specificata come valore dell'enum [PicturesCompression](../../com.aspose.slides/picturescompression). |

--------------------

Questo metodo modifica le dimensioni e la risoluzione dell'immagine in modo simile alla funzionalità di PowerPoint “Picture Format -> Compress Pictures”.

**Restituisce:**
boolean - Un booleano che indica se l'immagine è stata compressa con successo. Restituisce true se l'immagine è stata ridimensionata o ritagliata, altrimenti false.
### compressImage(boolean deleteCroppedAreasOfImage, float resolution) {#compressImage-boolean-float-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, float resolution)
```


Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

--------------------

> ```
> L’esempio seguente dimostra come utilizzare il metodo ```
> CompressImage
> ``` per ridurre le dimensioni di un’immagine in una presentazione impostando una risoluzione di destinazione e rimuovendo le aree ritagliate:
>   
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Compress the image with a target resolution of 150 DPI (Web resolution) and remove cropped areas
>      boolean result = picFrame.getPictureFormat().compressImage(true, 150f); // Web resolution
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | Se true, il metodo rimuoverà le aree ritagliate dell'immagine, potenzialmente riducendo ulteriormente le sue dimensioni. |
| resolution | float | La risoluzione target in DPI. Questo valore deve essere positivo e definisce come l'immagine sarà ridimensionata.

--------------------

Questo metodo modifica le dimensioni e la risoluzione dell'immagine in modo simile alla funzionalità di PowerPoint “Picture Format -> Compress Pictures”.

**Restituisce:**
boolean - Un booleano che indica se l'immagine è stata compressa con successo. Restituisce true se l'immagine è stata ridimensionata o ritagliata, altrimenti false.
### getTileOffsetX() {#getTileOffsetX--}
```
public abstract float getTileOffsetX()
```


Returns or sets the horizontal offset of the texture from the shape's origin in points. A positive value moves the texture to the right, while a negative value moves it to the left. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the horizontal offset of the texture to 20 points
>      pictureFillFormat.setTileOffsetX(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Restituisce:**
float
### setTileOffsetX(float value) {#setTileOffsetX-float-}
```
public abstract void setTileOffsetX(float value)
```


Returns or sets the horizontal offset of the texture from the shape's origin in points. A positive value moves the texture to the right, while a negative value moves it to the left. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the horizontal offset of the texture to 20 points
>      pictureFillFormat.setTileOffsetX(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getTileOffsetY() {#getTileOffsetY--}
```
public abstract float getTileOffsetY()
```


Returns or sets the vertical offset of the texture from the shape's origin in points. A positive value moves the texture down, while a negative value moves it up. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the vertical offset of the texture to -50 points
>      pictureFillFormat.setTileOffsetY(-50);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**Returns:**
float
### setTileOffsetY(float value) {#setTileOffsetY-float-}
```
public abstract void setTileOffsetY(float value)
```


Returns or sets the vertical offset of the texture from the shape's origin in points. A positive value moves the texture down, while a negative value moves it up. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the vertical offset of the texture to -50 points
>      pictureFillFormat.setTileOffsetY(-50);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileScaleX() {#getTileScaleX--}
```
public abstract float getTileScaleX()
```


Returns or sets the horizontal scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the horizontal scale for the texture to 120 percents
>      pictureFillFormat.setTileScaleX(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
float
### setTileScaleX(float value) {#setTileScaleX-float-}
```
public abstract void setTileScaleX(float value)
```


Returns or sets the horizontal scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the horizontal scale for the texture to 120 percents
>      pictureFillFormat.setTileScaleX(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getTileScaleY() {#getTileScaleY--}
```
public abstract float getTileScaleY()
```


Returns or sets the vertical scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the vertical scale for the texture to 120 percents
>      pictureFillFormat.setTileScaleY(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**Returns:**
float
### setTileScaleY(float value) {#setTileScaleY-float-}
```
public abstract void setTileScaleY(float value)
```


Returns or sets the vertical scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the vertical scale for the texture to 120 percents
>      pictureFillFormat.setTileScaleY(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileAlignment() {#getTileAlignment--}
```
public abstract byte getTileAlignment()
```


Returns or sets how the texture is aligned within the shape. This setting controls the starting point of the texture pattern and how it repeats across the shape. Read/write [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the alignment for the tiling to the right bottom
>      pictureFillFormat.setTileAlignment(RectangleAlignment.BottomRight);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

Default is [RectangleAlignment.TopLeft](../../com.aspose.slides/rectanglealignment\#TopLeft).

**Returns:**
byte
### setTileAlignment(byte value) {#setTileAlignment-byte-}
```
public abstract void setTileAlignment(byte value)
```


Returns or sets how the texture is aligned within the shape. This setting controls the starting point of the texture pattern and how it repeats across the shape. Read/write [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the alignment for the tiling to the right bottom
>      pictureFillFormat.setTileAlignment(RectangleAlignment.BottomRight);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

Il valore predefinito è [RectangleAlignment.TopLeft](../../com.aspose.slides/rectanglealignment\#TopLeft).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```


Flips the texture tile around its horizontal, vertical or both axis. Read/write [TileFlip](../../com.aspose.slides/tileflip).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Flips the texture tile around its vertical axis.
>      pictureFillFormat.setTileFlip(TileFlip.FlipY);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

Default is [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Returns:**
int
### setTileFlip(int value) {#setTileFlip-int-}
```
public abstract void setTileFlip(int value)
```


Flips the texture tile around its horizontal, vertical or both axis. Read/write [TileFlip](../../com.aspose.slides/tileflip).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Flips the texture tile around its vertical axis.
>      pictureFillFormat.setTileFlip(TileFlip.FlipY);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

Il valore predefinito è [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |