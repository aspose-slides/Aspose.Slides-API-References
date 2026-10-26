---
title: INormalViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Represents normal view properties.
type: docs
url: /zh-hant/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

表示普通視圖屬性。普通視圖由三個內容區域組成：幻燈片本身、側邊內容區以及底部內容區。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | 指定在普通視圖模式的任何內容區域顯示大綱內容時，應用程式是否應顯示圖示。 |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | 指定在普通視圖模式的任何內容區域顯示大綱內容時，應用程式是否應顯示圖示。 |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | 指定當側邊區域足夠小時，垂直分割線是否應自動收合至最小化狀態。 |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | 指定當側邊區域足夠小時，垂直分割線是否應自動收合至最小化狀態。 |
| [getVerticalBarState()](#getVerticalBarState--) | 指定垂直分割條應顯示的狀態。 |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | 指定垂直分割條應顯示的狀態。 |
| [getHorizontalBarState()](#getHorizontalBarState--) | 指定水平分割條應顯示的狀態。 |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | 指定水平分割條應顯示的狀態。 |
| [getPreferSingleView()](#getPreferSingleView--) | 指定使用者是否偏好以全視窗單一內容區域取代具有三個內容區域的標準普通視圖。 |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | 指定使用者是否偏好以全視窗單一內容區域取代具有三個內容區域的標準普通視圖。 |
| [getRestoredLeft()](#getRestoredLeft--) | 當此區域為可變的還原大小（既非最小化亦非最大化）時，此元素指定普通視圖側邊內容區的大小。 |
| [getRestoredTop()](#getRestoredTop--) | 當此區域為可變的還原大小（既非最小化亦非最大化）時，此元素指定普通視圖上方幻燈片區域的大小。 |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public abstract boolean getShowOutlineIcons()
```

指定在普通視圖模式的任何內容區域顯示大綱內容時，應用程式是否應顯示圖示。讀寫 boolean。

**返回:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```

指定在普通視圖模式的任何內容區域顯示大綱內容時，應用程式是否應顯示圖示。讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```

指定當側邊區域足夠小時，垂直分割線是否應自動收合至最小化狀態。讀寫 boolean。

**返回:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```

指定當側邊區域足夠小時，垂直分割線是否應自動收合至最小化狀態。讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBarState() {#getVerticalBarState--}
```
public abstract int getVerticalBarState()
```

指定垂直分割條應顯示的狀態。垂直分割條將幻燈片與側邊內容區分開。

**返回:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public abstract void setVerticalBarState(int value)
```

指定垂直分割條應顯示的狀態。垂直分割條將幻燈片與側邊內容區分開。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getHorizontalBarState() {#getHorizontalBarState--}
```
public abstract int getHorizontalBarState()
```

指定水平分割條應顯示的狀態。水平分割條將幻燈片與幻燈片下方的內容區分開。

**返回:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public abstract void setHorizontalBarState(int value)
```

指定水平分割條應顯示的狀態。水平分割條將幻燈片與幻燈片下方的內容區分開。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getPreferSingleView() {#getPreferSingleView--}
```
public abstract boolean getPreferSingleView()
```

指定使用者是否偏好以全視窗單一內容區域取代具有三個內容區域的標準普通視圖。若啟用，應用程式可能會選擇將其中一個內容區域顯示於整個視窗。讀寫 boolean。

**返回:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```

指定使用者是否偏好以全視窗單一內容區域取代具有三個內容區域的標準普通視圖。若啟用，應用程式可能會選擇將其中一個內容區域顯示於整個視窗。讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```

此元素指定普通視圖側邊內容區的大小，當此區域為可變的還原大小（既非最小化亦非最大化）。唯讀 [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)。

**返回:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredTop()
```

此元素指定普通視圖上方幻燈片區域的大小，當此區域為可變的還原大小（既非最小化亦非最大化）。唯讀 [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)。

**返回:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)