---
title: ILegacyDiagram
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一个传统图表对象
type: docs
url: /zh/com.aspose.slides/ilegacydiagram/
---
**所有已实现的接口：**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

表示一个传统 diagram 对象
## 方法

| 方法 | 描述 |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | 将传统 digram 转换为可编辑的 SmartArt 对象。创建的 SmartArt 对象会在相同位置添加到父组形状。 |
| [convertToGroupShape()](#convertToGroupShape--) | 将传统 digram 转换为可编辑的 group shape。创建的 GroupShape 对象会在相同位置添加到父组形状。 |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```

将传统 digram 转换为可编辑的 SmartArt 对象。创建的 SmartArt 对象会在相同位置添加到父组形状。

**返回：**
[ISmartArt](../../com.aspose.slides/ismartart) - 创建的 SmartArt 对象。
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```

将传统 digram 转换为可编辑的 group shape。创建的 GroupShape 对象会在相同位置添加到父组形状。

**返回：**
[IGroupShape](../../com.aspose.slides/igroupshape) - 创建的 GroupShape 对象。