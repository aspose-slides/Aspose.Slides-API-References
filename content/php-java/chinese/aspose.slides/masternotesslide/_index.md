---
title: MasterNotesSlide
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/masternotesslide/
---
## MasterNotesSlide 类

 表示备注的母版幻灯片。
 
### getDrawingGuides {#getDrawingGuides}

| 名称 | 描述 |
| --- | --- |
| getDrawingGuides () | 返回母版备注幻灯片的绘图参考线集合。 只读 IDrawingGuidesCollection |

 **返回：**
[DrawingGuidesCollection](../drawingguidescollection)


---


### getHeaderFooterManager {#getHeaderFooterManager}

| 名称 | 描述 |
| --- | --- |
| getHeaderFooterManager () | 返回母版备注幻灯片的页眉页脚管理器。 只读 IMasterHandoutSlideHeaderFooterManager. |

 **返回：**
[MasterNotesSlideHeaderFooterManager](../masternotesslideheaderfootermanager)


---


### getNotesStyle {#getNotesStyle}

| 名称 | 描述 |
| --- | --- |
| getNotesStyle () | 返回备注文本的样式。 只读 ITextStyle. |

 **返回：**
[TextStyle](../textstyle)


---


### getShowMasterShapes {#getShowMasterShapes}

| 名称 | 描述 |
| --- | --- |
| getShowMasterShapes () | 指定是否在幻灯片上显示母版幻灯片上的形状。 对于母版幻灯片本身，此属性始终返回 false。 可读写 布尔值。 |

 **返回：**
boolean

 **异常**

| 错误 | 条件 |
| --- | --- |
 | NotSupportedException | 为母版幻灯片设置 true 时抛出。 |


---


### getThemeManager {#getThemeManager}

| 名称 | 描述 |
| --- | --- |
| getThemeManager () | 返回主题管理器。 只读 IMasterThemeManager. |

 **返回：**
[MasterThemeManager](../masterthememanager)


---


### setShowMasterShapes {#setShowMasterShapes}

| 名称 | 描述 |
| --- | --- |
| setShowMasterShapes (boolean) | 指定是否在幻灯片上显示母版幻灯片上的形状。 对于母版幻灯片本身，此属性始终返回 false。 可读写 布尔值。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | NotSupportedException | 为母版幻灯片设置 true 时抛出。 |


---