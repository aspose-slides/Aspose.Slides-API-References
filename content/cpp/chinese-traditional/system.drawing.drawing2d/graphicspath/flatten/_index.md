---
title: Flatten()
second_title: Aspose.Slides for C++ API 參考文件
description: 將路徑中的每條曲線平坦化，將其轉換為一系列相連的直線。使用的平坦度值為 0.25。
type: docs
weight: 391
url: /zh-hant/system.drawing.drawing2d/graphicspath/flatten/
---
## GraphicsPath::Flatten() 方法

將路徑中的每條曲線平坦化，將其轉換為一系列相連的直線。使用的平坦度值為 0.25。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten()
```

## GraphicsPath::Flatten(const MatrixPtr\&) 方法

將路徑中的每條曲線平坦化，將其轉換為一系列相連的直線。使用的平坦度值為 0.25。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | 在平坦化之前套用於路徑的變換矩陣 |

## GraphicsPath::Flatten(const MatrixPtr\&, float) 方法

將路徑中的每條曲線平坦化，將其轉換為一系列相連的直線。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix, float flatness)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | 在平坦化之前套用於路徑的變換矩陣 |
| flatness | **float** | 指定曲線與其平坦化近似之間允許的最大誤差 |

## 另請參閱

* 型別定義 [MatrixPtr](../../matrixptr/)
* 類別 [GraphicsPath](../)
* 命名空間 [System::Drawing::Drawing2D](../../)
* 函式庫 [Aspose.Slides](../../../)