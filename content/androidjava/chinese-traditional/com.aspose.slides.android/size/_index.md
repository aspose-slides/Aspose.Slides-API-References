---
title: Size
second_title: Aspose.Slides for Android via Java API 參考
description: 用於描述寬度和高度尺寸的類別，單位為任意單位。
type: docs
url: /zh-hant/com.aspose.slides.android/size/
---
**繼承:**
java.lang.Object
```
public class Size
```

用於描述寬度和高度尺寸的類別，單位為任意單位。
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [Size(int width, int height)](#Size-int-int-) | 建立新的 Size 實例。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getWidth()](#getWidth--) | 取得尺寸的寬度。 |
| [getHeight()](#getHeight--) | 取得尺寸的高度。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 檢查此尺寸是否等於另一個尺寸。 |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | 以 "WxH" 格式返回尺寸的字串表示。 |
### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```

建立新的 Size 實例。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| width | int | 尺寸的寬度 |
| height | int | 尺寸的高度 |
### getWidth() {#getWidth--}
```
public int getWidth()
```

取得尺寸的寬度。

**傳回值:**
int - width
### getHeight() {#getHeight--}
```
public int getHeight()
```

取得尺寸的高度。

**傳回值:**
int - height
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

檢查此尺寸是否等於另一個尺寸。

兩個尺寸相等當且僅當它們的寬度和高度皆相等。

Size 物件永遠不會等於其他類型的物件。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object |  |
**傳回值:**
boolean -  true  如果物件相等，  false  否則
### hashCode() {#hashCode--}
```
public int hashCode()
```

**傳回值:**
int
### toString() {#toString--}
```
public String toString()
```

以 "WxH" 格式返回尺寸的字串表示。

**傳回值:**
java.lang.String - 尺寸的字串表示