---
title: Axis
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 차트 축을 나타내는 객체를 캡슐화합니다.
type: docs
url: /ko/com.aspose.slides/axis/
---
**상속:**  
java.lang.Object, com.aspose.slides.DomObject

**구현된 모든 인터페이스:**  
[com.aspose.slides.IAxis](../../com.aspose.slides/iaxis)  
```
public class Axis extends DomObject<AxesManager> implements IAxis
```

차트 축을 나타내는 객체를 캡슐화합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getChart()](#getChart--) | 상위 차트를 반환합니다. |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | 값 축이 범주 축을 범주 사이에서 교차하는지를 나타냅니다. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | 값 축이 범주 축을 범주 사이에서 교차하는지를 나타냅니다. |
| [getCategoryAxisType()](#getCategoryAxisType--) | 카테고리 축의 유형을 지정합니다. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | 카테고리 축의 유형을 지정합니다. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | 축 데이터에 기반하여 자동으로 결정되는 값을 사용하여 IAxis.CategoryAxisType 속성을 설정합니다. |
| [getCrossAt()](#getCrossAt--) | 수직 축이 교차하는 축상의 지점을 나타냅니다. |
| [setCrossAt(float value)](#setCrossAt-float-) | 수직 축이 교차하는 축상의 지점을 나타냅니다. |
| [getDisplayUnit()](#getDisplayUnit--) | 값 축에 대한 표시 단위의 스케일링 값을 지정합니다. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | 값 축에 대한 표시 단위의 스케일링 값을 지정합니다. |
| [getActualMaxValue()](#getActualMaxValue--) | 축의 실제 최대 값을 지정합니다. |
| [getActualMinValue()](#getActualMinValue--) | 축의 실제 최소 값을 지정합니다. |
| [getActualMajorUnit()](#getActualMajorUnit--) | 축의 실제 주요 단위를 지정합니다. |
| [getActualMinorUnit()](#getActualMinorUnit--) | 축의 실제 부단위를 지정합니다. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | 축의 실제 주요 단위 스케일을 지정합니다. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | 축의 실제 부단위 스케일을 지정합니다. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | 최대 값이 자동으로 할당되는지 여부를 나타냅니다. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | 최대 값이 자동으로 할당되는지 여부를 나타냅니다. |
| [getMaxValue()](#getMaxValue--) | 값 축의 최대 값을 나타냅니다. |
| [setMaxValue(double value)](#setMaxValue-double-) | 값 축의 최대 값을 나타냅니다. |
| [getMinorUnit()](#getMinorUnit--) | 날짜 또는 값 축에 대한 부단위를 나타냅니다. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | 날짜 또는 값 축에 대한 부단위를 나타냅니다. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | 축의 부단위가 자동으로 할당되는지 여부를 나타냅니다. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | 축의 부단위가 자동으로 할당되는지 여부를 나타냅니다. |
| [getMajorUnit()](#getMajorUnit--) | 날짜 또는 값 축에 대한 주요 단위를 나타냅니다. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | 날짜 또는 값 축에 대한 주요 단위를 나타냅니다. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | 축의 주요 단위가 자동으로 할당되는지 여부를 나타냅니다. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | 축의 주요 단위가 자동으로 할당되는지 여부를 나타냅니다. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | 최소 값이 자동으로 할당되는지 여부를 나타냅니다. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | 최소 값이 자동으로 할당되는지 여부를 나타냅니다. |
| [getMinValue()](#getMinValue--) | 값 축의 최소 값을 나타냅니다. |
| [setMinValue(double value)](#setMinValue-double-) | 값 축의 최소 값을 나타냅니다. |
| [isLogarithmic()](#isLogarithmic--) | 값 축 스케일 유형이 로그인지 여부를 나타냅니다. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | 값 축 스케일 유형이 로그인지 여부를 나타냅니다. |
| [getLogBase()](#getLogBase--) | 로그 베이스를 나타냅니다. |
| [setLogBase(double value)](#setLogBase-double-) | 로그 베이스를 나타냅니다. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | MS PowerPoint가 데이터 포인트를 마지막에서 첫 번째로 플롯하는지를 나타냅니다. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | MS PowerPoint가 데이터 포인트를 마지막에서 첫 번째로 플롯하는지를 나타냅니다. |
| [isVisible()](#isVisible--) | 축이 보이는지 여부를 나타냅니다. |
| [setVisible(boolean value)](#setVisible-boolean-) | 축이 보이는지 여부를 나타냅니다. |
| [getMajorTickMark()](#getMajorTickMark--) | 지정된 축에 대한 주요 눈금 표시 유형을 나타냅니다. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | 지정된 축에 대한 주요 눈금 표시 유형을 나타냅니다. |
| [getMinorTickMark()](#getMinorTickMark--) | 지정된 축에 대한 부 눈금 표시 유형을 나타냅니다. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | 지정된 축에 대한 부 눈금 표시 유형을 나타냅니다. |
| [getTickLabelPosition()](#getTickLabelPosition--) | 지정된 축에 대한 눈금 레이블 위치를 나타냅니다. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | 지정된 축에 대한 눈금 레이블 위치를 나타냅니다. |
| [getMajorUnitScale()](#getMajorUnitScale--) | 날짜 축에 대한 주요 단위 스케일을 나타냅니다. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | 날짜 축에 대한 주요 단위 스케일을 나타냅니다. |
| [getMinorUnitScale()](#getMinorUnitScale--) | 날짜 축에 대한 주요 단위 스케일을 나타냅니다. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | 날짜 축에 대한 주요 단위 스케일을 나타냅니다. |
| [getBaseUnitScale()](#getBaseUnitScale--) | 날짜 축에 표시되는 가장 작은 시간 단위를 지정합니다. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | 날짜 축에 표시되는 가장 작은 시간 단위를 지정합니다. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | 차트 축에 대한 부 그리드선 형식을 나타냅니다. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | 차트 축에 대한 주요 그리드선 형식을 나타냅니다. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | 부 그리드선을 숨기려면 MinorGridLinesFormat.Line.FillFormat.FillType을 FillType.NoFill로 설정합니다. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | 주요 그리드선을 숨기려면 MajorGridLinesFormat.Line.FillFormat.FillType을 FillType.NoFill로 설정합니다. |
| [getFormat()](#getFormat--) | 축의 형식을 나타냅니다. |
| [getTextFormat()](#getTextFormat--) | 텍스트의 형식을 나타냅니다. |
| [getTitle()](#getTitle--) | 축의 제목을 가져옵니다. |
| [getCrossType()](#getCrossType--) | 다른 축이 교차하는 지정된 축의 CrossType을 나타냅니다. |
| [setCrossType(int value)](#setCrossType-int-) | 다른 축이 교차하는 지정된 축의 CrossType을 나타냅니다. |
| [getPosition()](#getPosition--) | 축의 위치를 나타냅니다. |
| [setPosition(int value)](#setPosition-int-) | 축의 위치를 나타냅니다. |
| [hasTitle()](#hasTitle--) | 축에 표시 가능한 제목이 있는지 여부를 결정합니다. |
| [setTitle(boolean value)](#setTitle-boolean-) | 축에 표시 가능한 제목이 있는지 여부를 결정합니다. |
| [getNumberFormat()](#getNumberFormat--) | 축 레이블에 대한 형식 문자열을 나타냅니다. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | 축 레이블에 대한 형식 문자열을 나타냅니다. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | 형식이 원본 데이터에 연결되어 있는지 여부를 나타냅니다. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | 형식이 원본 데이터에 연결되어 있는지 여부를 나타냅니다. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | 눈금 레이블의 회전 각도를 나타냅니다. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | 눈금 레이블의 회전 각도를 나타냅니다. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | 그려지는 레이블 사이에 건너뛰는 눈금 레이블 수를 지정합니다. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | 그려지는 레이블 사이에 건너뛰는 눈금 레이블 수를 지정합니다. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | 자동 눈금 레이블 간격 값을 지정합니다. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | 자동 눈금 레이블 간격 값을 지정합니다. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | 다음 눈금이 그려지기 전에 건너뛰어야 할 눈금 수를 지정합니다. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | 다음 눈금이 그려지기 전에 건너뛰어야 할 눈금 수를 지정합니다. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | 자동 눈금 간격 값을 지정합니다. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | 자동 눈금 간격 값을 지정합니다. |
| [getLabelOffset()](#getLabelOffset--) | 레이블을 축에서 떨어뜨린 거리를 지정합니다. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | 레이블을 축에서 떨어뜨린 거리를 지정합니다. |
| [getAggregationType()](#getAggregationType--) | 카테고리 축(빈닝)의 집계 유형을 나타냅니다. |
| [setAggregationType(int value)](#setAggregationType-int-) | 카테고리 축(빈닝)의 집계 유형을 나타냅니다. |
| [getBinWidth()](#getBinWidth--) | AggregationType 속성 값이 AxisAggregationType.ByBinWidth으로 설정된 경우 빈 너비를 지정합니다. |
| [setBinWidth(double value)](#setBinWidth-double-) | AggregationType 속성 값이 AxisAggregationType.ByBinWidth으로 설정된 경우 빈 너비를 지정합니다. |
| [getNumberOfBins()](#getNumberOfBins--) | AggregationType 속성 값이 AxisAggregationType.ByNumberOfBins으로 설정된 경우 빈 개수를 지정합니다. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | AggregationType 속성 값이 AxisAggregationType.ByNumberOfBins으로 설정된 경우 빈 개수를 지정합니다. |
| [isOverflowBin()](#isOverflowBin--) | 오버플로우 빈이 적용되는지 여부를 지정합니다. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | 오버플로우 빈이 적용되는지 여부를 지정합니다. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | 자동 오버플로우 빈 값을 지정합니다. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | 자동 오버플로우 빈 값을 지정합니다. |
| [getOverflowBin()](#getOverflowBin--) | 오버플로우 빈 사용자 정의 값을 지정합니다. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | 오버플로우 빈 사용자 정의 값을 지정합니다. |
| [isUnderflowBin()](#isUnderflowBin--) | 언더플로우 빈이 적용되는지 여부를 지정합니다. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | 언더플로우 빈이 적용되는지 여부를 지정합니다. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | 자동 언더플로우 빈 값을 지정합니다. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | 자동 언더플로우 빈 값을 지정합니다. |
| [getUnderflowBin()](#getUnderflowBin--) | 언더플로우 빈 사용자 정의 값을 지정합니다. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | 언더플로우 빈 사용자 정의 값을 지정합니다. |
| [getSlide()](#getSlide--) | FillFormat의 상위 슬라이드를 반환합니다. |
| [getPresentation()](#getPresentation--) | FillFormat의 상위 프레젠테이션을 반환합니다. |

### getChart() {#getChart--}
```
public final IChart getChart()
```

상위 차트를 반환합니다. 읽기 전용 [IChart](../../com.aspose.slides/ichart).

**반환값:**
[IChart](../../com.aspose.slides/ichart)

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```

값 축이 범주 축을 범주 사이에서 교차하는지를 나타냅니다. 이 속성은 카테고리 축에만 적용되며 3D 차트에는 적용되지 않습니다. 읽기/쓰기 boolean.

**반환값:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

값 축이 범주 축을 범주 사이에서 교차하는지를 나타냅니다. 이 속성은 카테고리 축에만 적용되며 3D 차트에는 적용되지 않습니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```

카테고리 축의 유형을 지정합니다. 읽기/쓰기 [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**반환값:**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```

카테고리 축의 유형을 지정합니다. 읽기/쓰기 [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public final void setCategoryAxisTypeAutomatically()
```

축 데이터에 기반하여 자동으로 결정되는 값을 사용하여 IAxis.CategoryAxisType 속성을 설정합니다.

### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```

수직 축이 교차하는 축상의 지점을 나타냅니다. 읽기/쓰기 float.

**반환값:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

수직 축이 교차하는 축상의 지점을 나타냅니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```

값 축에 대한 표시 단위의 스케일링 값을 지정합니다. 읽기/쓰기 [DisplayUnitType](../../com.aspose.slides/displayunittype).

**반환값:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```

값 축에 대한 표시 단위의 스케일링 값을 지정합니다. 읽기/쓰기 [DisplayUnitType](../../com.aspose.slides/displayunittype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```

축의 실제 최대 값을 지정합니다. 실제 값을 얻으려면 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오.

**반환값:**
double

### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

축의 실제 최소 값을 지정합니다. 실제 값을 얻으려면 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오.

**반환값:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

축의 실제 주요 단위를 지정합니다. 실제 값을 얻으려면 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오.

**반환값:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

축의 실제 부단위를 지정합니다. 실제 값을 얻으려면 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오.

**반환값:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

축의 실제 주요 단위 스케일을 지정합니다. 실제 값을 얻으려면 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오.

**반환값:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

축의 실제 부단위 스케일을 지정합니다. 실제 값을 얻으려면 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오.

**반환값:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

최대 값이 자동으로 할당되는지 여부를 나타냅니다. 읽기/쓰기 boolean.

**반환값:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

최대 값이 자동으로 할당되는지 여부를 나타냅니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

값 축의 최대 값을 나타냅니다. 읽기/쓰기 double.

**반환값:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

값 축의 최대 값을 나타냅니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

날짜 또는 값 축에 대한 부단위를 나타냅니다. 읽기/쓰기 double.

**반환값:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```

날짜 또는 값 축에 대한 부단위를 나타냅니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```

축의 부단위가 자동으로 할당되는지 여부를 나타냅니다. 읽기/쓰기 boolean.

**반환값:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```

축의 부단위가 자동으로 할당되는지 여부를 나타냅니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```

날짜 또는 값 축에 대한 주요 단위를 나타냅니다. 읽기/쓰기 double.

**반환값:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```

날짜 또는 값 축에 대한 주요 단위를 나타냅니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```

축의 주요 단위가 자동으로 할당되는지 여부를 나타냅니다. 읽기/쓰기 boolean.

**반환값:**
boolean

### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```

축의 주요 단위가 자동으로 할당되는지 여부를 나타냅니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```

최소 값이 자동으로 할당되는지 여부를 나타냅니다. 읽기/쓰기 boolean.

**반환값:**
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```

최소 값이 자동으로 할당되는지 여부를 나타냅니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```

값 축의 최소 값을 나타냅니다. 읽기/쓰기 double.

**반환값:**
double

### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```

값 축의 최소 값을 나타냅니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```

값 축 스케일 유형이 로그인지 여부를 나타냅니다. 읽기/쓰기 boolean.

**반환값:**
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```

값 축 스케일 유형이 로그인지 여부를 나타냅니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```

로그 베이스를 나타냅니다. 기본값은 10입니다. 읽기/쓰기 double.

**반환값:**
double

### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```

로그 베이스를 나타냅니다. 기본값은 10입니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public final boolean isPlotOrderReversed()
```

MS PowerPoint가 데이터 포인트를 마지막에서 첫 번째로 플롯하는지를 나타냅니다. 읽기/쓰기 boolean.

**반환값:**
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```

MS PowerPoint가 데이터 포인트를 마지막에서 첫 번째로 플롯하는지를 나타냅니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

축이 보이는지 여부를 나타냅니다. 읽기/쓰기 boolean.

**반환값:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

축이 보이는지 여부를 나타냅니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```

지정된 축에 대한 주요 눈금 표시 유형을 나타냅니다. 읽기/쓰기 [TickMarkType](../../com.aspose.slides/tickmarktype).

**반환값:**
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```

지정된 축에 대한 주요 눈금 표시 유형을 나타냅니다. 읽기/쓰기 [TickMarkType](../../com.aspose.slides/tickmarktype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```

지정된 축에 대한 부 눈금 표시 유형을 나타냅니다. 읽기/쓰기 [TickMarkType](../../com.aspose.slides/tickmarktype).

**반환값:**
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```

지정된 축에 대한 부 눈금 표시 유형을 나타냅니다. 읽기/쓰기 [TickMarkType](../../com.aspose.slides/tickmarktype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```

지정된 축에 대한 눈금 레이블 위치를 나타냅니다. 읽기/쓰기 [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**반환값:**
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```

지정된 축에 대한 눈금 레이블 위치를 나타냅니다. 읽기/쓰기 [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```

날짜 축에 대한 주요 단위 스케일을 나타냅니다. 읽기/쓰기 [TimeUnitType](../../com.aspose.slides/timeunittype).

**반환값:**
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```

날짜 축에 대한 주요 단위 스케일을 나타냅니다. 읽기/쓰기 [TimeUnitType](../../com.aspose.slides/timeunittype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```

날짜 축에 대한 주요 단위 스케일을 나타냅니다. 읽기/쓰기 [TimeUnitType](../../com.aspose.slides/timeunittype).

**반환값:**
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```

날짜 축에 대한 주요 단위 스케일을 나타냅니다. 읽기/쓰기 [TimeUnitType](../../com.aspose.slides/timeunittype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```

날짜 축에 표시되는 가장 작은 시간 단위를 지정합니다. 읽기/쓰기 [TimeUnitType](../../com.aspose.slides/timeunittype).

**반환값:**
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```

날짜 축에 표시되는 가장 작은 시간 단위를 지정합니다. 읽기/쓰기 [TimeUnitType](../../com.aspose.slides/timeunittype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```

차트 축에 대한 부 그리드선 형식을 나타냅니다. 읽기 전용 [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**반환값:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMajorGridLinesFormat()
```

차트 축에 대한 주요 그리드선 형식을 나타냅니다. 읽기 전용 [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**반환값:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```

부 그리드선을 숨기려면 MinorGridLinesFormat.Line.FillFormat.FillType을 FillType.NoFill로 설정합니다. 읽기 전용 boolean.

**반환값:**
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```

주 그리드선을 숨기려면 MajorGridLinesFormat.Line.FillFormat.FillType을 FillType.NoFill로 설정합니다. 읽기 전용 boolean.

**반환값:**
boolean

### getFormat() {#getFormat--}
```
public final IAxisFormat getFormat()
```

축의 형식을 나타냅니다. 읽기 전용 [IAxisFormat](../../com.aspose.slides/iaxisformat).

**반환값:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

텍스트의 형식을 나타냅니다. 읽기 전용 [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**반환값:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getTitle() {#getTitle--}
```
public final IChartTitle getTitle()
```

축의 제목을 가져옵니다. 읽기 전용 [IChartTitle](../../com.aspose.slides/icharttitle).

**반환값:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```

다른 축이 교차하는 지정된 축의 CrossType을 나타냅니다. 읽기/쓰기 [CrossesType](../../com.aspose.slides/crossestype).

**반환값:**
int

### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```

다른 축이 교차하는 지정된 축의 CrossType을 나타냅니다. 읽기/쓰기 [CrossesType](../../com.aspose.slides/crossestype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```

축의 위치를 나타냅니다. 읽기/쓰기 [AxisPositionType](../../com.aspose.slides/axispositiontype).

**반환값:**
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

축의 위치를 나타냅니다. 읽기/쓰기 [AxisPositionType](../../com.aspose.slides/axispositiontype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

축에 표시 가능한 제목이 있는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

축에 표시 가능한 제목이 있는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

축 레이블에 대한 형식 문자열을 나타냅니다. 읽기/쓰기 String.

**반환값:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

축 레이블에 대한 형식 문자열을 나타냅니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

형식이 원본 데이터에 연결되어 있는지 여부를 나타냅니다. 읽기/쓰기 boolean.

**반환값:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

형식이 원본 데이터에 연결되어 있는지 여부를 나타냅니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```

눈금 레이블의 회전 각도를 나타냅니다. 읽기/쓰기 float.

**반환값:**
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```

눈금 레이블의 회전 각도를 나타냅니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```

그려지는 레이블 사이에 건너뛰는 눈금 레이블 수를 지정합니다. 범주 또는 시리즈 축에 적용됩니다. 읽기/쓰기 long.

**반환값:**
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```

그려지는 레이블 사이에 건너뛰는 눈금 레이블 수를 지정합니다. 범주 또는 시리즈 축에 적용됩니다. 읽기/쓰기 long.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```

자동 눈금 레이블 간격 값을 지정합니다. false인 경우 TickLabelSpacing 속성을 사용합니다. 읽기/쓰기 boolean.

**반환값:**
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```

자동 눈금 레이블 간격 값을 지정합니다. false인 경우 TickLabelSpacing 속성을 사용합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```

다음 눈금이 그려지기 전에 건너뛰어야 할 눈금 수를 지정합니다. 범주 또는 시리즈 축에 적용됩니다. 읽기/쓰기 int.

**반환값:**
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```

다음 눈금이 그려지기 전에 건너뛰어야 할 눈금 수를 지정합니다. 범주 또는 시리즈 축에 적용됩니다. 읽기/쓰기 int.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```

자동 눈금 간격 값을 지정합니다. false인 경우 TickMarksSpacing 속성을 사용합니다. 읽기/쓰기 boolean.

**반환값:**
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```

자동 눈금 간격 값을 지정합니다. false인 경우 TickMarksSpacing 속성을 사용합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```

축으로부터 레이블까지의 거리를 지정합니다. 범주 또는 날짜 축에 적용됩니다. 값은 0%에서 1000% 사이여야 합니다. 읽기/쓰기 int.

**반환값:**
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```

축으로부터 레이블까지의 거리를 지정합니다. 범주 또는 날짜 축에 적용됩니다. 값은 0%에서 1000% 사이여야 합니다. 읽기/쓰기 int.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```

카테고리 축(빈닝)의 집계 유형을 나타냅니다. 카테고리에 적용됩니다. 히스토그램 또는 HistogramPareto 시리즈와 함께 사용됩니다.

**반환값:**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```

카테고리 축(빈닝)의 집계 유형을 나타냅니다. 카테고리에 적용됩니다. 히스토그램 또는 HistogramPareto 시리즈와 함께 사용됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```

AggregationType 속성 값이 AxisAggregationType.ByBinWidth으로 설정된 경우 빈 너비를 지정합니다. 카테고리 축에 적용됩니다. 히스토그램 또는 HistogramPare토 시리즈와 함께 사용됩니다.

**반환값:**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```

AggregationType 속성 값이 AxisAggregationType.ByBinWidth으로 설정된 경우 빈 너비를 지정합니다. 카테고리 축에 적용됩니다. 히스토그램 또는 HistogramPare토 시리즈와 함께 사용됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```

AggregationType 속성 값이 AxisAggregationType.ByNumberOfBins으로 설정된 경우 빈 개수를 지정합니다. 카테고리 축에 적용됩니다. 히스토그램 또는 HistogramPare토 시리즈와 함께 사용됩니다.

**반환값:**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```

AggregationType 속성 값이 AxisAggregationType.ByNumberOfBins으로 설정된 경우 빈 개수를 지정합니다. 카테고리 축에 적용됩니다. 히스토그램 또는 HistogramPare토 시리즈와 함께 사용됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```

오버플로우 빈이 적용되는지 여부를 지정합니다. IsAutomaticOverflowBin 및 OverflowBin을 사용하여 오버플로우 빈 값을 조정하십시오.

**반환값:**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```

오버플로우 빈이 적용되는지 여부를 지정합니다. IsAutomaticOverflowBin 및 OverflowBin을 사용하여 오버플로우 빈 값을 조정하십시오.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```

자동 오버플로우 빈 값을 지정합니다. false인 경우 OverflowBin 속성을 사용합니다.

**반환값:**
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```

자동 오버플로우 빈 값을 지정합니다. false인 경우 OverflowBin 속성을 사용합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```

오버플로우 빈 사용자 정의 값을 지정합니다. IsAutomaticOverflowBin 속성이 false로 설정되고 IsOverflowBin 속성이 true인 경우에 적용됩니다.

**반환값:**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```

오버플로우 빈 사용자 정의 값을 지정합니다. IsAutomaticOverflowBin 속성이 false로 설정되고 IsOverflowBin 속성이 true인 경우에 적용됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```

언더플로우 빈이 적용되는지 여부를 지정합니다. IsAutomaticUnderflowBin 및 UnderflowBin을 사용하여 언더플로우 빈 값을 조정하십시오.

**반환값:**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```

언더플로우 빈이 적용되는지 여부를 지정합니다. IsAutomaticUnderflowBin 및 UnderflowBin을 사용하여 언더플로우 빈 값을 조정하십시오.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```

자동 언더플로우 빈 값을 지정합니다. false인 경우 UnderflowBin 속성을 사용합니다.

**반환값:**
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```

자동 언더플로우 빈 값을 지정합니다. false인 경우 UnderflowBin 속성을 사용합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```

언더플로우 빈 사용자 정의 값을 지정합니다. IsAutomaticUnderflowBin 속성이 false로 설정되고 IsUnderflowBin 속성이 true인 경우에 적용됩니다.

**반환값:**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```

언더플로우 빈 사용자 정의 값을 지정합니다. IsAutomaticUnderflowBin 속성이 false로 설정되고 IsUnderflowBin 속성이 true인 경우에 적용됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |

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