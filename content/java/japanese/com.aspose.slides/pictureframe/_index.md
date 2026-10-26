---
title: PictureFrame
second_title: Aspose.Slides for Java API リファレンス
description: 画像が内部にあるフレームを表します。
type: docs
url: /ja/com.aspose.slides/pictureframe/
---
**継承:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IPictureFrame](../../com.aspose.slides/ipictureframe)  
```
public class PictureFrame extends GeometryShape implements IPictureFrame
```

画像が内部にあるフレームを表します。

--------------------

> ```
> The following examples shows how to change Audio Frame Thumbnail.
>  
>  Presentation presentation = new Presentation();
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Adds an audio frame to the slide with a specified position and size.
>      FileInputStream audioStream = new FileInputStream("sample2.mp3");
>      IAudioFrame audioFrame = slide.getShapes().addAudioFrameEmbedded(150, 100, 50, 50, audioStream);
>      audioStream.close();
>      // Adds an image to presentation resources.
>      FileInputStream imageStream = new FileInputStream("eagle.jpeg");
>      IPPImage audioImage = presentation.getImages().addImage(imageStream);
>      imageStream.close();
>      // Sets the image for the audio frame.
>      audioFrame.getPictureFormat().getPicture().setImage(audioImage);
>      //Saves the modified presentation to disk
>      presentation.save("example_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | シェイプのロックを返します。 |
| [getShapeType()](#getShapeType--) |  |
| [setShapeType(int value)](#setShapeType-int-) |  |
| [getPictureFormat()](#getPictureFormat--) | 画像フレームの PictureFillFormat オブジェクトを返します。 |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | 画像フレームの高さのスケール（元の画像サイズに対する相対）を取得または設定します。 |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | 画像フレームの高さのスケール（元の画像サイズに対する相対）を取得または設定します。 |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | 画像フレームの幅のスケール（元の画像サイズに対する相対）を取得または設定します。 |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | 画像フレームの幅のスケール（元の画像サイズに対する相対）を取得または設定します。 |
| [isCameo()](#isCameo--) | PictureFrame が Cameo オブジェクトかどうかを判定します。 |

### getPictureFrameLock() {#getPictureFrameLock--}
```
public final IPictureFrameLock getPictureFrameLock()
```

シェイプのロックを返します。 読み取り専用 [IPictureFrameLock](../../com.aspose.slides/ipictureframelock)。

**戻り値:**  
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)

### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

PictureFrame の AutoShape タイプを取得または設定します。 [ShapeType](../../com.aspose.slides/shapetype) セットのすべての項目が使用可能ですが、すべての種類の線は除きます:
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

読み書き [ShapeType](../../com.aspose.slides/shapetype)。

**戻り値:**  
int

### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

PictureFrame の AutoShape タイプを取得または設定します。 [ShapeType](../../com.aspose.slides/shapetype) セットのすべての項目が使用可能ですが、すべての種類の線は除きます:
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

読み書き [ShapeType](../../com.aspose.slides/shapetype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPictureFormat() {#getPictureFormat--}
```
public final IPictureFillFormat getPictureFormat()
```

画像フレームの PictureFillFormat オブジェクトを返します。 読み取り専用 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)。

**戻り値:**  
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public final float getRelativeScaleHeight()
```

画像フレームの高さのスケール（元の画像サイズに対する相対）を取得または設定します。値 1.0 は 100% に相当します。読み書き  float .

**戻り値:**  
float

### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public final void setRelativeScaleHeight(float value)
```

画像フレームの高さのスケール（元の画像サイズに対する相対）を取得または設定します。値 1.0 は 100% に相当します。読み書き  float .

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public final float getRelativeScaleWidth()
```

画像フレームの幅のスケール（元の画像サイズに対する相対）を取得または設定します。値 1.0 は 100% に相当します。読み書き  float .

**戻り値:**  
float

### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public final void setRelativeScaleWidth(float value)
```

画像フレームの幅のスケール（元の画像サイズに対する相対）を取得または設定します。値 1.0 は 100% に相当します。読み書き  float .

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### isCameo() {#isCameo--}
```
public final boolean isCameo()
```

PictureFrame が Cameo オブジェクトかどうかを判定します。 読み取り専用 boolean。

**戻り値:**  
boolean