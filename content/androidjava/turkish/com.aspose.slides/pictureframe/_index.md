---
title: PictureFrame
second_title: Aspose.Slides for Android Java API Referansı
description: İçinde bir resim bulunan bir çerçeveyi temsil eder.
type: docs
url: /tr/com.aspose.slides/pictureframe/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public class PictureFrame extends GeometryShape implements IPictureFrame
```

İçinde bir resim bulunan bir çerçeveyi temsil eder.

--------------------

> ```
> The following examples shows how to change Audio Frame Thumbnail.
>  
>  Presentation presentation = new Presentation();
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Slayta belirtilen konum ve boyutta bir ses çerçevesi ekler.
>      FileInputStream audioStream = new FileInputStream("sample2.mp3");
>      IAudioFrame audioFrame = slide.getShapes().addAudioFrameEmbedded(150, 100, 50, 50, audioStream);
>      audioStream.close();
>      // Sunum kaynaklarına bir resim ekler.
>      FileInputStream imageStream = new FileInputStream("eagle.jpeg");
>      IPPImage audioImage = presentation.getImages().addImage(imageStream);
>      imageStream.close();
>      // Ses çerçevesi için resmi ayarlar.
>      audioFrame.getPictureFormat().getPicture().setImage(audioImage);
>      //Değiştirilmiş sunumu diske kaydeder
>      presentation.save("example_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | Şeklin kilitlerini döndürür. |
| [getShapeType()](#getShapeType--) |  |
| [setShapeType(int value)](#setShapeType-int-) |  |
| [getPictureFormat()](#getPictureFormat--) | Bir resim çerçevesi için PictureFillFormat nesnesini döndürür. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Resim çerçevesinin yüksekliğinin ölçeğini (orijinal resim boyutuna göre) döndürür veya ayarlar. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Resim çerçevesinin yüksekliğinin ölçeğini (orijinal resim boyutuna göre) döndürür veya ayarlar. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Resim çerçevesinin genişliğinin ölçeğini (orijinal resim boyutuna göre) döndürür veya ayarlar. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Resim çerçevesinin genişliğinin ölçeğini (orijinal resim boyutuna göre) döndürür veya ayarlar. |
| [isCameo()](#isCameo--) | PictureFrame'in Cameo nesnesi olup olmadığını belirler. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public final IPictureFrameLock getPictureFrameLock()
```


Şeklin kilitlerini döndürür. Salt okunur [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**Döndürür:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


PictureFrame için AutoShape türünü döndürür veya ayarlar. [ShapeType](../../com.aspose.slides/shapetype) kümesindeki tüm öğeler izin verilir, ancak tüm çizgi çeşitleri hariç:

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

Okunur/yazılabilir [ShapeType](../../com.aspose.slides/shapetype).

**Döndürür:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


PictureFrame için AutoShape türünü döndürür veya ayarlar. [ShapeType](../../com.aspose.slides/shapetype) kümesindeki tüm öğeler izin verilir, ancak tüm çizgi çeşitleri hariç:

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

Okunur/yazılabilir [ShapeType](../../com.aspose.slides/shapetype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPictureFormat() {#getPictureFormat--}
```
public final IPictureFillFormat getPictureFormat()
```


Bir resim çerçevesi için PictureFillFormat nesnesini döndürür. Salt okunur [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Döndürür:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public final float getRelativeScaleHeight()
```


Resim çerçevesinin yüksekliğinin ölçeğini (orijinal resim boyutuna göre) döndürür veya ayarlar. Değer 1.0, %100'e karşılık gelir. Okunur/yazılabilir  float .

**Döndürür:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public final void setRelativeScaleHeight(float value)
```


Resim çerçevesinin yüksekliğinin ölçeğini (orijinal resim boyutuna göre) döndürür veya ayarlar. Değer 1.0, %100'e karşılık gelir. Okunur/yazılabilir  float .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public final float getRelativeScaleWidth()
```


Resim çerçevesinin genişliğinin ölçeğini (orijinal resim boyutuna göre) döndürür veya ayarlar. Değer 1.0, %100'e karşılık gelir. Okunur/yazılabilir  float .

**Döndürür:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public final void setRelativeScaleWidth(float value)
```


Resim çerçevesinin genişliğinin ölçeğini (orijinal resim boyutuna göre) döndürür veya ayarlar. Değer 1.0, %100'e karşılık gelir. Okunur/yazılabilir  float .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### isCameo() {#isCameo--}
```
public final boolean isCameo()
```


PictureFrame'in Cameo nesnesi olup olmadığını belirler. Salt okunur boolean.

**Döndürür:**
boolean