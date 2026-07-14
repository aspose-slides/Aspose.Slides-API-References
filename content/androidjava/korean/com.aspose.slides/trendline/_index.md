---
title: Trendline
second_title: Java API 레퍼런스를 통한 Aspose.Slides for Android
description: 클래스는 차트 시리즈의 추세선을 나타냅니다
type: docs
url: /ko/com.aspose.slides/trendline/
---
**상속:**  
java.lang.Object, com.aspose.slides.DomObject

**구현된 모든 인터페이스:**  
[com.aspose.slides.ITrendline](../../com.aspose.slides/itrendline)  
```
public class Trendline extends DomObject<TrendlineCollection> implements ITrendline
```

클래스는 차트 시리즈의 추세선을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | 추세선의 이름을 가져오거나 설정합니다. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | 추세선의 이름을 가져오거나 설정합니다. |
| [getTrendlineType()](#getTrendlineType--) | 추세선의 유형을 가져오거나 설정합니다. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | 추세선의 유형을 가져오거나 설정합니다. |
| [getFormat()](#getFormat--) | 추세선의 형식을 나타냅니다. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | 추세선의 형식을 나타냅니다. |
| [getBackward()](#getBackward--) | 추세선이 시리즈 데이터 앞에 확장되는 범주(또는 산점도 차트의 단위) 수를 지정합니다. |
| [setBackward(double value)](#setBackward-double-) | 추세선이 시리즈 데이터 앞에 확장되는 범주(또는 산점도 차트의 단위) 수를 지정합니다. |
| [getForward()](#getForward--) | 추세선이 시리즈 데이터 뒤에 확장되는 범주(또는 산점도 차트의 단위) 수를 지정합니다. |
| [setForward(double value)](#setForward-double-) | 추세선이 시리즈 데이터 뒤에 확장되는 범주(또는 산점도 차트의 단위) 수를 지정합니다. |
| [getIntercept()](#getIntercept--) | 추세선이 y축과 교차하는 값을 지정합니다. |
| [setIntercept(double value)](#setIntercept-double-) | 추세선이 y축과 교차하는 값을 지정합니다. |
| [getDisplayEquation()](#getDisplayEquation--) | 추세선의 방정식이 차트에 표시되도록 지정합니다(R-squared 값과 같은 레이블에). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | 추세선의 방정식이 차트에 표시되도록 지정합니다(R-squared 값과 같은 레이블에). |
| [getOrder()](#getOrder--) | 다항식 추세선의 차수를 지정합니다. |
| [setOrder(byte value)](#setOrder-byte-) | 다항식 추세선의 차수를 지정합니다. |
| [getPeriod()](#getPeriod--) | 이동 평균 추세선의 기간을 지정합니다. |
| [setPeriod(byte value)](#setPeriod-byte-) | 이동 평균 추세선의 기간을 지정합니다. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | 추세선의 R-squared 값이 차트에 표시되도록 지정합니다(방정식과 같은 레이블에). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | 추세선의 R-squared 값이 차트에 표시되도록 지정합니다(방정식과 같은 레이블에). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | 이 추세선과 관련된 범례 항목을 나타냅니다. 읽기 전용 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | 텍스트 매개변수 "text"로 TextFrameForOverriding을 초기화합니다. |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | 리치 형식 텍스트를 포함할 수 있습니다. |
| [getTextFormat()](#getTextFormat--) | 텍스트 형식을 반환합니다. |
| [getChart()](#getChart--) | 상위 차트를 반환합니다. |
| [getSlide()](#getSlide--) | FillFormat의 상위 슬라이드를 반환합니다. |
| [getPresentation()](#getPresentation--) | FillFormat의 상위 프레젠테이션을 반환합니다. |

### getTrendlineName() {#getTrendlineName--}
```
public final String getTrendlineName()
```

추세선의 이름을 가져오거나 설정합니다. 읽기/쓰기 String.

**반환값:**  
java.lang.String

### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```

추세선의 이름을 가져오거나 설정합니다. 읽기/쓰기 String.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```

추세선의 유형을 가져오거나 설정합니다. 읽기/쓰기 [TrendlineType](../../com.aspose.slides/trendlinetype).

**반환값:**  
int

### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```

추세선의 유형을 가져오거나 설정합니다. 읽기/쓰기 [TrendlineType](../../com.aspose.slides/trendlinetype).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

추세선의 형식을 나타냅니다. 읽기/쓰기 [IFormat](../../com.aspose.slides/iformat).

**반환값:**  
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

추세선의 형식을 나타냅니다. 읽기/쓰기 [IFormat](../../com.aspose.slides/iformat).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getBackward() {#getBackward--}
```
public final double getBackward()
```

추세선이 시리즈 데이터 앞에 확장되는 범주(또는 산점도 차트의 단위) 수를 지정합니다. 산점도 및 비산점도 차트에서 값은 0 이상의 값이어야 합니다. 읽기/쓰기 double.

**반환값:**  
double

### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```

추세선이 시리즈 데이터 앞에 확장되는 범주(또는 산점도 차트의 단위) 수를 지정합니다. 산점도 및 비산점도 차트에서 값은 0 이상의 값이어야 합니다. 읽기/쓰기 double.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getForward() {#getForward--}
```
public final double getForward()
```

추세선이 시리즈 데이터 뒤에 확장되는 범주(또는 산점도 차트의 단위) 수를 지정합니다. 산점도 및 비산점도 차트에서 값은 0 이상의 값이어야 합니다. 읽기/쓰기 double.

**반환값:**  
double

### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```

추세선이 시리즈 데이터 뒤에 확장되는 범주(또는 산점도 차트의 단위) 수를 지정합니다. 산점도 및 비산점도 차트에서 값은 0 이상의 값이어야 합니다. 읽기/쓰기 double.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```

추세선이 y축과 교차하는 값을 지정합니다. 이 속성은 추세선 유형이 exp, linear 또는 poly인 경우에만 지원됩니다. 읽기/쓰기 double.

**반환값:**  
double

### setIntercept(double value) {#setIntercept-double-}
```
public final void setIntercept(double value)
```

추세선이 y축과 교차하는 값을 지정합니다. 이 속성은 추세선 유형이 exp, linear 또는 poly인 경우에만 지원됩니다. 읽기/쓰기 double.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getDisplayEquation() {#getDisplayEquation--}
```
public final boolean getDisplayEquation()
```

추세선의 방정식이 차트에 표시되도록 지정합니다(R-squared 값과 같은 레이블에). 읽기/쓰기 boolean.

**반환값:**  
boolean

### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public final void setDisplayEquation(boolean value)
```

추세선의 방정식이 차트에 표시되도록 지정합니다(R-squared 값과 같은 레이블에). 읽기/쓰기 boolean.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getOrder() {#getOrder--}
```
public final byte getOrder()
```

다항식 추세선의 차수를 지정합니다. 다른 추세선 유형에서는 무시됩니다. 값은 2에서 6 사이여야 합니다. 읽기/쓰기 byte.

**반환값:**  
byte

### setOrder(byte value) {#setOrder-byte-}
```
public final void setOrder(byte value)
```

다항식 추세선의 차수를 지정합니다. 다른 추세선 유형에서는 무시됩니다. 값은 2에서 6 사이여야 합니다. 읽기/쓰기 byte.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getPeriod() {#getPeriod--}
```
public final byte getPeriod()
```

이동 평균 추세선의 기간을 지정합니다. 다른 추세선 변형에서는 무시됩니다. 값은 2에서 255 사이여야 합니다. 읽기/쓰기 byte.

**반환값:**  
byte

### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```

이동 평균 추세선의 기간을 지정합니다. 다른 추세선 변형에서는 무시됩니다. 값은 2에서 255 사이여야 합니다. 읽기/쓰기 byte.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```

추세선의 R-squared 값이 차트에 표시되도록 지정합니다(방정식과 같은 레이블에). 읽기/쓰기 boolean.

**반환값:**  
boolean

### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public final void setDisplayRSquaredValue(boolean value)
```

추세선의 R-squared 값이 차트에 표시되도록 지정합니다(방정식과 같은 레이블에). 읽기/쓰기 boolean.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

이 추세선과 관련된 범례 항목을 나타냅니다. 읽기 전용 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**반환값:**  
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

텍스트 매개변수 "text"로 TextFrameForOverriding을 초기화합니다. TextFrameForOverriding이 이미 초기화된 경우 텍스트만 변경합니다.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 새 TextFrameForOverriding의 텍스트. |

**반환값:**  
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

리치 형식 텍스트를 포함할 수 있습니다. 이 속성이 null이 아니면 이 형식 텍스트 값이 데이터 레이블의 자동 생성 텍스트를 대체합니다. 자동 생성 텍스트는 ShowSeriesName, ShowValue 등 속성에 의해 관리되고 TextFormatManager.TextFormat 속성으로 형식이 지정된 텍스트를 의미합니다. 읽기 전용 [ITextFrame](../../com.aspose.slides/itextframe).

**반환값:**  
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

텍스트 형식을 반환합니다. 읽기 전용 [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**반환값:**  
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getChart() {#getChart--}
```
public final IChart getChart()
```

상위 차트를 반환합니다. 읽기 전용 [IChart](../../com.aspose.slides/ichart).

**반환값:**  
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat의 상위 슬라이드를 반환합니다. 읽기 전용 [BaseSlide](../../com.aspose.slides/baseslide).

**반환값:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat의 상위 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../com.aspose.slides/ipresentation).

**반환값:**  
[IPresentation](../../com.aspose.slides/ipresentation)