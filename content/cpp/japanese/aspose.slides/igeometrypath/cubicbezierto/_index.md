---
title: CubicBezierTo()
second_title: C++ 用 Aspose.Slides API リファレンス
description: パスの終端に立方ベジェ曲線を追加します
type: docs
weight: 92
url: /ja/aspose.slides/igeometrypath/cubicbezierto/
---
## IGeometryPath::CubicBezierTo(System::Drawing::PointF, System::Drawing::PointF, System::Drawing::PointF) メソッド

パスの終端に立方ベジェ曲線を追加します

```cpp
virtual void Aspose::Slides::IGeometryPath::CubicBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, System::Drawing::PointF point3)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 最初の方向点 |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 2番目の方向点 |
| point3 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 終了点 |

## IGeometryPath::CubicBezierTo(float, float, float, float, float, float) メソッド

パスの終端に立方ベジェ曲線を追加します

```cpp
virtual void Aspose::Slides::IGeometryPath::CubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| x1 | **float** | 最初の方向点の X 座標 |
| y1 | **float** | 最初の方向点の Y 座標 |
| x2 | **float** | 2番目の方向点の X 座標 |
| y2 | **float** | 2番目の方向点の Y 座標 |
| x3 | **float** | 終了点の X 座標 |
| y3 | **float** | 終了点の Y 座標 |

## IGeometryPath::CubicBezierTo(System::Drawing::PointF, System::Drawing::PointF, System::Drawing::PointF, uint32_t) メソッド

パスの指定した位置に立方ベジェ曲線を追加します

```cpp
virtual void Aspose::Slides::IGeometryPath::CubicBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, System::Drawing::PointF point3, uint32_t index)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 最初の方向点 |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 2番目の方向点 |
| point3 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 終了点 |
| index | **uint32_t** | PathData 内のセグメントインデックス |

## IGeometryPath::CubicBezierTo(float, float, float, float, float, float, uint32_t) メソッド

パスの指定した位置に立方ベジェ曲線を追加します

```cpp
virtual void Aspose::Slides::IGeometryPath::CubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, uint32_t index)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| x1 | **float** | 最初の方向点の X 座標 |
| y1 | **float** | 最初の方向点の Y 座標 |
| x2 | **float** | 2番目の方向点の X 座標 |
| y2 | **float** | 2番目の方向点の Y 座標 |
| x3 | **float** | 終了点の X 座標 |
| y3 | **float** | 終了点の Y 座標 |
| index | **uint32_t** | PathData 内のセグメントインデックス |

## 参照

* クラス [PointF](../../../system.drawing/pointf/)
* クラス [IGeometryPath](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)