---
title: ITrendline
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 클래스는 차트 시리즈의 추세선을 나타냅니다
type: docs
url: /ko/com.aspose.slides/itrendline/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface ITrendline extends IOverridableText
```

클래스는 차트 시리즈의 추세선을 나타냅니다
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | 추세선의 이름을 가져오거나 설정합니다. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | 추세선의 이름을 가져오거나 설정합니다. |
| [getTrendlineType()](#getTrendlineType--) | 추세선 유형을 가져오거나 설정합니다. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | 추세선 유형을 가져오거나 설정합니다. |
| [getFormat()](#getFormat--) | 추세선의 형식을 나타냅니다. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | 추세선의 형식을 나타냅니다. |
| [getBackward()](#getBackward--) | 추세선이 해당 시리즈 데이터 이전에 확장되는 카테고리 수(또는 산점도 차트의 단위)를 지정합니다. |
| [setBackward(double value)](#setBackward-double-) | 추세선이 해당 시리즈 데이터 이전에 확장되는 카테고리 수(또는 산점도 차트의 단위)를 지정합니다. |
| [getForward()](#getForward--) | 추세선이 해당 시리즈 데이터 이후에 확장되는 카테고리 수(또는 산점도 차트의 단위)를 지정합니다. |
| [setForward(double value)](#setForward-double-) | 추세선이 해당 시리즈 데이터 이후에 확장되는 카테고리 수(또는 산점도 차트의 단위)를 지정합니다. |
| [getIntercept()](#getIntercept--) | 추세선이 y축과 교차하는 값을 지정합니다. |
| [setIntercept(double value)](#setIntercept-double-) | 추세선이 y축과 교차하는 값을 지정합니다. |
| [getDisplayEquation()](#getDisplayEquation--) | 추세선 방정식이 차트에 표시되도록 지정합니다(Rsquaredvalue와 동일한 레이블에). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | 추세선 방정식이 차트에 표시되도록 지정합니다(Rsquaredvalue와 동일한 레이블에). |
| [getOrder()](#getOrder--) | 다항식 추세선의 차수를 지정합니다. |
| [setOrder(byte value)](#setOrder-byte-) | 다항식 추세선의 차수를 지정합니다. |
| [getPeriod()](#getPeriod--) | 이동 평균 추세선의 경우 추세선 기간을 지정합니다. |
| [setPeriod(byte value)](#setPeriod-byte-) | 이동 평균 추세선의 경우 추세선 기간을 지정합니다. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | 추세선의 R-제곱값이 차트에 표시되도록 지정합니다(방정식과 동일한 레이블에). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | 추세선의 R-제곱값이 차트에 표시되도록 지정합니다(방정식과 동일한 레이블에). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | 이 추세선과 관련된 범례 항목을 나타냅니다 읽기 전용 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |

### getTrendlineName() {#getTrendlineName--}
```
public abstract String getTrendlineName()
```

추세선의 이름을 가져오거나 설정합니다. 읽기/쓰기 String.

**반환:**  
java.lang.String

### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public abstract void setTrendlineName(String value)
```

추세선의 이름을 가져오거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTrendlineType() {#getTrendlineType--}
```
public abstract int getTrendlineType()
```

추세선 유형을 가져오거나 설정합니다. 읽기/쓰기 [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**반환:**  
int

### setTrendlineType(int value) {#setTrendlineType-int-}
```
public abstract void setTrendlineType(int value)
```

추세선 유형을 가져오거나 설정합니다. 읽기/쓰기 [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

추세선의 형식을 나타냅니다. 읽기/쓰기 [IFormat](../../com.aspose.slides/iformat).

**반환:**  
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

추세선의 형식을 나타냅니다. 읽기/쓰기 [IFormat](../../com.aspose.slides/iformat).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getBackward() {#getBackward--}
```
public abstract double getBackward()
```

추세선이 해당 시리즈 데이터 이전에 확장되는 카테고리 수(또는 산점도 차트의 단위)를 지정합니다. 산점도 및 비산점도 차트에서 값은 0 이상의 값을 가져야 합니다. 읽기/쓰기 double.

**반환:**  
double

### setBackward(double value) {#setBackward-double-}
```
public abstract void setBackward(double value)
```

추세선이 해당 시리즈 데이터 이전에 확장되는 카테고리 수(또는 산점도 차트의 단위)를 지정합니다. 산점도 및 비산점도 차트에서 값은 0 이상의 값을 가져야 합니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |

### getForward() {#getForward--}
```
public abstract double getForward()
```

추세선이 해당 시리즈 데이터 이후에 확장되는 카테고리 수(또는 산점도 차트의 단위)를 지정합니다. 산점도 및 비산점도 차트에서 값은 0 이상의 값을 가져야 합니다. 읽기/쓰기 double.

**반환:**  
double

### setForward(double value) {#setForward-double-}
```
public abstract void setForward(double value)
```

추세선이 해당 시리즈 데이터 이후에 확장되는 카테고리 수(또는 산점도 차트의 단위)를 지정합니다. 산점도 및 비산점도 차트에서 값은 0 이상의 값을 가져야 합니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |

### getIntercept() {#getIntercept--}
```
public abstract double getIntercept()
```

추세선이 y축과 교차하는 값을 지정합니다. 이 속성은 추세선 유형이 exp, linear 또는 poly인 경우에만 지원됩니다. 읽기/쓰기 double.

**반환:**  
double

### setIntercept(double value) {#setIntercept-double-}
```
public abstract void setIntercept(double value)
```

추세선이 y축과 교차하는 값을 지정합니다. 이 속성은 추세선 유형이 exp, linear 또는 poly인 경우에만 지원됩니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |

### getDisplayEquation() {#getDisplayEquation--}
```
public abstract boolean getDisplayEquation()
```

추세선 방정식이 차트에 표시되도록 지정합니다(Rsquaredvalue와 동일한 레이블에). 읽기/쓰기 boolean.

**반환:**  
boolean

### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public abstract void setDisplayEquation(boolean value)
```

추세선 방정식이 차트에 표시되도록 지정합니다(Rsquaredvalue와 동일한 레이블에). 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getOrder() {#getOrder--}
```
public abstract byte getOrder()
```

다항식 추세선의 차수를 지정합니다. 다른 추세선 유형에서는 무시됩니다. 값은 2에서 6 사이여야 합니다. 읽기/쓰기 byte.

**반환:**  
byte

### setOrder(byte value) {#setOrder-byte-}
```
public abstract void setOrder(byte value)
```

다항식 추세선의 차수를 지정합니다. 다른 추세선 유형에서는 무시됩니다. 값은 2에서 6 사이여야 합니다. 읽기/쓰기 byte.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getPeriod() {#getPeriod--}
```
public abstract byte getPeriod()
```

이동 평균 추세선의 경우 추세선 기간을 지정합니다. 다른 추세선 변형에서는 무시됩니다. 값은 2에서 255 사이여야 합니다. 읽기/쓰기 byte.

**반환:**  
byte

### setPeriod(byte value) {#setPeriod-byte-}
```
public abstract void setPeriod(byte value)
```

이동 평균 추세선의 경우 추세선 기간을 지정합니다. 다른 추세선 변형에서는 무시됩니다. 값은 2에서 255 사이여야 합니다. 읽기/쓰기 byte.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public abstract boolean getDisplayRSquaredValue()
```

추세선의 R-제곱값이 차트에 표시되도록 지정합니다(방정식과 동일한 레이블에). 읽기/쓰기 boolean.

**반환:**  
boolean

### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public abstract void setDisplayRSquaredValue(boolean value)
```

추세선의 R-제곱값이 차트에 표시되도록 지정합니다(방정식과 동일한 레이블에). 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

이 추세선과 관련된 범례 항목을 나타냅니다 읽기 전용 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**반환:**  
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)