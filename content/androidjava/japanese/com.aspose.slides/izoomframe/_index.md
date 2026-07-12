---
title: IZoomFrame
second_title: Aspose.Slides for Android の Java API リファレンス
description: スライド内の Slide Zoom オブジェクトを表します。
type: docs
url: /ja/com.aspose.slides/izoomframe/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface IZoomFrame extends IZoomObject
```

スライド内の Slide Zoom オブジェクトを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Slide Zoom オブジェクトがリンクしているスライド オブジェクトを取得または設定します。 |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Slide Zoom オブジェクトがリンクしているスライド オブジェクトを取得または設定します。 |
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

Slide Zoom オブジェクトがリンクしているスライド オブジェクトを取得または設定します。 読み取り/書き込み [ISlide](../../com.aspose.slides/islide)。

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
public abstract void setTargetSlide(ISlide value)
```

Slide Zoom オブジェクトがリンクしているスライド オブジェクトを取得または設定します。 読み取り/書き込み [ISlide](../../com.aspose.slides/islide)。

--------------------

> ```
> 次の例は、対象スライドを変更し、Slide Zoom オブジェクトの新しい画像を作成することを示しています:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |