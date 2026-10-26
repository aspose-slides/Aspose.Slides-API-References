---
title: BaseSlide
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/baseslide/
---
## BaseSlide 类

  表示所有幻灯片类型的通用数据。
 
### createThemeEffective {#createThemeEffective}

| 名称 | 描述 |
| --- | --- |
| createThemeEffective () | 返回此幻灯片的有效主题。 |

 **返回：**
ThemeEffectiveData


---


### equals {#equals}

| 名称 | 描述 |
| --- | --- |
| equals ([MasterHandoutSlide](../masterhandoutslide)) | 确定两个 IBaseSlide 实例是否相等。返回值基于幻灯片的结构和静态内容计算。如果所有形状、样式、文本、动画以及其他设置等都相等，则两个幻灯片相等。比较不考虑唯一标识符的值，例如 SlideId，以及动态内容，例如 Date Placeholder 中的当前日期值。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| slide | [MasterHandoutSlide](../masterhandoutslide) | 要与当前 IBaseSlide 比较的 IBaseSlide。 |

 **返回：**
boolean


---


### equals {#equals}

| 名称 | 描述 |
| --- | --- |
| equals ([BaseSlide](../baseslide)) | 确定两个 IBaseSlide 实例是否相等。返回值基于幻灯片的结构和静态内容计算。如果所有形状、样式、文本、动画以及其他设置等都相等，则两个幻灯片相等。比较不考虑唯一标识符的值，例如 SlideId，以及动态内容，例如 Date Placeholder 中的当前日期值。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| slide | [BaseSlide](../baseslide) | 要与当前 IBaseSlide 比较的 IBaseSlide。 |

 **返回：**
boolean


---


### equals {#equals}

| 名称 | 描述 |
| --- | --- |
| equals ([LayoutSlide](../layoutslide)) | 确定两个 IBaseSlide 实例是否相等。返回值基于幻灯片的结构和静态内容计算。如果所有形状、样式、文本、动画以及其他设置等都相等，则两个幻灯片相等。比较不考虑唯一标识符的值，例如 SlideId，以及动态内容，例如 Date Placeholder 中的当前日期值。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| slide | [LayoutSlide](../layoutslide) | 要与当前 IBaseSlide 比较的 IBaseSlide。 |

 **返回：**
boolean


---


### equals {#equals}

| 名称 | 描述 |
| --- | --- |
| equals ([Slide](../slide)) | 确定两个 IBaseSlide 实例是否相等。返回值基于幻灯片的结构和静态内容计算。如果所有形状、样式、文本、动画以及其他设置等都相等，则两个幻灯片相等。比较不考虑唯一标识符的值，例如 SlideId，以及动态内容，例如 Date Placeholder 中的当前日期值。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| slide | [Slide](../slide) | 要与当前 IBaseSlide 比较的 IBaseSlide。 |

 **返回：**
boolean


---


### equals {#equals}

| 名称 | 描述 |
| --- | --- |
| equals ([MasterSlide](../masterslide)) | 确定两个 IBaseSlide 实例是否相等。返回值基于幻灯片的结构和静态内容计算。如果所有形状、样式、文本、动画以及其他设置等都相等，则两个幻灯片相等。比较不考虑唯一标识符的值，例如 SlideId，以及动态内容，例如 Date Placeholder 中的当前日期值。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| slide | [MasterSlide](../masterslide) | 要与当前 IBaseSlide 比较的 IBaseSlide。 |

 **返回：**
boolean


---


### equals {#equals}

| 名称 | 描述 |
| --- | --- |
| equals ([NotesSlide](../notesslide)) | 确定两个 IBaseSlide 实例是否相等。返回值基于幻灯片的结构和静态内容计算。如果所有形状、样式、文本、动画以及其他设置等都相等，则两个幻灯片相等。比较不考虑唯一标识符的值，例如 SlideId，以及动态内容，例如 Date Placeholder 中的当前日期值。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| slide | [NotesSlide](../notesslide) | 要与当前 IBaseSlide 比较的 IBaseSlide。 |

 **返回：**
boolean


---


### equals {#equals}

| 名称 | 描述 |
| --- | --- |
| equals ([MasterNotesSlide](../masternotesslide)) | 确定两个 IBaseSlide 实例是否相等。返回值基于幻灯片的结构和静态内容计算。如果所有形状、样式、文本、动画以及其他设置等都相等，则两个幻灯片相等。比较不考虑唯一标识符的值，例如 SlideId，以及动态内容，例如 Date Placeholder 中的当前日期值。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| slide | [MasterNotesSlide](../masternotesslide) | 要与当前 IBaseSlide 比较的 IBaseSlide。 |

 **返回：**
boolean


---


### findShapeByAltText {#findShapeByAltText}

| 名称 | 描述 |
| --- | --- |
| findShapeByAltText (String) | 查找具有指定替代文本的形状的首次出现。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| altText | String | 替代文本。 |

 **返回：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### getBackground {#getBackground}

| 名称 | 描述 |
| --- | --- |
| getBackground () | 返回幻灯片的背景。只读 IBackground。 |

 **返回：**
[Background](../background)


---


### getControls {#getControls}

| 名称 | 描述 |
| --- | --- |
| getControls () | 返回幻灯片上 ActiveX 控件的集合。只读 IControlCollection。 |

 **返回：**
[ControlCollection](../controlcollection)


---


### getCustomData {#getCustomData}

| 名称 | 描述 |
| --- | --- |
| getCustomData () | 返回幻灯片的自定义数据。只读 ICustomData。 |

 **返回：**
[CustomData](../customdata)


---


### getHyperlinkQueries {#getHyperlinkQueries}

| 名称 | 描述 |
| --- | --- |
| getHyperlinkQueries () | 提供对包含的超链接的便捷访问。只读 IHyperlinkQueries。 |

 **返回：**
[HyperlinkQueries](../hyperlinkqueries)


---


### getName {#getName}

| 名称 | 描述 |
| --- | --- |
| getName () | 返回或设置幻灯片的名称。读/写 String。 |

 **返回：**
String


---


### getPresentation {#getPresentation}

| 名称 | 描述 |
| --- | --- |
| getPresentation () | 返回 IPresentation 接口。只读 IPresentation。 |

 **返回：**
[Presentation](../presentation)


---


### getShapes {#getShapes}

| 名称 | 描述 |
| --- | --- |
| getShapes () | 返回幻灯片的形状。只读 IShapeCollection。 |

 **返回：**
[ShapeCollection](../shapecollection)


---


### getShowMasterShapes {#getShowMasterShapes}

| 名称 | 描述 |
| --- | --- |
| getShowMasterShapes () | 指定主幻灯片上的形状是否应在幻灯片上显示。对于主幻灯片本身，此属性始终返回 false。读/写 boolean。 |

 **返回：**
boolean

 **异常**

| 错误 | 条件 |
| --- | --- |
 | NotSupportedException | 如果对主幻灯片设置为 true 则抛出。 |


---


### getSlide {#getSlide}

| 名称 | 描述 |
| --- | --- |
| getSlide () |  |

 **返回：**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### getSlideId {#getSlideId}

| 名称 | 描述 |
| --- | --- |
| getSlideId () | 返回幻灯片的 ID。只读 long。 |

 **返回：**
long


---


### getSlideShowTransition {#getSlideShowTransition}

| 名称 | 描述 |
| --- | --- |
| getSlideShowTransition () | 返回 Transition 对象，其中包含关于指定幻灯片在幻灯片放映期间如何前进的信息。只读 ISlideShowTransition。 |

 **返回：**
[SlideShowTransition](../slideshowtransition)


---


### getTimeline {#getTimeline}

| 名称 | 描述 |
| --- | --- |
| getTimeline () | 返回动画时间轴对象。只读 IAnimationTimeLine。 |

 **返回：**
[AnimationTimeLine](../animationtimeline)


---


### joinPortionsWithSameFormatting {#joinPortionsWithSameFormatting}

| 名称 | 描述 |
| --- | --- |
| joinPortionsWithSameFormatting () | 在所有可接受的形状的所有段落中合并具有相同格式的文本段。 |

 **返回：**
void


---


### joinPortionsWithSameFormatting {#joinPortionsWithSameFormatting}

| 名称 | 描述 |
| --- | --- |
| joinPortionsWithSameFormatting ([ShapeCollection](../shapecollection)) | 在所有可接受的形状的所有段落中合并具有相同格式的文本段。 |

 **返回：**
void


---


### setName {#setName}

| 名称 | 描述 |
| --- | --- |
| setName (String) | 返回或设置幻灯片的名称。读/写 String。 |

 **返回：**
void


---


### setShowMasterShapes {#setShowMasterShapes}

| 名称 | 描述 |
| --- | --- |
| setShowMasterShapes (boolean) | 指定主幻灯片上的形状是否应在幻灯片上显示。对于主幻灯片本身，此属性始终返回 false。读/写 boolean。 |

 **返回：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | NotSupportedException | 如果对主幻灯片设置为 true 则抛出。 |


---