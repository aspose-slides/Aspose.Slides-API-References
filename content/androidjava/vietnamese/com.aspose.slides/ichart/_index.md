---
title: IChart
second_title: Tham khảo API Java cho Aspose.Slides trên Android
description: Biểu diễn một biểu đồ đồ họa trên slide.
type: docs
url: /vi/com.aspose.slides/ichart/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface IChart extends IGraphicalObject, IFormattedTextContainer, IOverrideThemeable
```

Biểu diễn một biểu đồ đồ họa trên slide.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Xác định liệu chỉ các ô hiển thị được có được vẽ hay không. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Xác định liệu chỉ các ô hiển thị được có được vẽ hay không. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Trả về hoặc đặt cách vẽ các ô trống trên biểu đồ. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Trả về hoặc đặt cách vẽ các ô trống trên biểu đồ. |
| [getChartData()](#getChartData--) | Trả về thông tin về dữ liệu được liên kết hoặc nhúng liên quan đến biểu đồ. |
| [hasTitle()](#hasTitle--) | Xác định xem biểu đồ có tiêu đề hiển thị hay không. |
| [setTitle(boolean value)](#setTitle-boolean-) | Xác định xem biểu đồ có tiêu đề hiển thị hay không. |
| [getChartTitle()](#getChartTitle--) | Trả về hoặc đặt tiêu đề biểu đồ Chỉ đọc [IChartTitle](../../com.aspose.slides/icharttitle). |
| [hasDataTable()](#hasDataTable--) | Xác định xem biểu đồ có bảng dữ liệu hay không. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | Xác định xem biểu đồ có bảng dữ liệu hay không. |
| [hasLegend()](#hasLegend--) | Xác định xem biểu đồ có chú thích hay không. |
| [setLegend(boolean value)](#setLegend-boolean-) | Xác định xem biểu đồ có chú thích hay không. |
| [getLegend()](#getLegend--) | Trả về hoặc đặt chú thích cho biểu đồ. |
| [getChartDataTable()](#getChartDataTable--) | Trả về bảng dữ liệu của một biểu đồ. |
| [getStyle()](#getStyle--) | Trả về hoặc đặt kiểu biểu đồ. |
| [setStyle(int value)](#setStyle-int-) | Trả về hoặc đặt kiểu biểu đồ. |
| [getType()](#getType--) | Trả về hoặc đặt loại biểu đồ. |
| [setType(int value)](#setType-int-) | Trả về hoặc đặt loại biểu đồ. |
| [getPlotArea()](#getPlotArea--) | Biểu diễn khu vực vẽ của một biểu đồ. |
| [getRotation3D()](#getRotation3D--) | Trả về phép quay 3D của một biểu đồ. |
| [getBackWall()](#getBackWall--) | Trả về một đối tượng cho phép thay đổi định dạng của tường sau của biểu đồ 3D. |
| [getSideWall()](#getSideWall--) | Trả về một đối tượng cho phép thay đổi định dạng của tường bên của biểu đồ 3D. |
| [getFloor()](#getFloor--) | Trả về một đối tượng cho phép thay đổi định dạng của sàn của biểu đồ 3D. |
| [getUserShapes()](#getUserShapes--) | Xác định các hình dạng được vẽ trên biểu đồ. |
| [getAxes()](#getAxes--) | Cung cấp quyền truy cập vào các trục biểu đồ. |
| [validateChartLayout()](#validateChartLayout--) | Tính toán các giá trị thực tế của các phần tử biểu đồ. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Chỉ định nhãn dữ liệu trên mức tối đa của biểu đồ sẽ được hiển thị. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Chỉ định nhãn dữ liệu trên mức tối đa của biểu đồ sẽ được hiển thị. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Chỉ định khu vực biểu đồ sẽ có các góc bo tròn. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Chỉ định khu vực biểu đồ sẽ có các góc bo tròn. |

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public abstract boolean getPlotVisibleCellsOnly()
```

Xác định liệu chỉ các ô hiển thị được có được vẽ hay không. False để vẽ cả các ô hiển thị và ẩn. Đọc/ghi boolean.

**Trả về:**
boolean

### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public abstract void setPlotVisibleCellsOnly(boolean value)
```

Xác định liệu chỉ các ô hiển thị được có được vẽ hay không. False để vẽ cả các ô hiển thị và ẩn. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public abstract int getDisplayBlanksAs()
```

Trả về hoặc đặt cách vẽ các ô trống trên biểu đồ. Đọc/ghi [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Trả về:**
int

### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public abstract void setDisplayBlanksAs(int value)
```

Trả về hoặc đặt cách vẽ các ô trống trên biểu đồ. Đọc/ghi [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public abstract IChartData getChartData()
```

Trả về thông tin về dữ liệu được liên kết hoặc nhúng liên quan đến biểu đồ. Chỉ đọc [IChartData](../../com.aspose.slides/ichartdata).

**Trả về:**
[IChartData](../../com.aspose.slides/ichartdata)

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Xác định xem biểu đồ có tiêu đề hiển thị hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Xác định xem biểu đồ có tiêu đề hiển thị hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public abstract IChartTitle getChartTitle()
```

Trả về hoặc đặt tiêu đề biểu đồ Chỉ đọc [IChartTitle](../../com.aspose.slides/icharttitle).

**Trả về:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### hasDataTable() {#hasDataTable--}
```
public abstract boolean hasDataTable()
```

Xác định xem biểu đồ có bảng dữ liệu hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setDataTable(boolean value) {#setDataTable-boolean-}
```
public abstract void setDataTable(boolean value)
```

Xác định xem biểu đồ có bảng dữ liệu hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public abstract boolean hasLegend()
```

Xác định xem biểu đồ có chú thích hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setLegend(boolean value) {#setLegend-boolean-}
```
public abstract void setLegend(boolean value)
```

Xác định xem biểu đồ có chú thích hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public abstract ILegend getLegend()
```

Trả về hoặc đặt chú thích cho biểu đồ. Chỉ đọc [ILegend](../../com.aspose.slides/ilegend).

**Trả về:**
[ILegend](../../com.aspose.slides/ilegend)

### getChartDataTable() {#getChartDataTable--}
```
public abstract IDataTable getChartDataTable()
```

Trả về bảng dữ liệu của một biểu đồ. Chỉ đọc [IDataTable](../../com.aspose.slides/idatatable).

**Trả về:**
[IDataTable](../../com.aspose.slides/idatatable)

### getStyle() {#getStyle--}
```
public abstract int getStyle()
```

Trả về hoặc đặt kiểu biểu đồ. Đọc/ghi [StyleType](../../com.aspose.slides/styletype).

**Trả về:**
int

### setStyle(int value) {#setStyle-int-}
```
public abstract void setStyle(int value)
```

Trả về hoặc đặt kiểu biểu đồ. Đọc/ghi [StyleType](../../com.aspose.slides/styletype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public abstract int getType()
```

Trả về hoặc đặt loại biểu đồ. Đọc/ghi [ChartType](../../com.aspose.slides/charttype).

**Trả về:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Trả về hoặc đặt loại biểu đồ. Đọc/ ghi [ChartType](../../com.aspose.slides/charttype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public abstract IChartPlotArea getPlotArea()
```

Biểu diễn khu vực vẽ của một biểu đồ. Chỉ đọc [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Trả về:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)

### getRotation3D() {#getRotation3D--}
```
public abstract IRotation3D getRotation3D()
```

Trả về phép quay 3D của một biểu đồ. Chỉ đọc [IRotation3D](../../com.aspose.slides/irotation3d).

**Trả về:**
[IRotation3D](../../com.aspose.slides/irotation3d)

### getBackWall() {#getBackWall--}
```
public abstract IChartWall getBackWall()
```

Trả về một đối tượng cho phép thay đổi định dạng của tường sau của biểu đồ 3D. Chỉ đọc [IChartWall](../../com.aspose.slides/ichartwall).

**Trả về:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getSideWall() {#getSideWall--}
```
public abstract IChartWall getSideWall()
```

Trả về một đối tượng cho phép thay đổi định dạng của tường bên của biểu đồ 3D. Chỉ đọc [IChartWall](../../com.aspose.slides/ichartwall).

**Trả về:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getFloor() {#getFloor--}
```
public abstract IChartWall getFloor()
```

Trả về một đối tượng cho phép thay đổi định dạng của sàn của biểu đồ 3D. Chỉ đọc [IChartWall](../../com.aspose.slides/ichartwall).

**Trả về:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getUserShapes() {#getUserShapes--}
```
public abstract IGroupShape getUserShapes()
```

Xác định các hình dạng được vẽ trên biểu đồ. Chỉ đọc [IGroupShape](../../com.aspose.slides/igroupshape).

**Trả về:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### getAxes() {#getAxes--}
```
public abstract IAxesManager getAxes()
```

Cung cấp quyền truy cập vào các trục biểu đồ. Chỉ đọc [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Trả về:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)

### validateChartLayout() {#validateChartLayout--}
```
public abstract void validateChartLayout()
```

Tính toán các giá trị thực tế của các phần tử biểu đồ. Các giá trị thực tế bao gồm vị trí của các phần tử triển khai giao diện IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) và các giá trị thực tế của các trục (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)

### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public abstract boolean getShowDataLabelsOverMaximum()
```

Chỉ định nhãn dữ liệu trên mức tối đa của biểu đồ sẽ được hiển thị. Đọc/ghi boolean.

**Trả về:**
boolean

### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public abstract void setShowDataLabelsOverMaximum(boolean value)
```

Chỉ định nhãn dữ liệu trên mức tối đa của biểu đồ sẽ được hiển thị. Đọc/ ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public abstract boolean hasRoundedCorners()
```

Chỉ định khu vực biểu đồ sẽ có các góc bo tròn. Đọc/ ghi boolean.

**Trả về:**
boolean

### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public abstract void setRoundedCorners(boolean value)
```

Chỉ định khu vực biểu đồ sẽ có các góc bo tròn. Đọc/ ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |