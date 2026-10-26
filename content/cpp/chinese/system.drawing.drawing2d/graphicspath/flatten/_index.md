---
title: Flatten()
second_title: Aspose.Slides C++ API 参考
description: 通过将路径中的每条曲线转换为一系列相连的直线来展平它们。使用 0.25 的扁平度值。
type: docs
weight: 391
url: /zh/system.drawing.drawing2d/graphicspath/flatten/
---
## GraphicsPath::Flatten() 方法


将路径中的每条曲线展平，使其转换为一系列相连的直线。使用 0.25 的扁平度值。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten()
```

## GraphicsPath::Flatten(const MatrixPtr\&) 方法


将路径中的每条曲线展平，使其转换为一系列相连的直线。使用 0.25 的扁平度值。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | 在展平之前应用于路径的变换矩阵 |

## GraphicsPath::Flatten(const MatrixPtr\&, float) 方法


将路径中的每条曲线展平，使其转换为一系列相连的直线。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix, float flatness)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | 在展平之前应用于路径的变换矩阵 |
| flatness | **float** | 指定曲线与其展平近似之间允许的最大误差 |

## 另请参见

* Typedef [MatrixPtr](../../matrixptr/)
* Class [GraphicsPath](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)