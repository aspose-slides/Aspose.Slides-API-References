---
title: SmartArtNode
second_title: 适用于 Android 的 Aspose.Slides Java API 参考
description: 表示 SmartArt 对象的节点
type: docs
url: /zh/com.aspose.slides/smartartnode/
---
**继承:**
java.lang.Object

**所有实现的接口:**
[com.aspose.slides.ISmartArtNode](../../com.aspose.slides/ismartartnode)
```
public final class SmartArtNode implements ISmartArtNode
```

表示 SmartArt 对象的节点
## 方法

| 方法 | 描述 |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | 返回当前节点的所有子节点的集合。 |
| [getShapes()](#getShapes--) | 返回与该节点关联的所有形状的集合。 |
| [getTextFrame()](#getTextFrame--) | 返回节点的文本框。 |
| [isAssistant()](#isAssistant--) | 返回或设置该节点为助理。 |
| [setAssistant(boolean value)](#setAssistant-boolean-) | 返回或设置该节点为助理。 |
| [getLevel()](#getLevel--) | 返回节点的嵌套级别。 |
| [getBulletFillFormat()](#getBulletFillFormat--) | 返回 FillFormat 对象，其中包含节点项目符号的填充格式属性。 |
| [getPosition()](#getPosition--) | 返回或设置节点在同级节点中的零基位置。 |
| [setPosition(int value)](#setPosition-int-) | 返回或设置节点在同级节点中的零基位置。 |
| [isHidden()](#isHidden--) | 如果此节点在数据模型中是隐藏节点，则返回 true。 |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | 返回或设置与当前节点关联的组织图布局类型。 |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | 返回或设置与当前节点关联的组织图布局类型。 |
| [remove()](#remove--) | 移除当前节点。 |
### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```

返回当前节点的所有子节点的集合。只读 [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)。

**返回:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```

返回与该节点关联的所有形状的集合。只读 [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)。

**返回:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

返回节点的文本框。只读 [ITextFrame](../../com.aspose.slides/itextframe)。

**返回:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public final boolean isAssistant()
```

返回或设置该节点为助理。可读写 boolean。

**返回:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public final void setAssistant(boolean value)
```

返回或设置该节点为助理。可读写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public final int getLevel()
```

返回节点的嵌套级别。只读 int。

**返回:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```

返回 FillFormat 对象，其中包含节点项目符号的填充格式属性。注意：对于某些不提供节点项目符号的 SmartArt 布局类型，可能返回 null。只读 [IFillFormat](../../com.aspose.slides/ifillformat)。

**返回:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

返回或设置节点在同级节点中的零基位置。可读写 int 。

**返回:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

返回或设置节点在同级节点中的零基位置。可读写 int 。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

如果此节点在数据模型中是隐藏节点，则返回 true。只读 boolean。

**返回:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```

返回或设置与当前节点关联的组织图布局类型。可读写 [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype)。

**返回:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```

返回或设置与当前节点关联的组织图布局类型。可读写 [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public final boolean remove()
```

移除当前节点。

**返回:**
boolean - 如果成功移除则返回 true，否则返回 false