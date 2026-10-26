---
title: Point
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs
url: /zh/aspose.slides/point/
---
## Point 类

 表示动画点。
 
### Point {#Point}

| 名称 | 描述 |
| --- | --- |
| Point() | 默认函数。 |

 **返回：**
Point


---


### Point {#Point}

| 名称 | 描述 |
| --- | --- |
| Point(float, Object, String) | 使用时间、值和公式创建动画点。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| time | float | 时间值。 |
| value | Object | 点的值。 |
| formula | String | 公式。 |

 **返回：**
Point


---


### getFormula {#getFormula}

| 名称 | 描述 |
| --- | --- |
| getFormula () | 值、from、to、by 属性中的公式可以由以下组成：标准算术运算符：&#39+&#39, &#39-&#39, &#39*&#39, &#39/&#39, &#39^&#39, &#39%&#39 (mod) 常量：&#39pi&#39 &#39e&#39 条件运算符：&#39abs&#39, &#39min&#39, &#39max&#39, &#39&#63&#39 (if) 比较运算符：&#39==&#39, &#39&gt;=&#39, &#39&#39, &#39&#33&#61&#39, &#39&#33&#39 三角运算符：&#39sin()&#39, &#39cos()&#39, &#39tan()&#39, &#39asin()&#39, &#39acos()&#39, &#39atan()&#39 自然对数 &#39ln()&#39 属性引用（宿主支持的属性），例如："#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)" 读/写 String。 |

 **返回：**
String


---


### getTime {#getTime}

| 名称 | 描述 |
| --- | --- |
| getTime () | 表示时间值。读/写 float。 |

 **返回：**
float


---


### getValue {#getValue}

| 名称 | 描述 |
| --- | --- |
| getValue () | 表示点的值。仅限：bool, ColorFormat, float, int, string。读/写 Object。 |

 **返回：**
Object


---


### setFormula {#setFormula}

| 名称 | 描述 |
| --- | --- |
| setFormula (String) | 值、from、to、by 属性中的公式可以由以下组成：标准算术运算符：&#39+&#39, &#39-&#39, &#39*&#39, &#39/&#39, &#39^&#39, &#39%&#39 (mod) 常量：&#39pi&#39 &#39e&#39 条件运算符：&#39abs&#39, &#39min&#39, &#39max&#39, &#39&#63&#39 (if) 比较运算符：&#39==&#39, &#39&gt;=&#39, &#39&#39, &#39&#33&#61&#39, &#39&#33&#39 三角运算符：&#39sin()&#39, &#39cos()&#39, &#39tan()&#39, &#39asin()&#39, &#39acos()&#39, &#39atan()&#39 自然对数 &#39ln()&#39 属性引用（宿主支持的属性），例如："#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)" 读/写 String。 |

 **返回：**
void


---


### setTime {#setTime}

| 名称 | 描述 |
| --- | --- |
| setTime (float) | 表示时间值。读/写 float。 |

 **返回：**
void


---


### setValue {#setValue}

| 名称 | 描述 |
| --- | --- |
| setValue (Object) | 表示点的值。仅限：bool, ColorFormat, float, int, string。读/写 Object。 |

 **返回：**
void


---