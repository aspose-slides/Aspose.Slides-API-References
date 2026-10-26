---
title: SummaryZoomSection
second_title: Java API リファレンス（Android 用 Aspose.Slides）
description: Summary Zoom フレーム内の Summary Zoom Section オブジェクトを表します。
type: docs
url: /ja/com.aspose.slides/summaryzoomsection/
---
**継承:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject), [com.aspose.slides.SectionZoomFrame](../../com.aspose.slides/sectionzoomframe)

**実装されたすべてのインターフェイス:**
[com.aspose.slides.ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
```
public class SummaryZoomSection extends SectionZoomFrame implements ISummaryZoomSection
```

Summary Zoom フレーム内の Summary Zoom Section オブジェクトを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getTitle()](#getTitle--) | Summary Zoom Section オブジェクトのテキストタイトルを返します。 |
| [setTitle(String value)](#setTitle-java.lang.String-) | Summary Zoom Section オブジェクトのテキストタイトルを返します。 |
| [getDescription()](#getDescription--) | Summary Zoom Section オブジェクトのテキスト説明を返します。 |
| [setDescription(String value)](#setDescription-java.lang.String-) | Summary Zoom Section オブジェクトのテキスト説明を返します。 |
### getTitle() {#getTitle--}
```
public final String getTitle()
```


Summary Zoom Section オブジェクトのテキストタイトルを返します。

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
> ```

**戻り値:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Summary Zoom Section オブジェクトのテキストタイトルを返します。

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Summary Zoom Section オブジェクトのテキスト説明を返します。

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**戻り値:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```


Summary Zoom Section オブジェクトのテキスト説明を返します。

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |