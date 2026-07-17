---
title: get_PathTypes()
second_title: Aspose.Slides for C++ API参考
description: 获取一个字节数组，指定元素路径中每个点的类型。
type: docs
weight: 27
url: /zh/aspose.slides/shapeelement/get_pathtypes/
---
## ShapeElement::get_PathTypes() 方法

获取一个字节数组，指定元素路径中每个点的类型。

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::ShapeElement::get_PathTypes()
```

## 备注

**0** 表示该点是图形的起始点。

**1** 表示该点是线段的两个端点之一。

**3** 表示该点是三次贝塞尔样条的端点或控制点。

**7** 屏蔽除低三位之外的所有位，这三位指示点的类型。

**16** 指定相应的线段为虚线。

**32** 指定该点为标记。

**128** 指定该点是闭合子路径（图形）中的最后一点。

**129** 表示该数据点既是线段的端点也是闭合子路径的最后一点。

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [ShapeElement](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)