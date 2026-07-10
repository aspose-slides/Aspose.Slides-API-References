---
title: IPoint
second_title: Aspose.Slides for Android via Java API Reference
description: 表示动画点。
type: docs
url: /zh/com.aspose.slides/ipoint/
---```
public interface IPoint
```

表示动画点。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getTime()](#getTime--) | 表示时间值。 |
| [setTime(float value)](#setTime-float-) | 表示时间值。 |
| [getValue()](#getValue--) | 表示点值。 |
| [setValue(Object value)](#setValue-java.lang.Object-) | 表示点值。 |
| [getFormula()](#getFormula--) | 公式可以在 values、from、to、by 属性中使用，由以下组成：标准算术运算符：'+', '-', '*', '/', '^', '%'（mod） 常量：'pi' 'e' 条件运算符：'abs', 'min', 'max', '?'（if） 比较运算符：'==', '>=', '', '!=', '!' 三角函数运算符：'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' 自然对数 'ln()' 属性引用（主机支持的属性），例如："\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" 可读写 String。 |
| [setFormula(String value)](#setFormula-java.lang.String-) | 公式可以在 values、from、to、by 属性中使用，由以下组成：标准算术运算符：'+', '-', '*', '/', '^', '%'（mod） 常量：'pi' 'e' 条件运算符：'abs', 'min', 'max', '?'（if） 比较运算符：'==', '>=', '', '!=', '!' 三角函数运算符：'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' 自然对数 'ln()' 属性引用（主机支持的属性），例如："\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" 可读写 String。 |
### getTime() {#getTime--}
```
public abstract float getTime()
```

表示时间值。可读写 float。

**返回:**
float
### setTime(float value) {#setTime-float-}
```
public abstract void setTime(float value)
```

表示时间值。可读写 float。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

表示点值。仅限：bool, ColorFormat, float, int, string。可读写 Object。

**返回:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

表示点值。仅限：bool, ColorFormat, float, int, string。可读写 Object。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Object |  |
### getFormula() {#getFormula--}
```
public abstract String getFormula()
```

公式可以在 values、from、to、by 属性中使用，由以下组成：标准算术运算符：'+', '-', '*', '/', '^', '%'（mod） 常量：'pi' 'e' 条件运算符：'abs', 'min', 'max', '?'（if） 比较运算符：'==', '>=', '', '!=', '!' 三角函数运算符：'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' 自然对数 'ln()' 属性引用（主机支持的属性），例如："\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" 可读写 String。

**返回:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```

公式可以在 values、from、to、by 属性中使用，由以下组成：标准算术运算符：'+', '-', '*', '/', '^', '%'（mod） 常量：'pi' 'e' 条件运算符：'abs', 'min', 'max', '?'（if） 比较运算符：'==', '>=', '', '!=', '!' 三角函数运算符：'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' 自然对数 'ln()' 属性引用（主机支持的属性），例如："\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" 可读写 String。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |