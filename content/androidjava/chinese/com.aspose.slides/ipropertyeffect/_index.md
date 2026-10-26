---
title: IPropertyEffect
second_title: Aspose.Slides Android 通过 Java API 参考
description: 表示属性效果的行为。
type: docs
url: /zh/com.aspose.slides/ipropertyeffect/
---
**所有实现的接口：**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IPropertyEffect extends IBehavior
```

表示属性效果的行为。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFrom()](#getFrom--) | 指定动画的起始值。 |
| [setFrom(String value)](#setFrom-java.lang.String-) | 指定动画的起始值。 |
| [getTo()](#getTo--) | 指定动画的结束值。 |
| [setTo(String value)](#setTo-java.lang.String-) | 指定动画的结束值。 |
| [getBy()](#getBy--) | 指定相对于动画开始前位置的相对偏移值。 |
| [setBy(String value)](#setBy-java.lang.String-) | 指定相对于动画开始前位置的相对偏移值。 |
| [getValueType()](#getValueType--) | 指定属性值的类型。 |
| [setValueType(int value)](#setValueType-int-) | 指定属性值的类型。 |
| [getCalcMode()](#getCalcMode--) | 指定动画的插值模式 读/写 [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype)。 |
| [setCalcMode(int value)](#setCalcMode-int-) | 指定动画的插值模式 读/写 [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype)。 |
| [getPoints()](#getPoints--) | 指定动画的点。 |
| [setPoints(IPointCollection value)](#setPoints-com.aspose.slides.IPointCollection-) | 指定动画的点。 |
### getFrom() {#getFrom--}
```
public abstract String getFrom()
```

指定动画的起始值。读/写 String。

**返回：**
java.lang.String
### setFrom(String value) {#setFrom-java.lang.String-}
```
public abstract void setFrom(String value)
```

指定动画的起始值。读/写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTo() {#getTo--}
```
public abstract String getTo()
```

指定动画的结束值。读/写 String。

**返回：**
java.lang.String
### setTo(String value) {#setTo-java.lang.String-}
```
public abstract void setTo(String value)
```

指定动画的结束值。读/写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getBy() {#getBy--}
```
public abstract String getBy()
```

指定相对于动画开始前位置的相对偏移值。读/写 String。

**返回：**
java.lang.String
### setBy(String value) {#setBy-java.lang.String-}
```
public abstract void setBy(String value)
```

指定相对于动画开始前位置的相对偏移值。读/写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

指定属性值的类型。读/写 [PropertyValueType](../../com.aspose.slides/propertyvaluetype)。

**返回：**
int
### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

指定属性值的类型。读/写 [PropertyValueType](../../com.aspose.slides/propertyvaluetype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getCalcMode() {#getCalcMode--}
```
public abstract int getCalcMode()
```

指定动画的插值模式 读/写 [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype)。

**返回：**
int
### setCalcMode(int value) {#setCalcMode-int-}
```
public abstract void setCalcMode(int value)
```

指定动画的插值模式 读/写 [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPoints() {#getPoints--}
```
public abstract IPointCollection getPoints()
```

指定动画的点。读/写 [IPointCollection](../../com.aspose.slides/ipointcollection)。

**返回：**
[IPointCollection](../../com.aspose.slides/ipointcollection)
### setPoints(IPointCollection value) {#setPoints-com.aspose.slides.IPointCollection-}
```
public abstract void setPoints(IPointCollection value)
```

指定动画的点。读/写 [IPointCollection](../../com.aspose.slides/ipointcollection)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IPointCollection](../../com.aspose.slides/ipointcollection) |  |