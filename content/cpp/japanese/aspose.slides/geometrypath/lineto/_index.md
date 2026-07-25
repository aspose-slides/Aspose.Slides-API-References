---
title: LineTo()
second_title: Aspose.Slides for C++ API リファレンス
description: パスの末端に線を追加します
type: docs
weight: 92
url: /ja/aspose.slides/geometrypath/lineto/
---
## GeometryPath::LineTo(System::Drawing::PointF) メソッド

パスの末端に線を追加します

```cpp
void Aspose::Slides::GeometryPath::LineTo(System::Drawing::PointF point) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| point | [System::Drawing::PointF](../../../system.drawing/pointf/) | 線の終点 |

## GeometryPath::LineTo(float, float) メソッド

パスの末端に線を追加します

```cpp
void Aspose::Slides::GeometryPath::LineTo(float x, float y) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 線の終点の X 座標 |
| y | **float** | 線の終点の Y 座標 |

## GeometryPath::LineTo(System::Drawing::PointF, uint32_t) メソッド

パスの指定された場所に線を追加します

```cpp
void Aspose::Slides::GeometryPath::LineTo(System::Drawing::PointF point, uint32_t index) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| point | [System::Drawing::PointF](../../../system.drawing/pointf/) | 終点 |
| index | **uint32_t** | PathData のセグメントのインデックス |

## GeometryPath::LineTo(float, float, uint32_t) メソッド

パスの指定された場所に線を追加します

```cpp
void Aspose::Slides::GeometryPath::LineTo(float x, float y, uint32_t index) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 点の X 座標 |
| y | **float** | 点の Y 座標 |
| index | **uint32_t** | PathData のセグメントのインデックス |

## 参照

* クラス [PointF](../../../system.drawing/pointf/)
* クラス [GeometryPath](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)