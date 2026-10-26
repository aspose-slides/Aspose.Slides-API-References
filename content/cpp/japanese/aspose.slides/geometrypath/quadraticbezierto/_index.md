---
title: QuadraticBezierTo()
second_title: Aspose.Slides for C++ API リファレンス
description: パスの末尾に二次ベジェ曲線を追加します
type: docs
weight: 118
url: /ja/aspose.slides/geometrypath/quadraticbezierto/
---
## GeometryPath::QuadraticBezierTo(System::Drawing::PointF, System::Drawing::PointF) メソッド

パスの末尾に二次ベジェ曲線を追加します

```cpp
void Aspose::Slides::GeometryPath::QuadraticBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 方向点 |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 終点 |

## GeometryPath::QuadraticBezierTo(float, float, float, float) メソッド

パスの末尾に二次ベジェ曲線を追加します

```cpp
void Aspose::Slides::GeometryPath::QuadraticBezierTo(float x1, float y1, float x2, float y2) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x1 | **float** | 方向点の X 座標 |
| y1 | **float** | 方向点の Y 座標 |
| x2 | **float** | 終点の X 座標 |
| y2 | **float** | 終点の Y 座標 |

## GeometryPath::QuadraticBezierTo(System::Drawing::PointF, System::Drawing::PointF, uint32_t) メソッド

パスの指定された場所に二次ベジェ曲線を追加します

```cpp
void Aspose::Slides::GeometryPath::QuadraticBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, uint32_t index) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 方向点 |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 終点 |
| index | **uint32_t** | PathData 内のセグメントのインデックス |

## GeometryPath::QuadraticBezierTo(float, float, float, float, uint32_t) メソッド

パスの指定された場所に二次ベジェ曲線を追加します

```cpp
void Aspose::Slides::GeometryPath::QuadraticBezierTo(float x1, float y1, float x2, float y2, uint32_t index) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x1 | **float** | 方向点の X 座標 |
| y1 | **float** | 方向点の Y 座標 |
| x2 | **float** | 終点の X 座標 |
| y2 | **float** | 終点の Y 座標 |
| index | **uint32_t** | PathData 内のセグメントのインデックス |

## 参照

* クラス [PointF](../../../system.drawing/pointf/)
* クラス [GeometryPath](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)