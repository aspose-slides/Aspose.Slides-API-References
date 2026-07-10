---
title: Point
second_title: Aspose.Slides for Android via Java API 参考
description: 表示动画点。
type: docs
url: /zh/com.aspose.slides/point/
---
**继承:**
java.lang.Object

**所有实现的接口:**
[com.aspose.slides.IPoint](../../com.aspose.slides/ipoint)
```
public class Point implements IPoint
```

表示动画点。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Point()](#Point--) | 默认构造函数。 |
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | 使用时间、值和公式创建动画点。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getTime()](#getTime--) | 表示时间值。 |
| [setTime(float value)](#setTime-float-) | 表示时间值。 |
| [getValue()](#getValue--) | 表示点值。 |
| [setValue(Object value)](#setValue-java.lang.Object-) | 表示点值。 |
| [getFormula()](#getFormula--) | 值、from、to、by 属性中的公式可以由以下组成：标准算术运算符：'+', '-', '*', '/', '^', '%'（取模） 常量：'pi' 'e' 条件运算符：'abs', 'min', 'max', '?'（if） 比较运算符：'==', '>=', '', '!=', '!' 三角函数运算符：'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' 自然对数 'ln()' 属性引用（宿主支持的属性），例如："\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" 读/写 String。 |
| [setFormula(String value)](#setFormula-java.lang.String-) | 值、from、to、by 属性中的公式可以由以下组成：标准算术运算符：'+', '-', '*', '/', '^', '%'（取模） 常量：'pi' 'e' 条件运算符：'abs', 'min', 'max', '?'（if） 比较运算符：'==', '>=', '', '!=', '!' 三角函数运算符：'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' 自然对数 'ln()' 属性引用（宿主支持的属性），例如："\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" 读/写 String。 |
### Point() {#Point--}
```
public Point()
```

默认构造函数。

### Point(float time, Object value, String formula) {#Point-float-java.lang.Object-java.lang.String-}
```
public Point(float time, Object value, String formula)
```

使用时间、值和公式创建动画点。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| time | float | 时间值。 |
| value | java.lang.Object | 点值。 |
| formula | java.lang.String | 公式。 |

### getTime() {#getTime--}
```
public final float getTime()
```

表示时间值。 读/写 float。

**返回值：**
float
### setTime(float value) {#setTime-float-}
```
public final void setTime(float value)
```

表示时间值。 读/写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

表示点值。 仅限：bool, ColorFormat, float, int, string。 读/写 Object。

**返回值：**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

表示点值。 仅限：bool, ColorFormat, float, int, string。 读/写 Object。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```

值、from、to、by 属性中的公式可以由以下组成：标准算术运算符：'+', '-', '*', '/', '^', '%'（取模） 常量：'pi' 'e' 条件运算符：'abs', 'min', 'max', '?'（if） 比较运算符：'==', '>=', '', '!=', '!' 三角函数运算符：'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' 自然对数 'ln()' 属性引用（宿主支持的属性），例如："\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" 读/写 String。

**返回值：**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```

值、from、to、by 属性中的公式可以由以下组成：标准算术运算符：'+', '-', '*', '/', '^', '%'（取模） 常量：'pi' 'e' 条件运算符：'abs', 'min', 'max', '?'（if） 比较运算符：'==', '>=', '', '!=', '!' 三角函数运算符：'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' 自然对数 'ln()' 属性引用（宿主支持的属性），例如："\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" 读/写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |