---
title: CustomLineCap()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立一個新的 CustomLineCap 類別實例，該實例代表具有指定屬性的使用者自訂線帽。
type: docs
weight: 1
url: /zh-hant/system.drawing.drawing2d/customlinecap/customlinecap/
---
## CustomLineCap::CustomLineCap(const SharedPtr\<GraphicsPath\>\&, const SharedPtr\<GraphicsPath\>\&, LineCap, float) 建構函式

建構一個新的 [CustomLineCap](../) 類別實例，該實例代表具有指定屬性的使用者自訂線帽。

```cpp
System::Drawing::Drawing2D::CustomLineCap::CustomLineCap(const SharedPtr<GraphicsPath> &fillPath, const SharedPtr<GraphicsPath> &strokePath, LineCap baseCap=LineCap::Flat, float baseInset=0)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fillPath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | 指定自訂帽的填充 |
| strokePath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | 指定自訂帽的輪廓 |
| baseCap | [LineCap](../../linecap/) | 建立自訂帽的基礎線帽 |
| baseInset | **float** | 指定線條與帽子之間的距離 |

## 另請參閱

* 列舉 [LineCap](../../linecap/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [GraphicsPath](../../graphicspath/)
* 類別 [CustomLineCap](../)
* 命名空間 [System::Drawing::Drawing2D](../../)
* 函式庫 [Aspose.Slides](../../../)