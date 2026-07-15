---
title: IPoint
second_title: Aspose.Slides for Android via Java API Reference
description: Represent animation point.
type: docs
url: /zh-hant/com.aspose.slides/ipoint/
---```
public interface IPoint
```

代表動畫點。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getTime()](#getTime--) | 表示時間值。 |
| [setTime(float value)](#setTime-float-) | 表示時間值。 |
| [getValue()](#getValue--) | 表示點值。 |
| [setValue(Object value)](#setValue-java.lang.Object-) | 表示點值。 |
| [getFormula()](#getFormula--) | 在 values、from、to、by 屬性中的公式可以由以下組成：標準算術運算子：'+', '-', '*', '/', '^', '%'（模） 常數：'pi' 'e' 條件運算子：'abs', 'min', 'max', '?'（if） 比較運算子：'==', '>=', '', '!=', '!' 三角函數運算子：'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' 自然對數 'ln()' 屬性參考（主機支援的屬性），例如："\#ppt\_x+(cos(-2*pi*(1-$))*-\#ppt\_x-sin(-2*pi*(1-$))*(1-\#ppt\_y))*(1-$)" 可讀寫 String。 |
| [setFormula(String value)](#setFormula-java.lang.String-) | 在 values、from、to、by 屬性中的公式可以由以下組成：標準算術運算子：'+', '-', '*', '/', '^', '%'（模） 常數：'pi' 'e' 條件運算子：'abs', 'min', 'max', '?'（if） 比較運算子：'==', '>=', '', '!=', '!' 三角函數運算子：'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' 自然對數 'ln()' 屬性參考（主機支援的屬性），例如："\#ppt\_x+(cos(-2*pi*(1-$))*-\#ppt\_x-sin(-2*pi*(1-$))*(1-\#ppt\_y))*(1-$)" 可讀寫 String。 |

### getTime() {#getTime--}
```
public abstract float getTime()
```

表示時間值。可讀寫 float。

**Returns:**
float

### setTime(float value) {#setTime-float-}
```
public abstract void setTime(float value)
```

表示時間值。可讀寫 float。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```

表示點值。僅支援：bool, ColorFormat, float, int, string。可讀寫 Object。

**Returns:**
java.lang.Object

### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

表示點值。僅支援：bool, ColorFormat, float, int, string。可讀寫 Object。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public abstract String getFormula()
```

在 values、from、to、by 屬性中的公式可以由以下組成：標準算術運算子：'+', '-', '*', '/', '^', '%'（模） 常數：'pi' 'e' 條件運算子：'abs', 'min', 'max', '?'（if） 比較運算子：'==', '>=', '', '!=', '!' 三角函數運算子：'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' 自然對數 'ln()' 屬性參考（主機支援的屬性），例如："\#ppt\_x+(cos(-2*pi*(1-$))*-\#ppt\_x-sin(-2*pi*(1-$))*(1-\#ppt\_y))*(1-$)" 可讀寫 String。

**Returns:**
java.lang.String

### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```

在 values、from、to、by 屬性中的公式可以由以下組成：標準算術運算子：'+', '-', '*', '/', '^', '%'（模） 常數：'pi' 'e' 條件運算子：'abs', 'min', 'max', '?'（if） 比較運算子：'==', '>=', '', '!=', '!' 三角函數運算子：'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' 自然對數 'ln()' 屬性參考（主機支援的屬性），例如："\#ppt\_x+(cos(-2*pi*(1-$))*-\#ppt\_x-sin(-2*pi*(1-$))*(1-\#ppt\_y))*(1-$)" 可讀寫 String。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |