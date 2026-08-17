---
title: ILegacyDiagram
second_title: Aspose.Slides for Java API 参考
description: 表示一个遗留的图表对象
type: docs
url: /zh/com.aspose.slides/ilegacydiagram/
---
**所有已实现的接口:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

表示一个遗留的图表对象
## 方法

| 方法 | 描述 |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | 将遗留图表转换为可编辑的 SmartArt 对象。 |
| [convertToGroupShape()](#convertToGroupShape--) | 将遗留图表转换为可编辑的组形状。 |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```

将遗留图表转换为可编辑的 SmartArt 对象。创建的 SmartArt 对象会添加到父 GroupShape 中，位置相同。

**返回:**
[ISmartArt](../../com.aspose.slides/ismartart) - 已创建的 SmartArt 对象。
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```

将遗留图表转换为可编辑的组形状。创建的 GroupShape 对象会添加到父 GroupShape 中，位置相同。

**返回:**
[IGroupShape](../../com.aspose.slides/igroupshape) - 已创建的 GroupShape 对象。