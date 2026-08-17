---
title: ISmartArt
second_title: Aspose.Slides for Java API 参考
description: 表示一个 SmartArt 图表。
type: docs
url: /zh/com.aspose.slides/ismartart/
---
**已实现的接口：**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISmartArt extends IGraphicalObject
```

表示一个 SmartArt 图表。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | 返回 SmartArt 对象中所有节点的集合。 |
| [getNodes()](#getNodes--) | 返回 SmartArt 对象中根节点的集合。 |
| [getLayout()](#getLayout--) | 返回或设置 SmartArt 对象的布局。 |
| [setLayout(int value)](#setLayout-int-) | 返回或设置 SmartArt 对象的布局。 |
| [getQuickStyle()](#getQuickStyle--) | 返回或设置 SmartArt 对象的快速样式。 |
| [setQuickStyle(int value)](#setQuickStyle-int-) | 返回或设置 SmartArt 对象的快速样式。 |
| [getColorStyle()](#getColorStyle--) | 返回或设置 SmartArt 对象的颜色样式。 |
| [setColorStyle(int value)](#setColorStyle-int-) | 返回或设置 SmartArt 对象的颜色样式。 |
| [isReversed()](#isReversed--) | 返回或设置 SmartArt 图表的状态，以指示从左到右 (LTR) 或从右到左 (RTL)，如果图表支持反转。 |
| [setReversed(boolean value)](#setReversed-boolean-) | 返回或设置 SmartArt 图表的状态，以指示从左到右 (LTR) 或从右到左 (RTL)，如果图表支持反转。 |

### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```

返回 SmartArt 对象中所有节点的集合。只读 [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)。

**返回：**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)

### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```

返回 SmartArt 对象中根节点的集合。只读 [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)。

**返回：**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)

### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

返回或设置 SmartArt 对象的布局。读/写 [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype)。

**返回：**
int

### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```

返回或设置 SmartArt 对象的布局。读/写 [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```

返回或设置 SmartArt 对象的快速样式。读/写 [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype)。

**返回：**
int

### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickStyle(int value)
```

返回或设置 SmartArt 对象的快速样式。读/写 [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```

返回或设置 SmartArt 对象的颜色样式。读/写 [SmartArtColorType](../../com.aspose.slides/smartartcolortype)。

**返回：**
int

### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```

返回或设置 SmartArt 对象的颜色样式。读/写 [SmartArtColorType](../../com.aspose.slides/smartartcolortype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```

返回或设置 SmartArt 图表的状态，以指示从左到右 (LTR) 或从右到左 (RTL)，如果图表支持反转。读/写 布尔值。

**返回：**
boolean

### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```

返回或设置 SmartArt 图表的状态，以指示从左到右 (LTR) 或从右到左 (RTL)，如果图表支持反转。读/写 布尔值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |