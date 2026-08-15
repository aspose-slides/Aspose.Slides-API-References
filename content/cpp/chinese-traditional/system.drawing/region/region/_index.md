---
title: Region()
second_title: Aspose.Slides for C++ API 參考
description: 建立 Region 類別的新實例。
type: docs
weight: 1
url: /zh-hant/system.drawing/region/region/
---
## Region::Region() 建構子

建立 [Region](../) 類別的新實例。

```cpp
System::Drawing::Region::Region()
```

## Region::Region(const RectangleF&) 建構子

建立 [Region](../) 類別的新實例，該實例表示由指定矩形定義的區域。

```cpp
System::Drawing::Region::Region(const RectangleF &rect)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | 定義區域的矩形 |

## Region::Region(const Rectangle&) 建構子

建立 [Region](../) 類別的新實例，該實例表示由指定矩形定義的區域。

```cpp
System::Drawing::Region::Region(const Rectangle &rect)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 定義區域的矩形 |

## Region::Region(const SharedPtr\<Drawing2D::GraphicsPath\>\&) 建構子

建立 [Region](../) 類別的新實例，該實例表示由指定路徑定義的區域。

```cpp
System::Drawing::Region::Region(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | 定義區域的路徑 |

## Region::Region(const SkPath&) 建構子




```cpp
System::Drawing::Region::Region(const SkPath &path)
```

## Region::Region(const SharedPtr\<Drawing2D::RegionData\>\&) 建構子

建立 [Region](../) 類別的新實例，該實例表示由指定 RegionData 物件定義的區域。

```cpp
System::Drawing::Region::Region(const SharedPtr<Drawing2D::RegionData> &region_data)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| region_data | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::RegionData](../../../system.drawing.drawing2d/regiondata/)\>\& | 定義區域的 RegionData 物件 |

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Region](../)
* 類別 [RectangleF](../../rectanglef/)
* 類別 [Rectangle](../../rectangle/)
* 類別 [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* 類別 [RegionData](../../../system.drawing.drawing2d/regiondata/)
* 命名空間 [System::Drawing](../../)
* 函式庫 [Aspose.Slides](../../../)