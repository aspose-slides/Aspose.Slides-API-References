---
title: GetBounds()
second_title: Aspose.Slides for C++ API 參考
description: 傳回一個 RectangleF 物件，該物件表示在使用指定矩陣變換時，當前物件所表示的路徑的外接矩形。
type: docs
weight: 339
url: /zh-hant/system.drawing.drawing2d/graphicspath/getbounds/
---
## GraphicsPath::GetBounds(const MatrixPtr\&, const SharedPtr\<Pen\>\&) const 方法


傳回一個 [RectangleF](../../../system.drawing/rectanglef/) 物件，該物件表示在使用指定矩陣變換時，當前物件所表示的路徑的外接矩形。


```cpp
RectangleF System::Drawing::Drawing2D::GraphicsPath::GetBounds(const MatrixPtr &matrix=nullptr, const SharedPtr<Pen> &pen=nullptr) const
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | 變換矩陣 |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../../system.drawing/pen/)\>\& | 用於計算外接矩形的 [Pen](../../../system.drawing/pen/) |


## 另請參閱

* Typedef [MatrixPtr](../../matrixptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [RectangleF](../../../system.drawing/rectanglef/)
* 類別 [Pen](../../../system.drawing/pen/)
* 類別 [GraphicsPath](../)
* 命名空間 [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)