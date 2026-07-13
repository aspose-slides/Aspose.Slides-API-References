---
title: PictureFrame
second_title: Aspose.Slides dla Androida - odniesienie do Java API
description: Reprezentuje ramkę z obrazem wewnątrz.
type: docs
url: /pl/com.aspose.slides/pictureframe/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public class PictureFrame extends GeometryShape implements IPictureFrame
```

Reprezentuje ramkę z obrazem wewnątrz.

--------------------

> ```
> The following examples shows how to change Audio Frame Thumbnail.
>  
>  Presentation presentation = new Presentation();
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Dodaje ramkę audio do slajdu w określonej pozycji i rozmiarze.
>      FileInputStream audioStream = new FileInputStream("sample2.mp3");
>      IAudioFrame audioFrame = slide.getShapes().addAudioFrameEmbedded(150, 100, 50, 50, audioStream);
>      audioStream.close();
>      // Dodaje obraz do zasobów prezentacji.
>      FileInputStream imageStream = new FileInputStream("eagle.jpeg");
>      IPPImage audioImage = presentation.getImages().addImage(imageStream);
>      imageStream.close();
>      // Ustawia obraz dla ramki audio.
>      audioFrame.getPictureFormat().getPicture().setImage(audioImage);
>      //Zapisuje zmodyfikowaną prezentację na dysk
>      presentation.save("example_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

## Metody

| Metoda | Opis |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | Zwraca blokady kształtu. |
| [getShapeType()](#getShapeType--) |  |
| [setShapeType(int value)](#setShapeType-int-) |  |
| [getPictureFormat()](#getPictureFormat--) | Zwraca obiekt PictureFillFormat dla ramki obrazu. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Zwraca lub ustawia skalę wysokości (względem oryginalnego rozmiaru obrazu) ramki obrazu. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Zwraca lub ustawia skalę wysokości (względem oryginalnego rozmiaru obrazu) ramki obrazu. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Zwraca lub ustawia skalę szerokości (względem oryginalnego rozmiaru obrazu) ramki obrazu. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Zwraca lub ustawia skalę szerokości (względem oryginalnego rozmiaru obrazu) ramki obrazu. |
| [isCameo()](#isCameo--) | Określa, czy PictureFrame jest obiektem typu Cameo. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public final IPictureFrameLock getPictureFrameLock()
```

Zwraca blokady kształtu. Tylko do odczytu [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**Zwraca:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

Zwraca lub ustawia typ AutoShape dla PictureFrame. Dozwolone są wszystkie elementy zestawu [ShapeType](../../com.aspose.slides/shapetype), z wyjątkiem wszystkich rodzajów linii:

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

Odczyt/zapis [ShapeType](../../com.aspose.slides/shapetype).

**Zwraca:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

Zwraca lub ustawia typ AutoShape dla PictureFrame. Dozwolone są wszystkie elementy zestawu [ShapeType](../../com.aspose.slides/shapetype), z wyjątkiem wszystkich rodzajów linii:

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

Odczyt/zapis [ShapeType](../../com.aspose.slides/shapetype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getPictureFormat() {#getPictureFormat--}
```
public final IPictureFillFormat getPictureFormat()
```

Zwraca obiekt PictureFillFormat dla ramki obrazu. Tylko do odczytu [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Zwraca:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public final float getRelativeScaleHeight()
```

Zwraca lub ustawia skalę wysokości (względem oryginalnego rozmiaru obrazu) ramki obrazu. Wartość 1.0 odpowiada 100%. Odczyt/zapis  float .

**Zwraca:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public final void setRelativeScaleHeight(float value)
```

Zwraca lub ustawia skalę wysokości (względem oryginalnego rozmiaru obrazu) ramki obrazu. Wartość 1.0 odpowiada 100%. Odczyt/zapis  float .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |
### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public final float getRelativeScaleWidth()
```

Zwraca lub ustawia skalę szerokości (względem oryginalnego rozmiaru obrazu) ramki obrazu. Wartość 1.0 odpowiada 100%. Odczyt/zapis  float .

**Zwraca:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public final void setRelativeScaleWidth(float value)
```

Zwraca lub ustawia skalę szerokości (względem oryginalnego rozmiaru obrazu) ramki obrazu. Wartość 1.0 odpowiada 100%. Odczyt/zapis  float .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |
### isCameo() {#isCameo--}
```
public final boolean isCameo()
```

Określa, czy PictureFrame jest obiektem typu Cameo. Tylko do odczytu boolean.

**Zwraca:**
boolean