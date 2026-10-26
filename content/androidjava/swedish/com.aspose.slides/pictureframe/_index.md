---
title: PictureFrame
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en ram med en bild inuti.
type: docs
url: /sv/com.aspose.slides/pictureframe/
---
**Arv:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public class PictureFrame extends GeometryShape implements IPictureFrame
```

Representerar en ram med en bild inuti.

--------------------

> ```
> The following examples shows how to change Audio Frame Thumbnail.
>  
>  Presentation presentation = new Presentation();
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Lägger till en ljudram på bilden med en specificerad position och storlek.
>      FileInputStream audioStream = new FileInputStream("sample2.mp3");
>      IAudioFrame audioFrame = slide.getShapes().addAudioFrameEmbedded(150, 100, 50, 50, audioStream);
>      audioStream.close();
>      // Lägger till en bild i presentationens resurser.
>      FileInputStream imageStream = new FileInputStream("eagle.jpeg");
>      IPPImage audioImage = presentation.getImages().addImage(imageStream);
>      imageStream.close();
>      // Ställer in bilden för ljudramen.
>      audioFrame.getPictureFormat().getPicture().setImage(audioImage);
>      //Sparar den modifierade presentationen till disk
>      presentation.save("example_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | Returnerar formens lås. |
| [getShapeType()](#getShapeType--) |  |
| [setShapeType(int value)](#setShapeType-int-) |  |
| [getPictureFormat()](#getPictureFormat--) | Returnerar PictureFillFormat-objektet för en bildram. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Returnerar eller ställer in skalan för höjden (i förhållande till originalbildens storlek) för bildramen. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Returnerar eller ställer in skalan för höjden (i förhållande till originalbildens storlek) för bildramen. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Returnerar eller ställer in breddens skala (i förhållande till originalbildens storlek) för bildramen. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Returnerar eller ställer in breddens skala (i förhållande till originalbildens storlek) för bildramen. |
| [isCameo()](#isCameo--) | Bestämmer om PictureFrame är ett Cameo-objekt eller inte. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public final IPictureFrameLock getPictureFrameLock()
```

Returnerar formens lås. Endast läsning [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**Returnerar:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

Returnerar eller ställer in AutoShape-typen för en PictureFrame. Det finns tillåtna alla objekt i mängden [ShapeType](../../com.aspose.slides/shapetype), förutom alla typer av linjer:

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

Läs/skriv [ShapeType](../../com.aspose.slides/shapetype).

**Returnerar:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

Returnerar eller ställer in AutoShape-typen för en PictureFrame. Det finns tillåtna alla objekt i mängden [ShapeType](../../com.aspose.slides/shapetype), förutom alla typer av linjer:

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

Läs/skriv [ShapeType](../../com.aspose.slides/shapetype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getPictureFormat() {#getPictureFormat--}
```
public final IPictureFillFormat getPictureFormat()
```

Returnerar PictureFillFormat-objektet för en bildram. Endast läsning [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Returnerar:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public final float getRelativeScaleHeight()
```

Returnerar eller ställer in skalan för höjden (i förhållande till originalbildens storlek) för bildramen. Värde 1.0 motsvarar 100 %. Läs/skriv float .

**Returnerar:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public final void setRelativeScaleHeight(float value)
```

Returnerar eller ställer in skalan för höjden (i förhållande till originalbildens storlek) för bildramen. Värde 1.0 motsvarar 100 %. Läs/skriv float .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public final float getRelativeScaleWidth()
```

Returnerar eller ställer in breddens skala (i förhållande till originalbildens storlek) för bildramen. Värde 1.0 motsvarar 100 %. Läs/skriv float .

**Returnerar:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public final void setRelativeScaleWidth(float value)
```

Returnerar eller ställer in breddens skala (i förhållande till originalbildens storlek) för bildramen. Värde 1.0 motsvarar 100 %. Läs/skriv float .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### isCameo() {#isCameo--}
```
public final boolean isCameo()
```

Bestämmer om PictureFrame är ett Cameo-objekt eller inte. Endast läsning boolean.

**Returnerar:**
boolean