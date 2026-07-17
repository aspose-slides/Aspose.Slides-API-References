---
title: CustomLineCap()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个新的 CustomLineCap 类实例，该实例表示具有指定属性的用户定义线帽。
type: docs
weight: 1
url: /zh/system.drawing.drawing2d/customlinecap/customlinecap/
---
## CustomLineCap::CustomLineCap(const SharedPtr\<GraphicsPath\>\&, const SharedPtr\<GraphicsPath\>\&, LineCap, float) 构造函数

构造一个新的 [CustomLineCap](../) 类实例，该实例表示具有指定属性的用户定义线帽。

```cpp
System::Drawing::Drawing2D::CustomLineCap::CustomLineCap(const SharedPtr<GraphicsPath> &fillPath, const SharedPtr<GraphicsPath> &strokePath, LineCap baseCap=LineCap::Flat, float baseInset=0)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fillPath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | 指定自定义帽的填充 |
| strokePath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | 指定自定义帽的轮廓 |
| baseCap | [LineCap](../../linecap/) | 创建自定义帽的基础线帽 |
| baseInset | **float** | 指定线条与帽之间的距离 |

## 另见

* Enum [LineCap](../../linecap/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsPath](../../graphicspath/)
* Class [CustomLineCap](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)