---
title: Region()
second_title: Aspose.Slides for C++ API リファレンス
description: Region クラスの新しいインスタンスを作成します。
type: docs
weight: 1
url: /ja/system.drawing/region/region/
---
## Region::Region() コンストラクタ

新しい [Region](../) クラスのインスタンスを構築します。

```cpp
System::Drawing::Region::Region()
```

## Region::Region(const RectangleF\&) コンストラクタ

指定された矩形で定義された領域を表す新しい [Region](../) クラスのインスタンスを構築します。

```cpp
System::Drawing::Region::Region(const RectangleF &rect)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | 領域を定義する矩形 |

## Region::Region(const Rectangle\&) コンストラクタ

指定された矩形で定義された領域を表す新しい [Region](../) クラスのインスタンスを構築します。

```cpp
System::Drawing::Region::Region(const Rectangle &rect)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 領域を定義する矩形 |

## Region::Region(const SharedPtr\<Drawing2D::GraphicsPath\>\&) コンストラクタ

指定されたパスで定義された領域を表す新しい [Region](../) クラスのインスタンスを構築します。

```cpp
System::Drawing::Region::Region(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | 領域を定義するパス |

## Region::Region(const SkPath\&) コンストラクタ

```cpp
System::Drawing::Region::Region(const SkPath &path)
```

## Region::Region(const SharedPtr\<Drawing2D::RegionData\>\&) コンストラクタ

指定された RegionData オブジェクトで定義された領域を表す新しい [Region](../) クラスのインスタンスを構築します。

```cpp
System::Drawing::Region::Region(const SharedPtr<Drawing2D::RegionData> &region_data)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| region_data | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::RegionData](../../../system.drawing.drawing2d/regiondata/)\>\& | 領域を定義する RegionData オブジェクト |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Region](../)
* Class [RectangleF](../../rectanglef/)
* Class [Rectangle](../../rectangle/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Class [RegionData](../../../system.drawing.drawing2d/regiondata/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)