---
title: ChartDataPoint
second_title: Aspose.Slides for Android - Java API 참조
description: 시리즈 데이터 포인트를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/chartdatapoint/
---
**상속:**  
java.lang.Object

**모든 구현된 인터페이스:**  
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject  
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

시리즈 데이터 포인트를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | 차트 데이터 포인트의 크기 값을 반환합니다. |
| [getColorValue()](#getColorValue--) | 차트 데이터 포인트의 색상 값을 반환합니다. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Custom 값 유형인 경우 시리즈 오류 막대 값을 나타냅니다. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | 버블에 3-D 효과가 적용되었음을 지정합니다. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | 버블에 3-D 효과가 적용되었음을 지정합니다. |
| [getExplosion()](#getExplosion--) | 파이 중심에서 데이터 포인트가 이동할 양을 지정합니다. |
| [setExplosion(int value)](#setExplosion-int-) | 파이 중심에서 데이터 포인트가 이동할 양을 지정합니다. |
| [getFormat()](#getFormat--) | 서식 속성을 나타냅니다. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | 서식 속성을 나타냅니다. |
| [getMarker()](#getMarker--) | 데이터 마커를 지정합니다. |
| [getSetAsTotal()](#getSetAsTotal--) | 데이터 포인트를 총계로 설정합니다. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | 데이터 포인트를 총계로 설정합니다. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | 다음 목록에 있는 차트 유형인 경우 해당 범례 항목의 속성: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | 차트 시리즈에서 DataPoint를 제거합니다. |
| [getDataPointLevels()](#getDataPointLevels--) | 데이터 포인트 레벨의 컨테이너를 반환합니다. |
| [getIndex()](#getIndex--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | 시리즈 인덱스, 데이터 포인트 인덱스, ParentSeriesGroup.IsColorVaried 속성 및 차트 스타일을 기반으로 데이터 포인트의 자동 색상을 반환합니다. |
| [getInvertIfNegative()](#getInvertIfNegative--) | 값이 음수인 경우 데이터 포인트가 색상을 반전하도록 지정합니다. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | 값이 음수인 경우 데이터 포인트가 색상을 반전하도록 지정합니다. |
| [getActualX()](#getActualX--) | 차트 왼쪽 상단 모서리를 기준으로 차트 요소의 실제 x 위치(왼쪽)를 지정합니다. |
| [getActualY()](#getActualY--) | 차트 왼쪽 상단 모서리를 기준으로 차트 요소의 실제 상단을 지정합니다. |
| [getActualWidth()](#getActualWidth--) | 차트 요소의 실제 너비를 지정합니다. |
| [getActualHeight()](#getActualHeight--) | 차트 요소의 실제 높이를 지정합니다. |

### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```

XValue. 읽기 전용 [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**반환값:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```

YValue. 읽기 전용 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**반환값:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```

BubbleSize. 읽기 전용 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**반환값:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```

Value. 읽기 전용 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**반환값:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```

차트 데이터 포인트의 크기 값을 반환합니다. Treemap 및 Sunburst 차트에서 사용됩니다. 읽기 전용 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**반환값:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

차트 데이터 포인트의 색상 값을 반환합니다. Map 차트에서 사용됩니다. 읽기 전용 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**반환값:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

Custom 값 유형인 경우 시리즈 오류 막대 값을 나타냅니다. 읽기 전용 [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**반환값:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```

Label. 읽기 전용 [IDataLabel](../../com.aspose.slides/idatalabel).

**반환값:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```

버블에 3-D 효과가 적용되었음을 지정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

버블에 3-D 효과가 적용되었음을 지정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

파이 중심에서 데이터 포인트가 이동할 양을 지정합니다. 읽기/쓰기 int.

**반환값:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

파이 중심에서 데이터 포인트가 이동할 양을 지정합니다. 읽기/쓰기 int.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

서식 속성을 나타냅니다. 읽기/쓰기 [IFormat](../../com.aspose.slides/iformat).

**반환값:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

서식 속성을 나타냅니다. 읽기/쓰기 [IFormat](../../com.aspose.slides/iformat).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

데이터 마커를 지정합니다. 읽기 전용 [IMarker](../../com.aspose.slides/imarker).

**반환값:**
[IMarker](../../com.aspose.slides/imarker)

### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

데이터 포인트를 총계로 설정합니다. Waterfall 시리즈 유형에만 적용됩니다.

**반환값:**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

데이터 포인트를 총계로 설정합니다. Waterfall 시리즈 유형에만 적용됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

다음 목록에 있는 차트 유형인 경우 해당 범례 항목의 속성: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. 읽기 전용 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**반환값:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### remove() {#remove--}
```
public final void remove()
```

차트 시리즈에서 DataPoint를 제거합니다.

### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```

데이터 포인트 레벨의 컨테이너를 반환합니다. Treeamp 및 Sunburst 시리즈에 적용됩니다. 데이터 포인트 레벨 인덱싱은 0부터 시작합니다.

**반환값:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public final long getIndex()
```

  

**반환값:**
long

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환값:**
com.aspose.slides.IDOMObject

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Integer getAutomaticDataPointColor()
```

시리즈 인덱스, 데이터 포인트 인덱스, ParentSeriesGroup.IsColorVaried 속성 및 차트 스타일을 기반으로 데이터 포인트의 자동 색상을 반환합니다. FillType이 NotDefined인 경우 기본적으로 이 색상이 사용됩니다.

**반환값:**
java.lang.Integer

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

값이 음수인 경우 데이터 포인트가 색상을 반전하도록 지정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

값이 음수인 경우 데이터 포인트가 색상을 반전하도록 지정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

차트 왼쪽 상단 모서리를 기준으로 차트 요소의 실제 x 위치(왼쪽)를 지정합니다. 실제 값을 얻기 위해 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오. 읽기 float.

**반환값:**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

차트 왼쪽 상단 모서리를 기준으로 차트 요소의 실제 상단을 지정합니다. 실제 값을 얻기 위해 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오. 읽기 float.

**반환값:**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

차트 요소의 실제 너비를 지정합니다. 실제 값을 얻기 위해 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오. 읽기 float.

**반환값:**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

차트 요소의 실제 높이를 지정합니다. 실제 값을 얻기 위해 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오. 읽기 float.

**반환값:**
float