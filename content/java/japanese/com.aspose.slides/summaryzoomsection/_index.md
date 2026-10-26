---
title: SummaryZoomSection
second_title: Aspose.Slides for Java API リファレンス
description: Summary Zoomフレーム内のSummary Zoom Sectionオブジェクトを表します。
type: docs
url: /ja/com.aspose.slides/summaryzoomsection/
---
**継承:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject), [com.aspose.slides.SectionZoomFrame](../../com.aspose.slides/sectionzoomframe)

**実装インターフェイス:**
[com.aspose.slides.ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
```
public class SummaryZoomSection extends SectionZoomFrame implements ISummaryZoomSection
```

Summary Zoomフレーム内のSummary Zoom Sectionオブジェクトを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getTitle()](#getTitle--) | Summary Zoom Sectionオブジェクトのテキストタイトルを返します。 |
| [setTitle(String value)](#setTitle-java.lang.String-) | Summary Zoom Sectionオブジェクトのテキストタイトルを返します。 |
| [getDescription()](#getDescription--) | Summary Zoom Sectionオブジェクトのテキスト説明を返します。 |
| [setDescription(String value)](#setDescription-java.lang.String-) | Summary Zoom Sectionオブジェクトのテキスト説明を返します。 |
### getTitle() {#getTitle--}
```
public final String getTitle()
```


Summary Zoom Sectionオブジェクトのテキストタイトルを返します。

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


Summary Zoom Sectionオブジェクトのテキストタイトルを返します。

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Summary Zoom Sectionオブジェクトのテキスト説明を返します。

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


Summary Zoom Sectionオブジェクトのテキスト説明を返します。

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |