---
title: LayoutSlide
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs
url: /zh/aspose.slides/layoutslide/
---
## LayoutSlide 类

 表示一个布局幻灯片。

### getDependingSlides {#getDependingSlides}

| 名称 | 描述 |
| --- | --- |
| getDependingSlides () | 返回一个数组，包含所有依赖于此布局幻灯片的幻灯片。 |

 **返回：**
[Slide](../slide)


---


### getDrawingGuides {#getDrawingGuides}

| 名称 | 描述 |
| --- | --- |
| getDrawingGuides () | 返回布局幻灯片的绘图参考线集合。只读 IDrawingGuidesCollection |

 **返回：**
[DrawingGuidesCollection](../drawingguidescollection)


---


### getHeaderFooterManager {#getHeaderFooterManager}

| 名称 | 描述 |
| --- | --- |
| getHeaderFooterManager () | 返回布局幻灯片的页眉页脚管理器。只读 ILayoutSlideHeaderFooterManager. |

 **返回：**
[LayoutSlideHeaderFooterManager](../layoutslideheaderfootermanager)


---


### getLayoutType {#getLayoutType}

| 名称 | 描述 |
| --- | --- |
| getLayoutType () | 返回此布局幻灯片的布局类型。只读 SlideLayoutType. |

 **返回：**
byte


---


### getMasterSlide {#getMasterSlide}

| 名称 | 描述 |
| --- | --- |
| getMasterSlide () | 返回或设置布局的母版幻灯片。读写 IMasterSlide. |

 **返回：**
[MasterSlide](../masterslide)


---


### getPlaceholderManager {#getPlaceholderManager}

| 名称 | 描述 |
| --- | --- |
| getPlaceholderManager () | 返回布局幻灯片的占位符管理器。只读 ILayoutPlaceholderManager. |

 **返回：**
[LayoutPlaceholderManager](../layoutplaceholdermanager)


---


### getShowMasterShapes {#getShowMasterShapes}

| 名称 | 描述 |
| --- | --- |
| getShowMasterShapes () | 指定是否在幻灯片上显示母版幻灯片上的形状。读写 boolean. |

 **返回：**
boolean


---


### getThemeManager {#getThemeManager}

| 名称 | 描述 |
| --- | --- |
| getThemeManager () | 返回覆盖主题管理器。只读 IOverrideThemeManager. |

 **返回：**
[SlideThemeManager](../slidethememanager), [LayoutSlideThemeManager](../layoutslidethememanager), [ChartThemeManager](../chartthememanager), [BaseOverrideThemeManager](../baseoverridethememanager), [NotesSlideThemeManager](../notesslidethememanager)


---


### hasDependingSlides {#hasDependingSlides}

| 名称 | 描述 |
| --- | --- |
| hasDependingSlides () | 如果存在至少一个依赖于此布局幻灯片的幻灯片，则返回 true。只读 boolean. |

 **返回：**
boolean


---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove () | 从演示文稿中移除布局。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | PptxEditException | 如果布局已从演示文稿中移除或布局在演示文稿中被使用（其 HasDependingSlides 属性为 true），则抛出此异常。为避免抛出 PptxEditException，请在此之前检查布局的 HasDependingSlides 属性。 |


---


### setMasterSlide {#setMasterSlide}

| 名称 | 描述 |
| --- | --- |
| setMasterSlide ([MasterSlide](../masterslide)) | 返回或设置布局的母版幻灯片。读写 IMasterSlide. |

 **返回：**
void


---


### setShowMasterShapes {#setShowMasterShapes}

| 名称 | 描述 |
| --- | --- |
| setShowMasterShapes (boolean) | 指定是否在幻灯片上显示母版幻灯片上的形状。读写 boolean. |

 **返回：**
void


---