---
title: IViewProperties
second_title: Aspose.Slides for Java API Reference
description: Presentation wide view properties.
type: docs
url: /zh-hant/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

演示文稿範圍的檢視屬性。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getLastView()](#getLastView--) | 指定在最後儲存簡報文件時所使用的檢視模式。 |
| [setLastView(int value)](#setLastView-int-) | 指定在最後儲存簡報文件時所使用的檢視模式。 |
| [getShowComments()](#getShowComments--) | 指定是否應顯示投影片註解。 |
| [setShowComments(byte value)](#setShowComments-byte-) | 指定是否應顯示投影片註解。 |
| [getSlideViewProperties()](#getSlideViewProperties--) | 指定與投影片檢視模式相關的共用檢視屬性。 |
| [getNotesViewProperties()](#getNotesViewProperties--) | 指定與備註檢視模式相關的共用檢視屬性。 |
| [getNormalViewProperties()](#getNormalViewProperties--) | 表示一般檢視屬性。 |
| [getGridSpacing()](#getGridSpacing--) | 傳回或設定在簡報文件底層網格應使用的網格間距（以點為單位）。 |
| [setGridSpacing(float value)](#setGridSpacing-float-) | 傳回或設定在簡報文件底層網格應使用的網格間距（以點為單位）。 |

### getLastView() {#getLastView--}
```
public abstract int getLastView()
```

指定在最後儲存簡報文件時所使用的檢視模式。讀寫 [ViewType](../../com.aspose.slides/viewtype)。

**傳回:**  
int

### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```

指定在最後儲存簡報文件時所使用的檢視模式。讀寫 [ViewType](../../com.aspose.slides/viewtype)。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```

指定是否應顯示投影片註解。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**傳回:**  
byte

### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```

指定是否應顯示投影片註解。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```

指定與投影片檢視模式相關的共用檢視屬性。唯讀 [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)。

**傳回:**  
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)

### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```

指定與備註檢視模式相關的共用檢視屬性。唯讀 [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)。

**傳回:**  
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)

### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```

表示一般檢視屬性。一般檢視由三個內容區域組成：投影片本身、側邊內容區以及底部內容區。唯讀 [INormalViewProperties](../../com.aspose.slides/inormalviewproperties)。

**傳回:**  
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)

### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
```

傳回或設定在簡報文件底層網格應使用的網格間距（以點為單位）。讀寫 float。

**傳回:**  
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

網格間距值必須為正數。典型的值範圍為 1 mm（2.8349607 點）到 2 英吋（144 點）。

**傳回:**  
float

### setGridSpacing(float value) {#setGridSpacing-float-}
```
public abstract void setGridSpacing(float value)
```

傳回或設定在簡報文件底層網格應使用的網格間距（以點為單位）。讀寫 float。

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

網格間距值必須為正數。典型的值範圍為 1 mm（2.8349607 點）到 2 英吋（144 點）。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | float |  |