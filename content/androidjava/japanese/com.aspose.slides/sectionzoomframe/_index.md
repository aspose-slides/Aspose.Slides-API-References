---
title: SectionZoomFrame
second_title: Java API リファレンスによる Android 向け Aspose.Slides
description: スライド内の Section Zoom オブジェクトを表します。
type: docs
url: /ja/com.aspose.slides/sectionzoomframe/
---
**継承:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public class SectionZoomFrame extends ZoomObject implements ISectionZoomFrame
```

スライド内の Section Zoom オブジェクトを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Section Zoom オブジェクトがリンクするセクションオブジェクトを取得または設定します。 |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Section Zoom オブジェクトがリンクするセクションオブジェクトを取得または設定します。 |
### getTargetSection() {#getTargetSection--}
```
public final ISection getTargetSection()
```


Section Zoom オブジェクトがリンクするセクションオブジェクトを取得または設定します。 読み取り/書き込み [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> Next example demonstrates changing target section and creates new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>      sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public final void setTargetSection(ISection value)
```


Section Zoom オブジェクトがリンクするセクションオブジェクトを取得または設定します。 読み取り/書き込み [ISection](../../com.aspose.slides/isection)。

--------------------

> ```
> Next example demonstrates changing target section and creates new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>      sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |