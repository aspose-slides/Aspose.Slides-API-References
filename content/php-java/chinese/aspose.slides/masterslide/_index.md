---
title: MasterSlide
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/masterslide/
---
## MasterSlide 类

 表示演示文稿中的母版幻灯片。
 
### applyExternalThemeToDependingSlides {#applyExternalThemeToDependingSlides}

| 名称 | 描述 |
| --- | --- |
| applyExternalThemeToDependingSlides (String) | 基于当前母版幻灯片创建一个新的母版幻灯片，应用外部主题，并将创建的母版幻灯片应用于所有依赖的幻灯片。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 外部主题文件(.thmx)的路径。 |

 **返回:**
[MasterSlide](../masterslide)

 **异常**

| 错误 | 条件 |
| --- | --- |
 | PptxReadException | 无法应用外部主题时。 |


---


### getBodyStyle {#getBodyStyle}

| 名称 | 描述 |
| --- | --- |
| getBodyStyle () | 返回正文文本的样式。只读 ITextStyle。 |

 **返回:**
[TextStyle](../textstyle)


---


### getDependingSlides {#getDependingSlides}

| 名称 | 描述 |
| --- | --- |
| getDependingSlides () | 返回一个包含所有依赖此母版幻灯片的幻灯片的数组。 |

 **返回:**
[Slide](../slide)


---


### getDrawingGuides {#getDrawingGuides}

| 名称 | 描述 |
| --- | --- |
| getDrawingGuides () | 返回母版幻灯片的绘图参考线集合。只读 IDrawingGuidesCollection |

 **返回:**
[DrawingGuidesCollection](../drawingguidescollection)


---


### getHeaderFooterManager {#getHeaderFooterManager}

| 名称 | 描述 |
| --- | --- |
| getHeaderFooterManager () | 返回母版幻灯片的 HeaderFooter 管理器。只读 IMasterSlideHeaderFooterManager。 |

 **返回:**
[MasterSlideHeaderFooterManager](../masterslideheaderfootermanager)


---


### getLayoutSlides {#getLayoutSlides}

| 名称 | 描述 |
| --- | --- |
| getLayoutSlides () | 返回此母版幻灯片的子布局幻灯片集合。只读 IMasterLayoutSlideCollection。您可以通过使用 ( IPresentation#getLayoutSlides) 属性访问用于添加/插入/删除/克隆布局幻灯片的替代 API。 |

 **返回:**
[MasterLayoutSlideCollection](../masterlayoutslidecollection)


---


### getName {#getName}

| 名称 | 描述 |
| --- | --- |
| getName () | 返回或设置母版幻灯片的名称。读/写 String。 |

 **返回:**
String


---


### getOtherStyle {#getOtherStyle}

| 名称 | 描述 |
| --- | --- |
| getOtherStyle () | 返回其他文本的样式。只读 ITextStyle。 |

 **返回:**
[TextStyle](../textstyle)


---


### getPreserve {#getPreserve}

| 名称 | 描述 |
| --- | --- |
| getPreserve () | 确定当所有跟随该母版的幻灯片被删除时，是否删除相应的母版。注意：Aspose.Slides 永远不会自行删除任何未使用的母版，若要实际删除未使用的母版，请调用 MasterSlideCollection#removeUnused(boolean)。读/写 boolean。 |

 **返回:**
boolean


---


### getShowMasterShapes {#getShowMasterShapes}

| 名称 | 描述 |
| --- | --- |
| getShowMasterShapes () | 指定是否在幻灯片上显示母版幻灯片上的形状。对于母版幻灯片本身，此属性始终返回 false。读/写 boolean。 |

 **返回:**
boolean

 **异常**

| 错误 | 条件 |
| --- | --- |
 | NotSupportedException | 为母版幻灯片设置 {@code true} 时抛出。 |


---


### getThemeManager {#getThemeManager}

| 名称 | 描述 |
| --- | --- |
| getThemeManager () | 返回主题管理器。只读 IMasterThemeManager。 |

 **返回:**
[MasterThemeManager](../masterthememanager)


---


### getTitleStyle {#getTitleStyle}

| 名称 | 描述 |
| --- | --- |
| getTitleStyle () | 返回标题文本的样式。只读 ITextStyle。 |

 **返回:**
[TextStyle](../textstyle)


---


### hasDependingSlides {#hasDependingSlides}

| 名称 | 描述 |
| --- | --- |
| hasDependingSlides () | 如果存在至少一个依赖此母版幻灯片的幻灯片，则返回 true。只读 boolean。 |

 **返回:**
boolean


---


### setName {#setName}

| 名称 | 描述 |
| --- | --- |
| setName (String) | 返回或设置母版幻灯片的名称。读/写 String。 |

 **返回:**
void


---


### setPreserve {#setPreserve}

| 名称 | 描述 |
| --- | --- |
| setPreserve (boolean) | 确定当所有跟随该母版的幻灯片被删除时，是否删除相应的母版。注意：Aspose.Slides 永远不会自行删除任何未使用的母版，若要实际删除未使用的母版，请调用 MasterSlideCollection#removeUnused(boolean)。读/写 boolean。 |

 **返回:**
void


---


### setShowMasterShapes {#setShowMasterShapes}

| 名称 | 描述 |
| --- | --- |
| setShowMasterShapes (boolean) | 指定是否在幻灯片上显示母版幻灯片上的形状。对于母版幻灯片本身，此属性始终返回 false。读/写 boolean。 |

 **返回:**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | NotSupportedException | 为母版幻灯片设置 {@code true} 时抛出。 |


---