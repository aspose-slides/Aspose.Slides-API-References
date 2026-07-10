---
title: SmartArtShape
second_title: Aspose.Slides for Android 通过 Java API 参考
description: 表示 SmartArt 形状
type: docs
url: /zh/com.aspose.slides/smartartshape/
---
**继承：**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**所有实现的接口：**
[com.aspose.slides.ISmartArtShape](../../com.aspose.slides/ismartartshape)
```
public class SmartArtShape extends GeometryShape implements ISmartArtShape
```

表示 SmartArt 形状
## 方法

| 方法 | 描述 |
| --- | --- |
| [getShapeType()](#getShapeType--) | 返回或设置几何预设类型。 |
| [setShapeType(int value)](#setShapeType-int-) | 返回或设置几何预设类型。 |
| [getTextFrame()](#getTextFrame--) | 返回 SmartArt 形状的文本。 |
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

返回或设置几何预设类型。注意：更改值时，所有调整值将重置为默认值。读/写 [ShapeType](../../com.aspose.slides/shapetype)。

**返回：**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

返回或设置几何预设类型。注意：更改值时，所有调整值将重置为默认值。读/写 [ShapeType](../../com.aspose.slides/shapetype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

返回 SmartArt 形状的文本。只读 [ITextFrame](../../com.aspose.slides/itextframe)。

**返回：**
[ITextFrame](../../com.aspose.slides/itextframe)