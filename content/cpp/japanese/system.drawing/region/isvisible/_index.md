---
title: IsVisible()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された点が現在のオブジェクトで表される領域に含まれているかどうかを判定します。
type: docs
weight: 196
url: /ja/system.drawing/region/isvisible/
---
## Region::IsVisible(const Point\&) const method

指定された点が現在のオブジェクトで表される領域に含まれているかどうかを判定します。

```cpp
bool System::Drawing::Region::IsVisible(const Point &point) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| point | const [Point](../../point/)\& | チェック対象の点 |

## Region::IsVisible(const PointF\&) const method

指定された点が現在のオブジェクトで表される領域に含まれているかどうかを判定します。

```cpp
bool System::Drawing::Region::IsVisible(const PointF &point) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| point | const [PointF](../../pointf/)\& | チェック対象の点 |

## Region::IsVisible(const Rectangle\&) method

指定された矩形の任意の部分が現在のオブジェクトで表される領域に含まれているかどうかを判定します。

```cpp
bool System::Drawing::Region::IsVisible(const Rectangle &rect)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | チェック対象の矩形 |

## Region::IsVisible(const RectangleF\&) method

指定された矩形の任意の部分が現在のオブジェクトで表される領域に含まれているかどうかを判定します。

```cpp
bool System::Drawing::Region::IsVisible(const RectangleF &rect)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | チェック対象の矩形 |

## Region::IsVisible(const Point\&, const SharedPtr\<Graphics\>\&) const method

指定されたグラフィックを使用して、指定された点が現在のオブジェクトで表される領域に含まれているかどうかを判定します。

```cpp
bool System::Drawing::Region::IsVisible(const Point &point, const SharedPtr<Graphics> &graphics) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| point | const [Point](../../point/)\& | チェック対象の点 |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | グラフィック コンテキスト |

## Region::IsVisible(const PointF\&, const SharedPtr\<Graphics\>\&) const method

指定されたグラフィックを使用して、指定された点が現在のオブジェクトで表される領域に含まれているかどうかを判定します。

```cpp
bool System::Drawing::Region::IsVisible(const PointF &point, const SharedPtr<Graphics> &graphics) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| point | const [PointF](../../pointf/)\& | チェック対象の点 |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | グラフィック コンテキスト |

## Region::IsVisible(const Rectangle\&, const SharedPtr\<Graphics\>\&) method

指定されたグラフィックを使用して、指定された矩形の任意の部分が現在のオブジェクトで表される領域に含まれているかどうかを判定します。

```cpp
bool System::Drawing::Region::IsVisible(const Rectangle &rect, const SharedPtr<Graphics> &graphics)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | チェック対象の矩形 |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | グラフィック コンテキスト |

## Region::IsVisible(const RectangleF\&, const SharedPtr\<Graphics\>\&) method

指定されたグラフィックを使用して、指定された矩形の任意の部分が現在のオブジェクトで表される領域に含まれているかどうかを判定します。

```cpp
bool System::Drawing::Region::IsVisible(const RectangleF &rect, const SharedPtr<Graphics> &graphics)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | チェック対象の矩形 |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | グラフィック コンテキスト |

## Region::IsVisible(float, float) const method

指定された点が現在のオブジェクトで表される領域に含まれているかどうかを判定します。

```cpp
bool System::Drawing::Region::IsVisible(float x, float y) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | チェックする点の X 座標 |
| y | **float** | チェックする点の Y 座標 |

## Region::IsVisible(float, float, const SharedPtr\<Graphics\>\&) const method

指定されたグラフィックを使用して、指定された点が現在のオブジェクトで表される領域に含まれているかどうかを判定します。

```cpp
bool System::Drawing::Region::IsVisible(float x, float y, const SharedPtr<Graphics> &graphics) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | チェックする点の X 座標 |
| y | **float** | チェックする点の Y 座標 |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | グラフィック コンテキスト |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Point](../../point/)
* Class [Region](../)
* Class [PointF](../../pointf/)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Class [Graphics](../../graphics/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)