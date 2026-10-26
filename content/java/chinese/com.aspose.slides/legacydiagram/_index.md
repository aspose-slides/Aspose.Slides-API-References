---
title: LegacyDiagram
second_title: Aspose.Slides for Java API 参考
description: 表示一个遗留图表对象。
type: docs
url: /zh/com.aspose.slides/legacydiagram/
---
**继承:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**已实现的接口:**  
[com.aspose.slides.ILegacyDiagram](../../com.aspose.slides/ilegacydiagram)  
```
public class LegacyDiagram extends GraphicalObject implements ILegacyDiagram
```

表示一个遗留图表对象。
## 方法

| 方法 | 描述 |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | 将旧版 digram 转换为可编辑的 SmartArt 对象。 |
| [convertToGroupShape()](#convertToGroupShape--) | 将旧版 digram 转换为可编辑的组形状。 |
### convertToSmartArt() {#convertToSmartArt--}
```
public final ISmartArt convertToSmartArt()
```

将旧版 digram 转换为可编辑的 SmartArt 对象。创建的 SmartArt 对象会在相同位置添加到父组形状中。

**返回:**  
[ISmartArt](../../com.aspose.slides/ismartart) - 已创建的 SmartArt 对象。
### convertToGroupShape() {#convertToGroupShape--}
```
public final IGroupShape convertToGroupShape()
```

将旧版 digram 转换为可编辑的组形状。创建的 GroupShape 对象会在相同位置添加到父组形状中。

**返回:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - 已创建的 GroupShape 对象。