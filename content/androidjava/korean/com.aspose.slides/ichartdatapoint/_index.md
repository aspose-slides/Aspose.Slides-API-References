---
title: IChartDataPoint
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 시리즈 데이터 포인트를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ichartdatapoint/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

시리즈 데이터 포인트를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getXValue()](#getXValue--) | 차트 데이터 포인트의 x 값을 반환합니다. |
| [getYValue()](#getYValue--) | 차트 데이터 포인트의 y 값을 반환합니다. |
| [getBubbleSize()](#getBubbleSize--) | 차트 데이터 포인트의 버블 크기를 반환합니다. |
| [getValue()](#getValue--) | 차트 데이터 포인트의 값을 반환합니다. |
| [getSizeValue()](#getSizeValue--) | 차트 데이터 포인트의 크기 값을 반환합니다. |
| [getColorValue()](#getColorValue--) | 차트 데이터 포인트의 색상 값을 반환합니다. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | 사용자 지정 값 유형인 경우 시리즈 오류 막대 값을 나타냅니다. |
| [getLabel()](#getLabel--) | 차트 데이터 포인트의 레이블을 나타냅니다. |
| [isBubble3D()](#isBubble3D--) | 버블에 3-D 효과가 적용되도록 지정합니다. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | 버블에 3-D 효과가 적용되도록 지정합니다. |
| [getExplosion()](#getExplosion--) | 파이 중심에서 데이터 포인트가 이동해야 하는 양을 지정합니다. |
| [setExplosion(int value)](#setExplosion-int-) | 파이 중심에서 데이터 포인트가 이동해야 하는 양을 지정합니다. |
| [getFormat()](#getFormat--) | 서식 속성을 나타냅니다. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | 서식 속성을 나타냅니다. |
| [getMarker()](#getMarker--) | 데이터 마커를 지정합니다. |
| [remove()](#remove--) | 차트 시리즈에서 DataPoint를 제거합니다. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | 시리즈 인덱스, 데이터 포인트 인덱스, ParentSeriesGroup.IsColorVaried 속성 및 차트 스타일을 기반으로 자동 색상을 반환합니다. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | 다음 차트 유형에 대한 해당 범례 항목의 속성: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | 데이터 포인트를 전체로 설정합니다. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | 데이터 포인트를 전체로 설정합니다. |
| [getInvertIfNegative()](#getInvertIfNegative--) | 값이 음수인 경우 데이터 포인트의 색상을 반전하도록 지정합니다. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | 값이 음수인 경우 데이터 포인트의 색상을 반전하도록 지정합니다. |
| [getDataPointLevels()](#getDataPointLevels--) | 데이터 포인트 레벨 컨테이너를 반환합니다. |
| [getIndex()](#getIndex--) | 부모의 자식 컬렉션 중 어느 것이 이 데이터 포인트에 적용되는지 결정합니다. |
### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```


차트 데이터 포인트의 x 값을 반환합니다. 읽기 전용 [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**반환값:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```


차트 데이터 포인트의 y 값을 반환합니다. 읽기 전용 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**반환값:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```


차트 데이터 포인트의 버블 크기를 반환합니다. 읽기 전용 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**반환값:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```


차트 데이터 포인트의 값을 반환합니다. 읽기 전용 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**반환값:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```


차트 데이터 포인트의 크기 값을 반환합니다. Treemap 및 Sunburst 차트에서 사용됩니다. 읽기 전용 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**반환값:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```


차트 데이터 포인트의 색상 값을 반환합니다. Map 차트에서 사용됩니다. 읽기 전용 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**반환값:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```


사용자 지정 값 유형인 경우 시리즈 오류 막대 값을 나타냅니다. 읽기 전용 [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**반환값:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```


차트 데이터 포인트의 레이블을 나타냅니다. 읽기 전용 [IDataLabel](../../com.aspose.slides/idatalabel).

**반환값:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```


버블에 3-D 효과가 적용되도록 지정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```


버블에 3-D 효과가 적용되도록 지정합니다. 읽기/쓰기 boolean.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```


파이 중심에서 데이터 포인트가 이동해야 하는 양을 지정합니다. 읽기/쓰기 int.

**반환값:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```


파이 중심에서 데이터 포인트가 이동해야 하는 양을 지정합니다. 읽기/쓰기 int.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


서식 속성을 나타냅니다. 읽기/쓰기 [IFormat](../../com.aspose.slides/iformat).

**반환값:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```


서식 속성을 나타냅니다. 읽기/쓰기 [IFormat](../../com.aspose.slides/iformat).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```


데이터 마커를 지정합니다. 읽기 전용 [IMarker](../../com.aspose.slides/imarker).

**반환값:**
[IMarker](../../com.aspose.slides/imarker)
### remove() {#remove--}
```
public abstract void remove()
```


차트 시리즈에서 DataPoint를 제거합니다.
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Integer getAutomaticDataPointColor()
```


시리즈 인덱스, 데이터 포인트 인덱스, ParentSeriesGroup.IsColorVaried 속성 및 차트 스타일을 기반으로 자동 색상을 반환합니다. FillType이 NotDefined일 경우 기본적으로 사용되는 색상입니다.

**반환값:**
java.lang.Integer - Automatic color of data point java.lang.Integer
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```


다음 차트 유형에 대한 해당 범례 항목의 속성: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. 읽기 전용 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**반환값:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```


데이터 포인트를 전체로 설정합니다. Waterfall 시리즈 유형에만 적용됩니다.

**반환값:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```


데이터 포인트를 전체로 설정합니다. Waterfall 시리즈 유형에만 적용됩니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```


값이 음수인 경우 데이터 포인트의 색상을 반전하도록 지정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```


값이 음수인 경우 데이터 포인트의 색상을 반전하도록 지정합니다. 읽기/쓰기 boolean.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```


데이터 포인트 레벨 컨테이너를 반환합니다. Treeamp 및 Sunburst 시리즈에 적용됩니다. 데이터 포인트 레벨 인덱싱은 0부터 시작합니다.

**반환값:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```


부모의 자식 컬렉션 중 어느 것이 이 데이터 포인트에 적용되는지 결정합니다. 읽기 long.

**반환값:**
long