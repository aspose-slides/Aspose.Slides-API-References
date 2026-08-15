---
title: RectangleF()
second_title: Aspose.Slides for C++ API 參考
description: 建立 RectangleF 物件的新實例，該物件表示一個矩形，其 X 與 Y 座標以及寬度和高度值皆設定為 0。
type: docs
weight: 1
url: /zh-hant/system.drawing/rectanglef/rectanglef/
---
## RectangleF::RectangleF() 建構子

建立 [RectangleF](../) 物件的新實例，該物件表示一個矩形，其 X 與 Y 座標以及寬度與高度值皆設定為 0。

```cpp
System::Drawing::RectangleF::RectangleF()
```

## RectangleF::RectangleF(float, float, float, float) 建構子

建立 [RectangleF](../) 物件的新實例，該物件表示一個矩形，其左上角的座標以及寬度與高度皆為指定值。

```cpp
System::Drawing::RectangleF::RectangleF(float x, float y, float width, float height)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | **float** | 矩形左上角的 X 座標值 |
| y | **float** | 矩形左上角的 Y 座標值 |
| width | **float** | 矩形的寬度 |
| height | **float** | 矩形的高度 |

## RectangleF::RectangleF(const PointF\&, const SizeF\&) 建構子

建立 [RectangleF](../) 物件的新實例，該物件表示一個矩形，其左上角座標以 [PointF](../../pointf/) 類別的實例指定，寬度與高度則以 [SizeF](../../sizef/) 類別的實例指定。

```cpp
System::Drawing::RectangleF::RectangleF(const PointF &location, const SizeF &size)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| location | const [PointF](../../pointf/)\& | 指定矩形左上角的位置 |
| size | const [SizeF](../../sizef/)\& | 指定矩形的寬度與高度 |

## RectangleF::RectangleF(const Rectangle\&) 建構子

建立 [RectangleF](../) 物件的新實例，該物件表示與指定矩形等價的矩形。

```cpp
System::Drawing::RectangleF::RectangleF(const Rectangle &rect)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | [Rectangle](../../rectangle/) 類別的實例，指定欲被建構之物件所代表之矩形的位置與尺寸 |

## 另請參閱

* 類別 [RectangleF](../)
* 類別 [PointF](../../pointf/)
* 類別 [SizeF](../../sizef/)
* 類別 [Rectangle](../../rectangle/)
* 命名空間 [System::Drawing](../../)
* 函式庫 [Aspose.Slides](../../../)