---
title: IErrorBarsFormat
second_title: Aspose.Slides Java API 레퍼런스
description: 차트 시리즈의 오류 막대를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ierrorbarsformat/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

차트 시리즈의 오류 막대를 나타냅니다. ErrorBars 사용자 정의 값은 IChartDataPointCollection에 있으며 ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) 속성에 있습니다).
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | 오류 막대 유형을 가져오거나 설정합니다. |
| [setType(int value)](#setType-int-) | 오류 막대 유형을 가져오거나 설정합니다. |
| [getValueType()](#getValueType--) | 오류 막대 길이를 결정하는 가능한 방법을 나타냅니다. |
| [setValueType(int value)](#setValueType-int-) | 오류 막대 길이를 결정하는 가능한 방법을 나타냅니다. |
| [hasEndCap()](#hasEndCap--) | 오류 막대에 끝 캡이 그려지지 않음을 지정합니다. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | 오류 막대에 끝 캡이 그려지지 않음을 지정합니다. |
| [getValue()](#getValue--) | 오류 막대 길이를 결정하기 위해 Fixed, Percentage 및 StandardDeviation 값 유형과 함께 사용되는 값을 가져오거나 설정합니다. |
| [setValue(float value)](#setValue-float-) | 오류 막대 길이를 결정하기 위해 Fixed, Percentage 및 StandardDeviation 값 유형과 함께 사용되는 값을 가져오거나 설정합니다. |
| [getFormat()](#getFormat--) | 오류 막대의 형식을 나타냅니다. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | 오류 막대의 형식을 나타냅니다. |
| [isVisible()](#isVisible--) | 오류 막대 가시성을 가져오거나 설정합니다. |
| [setVisible(boolean value)](#setVisible-boolean-) | 오류 막대 가시성을 가져오거나 설정합니다. |
### getType() {#getType--}
```
public abstract int getType()
```

오류 막대 유형을 가져오거나 설정합니다. 읽기/쓰기 [ErrorBarType](../../com.aspose.slides/errorbartype).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

오류 막대 유형을 가져오거나 설정합니다. 읽기/쓰기 [ErrorBarType](../../com.aspose.slides/errorbartype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

오류 막대 길이를 결정하는 가능한 방법을 나타냅니다. 사용자 정의 값 유형의 경우, 시리즈의 DataPoints 컬렉션에 있는 특정 데이터 포인트의 [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) 속성을 사용하여 값을 지정합니다. 읽기/쓰기 [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Returns:**
int
### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

오류 막대 길이를 결정하는 가능한 방법을 나타냅니다. 사용자 정의 값 유형의 경우, 시리즈의 DataPoints 컬렉션에 있는 특정 데이터 포인트의 [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) 속성을 사용하여 값을 지정합니다. 읽기/쓰기 [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

오류 막대에 끝 캡이 그려지지 않음을 지정합니다. 읽기/쓰기 boolean.

**Returns:**
boolean
### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

오류 막대에 끝 캡이 그려지지 않음을 지정합니다. 읽기/쓰기 boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getValue() {#getValue--}
```
public abstract float getValue()
```

오류 막대 길이를 결정하기 위해 Fixed, Percentage 및 StandardDeviation 값 유형과 함께 사용되는 값을 가져오거나 설정합니다. 읽기/쓰기 float.

**Returns:**
float
### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```

오류 막대 길이를 결정하기 위해 Fixed, Percentage 및 StandardDeviation 값 유형과 함께 사용되는 값을 가져오거나 설정합니다. 읽기/쓰기 float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

오류 막대의 형식을 나타냅니다. 읽기/쓰기 [IFormat](../../com.aspose.slides/iformat).

**Returns:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

오류 막대의 형식을 나타냅니다. 읽기/쓰기 [IFormat](../../com.aspose.slides/iformat).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

오류 막대 가시성을 가져오거나 설정합니다. 읽기/쓰기 boolean.

**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

오류 막대 가시성을 가져오거나 설정합니다. 읽기/쓰기 boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |