---
title: ISmartArtNode class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.smartart/ismartartnode/
---
## ISmartArtNode 类

表示 SmartArt 图表的节点。

ISmartArtNode 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`child_nodes`](/slides/python-net/zh/aspose.slides.smartart/ismartartnode/child_nodes/) | 返回当前节点的所有子节点的集合。<br/>            只读 [`ISmartArtNodeCollection`](/slides/python-net/zh/aspose.slides.smartart/ismartartnodecollection)。 |
| [`shapes`](/slides/python-net/zh/aspose.slides.smartart/ismartartnode/shapes/) | 返回与节点关联的所有形状的集合。<br/>            只读 [`ISmartArtShapeCollection`](/slides/python-net/zh/aspose.slides.smartart/ismartartshapecollection)。 |
| [`text_frame`](/slides/python-net/zh/aspose.slides.smartart/ismartartnode/text_frame/) | 返回或设置节点的文本。<br/>            只读 [`ITextFrame`](/slides/python-net/zh/aspose.slides/itextframe)。 |
| [`is_assistant`](/slides/python-net/zh/aspose.slides.smartart/ismartartnode/is_assistant/) | 返回或设置节点为助理。<br/>            可读写 **bool**。 |
| [`level`](/slides/python-net/zh/aspose.slides.smartart/ismartartnode/level/) | 返回节点的嵌套层级。<br/>            只读 **int**。 |
| [`bullet_fill_format`](/slides/python-net/zh/aspose.slides.smartart/ismartartnode/bullet_fill_format/) | 返回包含节点项目符号填充格式属性的 FillFormat 对象。<br/>            注意：对于某些不提供节点项目符号的 SmartArt 布局，可能返回 None。<br/>            只读 [`IFillFormat`](/slides/python-net/zh/aspose.slides/ifillformat)。 |
| [`position`](/slides/python-net/zh/aspose.slides.smartart/ismartartnode/position/) | 返回或设置节点在同级节点中的零基位置。<br/>            可读写 **int**。 |
| [`is_hidden`](/slides/python-net/zh/aspose.slides.smartart/ismartartnode/is_hidden/) | 如果此节点在数据模型中是隐藏节点，则返回 true。<br/>            只读 **bool**。 |
| [`organization_chart_layout`](/slides/python-net/zh/aspose.slides.smartart/ismartartnode/organization_chart_layout/) | 返回或设置与当前节点关联的组织结构图布局类型。<br/>            可读写 [`OrganizationChartLayoutType`](/slides/python-net/zh/aspose.slides.smartart/organizationchartlayouttype)。 |

## 方法

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/zh/aspose.slides.smartart/ismartartnode/remove/#) | 删除当前节点。 |

### 另见
* 模块 [`aspose.slides.smartart`](/slides/python-net/zh/aspose.slides.smartart)
* 库 [`Aspose.Slides`](/slides/python-net)