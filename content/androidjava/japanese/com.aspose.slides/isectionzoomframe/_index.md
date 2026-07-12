---
title: ISectionZoomFrame
second_title: Aspose.Slides for Android の Java API リファレンス
description: スライド内の Section Zoom オブジェクトを表します。
type: docs
url: /ja/com.aspose.slides/isectionzoomframe/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface ISectionZoomFrame extends IZoomObject
```

スライド内の Section Zoom オブジェクトを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Section Zoom オブジェクトがリンクされているセクションオブジェクトを取得または設定します。 |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Section Zoom オブジェクトがリンクされているセクションオブジェクトを取得または設定します。 |
### getTargetSection() {#getTargetSection--}
```
public abstract ISection getTargetSection()
```


Section Zoom オブジェクトがリンクされているセクションオブジェクトを取得または設定します。読み取り/書き込み [ISection](../../com.aspose.slides/isection)。

--------------------

> ```
> This example demonstrates changing target section and creates a new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>       sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public abstract void setTargetSection(ISection value)
```


Section Zoom オブジェクトがリンクされているセクションオブジェクトを取得または設定します。読み取り/書き込み [ISection](../../com.aspose.slides/isection)。

--------------------

> ```
> この例では、ターゲットセクションの変更とセクションズームオブジェクト用の新しい画像の作成を示します:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>       sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |