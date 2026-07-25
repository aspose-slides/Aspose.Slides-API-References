---
title: QuadraticBezierTo()
second_title: Aspose.Slides for C++ API リファレンス
description: パスの末端に二次ベジエ曲線を追加します
type: docs
weight: 105
url: /ja/aspose.slides/igeometrypath/quadraticbezierto/
---
## IGeometryPath::QuadraticBezierTo(System::Drawing::PointF, System::Drawing::PointF) メソッド


パスの末尾に二次ベジエ曲線を追加します

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 方向点 |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 終点 |

## IGeometryPath::QuadraticBezierTo(float, float, float, float) メソッド


パスの末尾に二次ベジエ曲線を追加します

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(float x1, float y1, float x2, float y2)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x1 | **float** | 方向点のX座標 |
| y1 | **float** | 方向点のY座標 |
| x2 | **float** | 終点のX座標 |
| y2 | **float** | 終点のY座標 |

## IGeometryPath::QuadraticBezierTo(System::Drawing::PointF, System::Drawing::PointF, uint32_t) メソッド


パスの指定位置に二次ベジエ曲線を追加します

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, uint32_t index)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 方向点 |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 終点 |
| index | **uint32_t** | PathData内のセグメントのインデックス |

## IGeometryPath::QuadraticBezierTo(float, float, float, float, uint32_t) メソッド


パスの指定位置に二次ベジエ曲線を追加します

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(float x1, float y1, float x2, float y2, uint32_t index)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x1 | **float** | 方向点のX座標 |
| y1 | **float** | 方向点のY座標 |
| x2 | **float** | 終点のX座標 |
| y2 | **float** | 終点のY座標 |
| index | **uint32_t** | PathData内のセグメントのインデックス |

## 参照

* クラス [PointF](../../../system.drawing/pointf/)
* クラス [IGeometryPath](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)