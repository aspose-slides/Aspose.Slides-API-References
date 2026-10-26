---
title: MasterHandoutSlide
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/masterhandoutslide/
---
## MasterHandoutSlide 类

 表示用于讲义的主母版幻灯片。
 
### getDrawingGuides {#getDrawingGuides}

| 名称 | 描述 |
| --- | --- |
| getDrawingGuides () | 返回 主母版讲义幻灯片 的绘图参考线集合。只读 IDrawingGuidesCollection |

 **返回:**
[DrawingGuidesCollection](../drawingguidescollection)


---


### getHeaderFooterManager {#getHeaderFooterManager}

| 名称 | 描述 |
| --- | --- |
| getHeaderFooterManager () | 返回主母版讲义幻灯片的 HeaderFooter 管理器。只读 IMasterHandoutSlideHeaderFooterManager. |

 **返回:**
[MasterHandoutSlideHeaderFooterManager](../masterhandoutslideheaderfootermanager)


---


### getShowMasterShapes {#getShowMasterShapes}

| 名称 | 描述 |
| --- | --- |
| getShowMasterShapes () | 指定是否在幻灯片上显示母版幻灯片上的形状。对于母版幻灯片本身，此属性始终返回 false。读/写 boolean. |

 **返回:**
boolean

 **异常**

| 错误 | 条件 |
| --- | --- |
 | NotSupportedException | 如果对母版幻灯片设置为 true 则抛出。 |


---


### getThemeManager {#getThemeManager}

| 名称 | 描述 |
| --- | --- |
| getThemeManager () | 返回主题管理器。只读 IMasterThemeManager. |

 **返回:**
[MasterThemeManager](../masterthememanager)


---


### setShowMasterShapes {#setShowMasterShapes}

| 名称 | 描述 |
| --- | --- |
| setShowMasterShapes (boolean) | 指定是否在幻灯片上显示母版幻灯片上的形状。对于母版幻灯片本身，此属性始终返回 false。读/写 boolean. |

 **返回:**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | NotSupportedException | 如果对母版幻灯片设置为 true 则抛出。 |


---