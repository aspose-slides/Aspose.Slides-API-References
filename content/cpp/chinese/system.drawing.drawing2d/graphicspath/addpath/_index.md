---
title: AddPath()
second_title: Aspose.Slides for C++ API 参考
description: 将指定的路径添加到当前对象所表示的路径中。
type: docs
weight: 222
url: /zh/system.drawing.drawing2d/graphicspath/addpath/
---
## GraphicsPath::AddPath(const SharedPtr\<GraphicsPath\>\&, bool) 方法


将指定的路径添加到当前对象所表示的路径中。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPath(const SharedPtr<GraphicsPath> &path, bool connect)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../)\>\& | 要添加的路径 |
| connect | **bool** | True 指定 **path** 中的最后一个首图形是当前对象所表示的路径的最后一个图形的一部分；false 指定 **path** 中的第一个图形和当前对象所表示的路径的最后一个图形是独立的图形 |

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [GraphicsPath](../)
* 命名空间 [System::Drawing::Drawing2D](../../)
* 库 [Aspose.Slides](../../../)