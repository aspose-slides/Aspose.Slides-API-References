---
title: IChartDataPoint
second_title: Aspose.Slides for Java API 레퍼런스
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
| [getXValue()](#getXValue--) | 차트 데이터 포인트의 x 값을 가져옵니다. |
| [getYValue()](#getYValue--) | 차트 데이터 포인트의 y 값을 가져옵니다. |
| [getBubbleSize()](#getBubbleSize--) | 차트 데이터 포인트의 버블 크기를 가져옵니다. |
| [getValue()](#getValue--) | 차트 데이터 포인트의 값을 가져옵니다. |
| [getCachedXValue()](#getCachedXValue--) | 차트 데이터 포인트의 캐시된 X 값을 가져옵니다. |
| [getCachedYValue()](#getCachedYValue--) | 차트 데이터 포인트의 캐시된 Y 값을 가져옵니다. |
| [getCachedValue()](#getCachedValue--) | 차트 데이터 포인트의 캐시된 값을 가져옵니다. |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | 차트 데이터 포인트의 캐시된 버블 크기를 가져옵니다. |
| [getSizeValue()](#getSizeValue--) | 차트 데이터 포인트의 크기 값을 가져옵니다. |
| [getColorValue()](#getColorValue--) | 차트 데이터 포인트의 색상 값을 가져옵니다. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | 사용자 지정 값 유형인 경우 시리즈 오류 막대 값을 나타냅니다. |
| [getLabel()](#getLabel--) | 차트 데이터 포인트의 레이블을 나타냅니다. |
| [isBubble3D()](#isBubble3D--) | 버블에 3D 효과가 적용되었음을 지정합니다. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | 버블에 3D 효과가 적용되었음을 지정합니다. |
| [getExplosion()](#getExplosion--) | 데이터 포인트를 파이 차트 중심에서 이동시킬 양을 지정합니다. |
| [setExplosion(int value)](#setExplosion-int-) | 데이터 포인트를 파이 차트 중심에서 이동시킬 양을 지정합니다. |
| [getFormat()](#getFormat--) | 포맷 속성을 나타냅니다. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | 포맷 속성을 나타냅니다. |
| [getMarker()](#getMarker--) | 데이터 마커를 지정합니다. |
| [remove()](#remove--) | 차트 시리즈에서 DataPoint를 제거합니다. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | 시리즈 인덱스, 데이터 포인트 인덱스, ParentSeriesGroup.IsColorVaried 속성 및 차트 스타일을 기반으로 데이터 포인트의 자동 색상을 반환합니다. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | 다음 목록에 있는 차트 유형인 ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie에 해당하는 범례 항목의 속성. |
| [getSetAsTotal()](#getSetAsTotal--) | 데이터 포인트를 합계로 설정합니다. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | 데이터 포인트를 합계로 설정합니다. |
| [getInvertIfNegative()](#getInvertIfNegative--) | 값이 음수인 경우 데이터 포인트의 색상을 반전시킵니다. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | 값이 음수인 경우 데이터 포인트의 색상을 반전시킵니다. |
| [getDataPointLevels()](#getDataPointLevels--) | 데이터 포인트 레벨의 컨테이너를 반환합니다. |
| [getIndex()](#getIndex--) | 이 데이터 포인트가 적용되는 상위 컬렉션의 자식 중 어느 것을 결정합니다. |

### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

차트 데이터 포인트의 x 값을 가져옵니다. 읽기 전용 [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**반환:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

차트 데이터 포인트의 y 값을 가져옵니다. 읽기 전용 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**반환:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

차트 데이터 포인트의 버블 크기를 가져옵니다. 읽기 전용 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**반환:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

차트 데이터 포인트의 값을 가져옵니다. 읽기 전용 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**반환:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getCachedXValue() {#getCachedXValue--}
```
public abstract ICachedChartValue getCachedXValue()
```

차트 데이터 포인트의 캐시된 X 값을 가져옵니다. 읽기 전용 [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // 차트 시리즈의 모든 캐시된 X 값을 출력합니다.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedXValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedYValue() {#getCachedYValue--}
```
public abstract ICachedChartValue getCachedYValue()
```

차트 데이터 포인트의 캐시된 Y 값을 가져옵니다. 읽기 전용 [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // 차트 시리즈의 모든 캐시된 Y 값을 출력합니다.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedYValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```

차트 데이터 포인트의 캐시된 값을 가져옵니다. 읽기 전용 [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // 차트 시리즈의 모든 캐시된 값을 출력합니다.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public abstract ICachedChartValue getCachedBubbleSize()
```

차트 데이터 포인트의 캐시된 버블 크기를 가져옵니다. 읽기 전용 [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // 차트 시리즈의 모든 캐시된 버블 크기 값을 출력합니다.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

차트 데이터 포인트의 크기 값을 가져옵니다. Treemap 및 Sunburst 차트와 함께 사용됩니다. 읽기 전용 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**반환:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

차트 데이터 포인트의 색상 값을 가져옵니다. Map 차트와 함께 사용됩니다. 읽기 전용 [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**반환:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

사용자 지정 값 유형인 경우 시리즈 오류 막대 값을 나타냅니다. 읽기 전용 [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**반환:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

차트 데이터 포인트의 레이블을 나타냅니다. 읽기 전용 [IDataLabel](../../com.aspose.slides/idatalabel).

**반환:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

버블에 3D 효과가 적용되었음을 지정합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

버블에 3D 효과가 적용되었음을 지정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

데이터 포인트를 파이 차트 중심에서 이동시킬 양을 지정합니다. 읽기/쓰기 int.

**반환:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

데이터 포인트를 파이 차트 중심에서 이동시킬 양을 지정합니다. 읽기/쓰기 int.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

포맷 속성을 나타냅니다. 읽기/쓰기 [IFormat](../../com.aspose.slides/iformat).

**반환:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

포맷 속성을 나타냅니다. 읽기/쓰기 [IFormat](../../com.aspose.slides/iformat).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

데이터 마커를 지정합니다. 읽기 전용 [IMarker](../../com.aspose.slides/imarker).

**반환:**
[IMarker](../../com.aspose.slides/imarker)
### remove() {#remove--}
```
public abstract void remove()
```

차트 시리즈에서 DataPoint를 제거합니다.

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Color getAutomaticDataPointColor()
```

시리즈 인덱스, 데이터 포인트 인덱스, ParentSeriesGroup.IsColorVaried 속성 및 차트 스타일을 기반으로 데이터 포인트의 자동 색상을 반환합니다. FillType이 NotDefined인 경우 이 색상이 기본값으로 사용됩니다.

**반환:**
java.awt.Color - 데이터 포인트의 자동 색상 java.awt.Color
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

다음 목록에 있는 차트 유형인 ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie에 해당하는 범례 항목의 속성. 읽기 전용 [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**반환:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

데이터 포인트를 합계로 설정합니다. Waterfall 시리즈 유형에만 적용됩니다.

**반환:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

데이터 포인트를 합계로 설정합니다. Waterfall 시리즈 유형에만 적용됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

값이 음수인 경우 데이터 포인트의 색상을 반전시킵니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

값이 음수인 경우 데이터 포인트의 색상을 반전시킵니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

데이터 포인트 레벨의 컨테이너를 반환합니다. Treeamp 및 Sunburst 시리즈에 적용됩니다. 데이터 포인트 레벨 인덱스는 0부터 시작합니다.

**반환:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

이 데이터 포인트가 적용되는 상위 컬렉션의 자식 중 어느 것을 결정합니다. 읽기 long.

**반환:**
long