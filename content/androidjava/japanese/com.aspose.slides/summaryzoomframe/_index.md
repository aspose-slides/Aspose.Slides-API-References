---
title: SummaryZoomFrame
second_title: Aspose.Slides for Android の Java API リファレンス
description: スライド内の Summary Zoom オブジェクトを表します。
type: docs
url: /ja/com.aspose.slides/summaryzoomframe/
---
**継承:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**実装されたすべてのインターフェイス:**
[com.aspose.slides.ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)
```
public class SummaryZoomFrame extends GraphicalObject implements ISummaryZoomFrame
```

スライド内の Summary Zoom オブジェクトを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getLayout()](#getLayout--) | フレーム内の Summary Zoom セクションのレイアウトを取得します。 |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Summary Zoom Frame オブジェクトの [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) を取得します。 |
### getLayout() {#getLayout--}
```
public final int getLayout()
```


フレーム内の Summary Zoom セクションのレイアウトを取得します。既定値は GridLayout です。

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>      int layout = zoomFrame.getLayout();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public final ISummaryZoomSectionCollection getSummaryZoomCollection()
```


Summary Zoom Frame オブジェクトの [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) を取得します。

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>      ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)