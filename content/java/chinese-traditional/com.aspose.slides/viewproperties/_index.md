---
title: ViewProperties
second_title: Aspose.Slides for Java API 參考
description: 整體簡報的檢視屬性。
type: docs
url: /zh-hant/com.aspose.slides/viewproperties/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.IViewProperties](../../com.aspose.slides/iviewproperties), com.aspose.slides.IDOMObject
```
public class ViewProperties implements IViewProperties, IDOMObject
```

整個簡報的檢視屬性。
## Methods

| 方法 | 描述 |
| --- | --- |
| [getLastView()](#getLastView--) | 指定簡報文件最後一次儲存時使用的檢視模式。 |
| [setLastView(int value)](#setLastView-int-) | 指定簡報文件最後一次儲存時使用的檢視模式。 |
| [getShowComments()](#getShowComments--) | 指定是否應顯示投影片註解。 |
| [setShowComments(byte value)](#setShowComments-byte-) | 指定是否應顯示投影片註解。 |
| [getNormalViewProperties()](#getNormalViewProperties--) | 表示普通檢視屬性。 |
| [getSlideViewProperties()](#getSlideViewProperties--) | 指定與投影片檢視模式相關的共用檢視屬性。 |
| [getNotesViewProperties()](#getNotesViewProperties--) | 指定與備註檢視模式相關的共用檢視屬性。 |
| [getGridSpacing()](#getGridSpacing--) | 返回或設定應用於簡報文件底層格線的格線間距（單位為點）。 |
| [setGridSpacing(float value)](#setGridSpacing-float-) | 返回或設定應用於簡報文件底層格線的格線間距（單位為點）。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getLastView() {#getLastView--}
```
public final int getLastView()
```

指定簡報文件最後一次儲存時使用的檢視模式。可讀寫 [ViewType](../../com.aspose.slides/viewtype)。

**傳回值：**
int
### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```

指定簡報文件最後一次儲存時使用的檢視模式。可讀寫 [ViewType](../../com.aspose.slides/viewtype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```

指定是否應顯示投影片註解。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**傳回值：**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```

指定是否應顯示投影片註解。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```

表示普通檢視屬性。普通檢視由三個內容區域組成：投影片本身、一個側邊內容區域，以及一個底部內容區域。唯讀 [INormalViewProperties](../../com.aspose.slides/inormalviewproperties)。

**傳回值：**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```

指定與投影片檢視模式相關的共用檢視屬性。唯讀 [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)。

**傳回值：**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```

指定與備註檢視模式相關的共用檢視屬性。唯讀 [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)。

**傳回值：**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```

返回或設定應用於簡報文件底層格線的格線間距（單位為點）。可讀寫 float。

**傳回值：**
float
--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

格線間距值必須為正數。典型的值範圍為 1 毫米（2.8349607 點）至 2 吋（144 點）。

**傳回值：**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public final void setGridSpacing(float value)
```

返回或設定應用於簡報文件底層格線的格線間距（單位為點）。可讀寫 float。

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

格線間距值必須為正數。典型的值範圍為 1 毫米（2.8349607 點）至 2 吋（144 點）。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 物件。唯讀 IDOMObject。

**傳回值：**
com.aspose.slides.IDOMObject