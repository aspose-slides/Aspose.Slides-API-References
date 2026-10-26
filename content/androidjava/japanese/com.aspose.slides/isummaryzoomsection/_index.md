---
title: ISummaryZoomSection
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: Summary Zoom フレーム内の Summary Zoom Section オブジェクトを表します。
type: docs
url: /ja/com.aspose.slides/isummaryzoomsection/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public interface ISummaryZoomSection extends ISectionZoomFrame
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
public abstract String getTitle()
```


Summary Zoom Section オブジェクトのテキストタイトルを返します。

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
>  ```

**戻り値:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```


Summary Zoom Section オブジェクトのテキストタイトルを返します。

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
>  ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public abstract String getDescription()
```


Summary Zoom Section オブジェクトのテキスト説明を返します。

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
>  ```

**戻り値:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public abstract void setDescription(String value)
```


Summary Zoom Section オブジェクトのテキスト説明を返します。

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