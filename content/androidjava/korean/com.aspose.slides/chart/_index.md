---
title: Chart
second_title: Java API를 통한 Android용 Aspose.Slides 레퍼런스
description: 슬라이드에 그래픽 차트를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/chart/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**All Implemented Interfaces:**  
[com.aspose.slides.IChart](../../com.aspose.slides/ichart)  
```
public class Chart extends GraphicalObject implements IChart
```

차트 슬라이드에 그래픽 차트를 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [validateChartLayout()](#validateChartLayout--) | 차트 요소의 실제 값을 계산합니다. |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | 보이는 셀만 플롯되는지 여부를 결정합니다. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | 보이는 셀만 플롯되는지 여부를 결정합니다. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | 차트에서 빈 셀을 플롯하는 방식을 가져오거나 설정합니다. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | 차트에서 빈 셀을 플롯하는 방식을 가져오거나 설정합니다. |
| [getChartData()](#getChartData--) | 차트와 연결된 또는 포함된 데이터에 대한 정보를 가져옵니다. |
| [hasTitle()](#hasTitle--) | 차트에 표시되는 제목이 있는지 여부를 결정합니다. |
| [setTitle(boolean value)](#setTitle-boolean-) | 차트에 표시되는 제목이 있는지 여부를 결정합니다. |
| [getChartTitle()](#getChartTitle--) | 차트 제목을 가져오거나 설정합니다. |
| [hasDataTable()](#hasDataTable--) | 차트에 데이터 테이블이 있는지 여부를 결정합니다. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | 차트에 데이터 테이블이 있는지 여부를 결정합니다. |
| [hasLegend()](#hasLegend--) | 차트에 범례가 있는지 여부를 결정합니다. |
| [setLegend(boolean value)](#setLegend-boolean-) | 차트에 범례가 있는지 여부를 결정합니다. |
| [getLegend()](#getLegend--) | 차트에 대한 범례를 가져오거나 설정합니다. |
| [getChartDataTable()](#getChartDataTable--) | 차트의 데이터 테이블을 가져옵니다. |
| [getStyle()](#getStyle--) | 차트 스타일을 가져오거나 설정합니다. |
| [setStyle(int value)](#setStyle-int-) | 차트 스타일을 가져오거나 설정합니다. |
| [getType()](#getType--) | 차트 유형을 가져오거나 설정합니다. |
| [setType(int value)](#setType-int-) | 차트 유형을 가져오거나 설정합니다. |
| [getPlotArea()](#getPlotArea--) | 차트의 플롯 영역을 나타냅니다. |
| [getRotation3D()](#getRotation3D--) | 차트의 3D 회전을 가져옵니다. |
| [getBackWall()](#getBackWall--) | 3D 차트의 뒷벽 서식을 변경할 수 있는 객체를 반환합니다. |
| [getSideWall()](#getSideWall--) | 3D 차트의 측벽 서식을 변경할 수 있는 객체를 반환합니다. |
| [getFloor()](#getFloor--) | 3D 차트의 바닥 서식을 변경할 수 있는 객체를 반환합니다. |
| [getTextFormat()](#getTextFormat--) | 차트 텍스트 서식을 반환합니다. |
| [createThemeEffective()](#createThemeEffective--) | 이 차트에 대한 적용된 테마를 반환합니다. |
| [getThemeManager()](#getThemeManager--) | 테마 관리자를 반환합니다. |
| [getUserShapes()](#getUserShapes--) | 차트 위에 그려지는 도형을 지정합니다. |
| [getAxes()](#getAxes--) | 차트 축에 대한 액세스를 제공합니다. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | 차트 최대값 위에 데이터 레이블을 표시하도록 지정합니다. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | 차트 최대값 위에 데이터 레이블을 표시하도록 지정합니다. |
| [hasRoundedCorners()](#hasRoundedCorners--) | 차트 영역에 둥근 모서리를 지정합니다. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | 차트 영역에 둥근 모서리를 지정합니다. |
| [getChart()](#getChart--) |  |

### validateChartLayout() {#validateChartLayout--}
```
public final void validateChartLayout()
```

차트 요소의 실제 값을 계산합니다. 실제 값에는 IActualLayout 인터페이스를 구현하는 요소의 위치(IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight)와 실제 축 값(IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)가 포함됩니다.

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public final boolean getPlotVisibleCellsOnly()
```

보이는 셀만 플롯되는지 여부를 결정합니다. False이면 보이는 셀과 숨겨진 셀 모두를 플롯합니다. 읽기/쓰기 boolean.

**반환:**  
boolean

### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public final void setPlotVisibleCellsOnly(boolean value)
```

보이는 셀만 플롯되는지 여부를 결정합니다. False이면 보이는 셀과 숨겨진 셀 모두를 플롯합니다. 읽기/쓰기 boolean.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public final int getDisplayBlanksAs()
```

차트에서 빈 셀을 플롯하는 방식을 가져오거나 설정합니다. 읽기/쓰기 [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**반환:**  
int

### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public final void setDisplayBlanksAs(int value)
```

차트에서 빈 셀을 플롯하는 방식을 가져오거나 설정합니다. 읽기/쓰기 [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public final IChartData getChartData()
```

차트와 연결된 또는 포함된 데이터에 대한 정보를 가져옵니다. 읽기 전용 [IChartData](../../com.aspose.slides/ichartdata).

**반환:**  
[IChartData](../../com.aspose.slides/ichartdata)

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

차트에 표시되는 제목이 있는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**  
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

차트에 표시되는 제목이 있는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public final IChartTitle getChartTitle()
```

차트 제목을 가져오거나 설정합니다. 읽기 전용 [IChartTitle](../../com.aspose.slides/icharttitle).

**반환:**  
[IChartTitle](../../com.aspose.slides/icharttitle)

### hasDataTable() {#hasDataTable--}
```
public final boolean hasDataTable()
```

차트에 데이터 테이블이 있는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**  
boolean

### setDataTable(boolean value) {#setDataTable-boolean-}
```
public final void setDataTable(boolean value)
```

차트에 데이터 테이블이 있는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public final boolean hasLegend()
```

차트에 범례가 있는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**  
boolean

### setLegend(boolean value) {#setLegend-boolean-}
```
public final void setLegend(boolean value)
```

차트에 범례가 있는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public final ILegend getLegend()
```

차트에 대한 범례를 가져오거나 설정합니다. 읽기 전용 [ILegend](../../com.aspose.slides/ilegend).

**반환:**  
[ILegend](../../com.aspose.slides/ilegend)

### getChartDataTable() {#getChartDataTable--}
```
public final IDataTable getChartDataTable()
```

차트의 데이터 테이블을 가져옵니다. 읽기 전용 [IDataTable](../../com.aspose.slides/idatatable).

**반환:**  
[IDataTable](../../com.aspose.slides/idatatable)

### getStyle() {#getStyle--}
```
public final int getStyle()
```

차트 스타일을 가져오거나 설정합니다. 읽기/쓰기 [StyleType](../../com.aspose.slides/styletype).

**반환:**  
int

### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```

차트 스타일을 가져오거나 설정합니다. 읽기/쓰기 [StyleType](../../com.aspose.slides/styletype).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

차트 유형을 가져오거나 설정합니다. 읽기/쓰기 [ChartType](../../com.aspose.slides/charttype).

**반환:**  
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

차트 유형을 가져오거나 설정합니다. 읽기/쓰기 [ChartType](../../com.aspose.slides/charttype).

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public final IChartPlotArea getPlotArea()
```

차트의 플롯 영역을 나타냅니다. 읽기 전용 [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**반환:**  
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)

### getRotation3D() {#getRotation3D--}
```
public final IRotation3D getRotation3D()
```

차트의 3D 회전을 가져옵니다. 읽기 전용 [IRotation3D](../../com.aspose.slides/irotation3d).

**반환:**  
[IRotation3D](../../com.aspose.slides/irotation3d)

### getBackWall() {#getBackWall--}
```
public final IChartWall getBackWall()
```

3D 차트의 뒷벽 서식을 변경할 수 있는 객체를 반환합니다. 읽기 전용 [IChartWall](../../com.aspose.slides/ichartwall).

**반환:**  
[IChartWall](../../com.aspose.slides/ichartwall)

### getSideWall() {#getSideWall--}
```
public final IChartWall getSideWall()
```

3D 차트의 측벽 서식을 변경할 수 있는 객체를 반환합니다. 읽기 전용 [IChartWall](../../com.aspose.slides/ichartwall).

**반환:**  
[IChartWall](../../com.aspose.slides/ichartwall)

### getFloor() {#getFloor--}
```
public final IChartWall getFloor()
```

3D 차트의 바닥 서식을 변경할 수 있는 객체를 반환합니다. 읽기 전용 [IChartWall](../../com.aspose.slides/ichartwall).

**반환:**  
[IChartWall](../../com.aspose.slides/ichartwall)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

차트 텍스트 서식을 반환합니다. 다음 유형에 대해서는 적용되지 않습니다: [ChartType.Treemap](../../com.aspose.slides/charttype\#Treemap), [ChartType.Sunburst](../../com.aspose.slides/charttype\#Sunburst), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel),[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker). 읽기 전용 [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**반환:**  
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

이 차트에 대한 적용된 테마를 반환합니다.

**반환:**  
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

테마 관리자를 반환합니다. 읽기 전용 [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**반환:**  
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getUserShapes() {#getUserShapes--}
```
public final IGroupShape getUserShapes()
```

차트 위에 그려지는 도형을 지정합니다. 읽기 전용 [IGroupShape](../../com.aspose.slides/igroupshape).

**반환:**  
[IGroupShape](../../com.aspose.slides/igroupshape)

### getAxes() {#getAxes--}
```
public final IAxesManager getAxes()
```

차트 축에 대한 액세스를 제공합니다. 읽기 전용 [IAxesManager](../../com.aspose.slides/iaxesmanager).

**반환:**  
[IAxesManager](../../com.aspose.slides/iaxesmanager)

### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public final boolean getShowDataLabelsOverMaximum()
```

차트 최대값 위에 데이터 레이블을 표시하도록 지정합니다. 읽기/쓰기 boolean.

**반환:**  
boolean

### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public final void setShowDataLabelsOverMaximum(boolean value)
```

차트 최대값 위에 데이터 레이블을 표시하도록 지정합니다. 읽기/쓰기 boolean.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public final boolean hasRoundedCorners()
```

차트 영역에 둥근 모서리를 지정합니다. 읽기/쓰기 boolean.

**반환:**  
boolean

### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public final void setRoundedCorners(boolean value)
```

차트 영역에 둥근 모서리를 지정합니다. 읽기/쓰기 boolean.

**매개변수:**  
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

차트를 반환합니다. 읽기 전용 [IChart](../../com.aspose.slides/ichart).

**반환:**  
[IChart](../../com.aspose.slides/ichart)