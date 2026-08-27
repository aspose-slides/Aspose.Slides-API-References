---
title: ViewProperties
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs
url: /zh/aspose.slides/viewproperties/
---
## ViewProperties 类

 整个演示文稿的视图属性。
 
### getGridSpacing {#getGridSpacing}

| 名称 | 描述 |
| --- | --- |
| getGridSpacing () | 返回或设置应用于演示文稿底层网格的网格间距，单位为点。读/写 float。网格间距值必须为正数。典型值范围为 1 mm (2.8349607 points) 到 2 英寸 (144 points)。 |

 **返回：**
float


---


### getLastView {#getLastView}

| 名称 | 描述 |
| --- | --- |
| getLastView () | 指定演示文稿上次保存时使用的视图模式。读/写 ViewType。 |

 **返回：**
int


---


### getNormalViewProperties {#getNormalViewProperties}

| 名称 | 描述 |
| --- | --- |
| getNormalViewProperties () | 表示普通视图属性。普通视图由三个内容区域组成：幻灯片本身、侧边内容区域和底部内容区域。只读 INormalViewProperties。 |

 **返回：**
[NormalViewProperties](../normalviewproperties)


---


### getNotesViewProperties {#getNotesViewProperties}

| 名称 | 描述 |
| --- | --- |
| getNotesViewProperties () | 指定与备注视图模式关联的通用视图属性。只读 ICommonSlideViewProperties。 |

 **返回：**
[CommonSlideViewProperties](../commonslideviewproperties)


---


### getShowComments {#getShowComments}

| 名称 | 描述 |
| --- | --- |
| getShowComments () | 指定是否应显示幻灯片批注。读/写 NullableBool。 |

 **返回：**
byte


---


### getSlideViewProperties {#getSlideViewProperties}

| 名称 | 描述 |
| --- | --- |
| getSlideViewProperties () | 指定与幻灯片视图模式关联的通用视图属性。只读 ICommonSlideViewProperties。 |

 **返回：**
[CommonSlideViewProperties](../commonslideviewproperties)


---


### setGridSpacing {#setGridSpacing}

| 名称 | 描述 |
| --- | --- |
| setGridSpacing (float) | 返回或设置应用于演示文稿底层网格的网格间距，单位为点。读/写 float。网格间距值必须为正数。典型值范围为 1 mm (2.8349607 points) 到 2 英寸 (144 points)。 |

 **返回：**
void


---


### setLastView {#setLastView}

| 名称 | 描述 |
| --- | --- |
| setLastView (int) | 指定演示文稿上次保存时使用的视图模式。读/写 ViewType。 |

 **返回：**
void


---


### setShowComments {#setShowComments}

| 名称 | 描述 |
| --- | --- |
| setShowComments (byte) | 指定是否应显示幻灯片批注。读/写 NullableBool。 |

 **返回：**
void


---