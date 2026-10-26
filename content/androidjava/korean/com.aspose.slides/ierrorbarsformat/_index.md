---
title: IErrorBarsFormat
second_title: Java API를 통한 Android용 Aspose.Slides 레퍼런스
description: 차트 시리즈의 오류 표시줄을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ierrorbarsformat/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

차트 시리즈의 오류 표시줄을 나타냅니다. 오류 표시줄의 사용자 지정 값은 IChartDataPointCollection에 있으며 ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) 속성에) 있습니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getType()](#getType--) | 오류 표시줄의 유형을 가져오거나 설정합니다. |
| [setType(int value)](#setType-int-) | 오류 표시줄의 유형을 가져오거나 설정합니다. |
| [getValueType()](#getValueType--) | 오류 표시줄 길이를 결정하는 가능한 방법을 나타냅니다. |
| [setValueType(int value)](#setValueType-int-) | 오류 표시줄 길이를 결정하는 가능한 방법을 나타냅니다. |
| [hasEndCap()](#hasEndCap--) | 오류 표시줄에 끝 캡이 그려지지 않도록 지정합니다. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | 오류 표시줄에 끝 캡이 그려지지 않도록 지정합니다. |
| [getValue()](#getValue--) | 고정, 백분율 및 표준편차 값 유형과 함께 사용되어 오류 표시줄 길이를 결정하는 값을 가져오거나 설정합니다. |
| [setValue(float value)](#setValue-float-) | 고정, 백분율 및 표준편차 값 유형과 함께 사용되어 오류 표시줄 길이를 결정하는 값을 가져오거나 설정합니다. |
| [getFormat()](#getFormat--) | 오류 표시줄의 형식을 나타냅니다. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | 오류 표시줄의 형식을 나타냅니다. |
| [isVisible()](#isVisible--) | 오류 표시줄의 가시성을 가져오거나 설정합니다. |
| [setVisible(boolean value)](#setVisible-boolean-) | 오류 표시줄의 가시성을 가져오거나 설정합니다. |

### getType() {#getType--}
```
public abstract int getType()
```

오류 표시줄의 유형을 가져오거나 설정합니다. 읽기/쓰기 [ErrorBarType](../../com.aspose.slides/errorbartype).

**반환값:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

오류 표시줄의 유형을 가져오거나 설정합니다. 읽기/쓰기 [ErrorBarType](../../com.aspose.slides/errorbartype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

오류 표시줄 길이를 결정하는 가능한 방법을 나타냅니다. 사용자 지정 값 유형의 경우 값을 지정하려면 시리즈의 DataPoints 컬렉션에 있는 특정 데이터 포인트의 [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) 속성을 사용합니다. 읽기/쓰기 [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**반환값:**
int

### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

오류 표시줄 길이를 결정하는 가능한 방법을 나타냅니다. 사용자 지정 값 유형의 경우 값을 지정하려면 시리즈의 DataPoints 컬렉션에 있는 특정 데이터 포인트의 [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) 속성을 사용합니다. 읽기/쓰기 [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

오류 표시줄에 끝 캡이 그려지지 않도록 지정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

오류 표시줄에 끝 캡이 그려지지 않도록 지정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public abstract float getValue()
```

고정, 백분율 및 표준편차 값 유형과 함께 사용되어 오류 표시줄 길이를 결정하는 값을 가져오거나 설정합니다. 읽기/쓰기 float.

**반환값:**
float

### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```

고정, 백분율 및 표준편차 값 유형과 함께 사용되어 오류 표시줄 길이를 결정하는 값을 가져오거나 설정합니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

오류 표시줄의 형식을 나타냅니다. 읽기/쓰기 [IFormat](../../com.aspose.slides/iformat).

**반환값:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

오류 표시줄의 형식을 나타냅니다. 읽기/쓰기 [IFormat](../../com.aspose.slides/iformat).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

오류 표시줄의 가시성을 가져오거나 설정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

오류 표시줄의 가시성을 가져오거나 설정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |