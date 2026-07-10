---
title: SmartArt
second_title: 适用于 Android 的 Aspose.Slides Java API 参考
description: 表示一个 SmartArt 图表
type: docs
url: /zh/com.aspose.slides/smartart/
---
**继承:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**所有实现的接口:**  
[com.aspose.slides.ISmartArt](../../com.aspose.slides/ismartart)  
```
public class SmartArt extends GraphicalObject implements ISmartArt
```

表示一个 SmartArt 图表

## 方法

| 方法 | 描述 |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | 返回 SmartArt 对象中所有节点的集合。 |
| [getNodes()](#getNodes--) | 返回 SmartArt 对象中根节点的集合。 |
| [getLayout()](#getLayout--) | 获取或设置 SmartArt 对象的布局。 |
| [setLayout(int value)](#setLayout-int-) | 获取或设置 SmartArt 对象的布局。 |
| [getQuickStyle()](#getQuickStyle--) | 获取或设置 SmartArt 对象的快速样式。 |
| [setQuickStyle(int value)](#setQuickStyle-int-) | 获取或设置 SmartArt 对象的快速样式。 |
| [getColorStyle()](#getColorStyle--) | 获取或设置 SmartArt 对象的颜色样式。 |
| [setColorStyle(int value)](#setColorStyle-int-) | 获取或设置 SmartArt 对象的颜色样式。 |
| [isReversed()](#isReversed--) | 获取或设置 SmartArt 图表的方向状态（从左到右 LTR 或从右到左 RTL），前提是图表支持反转。 |
| [setReversed(boolean value)](#setReversed-boolean-) | 获取或设置 SmartArt 图表的方向状态（从左到右 LTR 或从右到左 RTL），前提是图表支持反转。 |

### getAllNodes() {#getAllNodes--}
```
public final ISmartArtNodeCollection getAllNodes()
```

返回 SmartArt 对象中所有节点的集合。只读 [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)。

**返回：**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)

### getNodes() {#getNodes--}
```
public final ISmartArtNodeCollection getNodes()
```

返回 SmartArt 对象中根节点的集合。只读 [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)。

**返回：**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)

### getLayout() {#getLayout--}
```
public final int getLayout()
```

获取或设置 SmartArt 对象的布局。读写 [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype)。

**返回：**
int

### setLayout(int value) {#setLayout-int-}
```
public final void setLayout(int value)
```

获取或设置 SmartArt 对象的布局。读写 [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getQuickStyle() {#getQuickStyle--}
```
public final int getQuickStyle()
```

获取或设置 SmartArt 对象的快速样式。读写 [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype)。

**返回：**
int

### setQuickStyle(int value) {#setQuickStyle-int-}
```
public final void setQuickStyle(int value)
```

获取或设置 SmartArt 对象的快速样式。读写 [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getColorStyle() {#getColorStyle--}
```
public final int getColorStyle()
```

获取或设置 SmartArt 对象的颜色样式。读写 [SmartArtColorType](../../com.aspose.slides/smartartcolortype)。

**返回：**
int

### setColorStyle(int value) {#setColorStyle-int-}
```
public final void setColorStyle(int value)
```

获取或设置 SmartArt 对象的颜色样式。读写 [SmartArtColorType](../../com.aspose.slides/smartartcolortype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### isReversed() {#isReversed--}
```
public final boolean isReversed()
```

获取或设置 SmartArt 图表的方向状态（从左到右 LTR 或从右到左 RTL），前提是图表支持反转。读写 boolean 。

**返回：**
boolean

### setReversed(boolean value) {#setReversed-boolean-}
```
public final void setReversed(boolean value)
```

获取或设置 SmartArt 图表的方向状态（从左到右 LTR 或从右到左 RTL），前提是图表支持反转。读写 boolean 。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |