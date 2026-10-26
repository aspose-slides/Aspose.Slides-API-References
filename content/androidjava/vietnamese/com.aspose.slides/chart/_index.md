---
title: Chart
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu diễn một biểu đồ đồ họa trên slide.
type: docs
url: /vi/com.aspose.slides/chart/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IChart](../../com.aspose.slides/ichart)
```
public class Chart extends GraphicalObject implements IChart
```

Biểu diễn một biểu đồ đồ họa trên slide.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [validateChartLayout()](#validateChartLayout--) | Tính toán giá trị thực của các phần tử biểu đồ. |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Xác định liệu chỉ các ô hiển thị mới được vẽ. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Xác định liệu chỉ các ô hiển thị mới được vẽ. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Trả về hoặc đặt cách vẽ các ô trống trên biểu đồ. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Trả về hoặc đặt cách vẽ các ô trống trên biểu đồ. |
| [getChartData()](#getChartData--) | Trả về thông tin về dữ liệu liên kết hoặc nhúng liên quan đến biểu đồ. |
| [hasTitle()](#hasTitle--) | Xác định liệu biểu đồ có tiêu đề hiển thị hay không. |
| [setTitle(boolean value)](#setTitle-boolean-) | Xác định liệu biểu đồ có tiêu đề hiển thị hay không. |
| [getChartTitle()](#getChartTitle--) | Trả về hoặc đặt tiêu đề biểu đồ. |
| [hasDataTable()](#hasDataTable--) | Xác định liệu biểu đồ có bảng dữ liệu hay không. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | Xác định liệu biểu đồ có bảng dữ liệu hay không. |
| [hasLegend()](#hasLegend--) | Xác định liệu biểu đồ có chú giải hay không. |
| [setLegend(boolean value)](#setLegend-boolean-) | Xác định liệu biểu đồ có chú giải hay không. |
| [getLegend()](#getLegend--) | Trả về hoặc đặt chú giải cho biểu đồ. |
| [getChartDataTable()](#getChartDataTable--) | Trả về bảng dữ liệu của biểu đồ. |
| [getStyle()](#getStyle--) | Trả về hoặc đặt kiểu biểu đồ. |
| [setStyle(int value)](#setStyle-int-) | Trả về hoặc đặt kiểu biểu đồ. |
| [getType()](#getType--) | Trả về hoặc đặt loại biểu đồ. |
| [setType(int value)](#setType-int-) | Trả về hoặc đặt loại biểu đồ. |
| [getPlotArea()](#getPlotArea--) | Đại diện cho khu vực vẽ của biểu đồ. |
| [getRotation3D()](#getRotation3D--) | Trả về phép quay 3D của biểu đồ. |
| [getBackWall()](#getBackWall--) | Trả về một đối tượng cho phép thay đổi định dạng của tường sau của biểu đồ 3D. |
| [getSideWall()](#getSideWall--) | Trả về một đối tượng cho phép thay đổi định dạng của tường bên của biểu đồ 3D. |
| [getFloor()](#getFloor--) | Trả về một đối tượng cho phép thay đổi định dạng của sàn của biểu đồ 3D. |
| [getTextFormat()](#getTextFormat--) | Trả về định dạng văn bản của biểu đồ. |
| [createThemeEffective()](#createThemeEffective--) | Trả về chủ đề hiệu quả cho biểu đồ này. |
| [getThemeManager()](#getThemeManager--) | Trả về trình quản lý chủ đề. |
| [getUserShapes()](#getUserShapes--) | Xác định các hình dạng được vẽ trên biểu đồ. |
| [getAxes()](#getAxes--) | Cung cấp quyền truy cập vào các trục biểu đồ. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Chỉ định các nhãn dữ liệu trên mức tối đa của biểu đồ sẽ được hiển thị. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Chỉ định các nhãn dữ liệu trên mức tối đa của biểu đồ sẽ được hiển thị. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Chỉ định khu vực biểu đồ sẽ có góc bo tròn. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Chỉ định khu vực biểu đồ sẽ có góc bo tròn. |
| [getChart()](#getChart--) |  |
### validateChartLayout() {#validateChartLayout--}
```
public final void validateChartLayout()
```

Tính toán giá trị thực của các phần tử biểu đồ. Các giá trị thực bao gồm vị trí của các phần tử triển khai giao diện IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) và các giá trị trục thực (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public final boolean getPlotVisibleCellsOnly()
```

Xác định liệu chỉ các ô hiển thị mới được vẽ. False để vẽ cả ô hiển thị và ẩn. Đọc/ghi boolean.

**Trả về:**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public final void setPlotVisibleCellsOnly(boolean value)
```

Xác định liệu chỉ các ô hiển thị mới được vẽ. False để vẽ cả ô hiển thị và ẩn. Đọc/ghi boolean.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public final int getDisplayBlanksAs()
```

Trả về hoặc đặt cách vẽ các ô trống trên biểu đồ. Đọc/ghi [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Trả về:**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public final void setDisplayBlanksAs(int value)
```

Trả về hoặc đặt cách vẽ các ô trống trên biểu đồ. Đọc/ghi [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public final IChartData getChartData()
```

Trả về thông tin về dữ liệu liên kết hoặc nhúng liên quan đến biểu đồ. Chỉ đọc [IChartData](../../com.aspose.slides/ichartdata).

**Trả về:**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

Xác định liệu biểu đồ có tiêu đề hiển thị hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

Xác định liệu biểu đồ có tiêu đề hiển thị hay không. Đọc/ghi boolean.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public final IChartTitle getChartTitle()
```

Trả về hoặc đặt tiêu đề biểu đồ. Chỉ đọc [IChartTitle](../../com.aspose.slides/icharttitle).

**Trả về:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public final boolean hasDataTable()
```

Xác định liệu biểu đồ có bảng dữ liệu hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public final void setDataTable(boolean value)
```

Xác định liệu biểu đồ có bảng dữ liệu hay không. Đọc/ghi boolean.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public final boolean hasLegend()
```

Xác định liệu biểu đồ có chú giải hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public final void setLegend(boolean value)
```

Xác định liệu biểu đồ có chú giải hay không. Đọc/ghi boolean.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public final ILegend getLegend()
```

Trả về hoặc đặt chú giải cho biểu đồ. Chỉ đọc [ILegend](../../com.aspose.slides/ilegend).

**Trả về:**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public final IDataTable getChartDataTable()
```

Trả về bảng dữ liệu của biểu đồ. Chỉ đọc [IDataTable](../../com.aspose.slides/idatatable).

**Trả về:**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public final int getStyle()
```

Trả về hoặc đặt kiểu biểu đồ. Đọc/ghi [StyleType](../../com.aspose.slides/styletype).

**Trả về:**
int
### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```

Trả về hoặc đặt kiểu biểu đồ. Đọc/ghi [StyleType](../../com.aspose.slides/styletype).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

Trả về hoặc đặt loại biểu đồ. Đọc/ghi [ChartType](../../com.aspose.slides/charttype).

**Trả về:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Trả về hoặc đặt loại biểu đồ. Đọc/ghi [ChartType](../../com.aspose.slides/charttype).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public final IChartPlotArea getPlotArea()
```

Đại diện cho khu vực vẽ của biểu đồ. Chỉ đọc [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Trả về:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public final IRotation3D getRotation3D()
```

Trả về phép quay 3D của biểu đồ. Chỉ đọc [IRotation3D](../../com.aspose.slides/irotation3d).

**Trả về:**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public final IChartWall getBackWall()
```

Trả về một đối tượng cho phép thay đổi định dạng của tường sau của biểu đồ 3D. Chỉ đọc [IChartWall](../../com.aspose.slides/ichartwall).

**Trả về:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public final IChartWall getSideWall()
```

Trả về một đối tượng cho phép thay đổi định dạng của tường bên của biểu đồ 3D. Chỉ đọc [IChartWall](../../com.aspose.slides/ichartwall).

**Trả về:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public final IChartWall getFloor()
```

Trả về một đối tượng cho phép thay đổi định dạng của sàn của biểu đồ 3D. Chỉ đọc [IChartWall](../../com.aspose.slides/ichartwall).

**Trả về:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Trả về định dạng văn bản của biểu đồ. Thuộc tính không áp dụng cho các loại sau: [ChartType.Treemap](../../com.aspose.slides/charttype\#Treemap), [ChartType.Sunburst](../../com.aspose.slides/charttype\#Sunburst), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel),[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker). Chỉ đọc [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Trả về:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Trả về một chủ đề hiệu quả cho biểu đồ này.

**Trả về:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Trả về trình quản lý chủ đề. Chỉ đọc [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Trả về:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getUserShapes() {#getUserShapes--}
```
public final IGroupShape getUserShapes()
```

Xác định các hình dạng được vẽ trên biểu đồ. Chỉ đọc [IGroupShape](../../com.aspose.slides/igroupshape).

**Trả về:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public final IAxesManager getAxes()
```

Cung cấp quyền truy cập vào các trục biểu đồ. Chỉ đọc [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Trả về:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public final boolean getShowDataLabelsOverMaximum()
```

Chỉ định các nhãn dữ liệu trên mức tối đa của biểu đồ sẽ được hiển thị. Đọc/ghi boolean.

**Trả về:**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public final void setShowDataLabelsOverMaximum(boolean value)
```

Chỉ định các nhãn dữ liệu trên mức tối đa của biểu đồ sẽ được hiển thị. Đọc/ghi boolean.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public final boolean hasRoundedCorners()
```

Chỉ định khu vực biểu đồ sẽ có góc bo tròn. Đọc/ghi boolean.

**Trả về:**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public final void setRoundedCorners(boolean value)
```

Chỉ định khu vực biểu đồ sẽ có góc bo tròn. Đọc/ghi boolean.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Trả về biểu đồ. Chỉ đọc [IChart](../../com.aspose.slides/ichart).

**Trả về:**
[IChart](../../com.aspose.slides/ichart)