---
title: ZoomObject
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: スライド内の Zoom オブジェクトを表します。
type: docs
url: /ja/com.aspose.slides/zoomobject/
---
**継承:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)  
```
public class ZoomObject extends GraphicalObject implements IZoomObject
```

スライド内の Zoom オブジェクトを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getImageType()](#getImageType--) | ズーム オブジェクトの画像タイプを取得または設定します。 |
| [setImageType(int value)](#setImageType-int-) | ズーム オブジェクトの画像タイプを取得または設定します。 |
| [getReturnToParent()](#getReturnToParent--) | スライドショーでのナビゲーション動作を取得または設定します。 |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | スライドショーでのナビゲーション動作を取得または設定します。 |
| [getShowBackground()](#getShowBackground--) | Zoom が宛先スライドの背景を使用するかどうかを指定する値を取得または設定します。 |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Zoom が宛先スライドの背景を使用するかどうかを指定する値を取得または設定します。 |
| [getZoomImage()](#getZoomImage--) | ズーム オブジェクトの画像を取得または設定します。 |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | ズーム オブジェクトの画像を取得または設定します。 |
| [getTransitionDuration()](#getTransitionDuration--) | Zoom とスライド間の遷移の期間を取得または設定します。 |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Zoom とスライド間の遷移の期間を取得または設定します。 |

### getImageType() {#getImageType--}
```
public final int getImageType()
```

ズーム オブジェクトの画像タイプを取得または設定します。読み取り/書き込み [ZoomImageType](../../com.aspose.slides/zoomimagetype)。デフォルト値: Preview

--------------------

> ```
> Next example demonstrates changing Image Type to Preview value. 
>  In this case current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>          zoomFrame.setImageType(ZoomImageType.Preview);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Zoom オブジェクトがスライドのプレビューまたはカバー画像を使用しているかどうかを指定します。

**戻り値:**  
int

### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```

ズーム オブジェクトの画像タイプを取得または設定します。読み取り/書き込み [ZoomImageType](../../com.aspose.slides/zoomimagetype)。デフォルト値: Preview

--------------------

> ```
> 次の例は Image Type を Preview 値に変更することを示しています。 
>  この場合、Zoom オブジェクトの現在の画像がスライド画像に変更されます:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>          zoomFrame.setImageType(ZoomImageType.Preview);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Zoom オブジェクトがスライドのプレビューまたはカバー画像を使用しているかどうかを指定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getReturnToParent() {#getReturnToParent--}
```
public final boolean getReturnToParent()
```

スライドショーでのナビゲーション動作を取得または設定します。読み取り/書き込み boolean。デフォルト値: false

--------------------

> ```
> 例:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setReturnToParent(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

プロパティの true 値は、スライドショーでの親への戻りナビゲーション動作を指定します。

**戻り値:**  
boolean

### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public final void setReturnToParent(boolean value)
```

スライドショーでのナビゲーション動作を取得または設定します。読み取り/書き込み boolean。デフォルト値: false

--------------------

> ```
> 例:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setReturnToParent(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

プロパティの true 値は、スライドショーでの親への戻りナビゲーション動作を指定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public final boolean getShowBackground()
```

Zoom が宛先スライドの背景を使用するかどうかを指定する値を取得または設定します。読み取り/書き込み boolean。デフォルト値: true

--------------------

> ```
> この例は Zoom オブジェクトの画像の背景を削除することを示しています:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**  
boolean

### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public final void setShowBackground(boolean value)
```

Zoom が宛先スライドの背景を使用するかどうかを指定する値を取得または設定します。読み取り/書き込み boolean。デフォルト値: true

--------------------

> ```
> この例は Zoom オブジェクトの画像の背景を削除することを示しています:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getZoomImage() {#getZoomImage--}
```
public final IPPImage getZoomImage()
```

ズーム オブジェクトの画像を取得または設定します。読み取り/書き込み [IPPImage](../../com.aspose.slides/ippimage)。

--------------------

> ```
> この例は Zoom オブジェクトの画像を変更することを示しています:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          zoomFrame.setImage(image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**  
[IPPImage](../../com.aspose.slides/ippimage)

### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public final void setZoomImage(IPPImage value)
```

ズーム オブジェクトの画像を取得または設定します。読み取り/書き込み [IPPImage](../../com.aspose.slides/ippimage)。

--------------------

> ```
> この例は Zoom オブジェクトの画像を変更することを示しています:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          zoomFrame.setImage(image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getTransitionDuration() {#getTransitionDuration--}
```
public final float getTransitionDuration()
```

Zoom とスライド間の遷移の期間を取得または設定します。読み取り/書き込み float。デフォルト値: 1.0f

--------------------

> ```
> この例は Zoom とスライド間の遷移の期間を変更することを示しています:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

指定されていない場合 (TransitionDur = 0)、宛先スライドの遷移とその遷移に関連付けられたタイミングが使用されます。

**戻り値:**  
float

### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public final void setTransitionDuration(float value)
```

Zoom とスライド間の遷移の期間を取得または設定します。読み取り/書き込み float。デフォルト値: 1.0f

--------------------

> ```
> この例は Zoom とスライド間の遷移の期間を変更することを示しています:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

指定されていない場合 (TransitionDur = 0)、宛先スライドの遷移とその遷移に関連付けられたタイミングが使用されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |