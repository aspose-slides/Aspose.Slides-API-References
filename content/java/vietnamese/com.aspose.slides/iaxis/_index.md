---
title: IAxis
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đóng gói đối tượng đại diện cho trục biểu đồ.
type: docs
url: /vi/com.aspose.slides/iaxis/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

Bao gói đối tượng đại diện cho trục của biểu đồ.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Biểu thị nếu trục giá trị cắt trục danh mục giữa các danh mục. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Biểu thị nếu trục giá trị cắt trục danh mục giữa các danh mục. |
| [getCrossAt()](#getCrossAt--) | Biểu thị điểm trên trục mà trục vuông góc cắt qua nó. |
| [setCrossAt(float value)](#setCrossAt-float-) | Biểu thị điểm trên trục mà trục vuông góc cắt qua nó. |
| [getDisplayUnit()](#getDisplayUnit--) | Xác định giá trị tỷ lệ của đơn vị hiển thị cho trục giá trị. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Xác định giá trị tỷ lệ của đơn vị hiển thị cho trục giá trị. |
| [getActualMaxValue()](#getActualMaxValue--) | Xác định giá trị tối đa thực tế trên trục. |
| [getActualMinValue()](#getActualMinValue--) | Xác định giá trị tối thiểu thực tế trên trục. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Xác định đơn vị chính thực tế của trục. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Xác định đơn vị phụ thực tế của trục. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Xác định tỷ lệ đơn vị chính thực tế của trục. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Xác định tỷ lệ đơn vị phụ thực tế của trục. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Cho biết liệu giá trị tối đa có được gán tự động hay không. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Cho biết liệu giá trị tối đa có được gán tự động hay không. |
| [getMaxValue()](#getMaxValue--) | Biểu thị giá trị tối đa trên trục giá trị. |
| [setMaxValue(double value)](#setMaxValue-double-) | Biểu thị giá trị tối đa trên trục giá trị. |
| [getMinorUnit()](#getMinorUnit--) | Biểu thị các đơn vị phụ cho trục ngày hoặc trục giá trị. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Biểu thị các đơn vị phụ cho trục ngày hoặc trục giá trị. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Cho biết liệu đơn vị phụ của trục có được gán tự động hay không. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Cho biết liệu đơn vị phụ của trục có được gán tự động hay không. |
| [getMajorUnit()](#getMajorUnit--) | Biểu thị các đơn vị chính cho trục ngày hoặc trục giá trị. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Biểu thị các đơn vị chính cho trục ngày hoặc trục giá trị. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Cho biết liệu đơn vị chính của trục có được gán tự động hay không. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Cho biết liệu đơn vị chính của trục có được gán tự động hay không. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Cho biết liệu giá trị tối thiểu có được gán tự động hay không. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Cho biết liệu giá trị tối thiểu có được gán tự động hay không. |
| [getMinValue()](#getMinValue--) | Biểu thị giá trị tối thiểu trên trục giá trị. |
| [setMinValue(double value)](#setMinValue-double-) | Biểu thị giá trị tối thiểu trên trục giá trị. |
| [isLogarithmic()](#isLogarithmic--) | Biểu thị nếu loại tỷ lệ của trục giá trị là logarit hay không. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Biểu thị nếu loại tỷ lệ của trục giá trị là logarit hay không. |
| [getLogBase()](#getLogBase--) | Biểu thị cơ sở logarit. |
| [setLogBase(double value)](#setLogBase-double-) | Biểu thị cơ sở logarit. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Biểu thị nếu MS PowerPoint vẽ các điểm dữ liệu từ cuối tới đầu. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Biểu thị nếu MS PowerPoint vẽ các điểm dữ liệu từ cuối tới đầu. |
| [isVisible()](#isVisible--) | Biểu thị nếu trục hiển thị. |
| [setVisible(boolean value)](#setVisible-boolean-) | Biểu thị nếu trục hiển thị. |
| [getMajorTickMark()](#getMajorTickMark--) | Biểu thị loại nét đánh dấu chính cho trục đã chỉ định. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Biểu thị loại nét đánh dấu chính cho trục đã chỉ định. |
| [getMinorTickMark()](#getMinorTickMark--) | Biểu thị loại nét đánh dấu phụ cho trục đã chỉ định. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Biểu thị loại nét đánh dấu phụ cho trục đã chỉ định. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Biểu thị vị trí của nhãn đánh dấu trên trục đã chỉ định. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Biểu thị vị trí của nhãn đánh dấu trên trục đã chỉ định. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Biểu thị tỷ lệ đơn vị chính cho trục ngày. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Biểu thị tỷ lệ đơn vị chính cho trục ngày. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Biểu thị tỷ lệ đơn vị chính cho trục ngày. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Biểu thị tỷ lệ đơn vị chính cho trục ngày. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Xác định đơn vị thời gian nhỏ nhất được biểu diễn trên trục ngày. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Xác định đơn vị thời gian nhỏ nhất được biểu diễn trên trục ngày. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Biểu thị định dạng các đường lưới phụ trên trục biểu đồ. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Biểu thị định dạng các đường lưới chính trên trục biểu đồ. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Biểu thị nếu các đường lưới phụ được hiển thị. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Biểu thị nếu các đường lưới chính được hiển thị. |
| [getFormat()](#getFormat--) | Biểu thị định dạng của trục. |
| [getTitle()](#getTitle--) | Lấy tiêu đề của trục. |
| [getCrossType()](#getCrossType--) | Biểu thị CrossType trên trục đã chỉ định nơi trục khác cắt qua. |
| [setCrossType(int value)](#setCrossType-int-) | Biểu thị CrossType trên trục đã chỉ định nơi trục khác cắt qua. |
| [getPosition()](#getPosition--) | Biểu thị vị trí của trục. |
| [setPosition(int value)](#setPosition-int-) | Biểu thị vị trí của trục. |
| [hasTitle()](#hasTitle--) | Xác định liệu trục có tiêu đề hiển thị hay không. |
| [setTitle(boolean value)](#setTitle-boolean-) | Xác định liệu trục có tiêu đề hiển thị hay không. |
| [getNumberFormat()](#getNumberFormat--) | Biểu thị chuỗi định dạng cho Nhãn trục. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Biểu thị chuỗi định dạng cho Nhãn trục. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Cho biết liệu định dạng có liên kết với dữ liệu nguồn hay không. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Cho biết liệu định dạng có liên kết với dữ liệu nguồn hay không. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Biểu thị góc quay của các nhãn đánh dấu Đọc/ghi float. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Biểu thị góc quay của các nhãn đánh dấu Đọc/ghi float. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Xác định số lượng nhãn đánh dấu cần bỏ qua giữa các nhãn được vẽ. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Xác định số lượng nhãn đánh dấu cần bỏ qua giữa các nhãn được vẽ. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Xác định giá trị khoảng cách tự động giữa các nhãn đánh dấu. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Xác định giá trị khoảng cách tự động giữa các nhãn đánh dấu. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Xác định số lượng dấu tick sẽ bỏ qua trước khi dấu tiếp theo được vẽ. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Xác định số lượng dấu tick sẽ bỏ qua trước khi dấu tiếp theo được vẽ. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Xác định giá trị khoảng cách tự động giữa các dấu tick. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Xác định giá trị khoảng cách tự động giữa các dấu tick. |
| [getLabelOffset()](#getLabelOffset--) | Xác định khoảng cách của các nhãn từ trục. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Xác định khoảng cách của các nhãn từ trục. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Xác định loại trục danh mục. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Xác định loại trục danh mục. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Đặt thuộc tính IAxis.CategoryAxisType với giá trị được xác định tự động dựa trên dữ liệu trục. |
| [getAggregationType()](#getAggregationType--) | Biểu thị loại tổng hợp của trục danh mục (bình phân). |
| [setAggregationType(int value)](#setAggregationType-int-) | Biểu thị loại tổng hợp của trục danh mục (bình phân). |
| [getBinWidth()](#getBinWidth--) | Xác định độ rộng bin khi thuộc tính AggregationType được đặt thành AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Xác định độ rộng bin khi thuộc tính AggregationType được đặt thành AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Xác định số lượng bin khi thuộc tính AggregationType được đặt thành AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Xác định số lượng bin khi thuộc tính AggregationType được đặt thành AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Xác định nếu bin tràn được áp dụng. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Xác định nếu bin tràn được áp dụng. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Xác định giá trị bin tràn tự động. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Xác định giá trị bin tràn tự động. |
| [getOverflowBin()](#getOverflowBin--) | Xác định giá trị tùy chỉnh cho bin tràn. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Xác định giá trị tùy chỉnh cho bin tràn. |
| [isUnderflowBin()](#isUnderflowBin--) | Xác định nếu bin thiếu được áp dụng. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Xác định nếu bin thiếu được áp dụng. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Xác định giá trị bin thiếu tự động. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Xác định giá trị bin thiếu tự động. |
| [getUnderflowBin()](#getUnderflowBin--) | Xác định giá trị tùy chỉnh cho bin thiếu. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Xác định giá trị tùy chỉnh cho bin thiếu. |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

Biểu thị nếu trục giá trị cắt trục danh mục giữa các danh mục. Thuộc tính này chỉ áp dụng cho các trục danh mục và không áp dụng cho biểu đồ 3-D. Đọc/ghi boolean.

**Trả về:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

Biểu thị nếu trục giá trị cắt trục danh mục giữa các danh mục. Thuộc tính này chỉ áp dụng cho các trục danh mục và không áp dụng cho biểu đồ 3-D. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

Biểu thị điểm trên trục mà trục vuông góc cắt qua nó. Đọc/ghi float.

**Trả về:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

Biểu thị điểm trên trục mà trục vuông góc cắt qua nó. Đọc/ghi float.

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

Xác định giá trị tối đa thực tế trên trục. Gọi phương thức IChart.ValidateChartLayout() trước đó để lấy giá trị thực tế.

**Trả về:**
double

### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

Xác định giá trị tối thiểu thực tế trên trục. Gọi phương thức IChart.ValidateChartLayout() trước đó để lấy giá trị thực tế.

**Trả về:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

Xác định đơn vị chính thực tế của trục. Gọi phương thức IChart.ValidateChartLayout() trước đó để lấy giá trị thực tế.

**Trả về:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

Xác định đơn vị phụ thực tế của trục. Gọi phương thức IChart.ValidateChartLayout() trước đó để lấy giá trị thực tế.

**Trả về:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

Xác định tỷ lệ đơn vị chính thực tế của trục. Gọi phương thức IChart.ValidateChartLayout() trước đó để lấy giá trị thực tế.

**Trả về:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

Xác định tỷ lệ đơn vị phụ thực tế của trục. Gọi phương thức IChart.ValidateChartLayout() trước đó để lấy giá trị thực tế.

**Trả về:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

Cho biết liệu giá trị tối đa có được gán tự động hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

Cho biết liệu giá trị tối đa có được gán tự động hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

Biểu thị giá trị tối đa trên trục giá trị. Đọc/ghi double.

**Trả về:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

Biểu thị giá trị tối đa trên trục giá trị. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

Biểu thị các đơn vị phụ cho trục ngày hoặc trục giá trị. Đọc/ghi double.

**Trả về:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

Biểu thị các đơn vị phụ cho trục ngày hoặc trục giá trị. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

Cho biết liệu đơn vị phụ của trục có được gán tự động hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

Cho biết liệu đơn vị phụ của trục có được gán tự động hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

Biểu thị các đơn vị chính cho trục ngày hoặc trục giá trị. Đọc/ghi double.

**Trả về:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

Biểu thị các đơn vị chính cho trục ngày hoặc trục giá trị. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

Cho biết liệu đơn vị chính của trục có được gán tự động hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

Cho biết liệu đơn vị chính của trục có được gán tự động hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

Cho biết liệu giá trị tối thiểu có được gán tự động hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

Cho biết liệu giá trị tối thiểu có được gán tự động hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

Biểu diễn giá trị tối thiểu trên trục giá trị. Đọc/ghi double.

**Trả về:**
double

### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

Biểu diễn giá trị tối thiểu trên trục giá trị. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

Biểu diễn loại thang đo trục giá trị là logarit hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

Biểu diễn loại thang đo trục giá trị là logarit hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

Biểu diễn cơ số logarit. Giá trị mặc định là 10. Đọc/ghi double.

**Trả về:**
double

### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

Biểu diễn cơ số logarit. Giá trị mặc định là 10. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

Biểu diễn liệu MS PowerPoint vẽ các điểm dữ liệu từ cuối tới đầu hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

Biểu diễn liệu MS PowerPoint vẽ các điểm dữ liệu từ cuối tới đầu hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Biểu diễn liệu trục có hiển thị hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Biểu diễn liệu trục có hiển thị hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

Biểu diễn loại dấu tick chính cho trục đã chỉ định. Đọc/ghi [TickMarkType](../../com.aspose.slides/tickmarktype).

**Trả về:**
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

Biểu diễn loại dấu tick chính cho trục đã chỉ định. Đọc/ghi [TickMarkType](../../com.aspose.slides/tickmarktype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

Biểu diễn loại dấu tick phụ cho trục đã chỉ định. Đọc/ghi [TickMarkType](../../com.aspose.slides/tickmarktype).

**Trả về:**
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

Biểu diễn loại dấu tick phụ cho trục đã chỉ định. Đọc/ghi [TickMarkType](../../com.aspose.slides/tickmarktype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

Biểu diễn vị trí của nhãn dấu tick trên trục đã chỉ định. Đọc/ghi [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Trả về:**
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

Biểu diễn vị trí của nhãn dấu tick trên trục đã chỉ định. Đọc/ghi [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

Biểu diễn thang đo đơn vị chính cho trục ngày. Đọc/ghi [TimeUnitType](../../com.aspose.slides/timeunittype).

**Trả về:**
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

Biểu diễn thang đo đơn vị chính cho trục ngày. Đọc/ghi [TimeUnitType](../../com.aspose.slides/timeunittype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

Biểu diễn thang đo đơn vị chính cho trục ngày. Đọc/ghi [TimeUnitType](../../com.aspose.slides/timeunittype).

**Trả về:**
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

Biểu diễn thang đo đơn vị chính cho trục ngày. Đọc/ghi [TimeUnitType](../../com.aspose.slides/timeunittype).

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

Biểu diễn định dạng lưới phụ trên trục biểu đồ. Chỉ đọc [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Trả về:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

Biểu diễn định dạng lưới chính trên trục biểu đồ. Chỉ đọc [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Trả về:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

Biểu diễn liệu lưới phụ có hiển thị hay không. Chỉ đọc boolean.

**Trả về:**
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

Biểu diễn liệu lưới chính có hiển thị hay không. Chỉ đọc boolean.

**Trả về:**
boolean

### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

Biểu diễn định dạng của trục. Chỉ đọc [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Trả về:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

Lấy tiêu đề của trục. Chỉ đọc [IChartTitle](../../com.aspose.slides/icharttitle).

**Trả về:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

Biểu diễn CrossType trên trục đã chỉ định nơi trục kia giao nhau. Đọc/ghi [CrossesType](../../com.aspose.slides/crossestype).

**Trả về:**
int

### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

Biểu diễn CrossType trên trục đã chỉ định nơi trục kia giao nhau. Đọc/ghi [CrossesType](../../com.aspose.slides/crossestype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Biểu diễn vị trí của trục. Đọc/ghi [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Trả về:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Biểu diễn vị trí của trục. Đọc/ghi [AxisPositionType](../../com.aspose.slides/axispositiontype).

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

Biểu diễn chuỗi định dạng cho Nhãn trục. Đọc/ghi String.

**Trả về:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Biểu diễn chuỗi định dạng cho Nhãn trục. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Cho biết liệu định dạng có được liên kết với dữ liệu nguồn hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Cho biết liệu định dạng có được liên kết với dữ liệu nguồn hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

Biểu diễn góc xoay của nhãn tick. Đọc/ghi float.

**Trả về:**
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

Biểu diễn góc xoay của nhãn tick. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

Xác định số lượng nhãn tick được bỏ qua giữa các nhãn được vẽ. Đọc/ghi long.

**Trả về:**
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

Xác định số lượng nhãn tick được bỏ qua giữa các nhãn được vẽ. Đọc/ghi long.

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

Xác định số lượng dấu tick sẽ bị bỏ qua trước khi dấu tiếp theo được vẽ. Áp dụng cho trục danh mục hoặc chuỗi. Đọc/ghi int.

**Trả về:**
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

Xác định số lượng dấu tick sẽ bị bỏ qua trước khi dấu tiếp theo được vẽ. Áp dụng cho trục danh mục hoặc chuỗi. Đọc/ghi int.

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

Xác định khoảng cách của nhãn so với trục. Áp dụng cho trục danh mục hoặc ngày. Giá trị phải nằm trong khoảng 0% đến 1000%. Đọc/ghi int.

**Trả về:**
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

Xác định khoảng cách của nhãn so với trục. Áp dụng cho trục danh mục hoặc ngày. Giá trị phải nằm trong khoảng 0% đến 1000%. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

Xác định loại trục danh mục. Đọc/ghi [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Trả về:**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

Xác định loại trục danh mục. Đọc/ghi [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

Đặt thuộc tính IAxis.CategoryAxisType với một giá trị được xác định tự động dựa trên dữ liệu trục.

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

Biểu diễn loại tổng hợp của trục danh mục (phân nhóm). Áp dụng cho danh mục. Chỉ dùng với chuỗi Histogram hoặc HistogramPareto.

**Trả về:**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

Biểu diễn loại tổng hợp của trục danh mục (phân nhóm). Áp dụng cho danh mục. Chỉ dùng với chuỗi Histogram hoặc HistogramPareto.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

Xác định độ rộng bin khi giá trị thuộc tính AggregationType được đặt thành AxisAggregationType.ByBinWidth. Áp dụng cho các trục danh mục. Chỉ được sử dụng với chuỗi Histogram hoặc HistogramPareto.

**Trả về:**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

Xác định độ rộng bin khi giá trị thuộc tính AggregationType được đặt thành AxisAggregationType.ByBinWidth. Áp dụng cho các trục danh mục. Chỉ được sử dụng với chuỗi Histogram hoặc HistogramPareto.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

Xác định số bin khi giá trị thuộc tính AggregationType được đặt thành AxisAggregationType.ByNumberOfBins. Áp dụng cho các trục danh mục. Chỉ được sử dụng với chuỗi Histogram hoặc HistogramPareto.

**Trả về:**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

Xác định số bin khi giá trị thuộc tính AggregationType được đặt thành AxisAggregationType.ByNumberOfBins. Áp dụng cho các trục danh mục. Chỉ được sử dụng với chuỗi Histogram hoặc HistogramPareto.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

Xác định liệu bin tràn có được áp dụng hay không. Sử dụng IsAutomaticOverflowBin và OverflowBin để điều chỉnh giá trị bin tràn.

**Trả về:**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

Xác định liệu bin tràn có được áp dụng hay không. Sử dụng IsAutomaticOverflowBin và OverflowBin để điều chỉnh giá trị bin tràn.

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

Xác định giá trị tùy chỉnh cho bin tràn. Được áp dụng khi thuộc tính IsAutomaticOverflowBin được đặt thành false và thuộc tính IsOverflowBin bằng true.

**Trả về:**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

Xác định giá trị tùy chỉnh cho bin tràn. Được áp dụng khi thuộc tính IsAutomaticOverflowBin được đặt thành false và thuộc tính IsOverflowBin bằng true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

Xác định liệu bin thiếu (underflow) có được áp dụng hay không. Sử dụng IsAutomaticUnderflowBin và UnderflowBin để điều chỉnh giá trị bin thiếu.

**Trả về:**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

Xác định liệu bin thiếu (underflow) có được áp dụng hay không. Sử dụng IsAutomaticUnderflowBin và UnderflowBin để điều chỉnh giá trị bin thiếu.

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

Xác định giá trị tùy chỉnh cho bin thiếu. Được áp dụng khi thuộc tính IsAutomaticUnderflowBin được đặt thành false và thuộc tính IsUnderflowBin bằng true.

**Trả về:**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

Xác định giá trị tùy chỉnh cho bin thiếu. Được áp dụng khi thuộc tính IsAutomaticUnderflowBin được đặt thành false và thuộc tính IsUnderflowBin bằng true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |