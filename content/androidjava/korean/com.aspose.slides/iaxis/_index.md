---
title: IAxis
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 차트 축을 나타내는 객체를 캡슐화합니다.
type: docs
url: /ko/com.aspose.slides/iaxis/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

Encapsulates the object that represents a chart's axis.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | 값 축이 카테고리 축을 카테고리 사이에서 교차하는지 나타냅니다. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | 값 축이 카테고리 축을 카테고리 사이에서 교차하는지 나타냅니다. |
| [getCrossAt()](#getCrossAt--) | 축에 수직인 축이 교차하는 지점을 나타냅니다. |
| [setCrossAt(float value)](#setCrossAt-float-) | 축에 수직인 축이 교차하는 지점을 나타냅니다. |
| [getDisplayUnit()](#getDisplayUnit--) | 값 축에 대한 표시 단위의 스케일 값을 지정합니다. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | 값 축에 대한 표시 단위의 스케일 값을 지정합니다. |
| [getActualMaxValue()](#getActualMaxValue--) | 축의 실제 최대 값을 지정합니다. |
| [getActualMinValue()](#getActualMinValue--) | 축의 실제 최소 값을 지정합니다. |
| [getActualMajorUnit()](#getActualMajorUnit--) | 축의 실제 주요 단위를 지정합니다. |
| [getActualMinorUnit()](#getActualMinorUnit--) | 축의 실제 부단위를 지정합니다. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | 축의 실제 주요 단위 스케일을 지정합니다. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | 축의 실제 부단위 스케일을 지정합니다. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | 최대 값이 자동으로 할당되는지 나타냅니다. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | 최대 값이 자동으로 할당되는지 나타냅니다. |
| [getMaxValue()](#getMaxValue--) | 값 축의 최대 값을 나타냅니다. |
| [setMaxValue(double value)](#setMaxValue-double-) | 값 축의 최대 값을 나타냅니다. |
| [getMinorUnit()](#getMinorUnit--) | 날짜 또는 값 축에 대한 부단위를 나타냅니다. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | 날짜 또는 값 축에 대한 부단위를 나타냅니다. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | 축의 부단위가 자동으로 할당되는지 나타냅니다. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | 축의 부단위가 자동으로 할당되는지 나타냅니다. |
| [getMajorUnit()](#getMajorUnit--) | 날짜 또는 값 축에 대한 주요 단위를 나타냅니다. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | 날짜 및 값 축에 대한 주요 단위를 나타냅니다. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | 축의 주요 단위가 자동으로 할당되는지 나타냅니다. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | 축의 주요 단위가 자동으로 할당되는지 나타냅니다. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | 최소 값이 자동으로 할당되는지 나타냅니다. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | 최소 값이 자동으로 할당되는지 나타냅니다. |
| [getMinValue()](#getMinValue--) | 값 축의 최소 값을 나타냅니다. |
| [setMinValue(double value)](#setMinValue-double-) | 값 축의 최소 값을 나타냅니다. |
| [isLogarithmic()](#isLogarithmic--) | 값 축의 스케일 유형이 로그인지 여부를 나타냅니다. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | 값 축의 스케일 유형이 로그인지 여부를 나타냅니다. |
| [getLogBase()](#getLogBase--) | 로그 기반을 나타냅니다. |
| [setLogBase(double value)](#setLogBase-double-) | 로그 기반을 나타냅니다. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | MS PowerPoint가 데이터 포인트를 마지막부터 첫 번째까지 플롯하는지 나타냅니다. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | MS PowerPoint가 데이터 포인트를 마지막부터 첫 번째까지 플롯하는지 나타냅니다. |
| [isVisible()](#isVisible--) | 축이 표시되는지 나타냅니다. |
| [setVisible(boolean value)](#setVisible-boolean-) | 축이 표시되는지 나타냅니다. |
| [getMajorTickMark()](#getMajorTickMark--) | 지정된 축에 대한 주요 눈금표시 유형을 나타냅니다. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | 지정된 축에 대한 주요 눈금표시 유형을 나타냅니다. |
| [getMinorTickMark()](#getMinorTickMark--) | 지정된 축에 대한 부 눈금표시 유형을 나타냅니다. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | 지정된 축에 대한 부 눈금표시 유형을 나타냅니다. |
| [getTickLabelPosition()](#getTickLabelPosition--) | 지정된 축에 대한 눈금 라벨의 위치를 나타냅니다. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | 지정된 축에 대한 눈금 라벨의 위치를 나타냅니다. |
| [getMajorUnitScale()](#getMajorUnitScale--) | 날짜 축에 대한 주요 단위 스케일을 나타냅니다. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | 날짜 축에 대한 주요 단위 스케일을 나타냅니다. |
| [getMinorUnitScale()](#getMinorUnitScale--) | 날짜 축에 대한 주요 단위 스케일을 나타냅니다. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | 날짜 축에 대한 주요 단위 스케일을 나타냅니다. |
| [getBaseUnitScale()](#getBaseUnitScale--) | 날짜 축에 표시되는 가장 작은 시간 단위를 지정합니다. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | 날짜 축에 표시되는 가장 작은 시간 단위를 지정합니다. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | 차트 축의 부 그리드선 형식을 나타냅니다. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | 차트 축의 주요 그리드선 형식을 나타냅니다. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | 부 그리드선이 표시되는지 나타냅니다. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | 주요 그리드선이 표시되는지 나타냅니다. |
| [getFormat()](#getFormat--) | 축의 형식을 나타냅니다. |
| [getTitle()](#getTitle--) | 축의 제목을 가져옵니다. |
| [getCrossType()](#getCrossType--) | 지정된 축에서 다른 축이 교차하는 위치의 CrossType을 나타냅니다. |
| [setCrossType(int value)](#setCrossType-int-) | 지정된 축에서 다른 축이 교차하는 위치의 CrossType을 나타냅니다. |
| [getPosition()](#getPosition--) | 축의 위치를 나타냅니다. |
| [setPosition(int value)](#setPosition-int-) | 축의 위치를 나타냅니다. |
| [hasTitle()](#hasTitle--) | 축에 표시 가능한 제목이 있는지 결정합니다. |
| [setTitle(boolean value)](#setTitle-boolean-) | 축에 표시 가능한 제목이 있는지 결정합니다. |
| [getNumberFormat()](#getNumberFormat--) | 축 레이블의 서식 문자열을 나타냅니다. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | 축 레이블의 서식 문자열을 나타냅니다. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | 서식이 원본 데이터에 연결되어 있는지 나타냅니다. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | 서식이 원본 데이터에 연결되어 있는지 나타냅니다. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | 눈금 라벨의 회전 각도 Read/write float. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | 눈금 라벨의 회전 각도 Read/write float. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | 그려지는 라벨 사이에 건너뛸 눈금 라벨 수를 지정합니다. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | 그려지는 라벨 사이에 건너뛸 눈금 라벨 수를 지정합니다. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | 자동 눈금 라벨 간격 값을 지정합니다. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | 자동 눈금 라벨 간격 값을 지정합니다. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | 다음 눈금이 그려지기 전에 건너뛸 눈금 수를 지정합니다. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | 다음 눈금이 그려지기 전에 건너뛸 눈금 수를 지정합니다. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | 자동 눈금 간격 값을 지정합니다. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | 자동 눈금 간격 값을 지정합니다. |
| [getLabelOffset()](#getLabelOffset--) | 라벨을 축으로부터 떨어뜨리는 거리를 지정합니다. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | 라벨을 축으로부터 떨어뜨리는 거리를 지정합니다. |
| [getCategoryAxisType()](#getCategoryAxisType--) | 카테고리 축의 유형을 지정합니다. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | 카테고리 축의 유형을 지정합니다. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | 축 데이터에 따라 자동으로 결정되는 값으로 IAxis.CategoryAxisType 속성을 설정합니다. |
| [getAggregationType()](#getAggregationType--) | 카테고리 축(빈닝)의 집계 유형을 나타냅니다. |
| [setAggregationType(int value)](#setAggregationType-int-) | 카테고리 축(빈닝)의 집계 유형을 나타냅니다. |
| [getBinWidth()](#getBinWidth--) | AggregationType 속성 값이 AxisAggregationType.ByBinWidth 로 설정될 때 빈 폭을 지정합니다. |
| [setBinWidth(double value)](#setBinWidth-double-) | AggregationType 속성 값이 AxisAggregationType.ByBinWidth 로 설정될 때 빈 폭을 지정합니다. |
| [getNumberOfBins()](#getNumberOfBins--) | AggregationType 속성 값이 AxisAggregationType.ByNumberOfBins 로 설정될 때 빈 수를 지정합니다. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | AggregationType 속성 값이 AxisAggregationType.ByNumberOfBins 로 설정될 때 빈 수를 지정합니다. |
| [isOverflowBin()](#isOverflowBin--) | 오버플로우 빈이 적용되는지 지정합니다. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | 오버플로우 빈이 적용되는지 지정합니다. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | 자동 오버플로우 빈 값을 지정합니다. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | 자동 오버플로우 빈 값을 지정합니다. |
| [getOverflowBin()](#getOverflowBin--) | 오버플로우 빈 사용자 정의 값을 지정합니다. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | 오버플로우 빈 사용자 정의 값을 지정합니다. |
| [isUnderflowBin()](#isUnderflowBin--) | 언더플로우 빈이 적용되는지 지정합니다. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | 언더플로우 빈이 적용되는지 지정합니다. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | 자동 언더플로우 빈 값을 지정합니다. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | 자동 언더플로우 빈 값을 지정합니다. |
| [getUnderflowBin()](#getUnderflowBin--) | 언더플로우 빈 사용자 정의 값을 지정합니다. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | 언더플로우 빈 사용자 정의 값을 지정합니다. |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

값 축이 카테고리 축을 카테고리 사이에서 교차하는지 나타냅니다. 이 속성은 카테고리 축에만 적용되며 3D 차트에는 적용되지 않습니다. 읽기/쓰기 boolean.

**반환:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

값 축이 카테고리 축을 카테고리 사이에서 교차하는지 나타냅니다. 이 속성은 카테고리 축에만 적용되며 3D 차트에는 적용되지 않습니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

축에 수직인 축이 교차하는 지점을 나타냅니다. 읽기/쓰기 float.

**반환:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

축에 수직인 축이 교차하는 지점을 나타냅니다. 읽기/쓰기 float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

값 축에 대한 표시 단위의 스케일 값을 지정합니다. 읽기/쓰기 [DisplayUnitType](../../com.aspose.slides/displayunittype).

**반환:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

값 축에 대한 표시 단위의 스케일 값을 지정합니다. 읽기/쓰기 [DisplayUnitType](../../com.aspose.slides/displayunittype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

축의 실제 최대 값을 지정합니다. 실제 값을 얻으려면 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오.

**반환:**
double

### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

축의 실제 최소 값을 지정합니다. 실제 값을 얻으려면 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오.

**반환:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

축의 실제 주요 단위를 지정합니다. 실제 값을 얻으려면 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오.

**반환:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

축의 실제 부단위를 지정합니다. 실제 값을 얻으려면 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오.

**반환:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

축의 실제 주요 단위 스케일을 지정합니다. 실제 값을 얻으려면 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오.

**반환:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

축의 실제 부단위 스케일을 지정합니다. 실제 값을 얻으려면 먼저 IChart.ValidateChartLayout() 메서드를 호출하십시오.

**반환:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

최대 값이 자동으로 할당되는지 나타냅니다. 읽기/쓰기 boolean.

**반환:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

최대 값이 자동으로 할당되는지 나타냅니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

값 축의 최대 값을 나타냅니다. 읽기/쓰기 double.

**반환:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

값 축의 최대 값을 나타냅니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

날짜 또는 값 축에 대한 부단위를 나타냅니다. 읽기/쓰기 double.

**반환:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

날짜 또는 값 축에 대한 부단위를 나타냅니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

축의 부단위가 자동으로 할당되는지 나타냅니다. 읽기/쓰기 boolean.

**반환:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

축의 부단위가 자동으로 할당되는지 나타냅니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

날짜 또는 값 축에 대한 주요 단위를 나타냅니다. 읽기/쓰기 double.

**반환:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

날짜 및 값 축에 대한 주요 단위를 나타냅니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

축의 주요 단위가 자동으로 할당되는지 나타냅니다. 읽기/쓰기 boolean.

**반환:**
boolean

### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

축의 주요 단위가 자동으로 할당되는지 나타냅니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

최소 값이 자동으로 할당되는지 나타냅니다. 읽기/쓰기 boolean.

**반환:**
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

최소 값이 자동으로 할당되는지 나타냅니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

값 축의 최소 값을 나타냅니다. 읽기/쓰기 double.

**반환:**
double

### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

값 축의 최소 값을 나타냅니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

값 축의 스케일 유형이 로그인지 여부를 나타냅니다. 읽기/쓰기 boolean.

**반환:**
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

값 축의 스케일 유형이 로그인지 여부를 나타냅니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

로그 기반을 나타냅니다. 기본값은 10입니다. 읽기/쓰기 double.

**반환:**
double

### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

로그 기반을 나타냅니다. 기본값은 10입니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

MS PowerPoint가 데이터 포인트를 마지막부터 첫 번째까지 플롯하는지 나타냅니다. 읽기/쓰기 boolean.

**반환:**
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

MS PowerPoint가 데이터 포인트를 마지막부터 첫 번째까지 플롯하는지 나타냅니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

축이 표시되는지 나타냅니다. 읽기/쓰기 boolean.

**반환:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

축이 표시되는지 나타냅니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

지정된 축에 대한 주요 눈금표시 유형을 나타냅니다. 읽기/쓰기 [TickMarkType](../../com.aspose.slides/tickmarktype).

**반환:**
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

지정된 축에 대한 주요 눈금표시 유형을 나타냅니다. 읽기/쓰기 [TickMarkType](../../com.aspose.slides/tickmarktype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

지정된 축에 대한 부 눈금표시 유형을 나타냅니다. 읽기/쓰기 [TickMarkType](../../com.aspose.slides/tickmarktype).

**반환:**
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

지정된 축에 대한 부 눈금표시 유형을 나타냅니다. 읽기/쓰기 [TickMarkType](../../com.aspose.slides/tickmarktype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

지정된 축에 대한 눈금 라벨의 위치를 나타냅니다. 읽기/쓰기 [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**반환:**
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

지정된 축에 대한 눈금 라벨의 위치를 나타냅니다. 읽기/쓰기 [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

날짜 축에 대한 주요 단위 스케일을 나타냅니다. 읽기/쓰기 [TimeUnitType](../../com.aspose.slides/timeunittype).

**반환:**
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

날짜 축에 대한 주요 단위 스케일을 나타냅니다. 읽기/쓰기 [TimeUnitType](../../com.aspose.slides/timeunittype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

날짜 축에 대한 주요 단위 스케일을 나타냅니다. 읽기/쓰기 [TimeUnitType](../../com.aspose.slides/timeunittype).

**반환:**
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

날짜 축에 대한 주요 단위 스케일을 나타냅니다. 읽기/쓰기 [TimeUnitType](../../com.aspose.slides/timeunittype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

날짜 축에 표시되는 가장 작은 시간 단위를 지정합니다. 읽기/쓰기 [TimeUnitType](../../com.aspose.slides/timeunittype).

**반환:**
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

날짜 축에 표시되는 가장 작은 시간 단위를 지정합니다. 읽기/쓰기 [TimeUnitType](../../com.aspose.slides/timeunittype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

차트 축의 부 그리드선 형식을 나타냅니다. 읽기 전용 [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**반환:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMajorGridLinesFormat()
```

차트 축의 주요 그리드선 형식을 나타냅니다. 읽기 전용 [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**반환:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

부 그리드선이 표시되는지 나타냅니다. 읽기 전용 boolean.

**반환:**
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

주 그리드선이 표시되는지 나타냅니다. 읽기 전용 boolean.

**반환:**
boolean

### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

축의 형식을 나타냅니다. 읽기 전용 [IAxisFormat](../../com.aspose.slides/iaxisformat).

**반환:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

축의 제목을 가져옵니다. 읽기 전용 [IChartTitle](../../com.aspose.slides/icharttitle).

**반환:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

지정된 축에서 다른 축이 교차하는 위치의 CrossType을 나타냅니다. 읽기/쓰기 [CrossesType](../../com.aspose.slides/crossestype).

**반환:**
int

### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

지정된 축에서 다른 축이 교차하는 위치의 CrossType을 나타냅니다. 읽기/쓰기 [CrossesType](../../com.aspose.slides/crossestype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

축의 위치를 나타냅니다. 읽기/쓰기 [AxisPositionType](../../com.aspose.slides/axispositiontype).

**반환:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

축의 위치를 나타냅니다. 읽기/쓰기 [AxisPositionType](../../com.aspose.slides/axispositiontype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

축에 표시 가능한 제목이 있는지 결정합니다. 읽기/쓰기 boolean.

**반환:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

축에 표시 가능한 제목이 있는지 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

축 레이블의 서식 문자열을 나타냅니다. 읽기/쓰기 String.

**반환:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

축 레이블의 서식 문자열을 나타냅니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

서식이 원본 데이터에 연결되어 있는지 나타냅니다. 읽기/쓰기 boolean.

**반환:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

서식이 원본 데이터에 연결되어 있는지 나타냅니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

눈금 라벨의 회전 각도 Read/write float.

**반환:**
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

눈금 라벨의 회전 각도 Read/write float.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

그려지는 라벨 사이에 건너뛸 눈금 라벨 수를 지정합니다. 읽기/쓰기 long.

**반환:**
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

그려지는 라벨 사이에 건너뛸 눈금 라벨 수를 지정합니다. 읽기/쓰기 long.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

자동 눈금 라벨 간격 값을 지정합니다. false인 경우 TickLabelSpacing 속성을 사용합니다. 읽기/쓰기 boolean.

**반환:**
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

자동 눈금 라벨 간격 값을 지정합니다. false인 경우 TickLabelSpacing 속성을 사용합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

다음 눈금이 그려지기 전에 건너뛸 눈금 수를 지정합니다. 카테고리 또는 시리즈 축에 적용됩니다. 읽기/쓰기 int.

**반환:**
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

다음 눈금이 그려지기 전에 건너뛸 눈금 수를 지정합니다. 카테고리 또는 시리즈 축에 적용됩니다. 읽기/쓰기 int.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

자동 눈금 간격 값을 지정합니다. false인 경우 TickMarksSpacing 속성을 사용합니다. 읽기/쓰기 boolean.

**반환:**
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

자동 눈금 간격 값을 지정합니다. false인 경우 TickMarksSpacing 속성을 사용합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

카테고리 또는 날짜 축에 적용되는 라벨과 축 사이의 거리를 지정합니다. 값은 0%에서 1000% 사이여야 합니다. 읽기/쓰기 int.

**반환:**
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

카테고리 또는 날짜 축에 적용되는 라벨과 축 사이의 거리를 지정합니다. 값은 0%에서 1000% 사이여야 합니다. 읽기/쓰기 int.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

카테고리 축의 유형을 지정합니다. 읽기/쓰기 [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**반환:**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

카테고리 축의 유형을 지정합니다. 읽기/쓰기 [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

축 데이터에 따라 자동으로 결정되는 값으로 IAxis.CategoryAxisType 속성을 설정합니다.

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

카테고리 축(빈닝)의 집계 유형을 나타냅니다. 카테고리에 적용됩니다. 히스토그램 또는 히스토그램 파레토 시리즈와 함께 사용됩니다.

**반환:**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

카테고리 축(빈닝)의 집계 유형을 나타냅니다. 카테고리에 적용됩니다. 히스토그램 또는 히스토그램 파레토 시리즈와 함께 사용됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

AggregationType 속성 값이 AxisAggregationType.ByBinWidth 로 설정될 때 빈 폭을 지정합니다. 카테고리 축에 적용됩니다. 히스토그램 또는 히스토그램 파레토 시리즈와 함께 사용됩니다.

**반환:**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

AggregationType 속성 값이 AxisAggregationType.ByBinWidth 로 설정될 때 빈 폭을 지정합니다. 카테고리 축에 적용됩니다. 히스토그램 또는 히스토그램 파레토 시리즈와 함께 사용됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

AggregationType 속성 값이 AxisAggregationType.ByNumberOfBins 로 설정될 때 빈 수를 지정합니다. 카테고리 축에 적용됩니다. 히스토그램 또는 히스토그램 파레토 시리즈와 함께 사용됩니다.

**반환:**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

AggregationType 속성 값이 AxisAggregationType.ByNumberOfBins 로 설정될 때 빈 수를 지정합니다. 카테고리 축에 적용됩니다. 히스토그램 또는 히스토그램 파레토 시리즈와 함께 사용됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

오버플로우 빈이 적용되는지 지정합니다. IsAutomaticOverflowBin 및 OverflowBin을 사용하여 오버플로우 빈 값을 조정하십시오.

**반환:**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

오버플로우 빈이 적용되는지 지정합니다. IsAutomaticOverflowBin 및 OverflowBin을 사용하여 오버플로우 빈 값을 조정하십시오.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

자동 오버플로우 빈 값을 지정합니다. false인 경우 OverflowBin 속성을 사용합니다.

**반환:**
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

자동 오버플로우 빈 값을 지정합니다. false인 경우 OverflowBin 속성을 사용합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

오버플로우 빈 사용자 정의 값을 지정합니다. IsAutomaticOverflowBin 속성이 false이고 IsOverflowBin 속성이 true인 경우에 적용됩니다.

**반환:**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

오버플로우 빈 사용자 정의 값을 지정합니다. IsAutomaticOverflowBin 속성이 false이고 IsOverflowBin 속성이 true인 경우에 적용됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

언더플로우 빈이 적용되는지 지정합니다. IsAutomaticUnderflowBin 및 UnderflowBin을 사용하여 언더플로우 빈 값을 조정하십시오.

**반환:**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

언더플로우 빈이 적용되는지 지정합니다. IsAutomaticUnderflowBin 및 UnderflowBin을 사용하여 언더플로우 빈 값을 조정하십시오.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

자동 언더플로우 빈 값을 지정합니다. false인 경우 UnderflowBin 속성을 사용합니다.

**반환:**
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

자동 언더플로우 빈 값을 지정합니다. false인 경우 UnderflowBin 속성을 사용합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

언더플로우 빈 사용자 정의 값을 지정합니다. IsAutomaticUnderflowBin 속성이 false이고 IsUnderflowBin 속성이 true인 경우에 적용됩니다.

**반환:**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

언더플로우 빈 사용자 정의 값을 지정합니다. IsAutomaticUnderflowBin 속성이 false이고 IsUnderflowBin 속성이 true인 경우에 적용됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |