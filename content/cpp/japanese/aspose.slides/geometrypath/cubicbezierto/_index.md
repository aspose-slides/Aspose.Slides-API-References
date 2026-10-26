---
title: CubicBezierTo()
second_title: Aspose.Slides for C++ API リファレンス
description: パスの最後に立方ベジエ曲線を追加します
type: docs
weight: 105
url: /ja/aspose.slides/geometrypath/cubicbezierto/
---
## GeometryPath::CubicBezierTo(System::Drawing::PointF, System::Drawing::PointF, System::Drawing::PointF) メソッド

パスの最後に立方ベジエ曲線を追加します

```cpp
void Aspose::Slides::GeometryPath::CubicBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, System::Drawing::PointF point3) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 最初の方向点 |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 2番目の方向点 |
| point3 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 終点 |

## GeometryPath::CubicBezierTo(float, float, float, float, float, float) メソッド

パスの最後に立方ベジエ曲線を追加します

```cpp
void Aspose::Slides::GeometryPath::CubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| x1 | **float** | 最初の方向点のX座標 |
| y1 | **float** | 最初の方向点のY座標 |
| x2 | **float** | 2番目の方向点のX座標 |
| y2 | **float** | 2番目の方向点のY座標 |
| x3 | **float** | 終点のX座標 |
| y3 | **float** | 終点のY座標 |

## GeometryPath::CubicBezierTo(System::Drawing::PointF, System::Drawing::PointF, System::Drawing::PointF, uint32_t) メソッド

パスの指定された位置に立方ベジエ曲線を追加します

```cpp
void Aspose::Slides::GeometryPath::CubicBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, System::Drawing::PointF point3, uint32_t index) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 最初の方向点 |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 2番目の方向点 |
| point3 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 終点 |
| index | **uint32_t** | PathData のセグメントのインデックス |

## GeometryPath::CubicBezierTo(float, float, float, float, float, float, uint32_t) メソッド

パスの指定された位置に立方ベジエ曲線を追加します

```cpp
void Aspose::Slides::GeometryPath::CubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, uint32_t index) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| x1 | **float** | 最初の方向点のX座標 |
| y1 | **float** | 最初の方向点のY座標 |
| x2 | **float** | 2番目の方向点のX座標 |
| y2 | **float** | 2番目の方向点のY座標 |
| x3 | **float** | 終点のX座標 |
| y3 | **float** | 終点のY座標 |
| index | **uint32_t** | PathData のセグメントのインデックス |

## 参照

* クラス [PointF](../../../system.drawing/pointf/)
* クラス [GeometryPath](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)