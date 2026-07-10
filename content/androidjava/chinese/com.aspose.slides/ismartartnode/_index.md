---
title: ISmartArtNode
second_title: Aspose.Slides for Android via Java API 参考
description: 表示 SmartArt 图表的节点。
type: docs
url: /zh/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

表示 SmartArt 图表的节点。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | 返回当前节点的所有子节点的集合。 |
| [getShapes()](#getShapes--) | 返回与该节点关联的所有形状的集合。 |
| [getTextFrame()](#getTextFrame--) | 返回或设置节点的文本。 |
| [isAssistant()](#isAssistant--) | 返回或设置节点为助理。 |
| [setAssistant(boolean value)](#setAssistant-boolean-) | 返回或设置节点为助理。 |
| [getLevel()](#getLevel--) | 返回节点的嵌套层级。 |
| [getBulletFillFormat()](#getBulletFillFormat--) | 返回包含节点项目符号填充格式属性的 FillFormat 对象。 |
| [getPosition()](#getPosition--) | 返回或设置节点在同级节点中的零基位置。 |
| [setPosition(int value)](#setPosition-int-) | 返回或设置节点在同级节点中的零基位置。 |
| [isHidden()](#isHidden--) | 如果此节点在数据模型中是隐藏节点，则返回 true。 |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | 返回或设置与当前节点关联的组织结构图布局类型。 |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | 返回或设置与当前节点关联的组织结构图布局类型。 |
| [remove()](#remove--) | 删除当前节点。 |
### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```

返回当前节点的所有子节点的集合。只读 [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)。

**返回:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```

返回与该节点关联的所有形状的集合。只读 [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)。

**返回:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

返回或设置节点的文本。只读 [ITextFrame](../../com.aspose.slides/itextframe)。

**返回:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```

返回或设置节点为助理。读写 boolean。

**返回:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```

返回或设置节点为助理。读写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public abstract int getLevel()
```

返回节点的嵌套层级。只读 int。

**返回:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```

返回包含节点项目符号填充格式属性的 FillFormat 对象。注意：在某些不为节点提供项目符号的 SmartArt 布局类型中，可能返回 null。只读 [IFillFormat](../../com.aspose.slides/ifillformat)。

**返回:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

返回或设置节点在同级节点中的零基位置。读写 int。

**返回:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

返回或设置节点在同级节点中的零基位置。读写 int。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```

如果此节点在数据模型中是隐藏节点，则返回 true。只读 boolean。

**返回:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```

返回或设置与当前节点关联的组织结构图布局类型。读写 [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype)。

**返回:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```

返回或设置与当前节点关联的组织结构图布局类型。读写 [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public abstract boolean remove()
```

删除当前节点。

**返回:**
boolean - true if removed succesfully, otherwise false.