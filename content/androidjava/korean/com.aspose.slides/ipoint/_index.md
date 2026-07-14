---
title: IPoint
second_title: Aspose.Slides for Android via Java API Reference
description: 애니메이션 포인트를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ipoint/
---```
public interface IPoint
```

애니메이션 포인트를 나타냅니다.
## Methods

| Method | Description |
| --- | --- |
| [getTime()](#getTime--) | 시간 값을 나타냅니다. |
| [setTime(float value)](#setTime-float-) | 시간 값을 나타냅니다. |
| [getValue()](#getValue--) | 포인트 값을 나타냅니다. |
| [setValue(Object value)](#setValue-java.lang.Object-) | 포인트 값을 나타냅니다. |
| [getFormula()](#getFormula--) | 값, from, to, by 속성 내의 수식은 다음과 같이 구성될 수 있습니다: 표준 산술 연산자: '+', '-', '*', '/', '^', '%' (mod) 상수: 'pi' 'e' 조건 연산자: 'abs', 'min', 'max', '?' (if) 비교 연산자: '==', '>=', '', '!=', '!' 삼각 연산자: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' 자연 로그 'ln()' 속성 참조(호스트가 지원하는 속성) 예: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" 읽기/쓰기 String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | 값, from, to, by 속성 내의 수식은 다음과 같이 구성될 수 있습니다: 표준 산술 연산자: '+', '-', '*', '/', '^', '%' (mod) 상수: 'pi' 'e' 조건 연산자: 'abs', 'min', 'max', '?' (if) 비교 연산자: '==', '>=', '', '!=', '!' 삼각 연산자: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' 자연 로그 'ln()' 속성 참조(호스트가 지원하는 속성) 예: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" 읽기/쓰기 String. |
### getTime() {#getTime--}
```
public abstract float getTime()
```

시간 값을 나타냅니다. 읽기/쓰기 float.

**Returns:**
float
### setTime(float value) {#setTime-float-}
```
public abstract void setTime(float value)
```

시간 값을 나타냅니다. 읽기/쓰기 float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

포인트 값을 나타냅니다. 가능한 유형: bool, ColorFormat, float, int, string. 읽기/쓰기 Object.

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

포인트 값을 나타냅니다. 가능한 유형: bool, ColorFormat, float, int, string. 읽기/쓰기 Object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |
### getFormula() {#getFormula--}
```
public abstract String getFormula()
```

값, from, to, by 속성 내의 수식은 다음과 같이 구성될 수 있습니다: 표준 산술 연산자: '+', '-', '*', '/', '^', '%' (mod) 상수: 'pi' 'e' 조건 연산자: 'abs', 'min', 'max', '?' (if) 비교 연산자: '==', '>=', '', '!=', '!' 삼각 연산자: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' 자연 로그 'ln()' 속성 참조(호스트가 지원하는 속성) 예: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" 읽기/쓰기 String.

**Returns:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```

값, from, to, by 속성 내의 수식은 다음과 같이 구성될 수 있습니다: 표준 산술 연산자: '+', '-', '*', '/', '^', '%' (mod) 상수: 'pi' 'e' 조건 연산자: 'abs', 'min', 'max', '?' (if) 비교 연산자: '==', '>=', '', '!=', '!' 삼각 연산자: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' 자연 로그 'ln()' 속성 참조(호스트가 지원하는 속성) 예: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" 읽기/쓰기 String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |