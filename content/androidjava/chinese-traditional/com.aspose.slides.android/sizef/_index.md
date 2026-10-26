---
title: SizeF
second_title: Aspose.Slides for Android via Java API 參考
description: 用浮點數值在任意單位中描述寬度和高度尺寸的類別。
type: docs
url: /zh-hant/com.aspose.slides.android/sizef/
---
**繼承:**
java.lang.Object
```
public class SizeF
```

用浮點數值描述寬度和高度的任意單位尺寸類別。

## 建構子

| 建構子 | 描述 |
| --- | --- |
| [SizeF(float width, float height)](#SizeF-float-float-) | 建立一個新的 SizeF 實例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getWidth()](#getWidth--) | 取得尺寸的寬度。 |
| [getHeight()](#getHeight--) | 取得尺寸的高度。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 檢查此尺寸是否等於另一個尺寸。 |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | 以 "WxH" 格式回傳尺寸的字串表示。 |

### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```

建立一個新的 SizeF 實例。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| width | float | 尺寸的寬度 |
| height | float | 尺寸的高度 |

### getWidth() {#getWidth--}
```
public float getWidth()
```

取得尺寸的寬度。

**回傳值:**
float - 寬度

### getHeight() {#getHeight--}
```
public float getHeight()
```

取得尺寸的高度。

**回傳值:**
float - 高度

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

檢查此尺寸是否等於另一個尺寸。

兩個尺寸相等當且僅當它們的寬度和高度皆相同。

為此目的，僅當對每個值套用 Float\#floatToIntBits(float).floatToIntBits(float) 方法時回傳相同的 int 值，才視寬度/高度的 float 值為相同。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**回傳值:**
boolean -  true  如果物件相等，  false  否則

### hashCode() {#hashCode--}
```
public int hashCode()
```



**回傳值:**
int

### toString() {#toString--}
```
public String toString()
```

以 "WxH" 格式回傳尺寸的字串表示。

**回傳值:**
java.lang.String - 尺寸的字串表示