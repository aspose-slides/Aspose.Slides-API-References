---
title: LegacyDiagram
second_title: Aspose.Slides for Android 的 Java API 参考
description: 表示一个旧版图表对象。
type: docs
url: /zh/com.aspose.slides/legacydiagram/
---
**继承：**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**所有已实现的接口：**
[com.aspose.slides.ILegacyDiagram](../../com.aspose.slides/ilegacydiagram)
```
public class LegacyDiagram extends GraphicalObject implements ILegacyDiagram
```

表示一个旧版图表对象。
## 方法

| 方法 | 描述 |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | 将旧版图表转换为可编辑的 SmartArt 对象。 |
| [convertToGroupShape()](#convertToGroupShape--) | 将旧版图表转换为可编辑的组形状。 |
### convertToSmartArt() {#convertToSmartArt--}
```
public final ISmartArt convertToSmartArt()
```

将旧版图表转换为可编辑的 SmartArt 对象。创建的 SmartArt 对象会添加到父组形状的相同位置。

**返回：**
[ISmartArt](../../com.aspose.slides/ismartart) - 创建的 SmartArt 对象。
### convertToGroupShape() {#convertToGroupShape--}
```
public final IGroupShape convertToGroupShape()
```

将旧版图表转换为可编辑的组形状。创建的 GroupShape 对象会添加到父组形状的相同位置。

**返回：**
[IGroupShape](../../com.aspose.slides/igroupshape) - 创建的 GroupShape 对象。