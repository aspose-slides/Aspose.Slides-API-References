---
title: ISummaryZoomFrame
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: スライド内の Summary Zoom フレームを表します。
type: docs
url: /ja/com.aspose.slides/isummaryzoomframe/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISummaryZoomFrame extends IGraphicalObject
```

スライド内の Summary Zoom フレームを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getLayout()](#getLayout--) | フレーム内の Summary Zoom Sections のレイアウトを取得します。 |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Summary Zoom Frame オブジェクトの [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) を取得します。 |
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```


フレーム内の Summary Zoom Sections のレイアウトを取得します。デフォルト値は GridLayout です。

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       int layout = zoomFrame.getLayout();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public abstract ISummaryZoomSectionCollection getSummaryZoomCollection()
```


Summary Zoom Frame オブジェクトの [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) を取得します。

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)