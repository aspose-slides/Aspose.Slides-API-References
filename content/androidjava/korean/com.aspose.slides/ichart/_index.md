---
title: IChart
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 슬라이드에 그래픽 차트를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ichart/
---
**구현된 모든 인터페이스:**  
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface IChart extends IGraphicalObject, IFormattedTextContainer, IOverrideThemeable
```

슬라이드에 그래픽 차트를 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | 표시된 셀만 플롯되는지 여부를 결정합니다. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | 표시된 셀만 플롯되는지 여부를 결정합니다. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | 차트에서 빈 셀을 플롯하는 방식을 반환하거나 설정합니다. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | 차트에서 빈 셀을 플롯하는 방식을 반환하거나 설정합니다. |
| [getChartData()](#getChartData--) | 차트와 연결되거나 삽입된 데이터에 대한 정보를 반환합니다. |
| [hasTitle()](#hasTitle--) | 차트에 표시 가능한 제목이 있는지 여부를 결정합니다. |
| [setTitle(boolean value)](#setTitle-boolean-) | 차트에 표시 가능한 제목이 있는지 여부를 결정합니다. |
| [getChartTitle()](#getChartTitle--) | 차트 제목을 반환하거나 설정합니다. 읽기 전용 [IChartTitle](../../com.aspose.slides/icharttitle). |
| [hasDataTable()](#hasDataTable--) | 차트에 데이터 표가 있는지 여부를 결정합니다. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | 차트에 데이터 표가 있는지 여부를 결정합니다. |
| [hasLegend()](#hasLegend--) | 차트에 범례가 있는지 여부를 결정합니다. |
| [setLegend(boolean value)](#setLegend-boolean-) | 차트에 범례가 있는지 여부를 결정합니다. |
| [getLegend()](#getLegend--) | 차트에 대한 범례를 반환하거나 설정합니다. |
| [getChartDataTable()](#getChartDataTable--) | 차트의 데이터 표를 반환합니다. |
| [getStyle()](#getStyle--) | 차트 스타일을 반환하거나 설정합니다. |
| [setStyle(int value)](#setStyle-int-) | 차트 스타일을 반환하거나 설정합니다. |
| [getType()](#getType--) | 차트 유형을 반환하거나 설정합니다. |
| [setType(int value)](#setType-int-) | 차트 유형을 반환하거나 설정합니다. |
| [getPlotArea()](#getPlotArea--) | 차트의 플롯 영역을 나타냅니다. |
| [getRotation3D()](#getRotation3D--) | 차트의 3D 회전을 반환합니다. |
| [getBackWall()](#getBackWall--) | 3D 차트의 뒷벽 형식을 변경할 수 있는 객체를 반환합니다. |
| [getSideWall()](#getSideWall--) | 3D 차트의 측면 벽 형식을 변경할 수 있는 객체를 반환합니다. |
| [getFloor()](#getFloor--) | 3D 차트의 바닥 형식을 변경할 수 있는 객체를 반환합니다. |
| [getUserShapes()](#getUserShapes--) | 차트 위에 그려지는 모양을 지정합니다. |
| [getAxes()](#getAxes--) | 차트 축에 대한 접근을 제공합니다. |
| [validateChartLayout()](#validateChartLayout--) | 차트 요소의 실제 값을 계산합니다. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | 차트 최대값을 초과하는 데이터 레이블을 표시하도록 지정합니다. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | 차트 최대값을 초과하는 데이터 레이블을 표시하도록 지정합니다. |
| [hasRoundedCorners()](#hasRoundedCorners--) | 차트 영역에 둥근 모서리를 갖도록 지정합니다. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | 차트 영역에 둥근 모서리를 갖도록 지정합니다. |

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public abstract boolean getPlotVisibleCellsOnly()
```

표시된 셀만 플롯되는지 여부를 결정합니다. 숨겨진 셀도 플롯하려면 false를 사용합니다. 읽기/쓰기 부울.

**반환값:**  
boolean

### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public abstract void setPlotVisibleCellsOnly(boolean value)
```

표시된 셀만 플롯되는지 여부를 결정합니다. 숨겨진 셀도 플롯하려면 false를 사용합니다. 읽기/쓰기 부울.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public abstract int getDisplayBlanksAs()
```

차트에서 빈 셀을 플롯하는 방식을 반환하거나 설정합니다. 읽기/쓰기 [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**반환값:**  
int

### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public abstract void setDisplayBlanksAs(int value)
```

차트에서 빈 셀을 플롯하는 방식을 반환하거나 설정합니다. 읽기/쓰기 [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public abstract IChartData getChartData()
```

차트와 연결되거나 삽입된 데이터에 대한 정보를 반환합니다. 읽기 전용 [IChartData](../../com.aspose.slides/ichartdata).

**반환값:**  
[IChartData](../../com.aspose.slides/ichartdata)

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

차트에 표시 가능한 제목이 있는지 여부를 결정합니다. 읽기/쓰기 부울.

**반환값:**  
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

차트에 표시 가능한 제목이 있는지 여부를 결정합니다. 읽기/쓰기 부울.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public abstract IChartTitle getChartTitle()
```

차트 제목을 반환하거나 설정합니다. 읽기 전용 [IChartTitle](../../com.aspose.slides/icharttitle).

**반환값:**  
[IChartTitle](../../com.aspose.slides/icharttitle)

### hasDataTable() {#hasDataTable--}
```
public abstract boolean hasDataTable()
```

차트에 데이터 표가 있는지 여부를 결정합니다. 읽기/쓰기 부울.

**반환값:**  
boolean

### setDataTable(boolean value) {#setDataTable-boolean-}
```
public abstract void setDataTable(boolean value)
```

차트에 데이터 표가 있는지 여부를 결정합니다. 읽기/쓰기 부울.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public abstract boolean hasLegend()
```

차트에 범례가 있는지 여부를 결정합니다. 읽기/쓰기 부울.

**반환값:**  
boolean

### setLegend(boolean value) {#setLegend-boolean-}
```
public abstract void setLegend(boolean value)
```

차트에 범례가 있는지 여부를 결정합니다. 읽기/쓰기 부울.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public abstract ILegend getLegend()
```

차트에 대한 범례를 반환하거나 설정합니다. 읽기 전용 [ILegend](../../com.aspose.slides/ilegend).

**반환값:**  
[ILegend](../../com.aspose.slides/ilegend)

### getChartDataTable() {#getChartDataTable--}
```
public abstract IDataTable getChartDataTable()
```

차트의 데이터 표를 반환합니다. 읽기 전용 [IDataTable](../../com.aspose.slides/idatatable).

**반환값:**  
[IDataTable](../../com.aspose.slides/idatatable)

### getStyle() {#getStyle--}
```
public abstract int getStyle()
```

차트 스타일을 반환하거나 설정합니다. 읽기/쓰기 [StyleType](../../com.aspose.slides/styletype).

**반환값:**  
int

### setStyle(int value) {#setStyle-int-}
```
public abstract void setStyle(int value)
```

차트 스타일을 반환하거나 설정합니다. 읽기/쓰기 [StyleType](../../com.aspose.slides/styletype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public abstract int getType()
```

차트 유형을 반환하거나 설정합니다. 읽기/쓰기 [ChartType](../../com.aspose.slides/charttype).

**반환값:**  
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

차트 유형을 반환하거나 설정합니다. 읽기/쓰기 [ChartType](../../com.aspose.slides/charttype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public abstract IChartPlotArea getPlotArea()
```

차트의 플롯 영역을 나타냅니다. 읽기 전용 [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**반환값:**  
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)

### getRotation3D() {#getRotation3D--}
```
public abstract IRotation3D getRotation3D()
```

차트의 3D 회전을 반환합니다. 읽기 전용 [IRotation3D](../../com.aspose.slides/irotation3d).

**반환값:**  
[IRotation3D](../../com.aspose.slides/irotation3d)

### getBackWall() {#getBackWall--}
```
public abstract IChartWall getBackWall()
```

3D 차트의 뒷벽 형식을 변경할 수 있는 객체를 반환합니다. 읽기 전용 [IChartWall](../../com.aspose.slides/ichartwall).

**반환값:**  
[IChartWall](../../com.aspose.slides/ichartwall)

### getSideWall() {#getSideWall--}
```
public abstract IChartWall getSideWall()
```

3D 차트의 측면 벽 형식을 변경할 수 있는 객체를 반환합니다. 읽기 전용 [IChartWall](../../com.aspose.slides/ichartwall).

**반환값:**  
[IChartWall](../../com.aspose.slides/ichartwall)

### getFloor() {#getFloor--}
```
public abstract IChartWall getFloor()
```

3D 차트의 바닥 형식을 변경할 수 있는 객체를 반환합니다. 읽기 전용 [IChartWall](../../com.aspose.slides/ichartwall).

**반환값:**  
[IChartWall](../../com.aspose.slides/ichartwall)

### getUserShapes() {#getUserShapes--}
```
public abstract IGroupShape getUserShapes()
```

차트 위에 그려지는 모양을 지정합니다. 읽기 전용 [IGroupShape](../../com.aspose.slides/igroupshape).

**반환값:**  
[IGroupShape](../../com.aspose.slides/igroupshape)

### getAxes() {#getAxes--}
```
public abstract IAxesManager getAxes()
```

차트 축에 대한 접근을 제공합니다. 읽기 전형 [IAxesManager](../../com.aspose.slides/iaxesmanager).

**반환값:**  
[IAxesManager](../../com.aspose.slides/iaxesmanager)

### validateChartLayout() {#validateChartLayout--}
```
public abstract void validateChartLayout()
```

차트 요소의 실제 값을 계산합니다. 실제 값에는 IActualLayout 인터페이스를 구현하는 요소의 위치(IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight)와 실제 축 값(IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)이 포함됩니다.

### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public abstract boolean getShowDataLabelsOverMaximum()
```

차트 최대값을 초과하는 데이터 레이블을 표시하도록 지정합니다. 읽기/쓰기 부울.

**반환값:**  
boolean

### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public abstract void setShowDataLabelsOverMaximum(boolean value)
```

차트 최대값을 초과하는 데이터 레이블을 표시하도록 지정합니다. 읽기/쓰기 부울.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public abstract boolean hasRoundedCorners()
```

차트 영역에 둥근 모서리를 갖도록 지정합니다. 읽기/쓰기 부울.

**반환값:**  
boolean

### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public abstract void setRoundedCorners(boolean value)
```

차트 영역에 둥근 모서리를 갖도록 지정합니다. 읽기/쓰기 부울.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |