---
title: FromArgb()
second_title: Aspose.Slides for C++ API 參考文件
description: 建構 Color 類別的實例，以表示指定的顏色。
type: docs
weight: 235
url: /zh-hant/system.drawing/color/fromargb/
---
## Color::FromArgb(int) 方法

建構 [Color](../) 類別的實例，以表示指定的顏色。

```cpp
static Color System::Drawing::Color::FromArgb(int argb)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| argb | int | 要由被建構的物件表示的顏色的 32 位元 ARGB 值 |

### 傳回值

表示指定顏色的物件。

## Color::FromArgb(int, int, int, int) 方法

建構 [Color](../) 類別的實例，以表示指定的顏色。

```cpp
static Color System::Drawing::Color::FromArgb(int alpha, int red, int green, int blue)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| alpha | int | 顏色的 Alpha 成分值 |
| red | int | 顏色的紅色成分值 |
| green | int | 顏色的綠色成分值 |
| blue | int | 顏色的藍色成分值 |

### 傳回值

表示指定顏色的物件。

## Color::FromArgb(int, int, int) 方法

建構 [Color](../) 類別的實例，並將 Alpha 成分設為 0xFF，以表示指定的顏色。

```cpp
static Color System::Drawing::Color::FromArgb(int red, int green, int blue)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| red | int | 顏色的紅色成分值 |
| green | int | 顏色的綠色成分值 |
| blue | int | 顏色的藍色成分值 |

### 傳回值

表示指定顏色的物件。

## Color::FromArgb(int, Color) 方法

建構 [Color](../) 類別的實例，以表示指定的顏色。

```cpp
static Color System::Drawing::Color::FromArgb(int alpha, Color base_color)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| alpha | int | 顏色的 Alpha 成分值 |
| base_color | [Color](../) | 代表要由所建立的物件表示之顏色之紅、綠、藍成分的 [Color](../) 物件實例 |

### 傳回值

表示指定顏色的物件。

## 另請參閱

* 類別 [Color](../)
* 命名空間 [System::Drawing](../../)
* 函式庫 [Aspose.Slides](../../../)