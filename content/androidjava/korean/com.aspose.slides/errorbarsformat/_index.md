---
title: ErrorBarsFormat
second_title: Java API를 통한 Android용 Aspose.Slides 레퍼런스
description: 차트 시리즈의 오류 막대를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/errorbarsformat/
---
**상속:**
java.lang.Object, com.aspose.slides.DomObject

**구현된 모든 인터페이스:**
[com.aspose.slides.IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
```
public class ErrorBarsFormat extends DomObject<ChartSeries> implements IErrorBarsFormat
```

차트 시리즈의 오류 막대를 나타냅니다. ErrorBars 사용자 지정 값은 IChartDataPointCollection ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) 속성) 안에 있습니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getType()](#getType--) | 오류 막대의 유형을 가져오거나 설정합니다. |
| [setType(int value)](#setType-int-) | 오류 막대의 유형을 가져오거나 설정합니다. |
| [getValueType()](#getValueType--) | 오류 막대의 길이를 결정하는 가능한 방법을 나타냅니다. |
| [setValueType(int value)](#setValueType-int-) | 오류 막대의 길이를 결정하는 가능한 방법을 나타냅니다. |
| [hasEndCap()](#hasEndCap--) | 오류 막대에 끝 캡이 그려지지 않도록 지정합니다. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | 오류 막대에 끝 캡이 그려지지 않도록 지정합니다. |
| [getValue()](#getValue--) | 오류 막대의 길이를 결정하는 데 Fixed, Percentage 및 StandardDeviation 값 유형과 함께 사용되는 값을 가져오거나 설정합니다. |
| [setValue(float value)](#setValue-float-) | 오류 막대의 길이를 결정하는 데 Fixed, Percentage 및 StandardDeviation 값 유형과 함께 사용되는 값을 가져오거나 설정합니다. |
| [getFormat()](#getFormat--) | 오류 막대의 형식을 나타냅니다. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | 오류 막대의 형식을 나타냅니다. |
| [getChart()](#getChart--) | 부모 chart를 반환합니다. |
| [isVisible()](#isVisible--) | Error Bars 가시성을 가져오거나 설정합니다. |
| [setVisible(boolean value)](#setVisible-boolean-) | Error Bars 가시성을 가져오거나 설정합니다. |
| [getSlide()](#getSlide--) | 부모 FillFormat의 슬라이드를 반환합니다. |
| [getPresentation()](#getPresentation--) | 부모 FillFormat의 프레젠테이션을 반환합니다. |

### getType() {#getType--}
```
public final int getType()
```

오류 막대의 유형을 가져오거나 설정합니다. 읽기/쓰기 [ErrorBarType](../../com.aspose.slides/errorbartype).

**반환:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

오류 막대의 유형을 가져오거나 설정합니다. 읽기/쓰기 [ErrorBarType](../../com.aspose.slides/errorbartype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public final int getValueType()
```

오류 막대의 길이를 결정하는 가능한 방법을 나타냅니다. 사용자 지정 값 유형의 경우 값을 지정하려면 시리즈의 DataPoints 컬렉션에 있는 특정 데이터 포인트의 ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) 속성을 사용합니다. Fixed, Percentage 또는 StandardDeviation 값 유형의 경우 Value 속성을 사용하여 값을 지정합니다. 읽기/쓰기 [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**반환:**
int

### setValueType(int value) {#setValueType-int-}
```
public final void setValueType(int value)
```

오류 막대의 길이를 결정하는 가능한 방법을 나타냅니다. 사용자 지정 값 유형의 경우 값을 지정하려면 시리즈의 DataPoints 컬렉션에 있는 특정 데이터 포인트의 ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) 속성을 사용합니다. Fixed, Percentage 또는 StandardDeviation 값 유형의 경우 Value 속성을 사용하여 값을 지정합니다. 읽기/쓰기 [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public final boolean hasEndCap()
```

오류 막대에 끝 캡이 그려지지 않도록 지정합니다. 읽기/쓰기 boolean.

**반환:**
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public final void setEndCap(boolean value)
```

오류 막대에 끝 캡이 그려지지 않도록 지정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public final float getValue()
```

오류 막대의 길이를 결정하는 데 Fixed, Percentage 및 StandardDeviation 값 유형과 함께 사용되는 값을 가져오거나 설정합니다. 다른 경우에는 NaN을 반환합니다. 읽기/쓰기 float.

**반환:**
float

### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```

오류 막대의 길이를 결정하는 데 Fixed, Percentage 및 StandardDeviation 값 유형과 함께 사용되는 값을 가져오거나 설정합니다. 다른 경우에는 NaN을 반환합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

오류 막대의 형식을 나타냅니다. 읽기/쓰기 [IFormat](../../com.aspose.slides/iformat).

**반환:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

오류 막대의 형식을 나타냅니다. 읽기/쓰기 [IFormat](../../com.aspose.slides/iformat).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

부모 chart를 반환합니다. 읽기 전용 [IChart](../../com.aspose.slides/ichart).

**반환:**
[IChart](../../com.aspose.slides/ichart)

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Error Bars 가시성을 가져오거나 설정합니다. 읽기/쓰기 boolean.

**반환:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

Error Bars 가시성을 가져오고 설정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

부모 FillFormat의 슬라이드를 반환합니다. 읽기 전용 [BaseSlide](../../com.aspose.slides/baseslide).

**반환:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

부모 FillFormat의 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../com.aspose.slides/ipresentation).

**반환:**
[IPresentation](../../com.aspose.slides/ipresentation)