---
title: PictureFrame
second_title: Aspose.Slides pro Android pomocí referenčního Java API
description: Reprezentuje rám s obrázkem uvnitř.
type: docs
url: /cs/com.aspose.slides/pictureframe/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Všechny implementované rozhraní:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public class PictureFrame extends GeometryShape implements IPictureFrame
```

Reprezentuje rám s obrázkem uvnitř.

--------------------

> ```
> The following examples shows how to change Audio Frame Thumbnail.
>  
>  Presentation presentation = new Presentation();
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Přidá zvukový rámek do snímku se zadanou polohou a velikostí.
>      FileInputStream audioStream = new FileInputStream("sample2.mp3");
>      IAudioFrame audioFrame = slide.getShapes().addAudioFrameEmbedded(150, 100, 50, 50, audioStream);
>      audioStream.close();
>      // Přidá obrázek do prostředků prezentace.
>      FileInputStream imageStream = new FileInputStream("eagle.jpeg");
>      IPPImage audioImage = presentation.getImages().addImage(imageStream);
>      imageStream.close();
>      // Nastaví obrázek pro zvukový rámek.
>      audioFrame.getPictureFormat().getPicture().setImage(audioImage);
>      //Uloží upravenou prezentaci na disk
>      presentation.save("example_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

## Metody

| Metoda | Popis |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | Vrací zámky tvaru. |
| [getShapeType()](#getShapeType--) |  |
| [setShapeType(int value)](#setShapeType-int-) |  |
| [getPictureFormat()](#getPictureFormat--) | Vrací objekt PictureFillFormat pro obrázkový rám. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Vrací nebo nastavuje měřítko výšky (relativně k původní velikosti obrázku) PictureFrame. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Vrací nebo nastavuje měřítko výšky (relativně k původní velikosti obrázku) PictureFrame. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Vrací nebo nastavuje měřítko šířky (relativně k původní velikosti obrázku) PictureFrame. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Vrací nebo nastavuje měřítko šířky (relativně k původní velikosti obrázku) PictureFrame. |
| [isCameo()](#isCameo--) | Určuje, zda je PictureFrame objekt typu Cameo, nebo ne. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public final IPictureFrameLock getPictureFrameLock()
```

Vrací zámky tvaru. Pouze pro čtení [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**Vrací:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

Vrací nebo nastavuje typ AutoShape pro PictureFrame. Jsou povoleny všechny položky ze sady [ShapeType](../../com.aspose.slides/shapetype), kromě všech druhů čar:

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

Čtení/Zápis [ShapeType](../../com.aspose.slides/shapetype).

**Vrací:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

Vrací nebo nastavuje typ AutoShape pro PictureFrame. Jsou povoleny všechny položky ze sady [ShapeType](../../com.aspose.slides/shapetype), kromě všech druhů čar:

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

Čtení/Zápis [ShapeType](../../com.aspose.slides/shapetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getPictureFormat() {#getPictureFormat--}
```
public final IPictureFillFormat getPictureFormat()
```

Vrací objekt PictureFillFormat pro picture frame. Pouze pro čtení [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Vrací:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public final float getRelativeScaleHeight()
```

Vrací nebo nastavuje měřítko výšky (relativně k původní velikosti obrázku) picture frame. Hodnota 1.0 odpovídá 100 %. Čtení/Zápis  float .

**Vrací:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public final void setRelativeScaleHeight(float value)
```

Vrací nebo nastavuje měřítko výšky (relativně k původní velikosti obrázku) picture frame. Hodnota 1.0 odpovídá 100 %. Čtení/Zápis  float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public final float getRelativeScaleWidth()
```

Vrací nebo nastavuje měřítko šířky (relativně k původní velikosti obrázku) picture frame. Hodnota 1.0 odpovídá 100 %. Čtení/Zápis  float .

**Vrací:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public final void setRelativeScaleWidth(float value)
```

Vrací nebo nastavuje měřítko šířky (relativně k původní velikosti obrázku) picture frame. Hodnota 1.0 odpovídá 100 %. Čtení/Zápis  float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### isCameo() {#isCameo--}
```
public final boolean isCameo()
```

Určuje, zda je PictureFrame objekt typu Cameo, nebo ne. Pouze pro čtení boolean.

**Vrací:**
boolean