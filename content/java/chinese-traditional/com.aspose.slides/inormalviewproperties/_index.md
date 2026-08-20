---
title: INormalViewProperties
second_title: Aspose.Slides for Java API Reference
description: Represents normal view properties.
type: docs
url: /zh-hant/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

表示正常視圖屬性。正常視圖由三個內容區域組成：幻燈片本身、側邊內容區域以及底部內容區域。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | 指定當在正常視圖模式的任何內容區域顯示大綱內容時，應用程式是否應顯示圖示。 |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | 指定當在正常視圖模式的任何內容區域顯示大綱內容時，應用程式是否應顯示圖示。 |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | 指定當側邊區域足夠小時，垂直分割條是否應自動縮至最小化狀態。 |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | 指定當側邊區域足夠小時，垂直分割條是否應自動縮至最小化狀態。 |
| [getVerticalBarState()](#getVerticalBarState--) | 指定垂直分割條應顯示的狀態。 |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | 指定垂直分割條應顯示的狀態。 |
| [getHorizontalBarState()](#getHorizontalBarState--) | 指定水平分割條應顯示的狀態。 |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | 指定水平分割條應顯示的狀態。 |
| [getPreferSingleView()](#getPreferSingleView--) | 指定使用者是否偏好在全視窗單一內容區域顯示，而不是具有三個內容區域的標準正常視圖。 |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | 指定使用者是否偏好在全視窗單一內容區域顯示，而不是具有三個內容區域的標準正常視圖。 |
| [getRestoredLeft()](#getRestoredLeft--) | 此元素指定正常視圖側邊內容區域的尺寸，當該區域為可變的還原大小（既非最小化亦非最大化）時。 |
| [getRestoredTop()](#getRestoredTop--) | 此元素指定正常視圖頂部幻燈片區域的尺寸，當該區域為可變的還原大小（既非最小化亦非最大化）時。 |

### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public abstract boolean getShowOutlineIcons()
```

指定當在正常視圖模式的任何內容區域顯示大綱內容時，應用程式是否應顯示圖示。讀寫布林值。

**返回:**  
boolean

### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```

指定當在正常視圖模式的任何內容區域顯示大綱內容時，應用程式是否應顯示圖示。讀寫布林值。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```

指定當側邊區域足夠小時，垂直分割條是否應自動縮至最小化狀態。讀寫布林值。

**返回:**  
boolean

### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```

指定當側邊區域足夠小時，垂直分割條是否應自動縮至最小化狀態。讀寫布林值。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public abstract int getVerticalBarState()
```

指定垂直分割條應顯示的狀態。垂直分割條將幻燈片與側邊內容區域分開。

**返回:**  
int

### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public abstract void setVerticalBarState(int value)
```

指定垂直分割條應顯示的狀態。垂直分割條將幻燈片與側邊內容區域分開。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public abstract int getHorizontalBarState()
```

指定水平分割條應顯示的狀態。水平分割條將幻燈片與幻燈片下方的內容區域分開。

**返回:**  
int

### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public abstract void setHorizontalBarState(int value)
```

指定水平分割條應顯示的狀態。水平分割條將幻燈片與幻燈片下方的內容區域分開。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public abstract boolean getPreferSingleView()
```

指定使用者是否偏好在全視窗單一內容區域顯示，而不是具有三個內容區域的標準正常視圖。若啟用，應用程式可能會選擇將其中一個內容區域顯示於整個視窗。讀寫布林值。

**返回:**  
boolean

### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```

指定使用者是否偏好在全視窗單一內容區域顯示，而不是具有三個內容區域的標準正常視圖。若啟用，應用程式可能會選擇將其中一個內容區域顯示於整個視窗。讀寫布林值。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```

此元素指定正常視圖側邊內容區域的尺寸，當該區域為可變的還原大小（既非最小化亦非最大化）時。唯讀 [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)。

**返回:**  
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)

### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredTop()
```

此元素指定正常視圖頂部幻燈片區域的尺寸，當該區域為可變的還原大小（既非最小化亦非最大化）時。唯讀 [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)。

**返回:**  
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)