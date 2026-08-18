---
title: PictureFrame
second_title: Aspose.Slides Java API Referencia
description: Képkeretet ábrázol, amely képet tartalmaz.
type: docs
url: /hu/com.aspose.slides/pictureframe/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Minden megvalósított interfész:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public class PictureFrame extends GeometryShape implements IPictureFrame
```

Képkeretet ábrázol, amely képet tartalmaz.

--------------------

> ```
> The following examples shows how to change Audio Frame Thumbnail.
>  
>  Presentation presentation = new Presentation();
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Hozzáad egy hangkeretet a diára megadott pozícióval és mérettel.
>      FileInputStream audioStream = new FileInputStream("sample2.mp3");
>      IAudioFrame audioFrame = slide.getShapes().addAudioFrameEmbedded(150, 100, 50, 50, audioStream);
>      audioStream.close();
>      // Hozzáad egy képet a prezentáció erőforrásaihoz.
>      FileInputStream imageStream = new FileInputStream("eagle.jpeg");
>      IPPImage audioImage = presentation.getImages().addImage(imageStream);
>      imageStream.close();
>      // Beállítja a képet a hangkerethez.
>      audioFrame.getPictureFormat().getPicture().setImage(audioImage);
>      //Mentse a módosított prezentációt a lemezre
>      presentation.save("example_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

## Metódusok

| Módszer | Leírás |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | Visszaadja az alakzat zárolásait. |
| [getShapeType()](#getShapeType--) |  |
| [setShapeType(int value)](#setShapeType-int-) |  |
| [getPictureFormat()](#getPictureFormat--) | Visszaadja a PictureFillFormat objektumot egy képkerethez. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Visszaadja vagy beállítja a képkeret magasságának (az eredeti képmérettel relatívan) méretarányát. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Visszaadja vagy beállítja a képkeret magasságának (az eredeti képmérettel relatívan) méretarányát. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Visszaadja vagy beállítja a képkeret szélességének (az eredeti képmérettel relatívan) méretarányát. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Visszaadja vagy beállítja a képkeret szélességének (az eredeti képmérettel relatívan) méretarányát. |
| [isCameo()](#isCameo--) | Meghatározza, hogy a PictureFrame Cameo objektum-e vagy sem. |

### getPictureFrameLock() {#getPictureFrameLock--}
```
public final IPictureFrameLock getPictureFrameLock()
```

Visszaadja az alakzat zárolásait. Csak olvasható [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**Visszatér:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)

### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

Visszaadja vagy beállítja az AutoShape típusát egy PictureFrame-hez. A [ShapeType](../../com.aspose.slides/shapetype) halmazban lévő összes elem megengedett, kivéve a különböző vonalakat:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5.

Olvasás/írás [ShapeType](../../com.aspose.slides/shapetype).

**Visszatér:**
int

### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

Visszaadja vagy beállítja az AutoShape típusát egy PictureFrame-hez. A [ShapeType](../../com.aspose.slides/shapetype) halmazban lévő összes elem megengedett, kivéve a különböző vonalakat:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5.

Olvasás/írás [ShapeType](../../com.aspose.slides/shapetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPictureFormat() {#getPictureFormat--}
```
public final IPictureFillFormat getPictureFormat()
```

Visszaadja a PictureFillFormat objektumot egy képkerethez. Csak olvasható [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Visszatér:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public final float getRelativeScaleHeight()
```

Visszaadja vagy beállítja a képkeret magasságának (az eredeti képmérettel relatívan) méretarányát. Az 1,0 érték 100%-nak felel meg. Olvasás/írás  float .

**Visszatér:**
float

### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public final void setRelativeScaleHeight(float value)
```

Visszaadja vagy beállítja a képkeret magasságának (az eredeti képmérettel relatívan) méretarányát. Az 1,0 érték 100%-nak felel meg. Olvasás/írás  float .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public final float getRelativeScaleWidth()
```

Visszaadja vagy beállítja a képkeret szélességének (az eredeti képmérettel relatívan) méretarányát. Az 1,0 érték 100%-nak felel meg. Olvasás/írás  float .

**Visszatér:**
float

### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public final void setRelativeScaleWidth(float value)
```

Visszaadja vagy beállítja a képkeret szélességének (az eredeti képmérettel relatívan) méretarányát. Az 1,0 érték 100%-nak felel meg. Olvasás/írás  float .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### isCameo() {#isCameo--}
```
public final boolean isCameo()
```

Meghatározza, hogy a PictureFrame Cameo objektum-e vagy sem. Csak olvasható boolean.

**Visszatér:**
boolean