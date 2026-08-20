---
title: NormalViewProperties
second_title: Aspose.Slides for Java API 參考
description: 代表普通視圖屬性。
type: docs
url: /zh-hant/com.aspose.slides/normalviewproperties/
---
**繼承:**
java.lang.Object

**所有已實作的介面:**
[com.aspose.slides.INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
```
public class NormalViewProperties implements INormalViewProperties
```

代表普通視圖屬性。普通視圖由三個內容區域組成：投影片本身、一個側邊內容區域，以及一個底部內容區域。

--------------------

> ```
> The following example shows how to configure ViewProperties.NormalViewProperties properties of a PowerPoint Presentation.
>  
> //實例化一個代表簡報檔案的簡報物件
> Presentation pres = new Presentation("demo.pptx");
> try {
>     pres.getViewProperties().getNormalViewProperties().setHorizontalBarState(SplitterBarStateType.Restored);
>     pres.getViewProperties().getNormalViewProperties().setVerticalBarState(SplitterBarStateType.Maximized);
>     pres.getViewProperties().getNormalViewProperties().getRestoredTop().setAutoAdjust(true);
>     pres.getViewProperties().getNormalViewProperties().getRestoredTop().setDimensionSize(80);
>     pres.getViewProperties().getNormalViewProperties().setShowOutlineIcons(true);
>     pres.save("presentation_normal_view_state.pptx", SaveFormat.Pptx);
> } finally {
>     if (pres != null) pres.dispose();
> }
> ```

## 方法

| 方法 | 說明 |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | 指定在普通視圖模式的任何內容區域顯示大綱內容時，應用程式是否應顯示圖示。 |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | 指定在普通視圖模式的任何內容區域顯示大綱內容時，應用程式是否應顯示圖示。 |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | 指定當側邊區域足夠小時，垂直分割條是否應自動貼至最小化狀態。 |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | 指定當側邊區域足夠小時，垂直分割條是否應自動貼至最小化狀態。 |
| [getVerticalBarState()](#getVerticalBarState--) | 指定垂直分割條應以何種狀態顯示。 |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | 指定垂直分割條應以何種狀態顯示。 |
| [getHorizontalBarState()](#getHorizontalBarState--) | 指定水平分割條應以何種狀態顯示。 |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | 指定水平分割條應以何種狀態顯示。 |
| [getPreferSingleView()](#getPreferSingleView--) | 指定使用者是否偏好在完整視窗的單一內容區域，而非具有三個內容區域的標準普通視圖。 |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | 指定使用者是否偏好在完整視窗的單一內容區域，而非具有三個內容區域的標準普通視圖。 |
| [getRestoredLeft()](#getRestoredLeft--) | 此元素在側邊內容區域為可變的還原大小（非最小化亦非最大化）時，指定普通視圖的尺寸。 |
| [getRestoredTop()](#getRestoredTop--) | 此元素在頂部投影片區域為可變的還原大小（非最小化亦非最大化）時，指定普通視圖的尺寸。 |

### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public final boolean getShowOutlineIcons()
```

指定在普通視圖模式的任何內容區域顯示大綱內容時，應用程式是否應顯示圖示。讀寫布林值。

**回傳值:**
boolean

### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public final void setShowOutlineIcons(boolean value)
```

指定在普通視圖模式的任何內容區域顯示大綱內容時，應用程式是否應顯示圖示。讀寫布林值。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public final boolean getSnapVerticalSplitter()
```

指定當側邊區域足夠小時，垂直分割條是否應自動貼至最小化狀態。讀寫布林值。

**回傳值:**
boolean

### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public final void setSnapVerticalSplitter(boolean value)
```

指定當側邊區域足夠小時，垂直分割條是否應自動貼至最小化狀態。讀寫布林值。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public final int getVerticalBarState()
```

指定垂直分割條應以何種狀態顯示。垂直分割條將投影片與側邊內容區域分開。

**回傳值:**
int

### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public final void setVerticalBarState(int value)
```

指定垂直分割條應以何種狀態顯示。垂直分割條將投影片與側邊內容區域分開。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public final int getHorizontalBarState()
```

指定水平分割條應以何種狀態顯示。水平分割條將投影片與投影片底下的內容區域分開。

**回傳值:**
int

### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public final void setHorizontalBarState(int value)
```

指定水平分割條應以何種狀態顯示。水平分割條將投影片與投影片底下的內容區域分開。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public final boolean getPreferSingleView()
```

指定使用者是否偏好在完整視窗的單一內容區域，而非具有三個內容區域的標準普通視圖。若啟用，應用程式可能會選擇在整個視窗顯示其中一個內容區域。讀寫布林值。

**回傳值:**
boolean

### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public final void setPreferSingleView(boolean value)
```

指定使用者是否偏好在完整視窗的單一內容區域，而非具有三個內容區域的標準普通視圖。若啟用，應用程式可能會選擇在整個視窗顯示其中一個內容區域。讀寫布林值。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public final INormalViewRestoredProperties getRestoredLeft()
```

此元素在側邊內容區域為可變的還原大小（非最小化亦非最大化）時，指定普通視圖的尺寸。唯讀 [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)。

**回傳值:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)

### getRestoredTop() {#getRestoredTop--}
```
public final INormalViewRestoredProperties getRestoredTop()
```

此元素在頂部投影片區域為可變的還原大小（非最小化亦非最大化）時，指定普通視圖的尺寸。唯讀 [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)。

**回傳值:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)