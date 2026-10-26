---
title: IAxis
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Bao bọc đối tượng đại diện cho trục của biểu đồ.
type: docs
url: /vi/com.aspose.slides/iaxis/
---
**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

Bao bọc đối tượng đại diện cho trục của biểu đồ.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Cho biết trục giá trị có cắt trục danh mục giữa các danh mục hay không. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Cho biết trục giá trị có cắt trục danh mục giữa các danh mục hay không. |
| [getCrossAt()](#getCrossAt--) | Cho biết điểm trên trục mà trục vuông góc cắt qua nó. |
| [setCrossAt(float value)](#setCrossAt-float-) | Cho biết điểm trên trục mà trục vuông góc cắt qua nó. |
| [getDisplayUnit()](#getDisplayUnit--) | Xác định giá trị tỷ lệ của đơn vị hiển thị cho trục giá trị. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Xác định giá trị tỷ lệ của đơn vị hiển thị cho trục giá trị. |
| [getActualMaxValue()](#getActualMaxValue--) | Xác định giá trị tối đa thực tế trên trục. |
| [getActualMinValue()](#getActualMinValue--) | Xác định giá trị tối thiểu thực tế trên trục. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Xác định đơn vị chính thực tế của trục. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Xác định đơn vị phụ thực tế của trục. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Xác định tỷ lệ đơn vị chính thực tế của trục. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Xác định tỷ lệ đơn vị phụ thực tế của trục. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Chỉ ra liệu giá trị tối đa có được gán tự động hay không. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Chỉ ra liệu giá trị tối đa có được gán tự động hay không. |
| [getMaxValue()](#getMaxValue--) | Đại diện cho giá trị tối đa trên trục giá trị. |
| [setMaxValue(double value)](#setMaxValue-double-) | Đại diện cho giá trị tối đa trên trục giá trị. |
| [getMinorUnit()](#getMinorUnit--) | Đại diện cho các đơn vị phụ cho trục ngày hoặc giá trị. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Đại diện cho các đơn vị phụ cho trục ngày hoặc giá trị. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Chỉ ra liệu đơn vị phụ của trục có được gán tự động hay không. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Chỉ ra liệu đơn vị phụ của trục có được gán tự động hay không. |
| [getMajorUnit()](#getMajorUnit--) | Đại diện cho các đơn vị chính cho trục ngày hoặc giá trị. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Đại diện cho các đơn vị chính cho trục ngày hoặc giá trị. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Chỉ ra liệu đơn vị chính của trục có được gán tự động hay không. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Chỉ ra liệu đơn vị chính của trục có được gán tự động hay không. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Chỉ ra liệu giá trị tối thiểu có được gán tự động hay không. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Chỉ ra liệu giá trị tối thiểu có được gán tự động hay không. |
| [getMinValue()](#getMinValue--) | Đại diện cho giá trị tối thiểu trên trục giá trị. |
| [setMinValue(double value)](#setMinValue-double-) | Đại diện cho giá trị tối thiểu trên trục giá trị. |
| [isLogarithmic()](#isLogarithmic--) | Đại diện cho việc trục giá trị có kiểu tỷ lệ lôgarit hay không. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Đại diện cho việc trục giá trị có kiểu tỷ lệ lôgarit hay không. |
| [getLogBase()](#getLogBase--) | Đại diện cho cơ số lôgarit. |
| [setLogBase(double value)](#setLogBase-double-) | Đại diện cho cơ số lôgarit. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Đại diện cho việc MS PowerPoint vẽ các điểm dữ liệu từ cuối lên đầu. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Đại diện cho việc MS PowerPoint vẽ các điểm dữ liệu từ cuối lên đầu. |
| [isVisible()](#isVisible--) | Đại diện cho việc trục có hiển thị hay không. |
| [setVisible(boolean value)](#setVisible-boolean-) | Đại diện cho việc trục có hiển thị hay không. |
| [getMajorTickMark()](#getMajorTickMark--) | Đại diện cho kiểu dấu tick chính cho trục đã chỉ định. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Đại diện cho kiểu dấu tick chính cho trục đã chỉ định. |
| [getMinorTickMark()](#getMinorTickMark--) | Đại diện cho kiểu dấu tick phụ cho trục đã chỉ định. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Đại diện cho kiểu dấu tick phụ cho trục đã chỉ định. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Đại diện cho vị trí của nhãn dấu tick trên trục đã chỉ định. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Đại diện cho vị trí của nhãn dấu tick trên trục đã chỉ định. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Đại diện cho tỷ lệ đơn vị chính cho trục ngày. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Đại diện cho tỷ lệ đơn vị chính cho trục ngày. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Đại diện cho tỷ lệ đơn vị chính cho trục ngày. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Đại diện cho tỷ lệ đơn vị chính cho trục ngày. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Xác định đơn vị thời gian nhỏ nhất được biểu diễn trên trục ngày. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Xác định đơn vị thời gian nhỏ nhất được biểu diễn trên trục ngày. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Đại diện cho định dạng lưới phụ trên một trục biểu đồ. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Đại diện cho định dạng lưới chính trên một trục biểu đồ. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Đại diện cho việc hiển thị lưới phụ. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Đại diện cho việc hiển thị lưới chính. |
| [getFormat()](#getFormat--) | Đại diện cho định dạng của trục. |
| [getTitle()](#getTitle--) | Lấy tiêu đề của trục. |
| [getCrossType()](#getCrossType--) | Đại diện cho CrossType trên trục đã chỉ định nơi trục còn lại cắt. |
| [setCrossType(int value)](#setCrossType-int-) | Đại diện cho CrossType trên trục đã chỉ định nơi trục còn lại cắt. |
| [getPosition()](#getPosition--) | Đại diện cho vị trí của trục. |
| [setPosition(int value)](#setPosition-int-) | Đại diện cho vị trí của trục. |
| [hasTitle()](#hasTitle--) | Xác định liệu trục có tiêu đề hiển thị hay không. |
| [setTitle(boolean value)](#setTitle-boolean-) | Xác định liệu trục có tiêu đề hiển thị hay không. |
| [getNumberFormat()](#getNumberFormat--) | Đại diện cho chuỗi định dạng cho Nhãn Trục. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Đại diện cho chuỗi định dạng cho Nhãn Trục. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Chỉ ra liệu định dạng có được liên kết với dữ liệu nguồn hay không. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Chỉ ra liệu định dạng có được liên kết với dữ liệu nguồn hay không. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Đại diện cho góc quay của nhãn tick. Đọc/ghi float. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Đại diện cho góc quay của nhãn tick. Đọc/ghi float. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Xác định số nhãn tick cần bỏ qua giữa các nhãn được vẽ. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Xác định số nhãn tick cần bỏ qua giữa các nhãn được vẽ. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Xác định giá trị khoảng cách tự động cho nhãn tick. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Xác định giá trị khoảng cách tự động cho nhãn tick. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Xác định số dấu tick cần bỏ qua trước khi vẽ dấu tick tiếp theo. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Xác định số dấu tick cần bỏ qua trước khi vẽ dấu tick tiếp theo. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Xác định giá trị khoảng cách tự động cho dấu tick. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Xác định giá trị khoảng cách tự động cho dấu tick. |
| [getLabelOffset()](#getLabelOffset--) | Xác định khoảng cách của nhãn so với trục. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Xác định khoảng cách của nhãn so với trục. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Xác định kiểu của trục danh mục. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Xác định kiểu của trục danh mục. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Đặt thuộc tính IAxis.CategoryAxisType với giá trị tự động quyết định dựa trên dữ liệu trục. |
| [getAggregationType()](#getAggregationType--) | Đại diện cho kiểu tổng hợp của trục danh mục (phân lớp). |
| [setAggregationType(int value)](#setAggregationType-int-) | Đại diện cho kiểu tổng hợp của trục danh mục (phân lớp). |
| [getBinWidth()](#getBinWidth--) | Xác định độ rộng bin khi thuộc tính AggregationType được đặt thành AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Xác định độ rộng bin khi thuộc tính AggregationType được đặt thành AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Xác định số bin khi thuộc tính AggregationType được đặt thành AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Xác định số bin khi thuộc tính AggregationType được đặt thành AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Xác định liệu bin tràn áp dụng hay không. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Xác định liệu bin tràn áp dụng hay không. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Xác định giá trị bin tràn tự động. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Xác định giá trị bin tràn tự động. |
| [getOverflowBin()](#getOverflowBin--) | Xác định giá trị bin tràn tùy chỉnh. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Xác định giá trị bin tràn tùy chỉnh. |
| [isUnderflowBin()](#isUnderflowBin--) | Xác định liệu bin thiếu áp dụng hay không. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Xác định liệu bin thiếu áp dụng hay không. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Xác định giá trị bin thiếu tự động. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Xác định giá trị bin thiếu tự động. |
| [getUnderflowBin()](#getUnderflowBin--) | Xác định giá trị bin thiếu tùy chỉnh. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Xác định giá trị bin thiếu tùy chỉnh. |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

Cho biết trục giá trị có cắt trục danh mục giữa các danh mục hay không. Thuộc tính này chỉ áp dụng cho các trục danh mục và không áp dụng cho biểu đồ 3D. Đọc/ghi boolean.

**Trả về:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

Cho biết trục giá trị có cắt trục danh mục giữa các danh mục hay không. Thuộc tính này chỉ áp dụng cho các trục danh mục và không áp dụng cho biểu đồ 3D. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

Cho biết điểm trên trục mà trục vuông góc cắt qua nó. Đọc/ghi float.

**Trả về:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

Cho biết điểm trên trục mà trục vuông góc cắt qua nó. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

Xác định giá trị tỷ lệ của đơn vị hiển thị cho trục giá trị. Đọc/ghi [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Trả về:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

Xác định giá trị tỷ lệ của đơn vị hiển thị cho trục giá trị. Đọc/ghi [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

Xác định giá trị tối đa thực tế trên trục. Gọi phương thức IChart.ValidateChartLayout() trước để lấy giá trị thực tế.

**Trả về:**
double

### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

Xác định giá trị tối thiểu thực tế trên trục. Gọi phương thức IChart.ValidateChartLayout() trước để lấy giá trị thực tế.

**Trả về:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

Xác định đơn vị chính thực tế của trục. Gọi phương thức IChart.ValidateChartLayout() trước để lấy giá trị thực tế.

**Trả về:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

Xác định đơn vị phụ thực tế của trục. Gọi phương thức IChart.ValidateChartLayout() trước để lấy giá trị thực tế.

**Trả về:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

Xác định tỷ lệ đơn vị chính thực tế của trục. Gọi phương thức IChart.ValidateChartLayout() trước để lấy giá trị thực tế.

**Trả về:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

Xác định tỷ lệ đơn vị phụ thực tế của trục. Gọi phương thức IChart.ValidateChartLayout() trước để lấy giá trị thực tế.

**Trả về:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

Chỉ ra liệu giá trị tối đa có được gán tự động hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

Chỉ ra liệu giá trị tối đa có được gán tự động hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

Đại diện cho giá trị tối đa trên trục giá trị. Đọc/ghi double.

**Trả về:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

Đại diện cho giá trị tối đa trên trục giá trị. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

Đại diện cho các đơn vị phụ cho trục ngày hoặc giá trị. Đọc/ghi double.

**Trả về:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

Đại diện cho các đơn vị phụ cho trục ngày hoặc giá trị. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

Chỉ ra liệu đơn vị phụ của trục có được gán tự động hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

Chỉ ra liệu đơn vị phụ của trục có được gán tự động hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

Đại diện cho các đơn vị chính cho trục ngày hoặc giá trị. Đọc/ghi double.

**Trả về:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

Đại diện cho các đơn vị chính cho trục ngày hoặc giá trị. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

Chỉ ra liệu đơn vị chính của trục có được gán tự động hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

Chỉ ra liệu đơn vị chính của trục có được gán tự động hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

Chỉ ra liệu giá trị tối thiểu có được gán tự động hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

Chỉ ra liệu giá trị tối thiểu có được gán tự động hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

Đại diện cho giá trị tối thiểu trên trục giá trị. Đọc/ghi double.

**Trả về:**
double

### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

Đại diện cho giá trị tối thiểu trên trục giá trị. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

Đại diện cho việc trục giá trị có kiểu tỷ lệ lôgarit hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

Đại diện cho việc trục giá trị có kiểu tỷ lệ lôgarit hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

Đại diện cho cơ số lôgarit. Giá trị mặc định là 10. Đọc/ghi double.

**Trả về:**
double

### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

Đại diện cho cơ số lôgarit. Giá trị mặc định là 10. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

Đại diện cho việc MS PowerPoint vẽ các điểm dữ liệu từ cuối lên đầu. Đọc/ghi boolean.

**Trả về:**
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

Đại diện cho việc MS PowerPoint vẽ các điểm dữ liệu từ cuối lên đầu. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Đại diện cho việc trục có hiển thị hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Đại diện cho việc trục có hiển thị hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

Đại diện cho kiểu dấu tick chính cho trục đã chỉ định. Đọc/ghi [TickMarkType](../../com.aspose.slides/tickmarktype).

**Trả về:**
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

Đại diện cho kiểu dấu tick chính cho trục đã chỉ định. Đọc/ghi [TickMarkType](../../com.aspose.slides/tickmarktype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

Đại diện cho kiểu dấu tick phụ cho trục đã chỉ định. Đọc/ghi [TickMarkType](../../com.aspose.slides/tickmarktype).

**Trả về:**
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

Đại diện cho kiểu dấu tick phụ cho trục đã chỉ định. Đọc/ghi [TickMarkType](../../com.aspose.slides/tickmarktype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

Đại diện cho vị trí của nhãn dấu tick trên trục đã chỉ định. Đọc/ghi [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Trả về:**
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

Đại diện cho vị trí của nhãn dấu tick trên trục đã chỉ định. Đọc/ghi [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

Đại diện cho tỷ lệ đơn vị chính cho trục ngày. Đọc/ghi [TimeUnitType](../../com.aspose.slides/timeunittype).

**Trả về:**
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

Đại diện cho tỷ lệ đơn vị chính cho trục ngày. Đọc/ghi [TimeUnitType](../../com.aspose.slides/timeunittype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

Đại diện cho tỷ lệ đơn vị chính cho trục ngày. Đọc/ghi [TimeUnitType](../../com.aspose.slides/timeunittype).

**Trả về:**
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

Đại diện cho tỷ lệ đơn vị chính cho trục ngày. Đọc/ghi [TimeUnitType](../../com.aspose.slides/timeunittype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

Xác định đơn vị thời gian nhỏ nhất được biểu diễn trên trục ngày. Đọc/ghi [TimeUnitType](../../com.aspose.slides/timeunittype).

**Trả về:**
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

Xác định đơn vị thời gian nhỏ nhất được biểu diễn trên trục ngày. Đọc/ghi [TimeUnitType](../../com.aspose.slides/timeunittype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

Đại diện cho định dạng lưới phụ trên một trục biểu đồ. Chỉ-đọc [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Trả về:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMajorGridLinesFormat()
```

Đại diện cho định dạng lưới chính trên một trục biểu đồ. Chỉ-đọc [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Trả về:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

Đại diện cho việc hiển thị lưới phụ. Chỉ-đọc boolean.

**Trả về:**
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

Đại diện cho việc hiển thị lưới chính. Chỉ-đọc boolean.

**Trả về:**
boolean

### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

Đại diện cho định dạng của trục. Chỉ-đọc [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Trả về:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

Lấy tiêu đề của trục. Chỉ-đọc [IChartTitle](../../com.aspose.slides/icharttitle).

**Trả về:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

Đại diện cho CrossType trên trục đã chỉ định nơi trục còn lại cắt. Đọc/ghi [CrossesType](../../com.aspose.slides/crossestype).

**Trả về:**
int

### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

Đại diện cho CrossType trên trục đã chỉ định nơi trục còn lại cắt. Đọc/ghi [CrossesType](../../com.aspose.slides/crossestype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Đại diện cho vị trí của trục. Đọc/ghi [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Trả về:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Đại diện cho vị trí của trục. Đọc/ghi [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Xác định liệu trục có tiêu đề hiển thị hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Xác định liệu trục có tiêu đề hiển thị hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Đại diện cho chuỗi định dạng cho Nhãn Trục. Đọc/ghi String.

**Trả về:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Đại diện cho chuỗi định dạng cho Nhãn Trục. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Chỉ ra liệu định dạng có được liên kết với dữ liệu nguồn hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Chỉ ra liệu định dạng có được liên kết với dữ liệu nguồn hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

Đại diện cho góc quay của nhãn tick. Đọc/ghi float.

**Trả về:**
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

Đại diện cho góc quay của nhãn tick. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

Xác định số nhãn tick cần bỏ qua giữa các nhãn được vẽ. Đọc/ghi long.

**Trả về:**
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

Xác định số nhãn tick cần bỏ qua giữa các nhãn được vẽ. Đọc/ghi long.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

Xác định giá trị khoảng cách nhãn tick tự động. Nếu false: sử dụng thuộc tính TickLabelSpacing. Đọc/ghi boolean.

**Trả về:**
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

Xác định giá trị khoảng cách nhãn tick tự động. Nếu false: sử dụng thuộc tính TickLabelSpacing. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

Xác định số dấu tick cần bỏ qua trước khi vẽ dấu tick tiếp theo. Áp dụng cho trục danh mục hoặc trục series. Đọc/ghi int.

**Trả về:**
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

Xác định số dấu tick cần bỏ qua trước khi vẽ dấu tick tiếp theo. Áp dụng cho trục danh mục hoặc trục series. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

Xác định giá trị khoảng cách dấu tick tự động. Nếu false: sử dụng thuộc tính TickMarksSpacing. Đọc/ghi boolean.

**Trả về:**
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

Xác định giá trị khoảng cách dấu tick tự động. Nếu false: sử dụng thuộc tính TickMarksSpacing. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

Xác định khoảng cách của nhãn so với trục. Áp dụng cho trục danh mục hoặc trục ngày. Giá trị phải nằm trong khoảng 0% và 1000%. Đọc/ghi int.

**Trả về:**
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

Xác định khoảng cách của nhãn so với trục. Áp dụng cho trục danh mục hoặc trục ngày. Giá trị phải nằm trong khoảng 0% và 1000%. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

Xác định kiểu của trục danh mục. Đọc/ghi [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Trả về:**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

Xác định kiểu của trục danh mục. Đọc/ghi [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

Đặt thuộc tính IAxis.CategoryAxisType với giá trị tự động quyết định dựa trên dữ liệu trục.

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

Đại diện cho kiểu tổng hợp của trục danh mục (phân lớp). Áp dụng cho danh mục. Chỉ dùng với series Histogram hoặc HistogramPareto.

**Trả về:**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

Đại diện cho kiểu tổng hợp của trục danh mục (phân lớp). Áp dụng cho danh mục. Chỉ dùng với series Histogram hoặc HistogramPareto.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

Xác định độ rộng bin khi giá trị thuộc tính AggregationType được đặt thành AxisAggregationType.ByBinWidth. Áp dụng cho trục danh mục. Chỉ dùng với series Histogram hoặc HistogramPareto.

**Trả về:**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

Xác định độ rộng bin khi giá trị thuộc tính AggregationType được đặt thành AxisAggregationType.ByBinWidth. Áp dụng cho trục danh mục. Chỉ dùng với series Histogram hoặc HistogramPareto.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

Xác định số bin khi giá trị thuộc tính AggregationType được đặt thành AxisAggregationType.ByNumberOfBins. Áp dụng cho trục danh mục. Chỉ dùng với series Histogram hoặc HistogramPareto.

**Trả về:**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

Xác định số bin khi giá trị thuộc tính AggregationType được đặt thành AxisAggregationType.ByNumberOfBins. Áp dụng cho trục danh mục. Chỉ dùng với series Histogram hoặc HistogramPareto.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

Xác định liệu bin tràn áp dụng. Sử dụng IsAutomaticOverflowBin và OverflowBin để điều chỉnh giá trị bin tràn.

**Trả về:**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

Xác định liệu bin tràn áp dụng. Sử dụng IsAutomaticOverflowBin và OverflowBin để điều chỉnh giá trị bin tràn.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

Xác định giá trị bin tràn tự động. Nếu false: sử dụng thuộc tính OverflowBin.

**Trả về:**
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

Xác định giá trị bin tràn tự động. Nếu false: sử dụng thuộc tính OverflowBin.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

Xác định giá trị bin tràn tùy chỉnh. Áp dụng khi thuộc tính IsAutomaticOverflowBin được đặt thành false và IsOverflowBin bằng true.

**Trả về:**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

Xác định giá trị bin tràn tùy chỉnh. Áp dụng khi thuộc tính IsAutomaticOverflowBin được đặt thành false và IsOverflowBin bằng true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

Xác định liệu bin thiếu áp dụng. Sử dụng IsAutomaticUnderflowBin và UnderflowBin để điều chỉnh giá trị bin thiếu.

**Trả về:**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

Xác định liệu bin thiếu áp dụng. Sử dụng IsAutomaticUnderflowBin và UnderflowBin để điều chỉnh giá trị bin thiếu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

Xác định giá trị bin thiếu tự động. Nếu false: sử dụng thuộc tính UnderflowBin.

**Trả về:**
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

Xác định giá trị bin thiếu tự động. Nếu false: sử dụng thuộc tính UnderflowBin.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

Xác định giá trị bin thiếu tùy chỉnh. Áp dụng khi thuộc tính IsAutomaticUnderflowBin được đặt thành false và IsUnderflowBin bằng true.

**Trả về:**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

Xác định giá trị bin thiếu tùy chỉnh. Áp dụng khi thuộc tính IsAutomaticUnderflowBin được đặt thành false và IsUnderflowBin bằng true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |