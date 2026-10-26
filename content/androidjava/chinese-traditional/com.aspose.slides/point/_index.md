---
title: Point
second_title: Aspose.Slides for Android Java API 參考文件
description: 表示動畫點。
type: docs
url: /zh-hant/com.aspose.slides/point/
---
**繼承：**
java.lang.Object

**已實作的介面：**
[com.aspose.slides.IPoint](../../com.aspose.slides/ipoint)
```
public class Point implements IPoint
```

表示動畫點。
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [Point()](#Point--) | 預設建構函式。 |
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | 建立具有時間、值和公式的動畫點。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getTime()](#getTime--) | 表示時間值。 |
| [setTime(float value)](#setTime-float-) | 表示時間值。 |
| [getValue()](#getValue--) | 表示點值。 |
| [setValue(Object value)](#setValue-java.lang.Object-) | 表示點值。 |
| [getFormula()](#getFormula--) | 在 values、from、to、by 屬性中的公式可以由以下組成：Standard arithmetic operators: '+', '-', '*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" 讀/寫 String。 |
| [setFormula(String value)](#setFormula-java.lang.String-) | 在 values、from、to、by 屬性中的公式可以由以下組成：Standard arithmetic operators: '+', '-', '*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" 讀/寫 String。 |
### Point() {#Point--}
```
public Point()
```


預設建構函式。

### Point(float time, Object value, String formula) {#Point-float-java.lang.Object-java.lang.String-}
```
public Point(float time, Object value, String formula)
```


建立具有時間、值和公式的動畫點。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| time | float | 時間值。 |
| value | java.lang.Object | 點值。 |
| formula | java.lang.String | 公式。 |

### getTime() {#getTime--}
```
public final float getTime()
```


表示時間值。讀/寫 float。

**傳回：**
float
### setTime(float value) {#setTime-float-}
```
public final void setTime(float value)
```


表示時間值。讀/寫 float。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


表示點值。僅限：bool、ColorFormat、float、int、string。讀/寫 Object。

**傳回：**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


表示點值。僅限：bool、ColorFormat、float、int、string。讀/寫 Object。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```


在 values、from、to、by 屬性中的公式可以由以下組成：Standard arithmetic operators: '+', '-', '*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" 讀/寫 String。

**傳回：**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```


在 values、from、to、by 屬性中的公式可以由以下組成：Standard arithmetic operators: '+', '-', '*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" 讀/寫 String。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |