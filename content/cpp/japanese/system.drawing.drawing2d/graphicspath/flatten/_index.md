---
title: Flatten()
second_title: Aspose.Slides for C++ API リファレンス
description: パス内の各曲線を連続した直線の系列に変換して平坦化します。フラットネス値 0.25 が使用されます。
type: docs
weight: 391
url: /ja/system.drawing.drawing2d/graphicspath/flatten/
---
## GraphicsPath::Flatten() メソッド

パス内の各曲線を連続した直線の系列に変換して平坦化します。フラットネス値 0.25 が使用されます。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten()
```

## GraphicsPath::Flatten(const MatrixPtr\&) メソッド

パス内の各曲線を連続した直線の系列に変換して平坦化します。フラットネス値 0.25 が使用されます。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | 平坦化前にパスに適用する変換行列 |

## GraphicsPath::Flatten(const MatrixPtr\&, float) メソッド

パス内の各曲線を連続した直線の系列に変換して平坦化します。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix, float flatness)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | 平坦化前にパスに適用する変換行列 |
| flatness | **float** | 曲線と平坦化された近似との間で許容される最大誤差を指定します |

## 参照

* 型定義 [MatrixPtr](../../matrixptr/)
* クラス [GraphicsPath](../)
* 名前空間 [System::Drawing::Drawing2D](../../)
* ライブラリ [Aspose.Slides](../../../)