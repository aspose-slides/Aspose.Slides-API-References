---
title: IPropertyEffect
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示屬性效果的行為。
type: docs
url: /zh-hant/com.aspose.slides/ipropertyeffect/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IPropertyEffect extends IBehavior
```

表示屬性效果的行為。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getFrom()](#getFrom--) | 指定動畫的起始值。 |
| [setFrom(String value)](#setFrom-java.lang.String-) | 指定動畫的起始值。 |
| [getTo()](#getTo--) | 指定動畫的結束值。 |
| [setTo(String value)](#setTo-java.lang.String-) | 指定動畫的結束值。 |
| [getBy()](#getBy--) | 指定相對於動畫開始前位置的偏移值。 |
| [setBy(String value)](#setBy-java.lang.String-) | 指定相對於動畫開始前位置的偏移值。 |
| [getValueType()](#getValueType--) | 指定屬性值的類型。 |
| [setValueType(int value)](#setValueType-int-) | 指定屬性值的類型。 |
| [getCalcMode()](#getCalcMode--) | 指定動畫的插值模式 Read/write [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype)。 |
| [setCalcMode(int value)](#setCalcMode-int-) | 指定動畫的插值模式 Read/write [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype)。 |
| [getPoints()](#getPoints--) | 指定動畫的點。 |
| [setPoints(IPointCollection value)](#setPoints-com.aspose.slides.IPointCollection-) | 指定動畫的點。 |

### getFrom() {#getFrom--}
```
public abstract String getFrom()
```

指定動畫的起始值。Read/write String.

**傳回：**
java.lang.String

### setFrom(String value) {#setFrom-java.lang.String-}
```
public abstract void setFrom(String value)
```

指定動畫的起始值。Read/write String.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTo() {#getTo--}
```
public abstract String getTo()
```

指定動畫的結束值。Read/write String.

**傳回：**
java.lang.String

### setTo(String value) {#setTo-java.lang.String-}
```
public abstract void setTo(String value)
```

指定動畫的結束值。Read/write String.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getBy() {#getBy--}
```
public abstract String getBy()
```

指定相對於動畫開始前位置的偏移值。Read/write String.

**傳回：**
java.lang.String

### setBy(String value) {#setBy-java.lang.String-}
```
public abstract void setBy(String value)
```

指定相對於動畫開始前位置的偏移值。Read/write String.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

指定屬性值的類型。Read/write [PropertyValueType](../../com.aspose.slides/propertyvaluetype)。

**傳回：**
int

### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

指定屬性值的類型。Read/write [PropertyValueType](../../com.aspose.slides/propertyvaluetype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getCalcMode() {#getCalcMode--}
```
public abstract int getCalcMode()
```

指定動畫的插值模式 Read/write [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype)。

**傳回：**
int

### setCalcMode(int value) {#setCalcMode-int-}
```
public abstract void setCalcMode(int value)
```

指定動畫的插值模式 Read/write [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getPoints() {#getPoints--}
```
public abstract IPointCollection getPoints()
```

指定動畫的點。Read/write [IPointCollection](../../com.aspose.slides/ipointcollection)。

**傳回：**
[IPointCollection](../../com.aspose.slides/ipointcollection)

### setPoints(IPointCollection value) {#setPoints-com.aspose.slides.IPointCollection-}
```
public abstract void setPoints(IPointCollection value)
```

指定動畫的點。Read/write [IPointCollection](../../com.aspose.slides/ipointcollection)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IPointCollection](../../com.aspose.slides/ipointcollection) |  |