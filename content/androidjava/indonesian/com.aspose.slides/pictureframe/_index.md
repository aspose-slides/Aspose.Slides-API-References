---
title: PictureFrame
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili bingkai dengan gambar di dalamnya.
type: docs
url: /id/com.aspose.slides/pictureframe/
---
**Warisan:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)
```
public class PictureFrame extends GeometryShape implements IPictureFrame
```

Mewakili bingkai dengan gambar di dalamnya.

--------------------

> ```
> The following examples shows how to change Audio Frame Thumbnail.
>  
>  Presentation presentation = new Presentation();
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Menambahkan bingkai audio ke slide dengan posisi dan ukuran yang ditentukan.
>      FileInputStream audioStream = new FileInputStream("sample2.mp3");
>      IAudioFrame audioFrame = slide.getShapes().addAudioFrameEmbedded(150, 100, 50, 50, audioStream);
>      audioStream.close();
>      // Menambahkan gambar ke sumber daya presentasi.
>      FileInputStream imageStream = new FileInputStream("eagle.jpeg");
>      IPPImage audioImage = presentation.getImages().addImage(imageStream);
>      imageStream.close();
>      // Menetapkan gambar untuk bingkai audio.
>      audioFrame.getPictureFormat().getPicture().setImage(audioImage);
>      //Menyimpan presentasi yang dimodifikasi ke disk
>      presentation.save("example_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | Mengembalikan kunci shape. |
| [getShapeType()](#getShapeType--) |  |
| [setShapeType(int value)](#setShapeType-int-) |  |
| [getPictureFormat()](#getPictureFormat--) | Mengembalikan objek PictureFillFormat untuk bingkai gambar. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Mengembalikan atau mengatur skala tinggi (relatif terhadap ukuran gambar asli) dari bingkai gambar. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Mengembalikan atau mengatur skala tinggi (relatif terhadap ukuran gambar asli) dari bingkai gambar. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Mengembalikan atau mengatur skala lebar (relatif terhadap ukuran gambar asli) dari bingkai gambar. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Mengembalikan atau mengatur skala lebar (relatif terhadap ukuran gambar asli) dari bingkai gambar. |
| [isCameo()](#isCameo--) | Menentukan apakah PictureFrame adalah objek Cameo atau tidak. |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public final IPictureFrameLock getPictureFrameLock()
```


Mengembalikan kunci shape. Hanya-baca [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**Mengembalikan:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


Mengembalikan atau mengatur tipe AutoShape untuk PictureFrame. Semua item yang diizinkan dalam set [ShapeType](../../com.aspose.slides/shapetype), kecuali semua jenis garis:

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

Baca/tulis [ShapeType](../../com.aspose.slides/shapetype).

**Mengembalikan:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


Mengembalikan atau mengatur tipe AutoShape untuk PictureFrame. Semua item yang diizinkan dalam set [ShapeType](../../com.aspose.slides/shapetype), kecuali semua jenis garis:

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

Baca/tulis [ShapeType](../../com.aspose.slides/shapetype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getPictureFormat() {#getPictureFormat--}
```
public final IPictureFillFormat getPictureFormat()
```


Mengembalikan objek PictureFillFormat untuk bingkai gambar. Hanya-baca [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Mengembalikan:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public final float getRelativeScaleHeight()
```


Mengembalikan atau mengatur skala tinggi (relatif terhadap ukuran gambar asli) dari bingkai gambar. Nilai 1.0 sesuai dengan 100%. Baca/tulis  float .

**Mengembalikan:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public final void setRelativeScaleHeight(float value)
```


Mengembalikan atau mengatur skala tinggi (relatif terhadap ukuran gambar asli) dari bingkai gambar. Nilai 1.0 sesuai dengan 100%. Baca/tulis  float .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public final float getRelativeScaleWidth()
```


Mengembalikan atau mengatur skala lebar (relatif terhadap ukuran gambar asli) dari bingkai gambar. Nilai 1.0 sesuai dengan 100%. Baca/tulis  float .

**Mengembalikan:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public final void setRelativeScaleWidth(float value)
```


Mengembalikan atau mengatur skala lebar (relatif terhadap ukuran gambar asli) dari bingkai gambar. Nilai 1.0 sesuai dengan 100%. Baca/tulis  float .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### isCameo() {#isCameo--}
```
public final boolean isCameo()
```


Menentukan apakah PictureFrame adalah objek Cameo atau tidak. Hanya-baca boolean.

**Mengembalikan:**
boolean