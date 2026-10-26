---
title: IZoomObject
second_title: Aspose.Slides for Java API リファレンス
description: スライド内の Zoom オブジェクトを表します。
type: docs
url: /ja/com.aspose.slides/izoomobject/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IZoomObject extends IGraphicalObject
```

スライド内の Zoom オブジェクトを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getImageType()](#getImageType--) | Zoom オブジェクトの画像タイプを取得または設定します。 |
| [setImageType(int value)](#setImageType-int-) | Zoom オブジェクトの画像タイプを取得または設定します。 |
| [getReturnToParent()](#getReturnToParent--) | スライドショーでのナビゲーション動作を取得または設定します。 |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | スライドショーでのナビゲーション動作を取得または設定します。 |
| [getShowBackground()](#getShowBackground--) | Zoom が対象スライドの背景を使用するかどうかを指定する値を取得または設定します。 |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Zoom が対象スライドの背景を使用するかどうかを指定する値を取得または設定します。 |
| [getZoomImage()](#getZoomImage--) | Zoom オブジェクトの画像を取得または設定します。 |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Zoom オブジェクトの画像を取得または設定します。 |
| [getTransitionDuration()](#getTransitionDuration--) | Zoom とスライド間の遷移時間を取得または設定します。 |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Zoom とスライド間の遷移時間を取得または設定します。 |
### getImageType() {#getImageType--}
```
public abstract int getImageType()
```

Zoom オブジェクトの画像タイプを取得または設定します。読み取り/書き込み [ZoomImageType](../../com.aspose.slides/zoomimagetype)。デフォルト値: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>      zoomFrame.setImageType(ZoomImageType.Preview);
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
public abstract void setImageType(int value)
```

Zoom オブジェクトの画像タイプを取得または設定します。読み取り/書き込み [ZoomImageType](../../com.aspose.slides/zoomimagetype)。デフォルト値: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>      zoomFrame.setImageType(ZoomImageType.Preview);
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
public abstract boolean getReturnToParent()
```

スライドショーでのナビゲーション動作を取得または設定します。読み取り/書き込み boolean。デフォルト値: false

--------------------

> ```
> Example:
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

true の場合、プロパティはスライドショーでの親へ戻るナビゲーション動作を指定します。

**戻り値:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```

スライドショーでのナビゲーション動作を取得または設定します。読み取り/書き込み boolean。デフォルト値: false

--------------------

> ```
> Example:
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

true の場合、プロパティはスライドショーでの親へ戻るナビゲーション動作を指定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```

Zoom が対象スライドの背景を使用するかどうかを指定する値を取得または設定します。読み取り/書き込み boolean。デフォルト値: true

--------------------

> ```
> この例は Zoom オブジェクトの画像の背景を削除する方法を示しています:
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
public abstract void setShowBackground(boolean value)
```

Zoom が対象スライドの背景を使用するかどうかを指定する値を取得または設定します。読み取り/書き込み boolean。デフォルト値: true

--------------------

> ```
> The example demonstrates removing the background of an image of a Zoom object:
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
public abstract IPPImage getZoomImage()
```

Zoom オブジェクトの画像を取得または設定します。読み取り/書き込み [IPPImage](../../com.aspose.slides/ippimage)。

--------------------

> ```
> The example demonstrates changing an image of a Zoom object:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      zoomFrame.setImage(image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public abstract void setZoomImage(IPPImage value)
```

Zoom オブジェクトの画像を取得または設定します。読み取り/書き込み [IPPImage](../../com.aspose.slides/ippimage)。

--------------------

> ```
> The example demonstrates changing an image of a Zoom object:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      zoomFrame.setImage(image);
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
public abstract float getTransitionDuration()
```

Zoom とスライド間の遷移時間を取得または設定します。読み取り/書き込み float。デフォルト値: 1.0f

--------------------

> ```
> この例は Zoom とスライド間の遷移時間を変更することを示しています:
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

指定されていない場合 (TransitionDur = 0)、対象スライドの遷移とその遷移に関連付けられたタイミングが使用されます。

**戻り値:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
```

Zoom とスライド間の遷移時間を取得または設定します。読み取り/書き込み float。デフォルト値: 1.0f

--------------------

> ```
> この例は Zoom とスライド間の遷移時間を変更することを示しています:
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

指定されていない場合 (TransitionDur = 0)、対象スライドの遷移とその遷移に関連付けられたタイミングが使用されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |