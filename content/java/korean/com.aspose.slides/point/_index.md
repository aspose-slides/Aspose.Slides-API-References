---
title: Point
second_title: Aspose.Slides for Java API 레퍼런스
description: 애니메이션 포인트를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/point/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IPoint](../../com.aspose.slides/ipoint)
```
public class Point implements IPoint
```

애니메이션 포인트를 나타냅니다.
## Constructors

| Constructor | Description |
| --- | --- |
| [Point()](#Point--) | 기본 생성자. |
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | 시간, 값 및 수식으로 애니메이션 포인트를 생성합니다. |
## Methods

| Method | Description |
| --- | --- |
| [getTime()](#getTime--) | 시간 값을 나타냅니다. |
| [setTime(float value)](#setTime-float-) | 시간 값을 나타냅니다. |
| [getValue()](#getValue--) | 포인트 값을 나타냅니다. |
| [setValue(Object value)](#setValue-java.lang.Object-) | 포인트 값을 나타냅니다. |
| [getFormula()](#getFormula--) | 값, from, to, by 속성 내의 수식은 다음으로 구성될 수 있습니다: Standard arithmetic operators: '+', '-', '*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2*pi*(1-$))*-\#ppt\_x-sin(-2*pi*(1-$))*(1-\#ppt\_y))*(1-$)" 읽기/쓰기 String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | 값, from, to, by 속성 내의 수식은 다음으로 구성될 수 있습니다: Standard arithmetic operators: '+', '-', '*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2*pi*(1-$))*-\#ppt\_x-sin(-2*pi*(1-$))*(1-\#ppt\_y))*(1-$)" 읽기/쓰기 String. |
### Point() {#Point--}
```
public Point()
```


기본 생성자.

### Point(float time, Object value, String formula) {#Point-float-java.lang.Object-java.lang.String-}
```
public Point(float time, Object value, String formula)
```


시간, 값 및 수식으로 애니메이션 포인트를 생성합니다.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| time | float | 시간 값. |
| value | java.lang.Object | 포인트 값. |
| formula | java.lang.String | 수식. |

### getTime() {#getTime--}
```
public final float getTime()
```


시간 값을 나타냅니다. 읽기/쓰기 float.

**Returns:**
float
### setTime(float value) {#setTime-float-}
```
public final void setTime(float value)
```


시간 값을 나타냅니다. 읽기/쓰기 float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


포인트 값을 나타냅니다. Only: bool, ColorFormat, float, int, string. 읽기/쓰기 Object.

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


포인트 값을 나타냅니다. Only: bool, ColorFormat, float, int, string. 읽기/쓰기 Object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```


값, from, to, by 속성 내의 수식은 다음으로 구성될 수 있습니다: Standard arithmetic operators: '+', '-', '*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2*pi*(1-$))*-\#ppt\_x-sin(-2*pi*(1-$))*(1-\#ppt\_y))*(1-$)" 읽기/쓰기 String.

**Returns:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```


값, from, to, by 속성 내의 수식은 다음으로 구성될 수 있습니다: Standard arithmetic operators: '+', '-', '*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=' , '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2*pi*(1-$))*-\#ppt\_x-sin(-2*pi*(1-$))*(1-\#ppt\_y))*(1-$)" 읽기/쓰기 String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |