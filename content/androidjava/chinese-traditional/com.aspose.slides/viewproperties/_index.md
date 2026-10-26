---
title: ViewProperties
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 簡報全域檢視屬性。
type: docs
url: /zh-hant/com.aspose.slides/viewproperties/
---
**繼承:**
java.lang.Object

**所有已實作的介面:**
[com.aspose.slides.IViewProperties](../../com.aspose.slides/iviewproperties), com.aspose.slides.IDOMObject
```
public class ViewProperties implements IViewProperties, IDOMObject
```

簡報全域檢視屬性。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getLastView()](#getLastView--) | 指定上次儲存簡報文件時所使用的檢視模式。 |
| [setLastView(int value)](#setLastView-int-) | 指定上次儲存簡報文件時所使用的檢視模式。 |
| [getShowComments()](#getShowComments--) | 指定是否應顯示投影片註解。 |
| [setShowComments(byte value)](#setShowComments-byte-) | 指定是否應顯示投影片註解。 |
| [getNormalViewProperties()](#getNormalViewProperties--) | 表示普通檢視屬性。 |
| [getSlideViewProperties()](#getSlideViewProperties--) | 指定與投影片檢視模式相關的共用檢視屬性。 |
| [getNotesViewProperties()](#getNotesViewProperties--) | 指定與備註檢視模式相關的共用檢視屬性。 |
| [getGridSpacing()](#getGridSpacing--) | 取得或設定用於簡報文件底層格線的間距（以點為單位）。 |
| [setGridSpacing(float value)](#setGridSpacing-float-) | 取得或設定用於簡報文件底層格線的間距（以點為單位）。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getLastView() {#getLastView--}
```
public final int getLastView()
```

指定上次儲存簡報文件時所使用的檢視模式。可讀寫 [ViewType](../../com.aspose.slides/viewtype)。

**返回：**
int
### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```

指定上次儲存簡報文件時所使用的檢視模式。可讀寫 [ViewType](../../com.aspose.slides/viewtype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```

指定是否應顯示投影片註解。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
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

表示普通檢視屬性。普通檢視由三個內容區域組成：投影片本身、一側內容區域以及底部內容區域。唯讀 [INormalViewProperties](../../com.aspose.slides/inormalviewproperties)。

**返回：**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```

指定與投影片檢視模式相關的共用檢視屬性。唯讀 [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)。

**返回：**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```

指定與備註檢視模式相關的共用檢視屬性。唯讀 [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)。

**返回：**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```

取得或設定用於簡報文件底層格線的間距（以點為單位）。可讀寫 float.

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

格線間距值必須為正數。常見的值範圍為 1 毫米（2.8349607 點）至 2 英吋（144 點）。

**返回：**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public final void setGridSpacing(float value)
```

取得或設定用於簡報文件底層格線的間距（以點為單位）。可讀寫 float.

--------------------

> ```
> 以下範例程式碼示範如何在 PowerPoint 簡報中變更格線間距。
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

格線間距值必須為正數。常見的值範圍為 1 毫米（2.8349607 點）至 2 英吋（144 點）。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject