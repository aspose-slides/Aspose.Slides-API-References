---
title: LineTo()
second_title: Aspose.Slides for C++ API リファレンス
description: パスの末尾に線を追加します
type: docs
weight: 79
url: /ja/aspose.slides/igeometrypath/lineto/
---
## IGeometryPath::LineTo(System::Drawing::PointF) メソッド

パスの末尾に線を追加します

```cpp
virtual void Aspose::Slides::IGeometryPath::LineTo(System::Drawing::PointF point)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [System::Drawing::PointF](../../../system.drawing/pointf/) | 線の終点 |

## IGeometryPath::LineTo(float, float) メソッド

パスの末尾に線を追加します

```cpp
virtual void Aspose::Slides::IGeometryPath::LineTo(float x, float y)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 線の終点のX座標 |
| y | **float** | 線の終点のY座標 |

## IGeometryPath::LineTo(System::Drawing::PointF, uint32_t) メソッド

パスの指定された位置に線を追加します

```cpp
virtual void Aspose::Slides::IGeometryPath::LineTo(System::Drawing::PointF point, uint32_t index)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| point | [System::Drawing::PointF](../../../system.drawing/pointf/) | 終点 |
| index | **uint32_t** | PathData のセグメントのインデックス |

## IGeometryPath::LineTo(float, float, uint32_t) メソッド

パスの指定された位置に線を追加します

```cpp
virtual void Aspose::Slides::IGeometryPath::LineTo(float x, float y, uint32_t index)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 点のX座標 |
| y | **float** | 点のY座標 |
| index | **uint32_t** | PathData のセグメントのインデックス |

## 参照

* クラス [PointF](../../../system.drawing/pointf/)
* クラス [IGeometryPath](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)