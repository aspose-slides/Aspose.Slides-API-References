---
title: IViewProperties
second_title: Aspose.Slides for Android via Java API 參考文件
description: 簡報的全域檢視屬性。
type: docs
url: /zh-hant/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

簡報的全域檢視屬性。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLastView()](#getLastView--) | 指定在最後保存演示文稿時使用的檢視模式。 |
| [setLastView(int value)](#setLastView-int-) | 指定在最後保存演示文稿時使用的檢視模式。 |
| [getShowComments()](#getShowComments--) | 指定是否應顯示投影片註釋。 |
| [setShowComments(byte value)](#setShowComments-byte-) | 指定是否應顯示投影片註釋。 |
| [getSlideViewProperties()](#getSlideViewProperties--) | 指定與投影片檢視模式相關的通用檢視屬性。 |
| [getNotesViewProperties()](#getNotesViewProperties--) | 指定與備註檢視模式相關的通用檢視屬性。 |
| [getNormalViewProperties()](#getNormalViewProperties--) | 表示一般檢視屬性。 |
| [getGridSpacing()](#getGridSpacing--) | 取得或設定簡報文件底層格線的間距（點為單位）。 |
| [setGridSpacing(float value)](#setGridSpacing-float-) | 取得或設定簡報文件底層格線的間距（點為單位）。 |
### getLastView() {#getLastView--}
```
public abstract int getLastView()
```

指定在最後保存演示文稿時使用的檢視模式。 可讀寫 [ViewType](../../com.aspose.slides/viewtype)。

**回傳：**
int
### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```

指定在最後保存演示文稿時使用的檢視模式。 可讀寫 [ViewType](../../com.aspose.slides/viewtype)。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```

指定是否應顯示投影片註釋。 可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**回傳：**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```

指定是否應顯示投影片註釋。 可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```

指定與投影片檢視模式相關的通用檢視屬性。 唯讀 [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)。

**回傳：**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```

指定與備註檢視模式相關的通用檢視屬性。 唯讀 [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)。

**回傳：**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```

表示一般檢視屬性。一般檢視由三個內容區域組成：投影片本身、側邊內容區域與底部內容區域。 唯讀 [INormalViewProperties](../../com.aspose.slides/inormalviewproperties)。

**回傳：**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
```

取得或設定簡報文件底層格線的間距（點為單位）。 可讀寫 float。

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

格線間距值必須為正數。典型的值範圍為 1 mm（2.8349607 點）到 2 英吋（144 點）。

**回傳：**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public abstract void setGridSpacing(float value)
```

取得或設定簡報文件底層格線的間距（點為單位）。 可讀寫 float。

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

格線間距值必須為正數。典型的值範圍為 1 mm（2.8349607 點）到 2 英吋（144 點）。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | float |  |