---
title: ZoomFrame
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: スライド内の Slide Zoom オブジェクトを表します。
type: docs
url: /ja/com.aspose.slides/zoomframe/
---
**継承:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IZoomFrame](../../com.aspose.slides/izoomframe)  
```
public class ZoomFrame extends ZoomObject implements IZoomFrame
```

スライド内の Slide Zoom オブジェクトを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Slide Zoom オブジェクトがリンクするスライドオブジェクトを取得または設定します。 |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Slide Zoom オブジェクトがリンクするスライドオブジェクトを取得または設定します。 |

### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

Slide Zoom オブジェクトがリンクするスライドオブジェクトを取得または設定します。読み取り/書き込み [ISlide](../../com.aspose.slides/islide)。

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```


**戻り値:**  
[ISlide](../../com.aspose.slides/islide)

### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public final void setTargetSlide(ISlide value)
```

Slide Zoom オブジェクトがリンクするスライドオブジェクトを取得または設定します。読み取り/書き込み [ISlide](../../com.aspose.slides/islide)。

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```


**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |