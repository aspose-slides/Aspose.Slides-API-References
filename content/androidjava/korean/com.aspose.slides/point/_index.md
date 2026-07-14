---
title: Point
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 애니메이션 포인트를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/point/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.IPoint](../../com.aspose.slides/ipoint)  
```
public class Point implements IPoint
```

애니메이션 포인트를 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Point()](#Point--) | 기본 생성자. |
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | 시간, 값 및 수식으로 애니메이션 포인트를 생성합니다. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getTime()](#getTime--) | 시간 값을 나타냅니다. |
| [setTime(float value)](#setTime-float-) | 시간 값을 나타냅니다. |
| [getValue()](#getValue--) | 포인트 값을 나타냅니다. |
| [setValue(Object value)](#setValue-java.lang.Object-) | 포인트 값을 나타냅니다. |
| [getFormula()](#getFormula--) | 값, from, to, by 속성 내의 수식은 다음으로 구성될 수 있습니다: 표준 산술 연산자: '+', '-', '*', '/', '^', '%' (mod) 상수: 'pi' 'e' 조건 연산자: 'abs', 'min', 'max', '?' (if) 비교 연산자: '==', '>=', '', '!=', '!' 삼각 연산자: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' 자연 로그 'ln()' 속성 참조(호스트 지원 속성) 예: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" 읽기/쓰기 String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | 값, from, to, by 속성 내의 수식은 다음으로 구성될 수 있습니다: 표준 산술 연산자: '+', '-', '*', '/', '^', '%' (mod) 상수: 'pi' 'e' 조건 연산자: 'abs', 'min', 'max', '?' (if) 비교 연산자: '==', '>=', '', '!=', '!' 삼각 연산자: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' 자연 로그 'ln()' 속성 참조(호스트 지원 속성) 예: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" 읽기/쓰기 String. |

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

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| time | float | 시간 값. |
| value | java.lang.Object | 포인트 값. |
| formula | java.lang.String | 수식. |

### getTime() {#getTime--}
```
public final float getTime()
```

시간 값을 나타냅니다. 읽기/쓰기 float.

**반환:**
float

### setTime(float value) {#setTime-float-}
```
public final void setTime(float value)
```

시간 값을 나타냅니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

포인트 값을 나타냅니다. 지원 타입: bool, ColorFormat, float, int, string. 읽기/쓰기 Object.

**반환:**
java.lang.Object

### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

포인트 값을 나타냅니다. 지원 타입: bool, ColorFormat, float, int, string. 읽기/쓰기 Object.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```

값, from, to, by 속성 내의 수식은 다음으로 구성될 수 있습니다: 표준 산술 연산자: '+', '-', '*', '/', '^', '%' (mod) 상수: 'pi' 'e' 조건 연산자: 'abs', 'min', 'max', '?' (if) 비교 연산자: '==', '>=', '', '!=', '!' 삼각 연산자: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' 자연 로그 'ln()' 속성 참조(호스트 지원 속성) 예: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" 읽기/쓰기 String.

**반환:**
java.lang.String

### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```

값, from, to, by 속성 내의 수식은 다음으로 구성될 수 있습니다: 표준 산술 연산자: '+', '-', '*', '/', '^', '%' (mod) 상수: 'pi' 'e' 조건 연산자: 'abs', 'min', 'max', '?' (if) 비교 연산자: '==', '>=', '', '!=', '!' 삼각 연산자: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' 자연 로그 'ln()' 속성 참조(호스트 지원 속성) 예: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |