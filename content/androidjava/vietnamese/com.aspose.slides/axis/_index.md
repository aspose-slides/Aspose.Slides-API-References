---
title: Axis
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Bọc đối tượng đại diện cho trục của biểu đồ.
type: docs
url: /vi/com.aspose.slides/axis/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được thực hiện:**
[com.aspose.slides.IAxis](../../com.aspose.slides/iaxis)
```
public class Axis extends DomObject<AxesManager> implements IAxis
```

Bọc đối tượng đại diện cho trục của biểu đồ.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getChart()](#getChart--) | Trả về biểu đồ cha. |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Biểu thị nếu trục giá trị cắt trục danh mục giữa các danh mục. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Biểu thị nếu trục giá trị cắt trục danh mục giữa các danh mục. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Xác định loại trục danh mục. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Xác định loại trục danh mục. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Đặt thuộc tính IAxis.CategoryAxisType với một giá trị được tự động xác định dựa trên dữ liệu trục. |
| [getCrossAt()](#getCrossAt--) | Biểu thị điểm trên trục mà trục vuông góc cắt qua. |
| [setCrossAt(float value)](#setCrossAt-float-) | Biểu thị điểm trên trục mà trục vuông góc cắt qua. |
| [getDisplayUnit()](#getDisplayUnit--) | Xác định giá trị tỷ lệ của các đơn vị hiển thị cho trục giá trị. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Xác định giá trị tỷ lệ của các đơn vị hiển thị cho trục giá trị. |
| [getActualMaxValue()](#getActualMaxValue--) | Xác định giá trị tối đa thực tế trên trục. |
| [getActualMinValue()](#getActualMinValue--) | Xác định giá trị tối thiểu thực tế trên trục. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Xác định đơn vị chính thực tế của trục. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Xác định đơn vị phụ thực tế của trục. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Xác định tỷ lệ đơn vị chính thực tế của trục. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Xác định tỷ lệ đơn vị phụ thực tế của trục. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Cho biết giá trị tối đa có được tự động gán hay không. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Cho biết giá trị tối đa có được tự động gán hay không. |
| [getMaxValue()](#getMaxValue--) | Biểu thị giá trị tối đa trên trục giá trị. |
| [setMaxValue(double value)](#setMaxValue-double-) | Biểu thị giá trị tối đa trên trục giá trị. |
| [getMinorUnit()](#getMinorUnit--) | Biểu thị các đơn vị phụ cho trục ngày hoặc giá trị. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Biểu thị các đơn vị phụ cho trục ngày hoặc giá trị. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Cho biết đơn vị phụ của trục có được tự động gán hay không. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Cho biết đơn vị phụ của trục có được tự động gán hay không. |
| [getMajorUnit()](#getMajorUnit--) | Biểu thị các đơn vị chính cho trục ngày hoặc giá trị. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Biểu thị các đơn vị chính cho trục ngày hoặc giá trị. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Cho biết đơn vị chính của trục có được tự động gán hay không. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Cho biết đơn vị chính của trục có được tự động gán hay không. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Cho biết giá trị tối thiểu có được tự động gán hay không. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Cho biết giá trị tối thiểu có được tự động gán hay không. |
| [getMinValue()](#getMinValue--) | Biểu thị giá trị tối thiểu trên trục giá trị. |
| [setMinValue(double value)](#setMinValue-double-) | Biểu thị giá trị tối thiểu trên trục giá trị. |
| [isLogarithmic()](#isLogarithmic--) | Biểu thị nếu loại tỷ lệ trục giá trị là logarit hay không. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Biểu thị nếu loại tỷ lệ trục giá trị là logarit hay không. |
| [getLogBase()](#getLogBase--) | Biểu thị cơ số logarit. |
| [setLogBase(double value)](#setLogBase-double-) | Biểu thị cơ số logarit. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Biểu thị nếu MS PowerPoint vẽ các điểm dữ liệu từ cuối lên đầu. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Biểu thị nếu MS PowerPoint vẽ các điểm dữ liệu từ cuối lên đầu. |
| [isVisible()](#isVisible--) | Biểu thị nếu trục hiển thị. |
| [setVisible(boolean value)](#setVisible-boolean-) | Biểu thị nếu trục hiển thị. |
| [getMajorTickMark()](#getMajorTickMark--) | Biểu thị loại dấu tick chính cho trục được chỉ định. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Biểu thị loại dấu tick chính cho trục được chỉ định. |
| [getMinorTickMark()](#getMinorTickMark--) | Biểu thị loại dấu tick phụ cho trục được chỉ định. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Biểu thị loại dấu tick phụ cho trục được chỉ định. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Biểu thị vị trí của nhãn tick trên trục được chỉ định. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Biểu thị vị trí của nhãn tick trên trục được chỉ định. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Biểu thị tỷ lệ đơn vị chính cho trục ngày. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Biểu thị tỷ lệ đơn vị chính cho trục ngày. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Biểu thị tỷ lệ đơn vị chính cho trục ngày. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Biểu thị tỷ lệ đơn vị chính cho trục ngày. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Xác định đơn vị thời gian nhỏ nhất được đại diện trên trục ngày. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Xác định đơn vị thời gian nhỏ nhất được đại diện trên trục ngày. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Biểu thị định dạng lưới phụ trên trục biểu đồ. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Biểu thị định dạng lưới chính trên trục biểu đồ. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Để ẩn lưới phụ, đặt MinorGridLinesFormat.Line.FillFormat.FillType thành FillType.NoFill. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Để ẩn lưới chính, đặt MajorGridLinesFormat.Line.FillFormat.FillType thành FillType.NoFill. |
| [getFormat()](#getFormat--) | Biểu thị định dạng của trục. |
| [getTextFormat()](#getTextFormat--) | Biểu thị định dạng của văn bản. |
| [getTitle()](#getTitle--) | Lấy tiêu đề của trục. |
| [getCrossType()](#getCrossType--) | Biểu thị CrossType trên trục được chỉ định nơi trục khác cắt qua. |
| [setCrossType(int value)](#setCrossType-int-) | Biểu thị CrossType trên trục được chỉ định nơi trục khác cắt qua. |
| [getPosition()](#getPosition--) | Biểu thị vị trí của trục. |
| [setPosition(int value)](#setPosition-int-) | Biểu thị vị trí của trục. |
| [hasTitle()](#hasTitle--) | Xác định liệu trục có tiêu đề hiển thị hay không. |
| [setTitle(boolean value)](#setTitle-boolean-) | Xác định liệu trục có tiêu đề hiển thị hay không. |
| [getNumberFormat()](#getNumberFormat--) | Biểu thị chuỗi định dạng cho Nhãn Trục. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Biểu thị chuỗi định dạng cho Nhãn Trục. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Cho biết định dạng có được liên kết với dữ liệu nguồn hay không. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Cho biết định dạng có được liên kết với dữ liệu nguồn hay không. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Biểu thị góc quay của nhãn tick. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Biểu thị góc quay của nhãn tick. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Xác định số lượng nhãn tick cần bỏ qua giữa các nhãn được vẽ. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Xác định số lượng nhãn tick cần bỏ qua giữa các nhãn được vẽ. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Xác định giá trị khoảng cách tự động cho nhãn tick. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Xác định giá trị khoảng cách tự động cho nhãn tick. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Xác định số lượng dấu tick sẽ bị bỏ qua trước khi dấu tiếp theo được vẽ. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Xác định số lượng dấu tick sẽ bị bỏ qua trước khi dấu tiếp theo được vẽ. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Xác định giá trị khoảng cách tự động cho dấu tick. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Xác định giá trị khoảng cách tự động cho dấu tick. |
| [getLabelOffset()](#getLabelOffset--) | Xác định khoảng cách của nhãn so với trục. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Xác định khoảng cách của nhãn so với trục. |
| [getAggregationType()](#getAggregationType--) | Biểu thị loại tổng hợp của trục danh mục (phân nhóm). |
| [setAggregationType(int value)](#setAggregationType-int-) | Biểu thị loại tổng hợp của trục danh mục (phân nhóm). |
| [getBinWidth()](#getBinWidth--) | Xác định độ rộng bin khi giá trị thuộc tính AggregationType được đặt thành AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Xác định độ rộng bin khi giá trị thuộc tính AggregationType được đặt thành AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Xác định số lượng bin khi giá trị thuộc tính AggregationType được đặt thành AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Xác định số lượng bin khi giá trị thuộc tính AggregationType được đặt thành AxisAggregationType.ByNumberOfBins. |
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
| [getSlide()](#getSlide--) | Trả về slide cha của FillFormat. |
| [getPresentation()](#getPresentation--) | Trả về bản trình bày cha của FillFormat. |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Trả về biểu đồ cha. Chỉ đọc [IChart](../../com.aspose.slides/ichart).

**Trả về:**
[IChart](../../com.aspose.slides/ichart)

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```

Biểu thị nếu trục giá trị cắt trục danh mục giữa các danh mục. Thuộc tính này chỉ áp dụng cho trục danh mục và không áp dụng cho biểu đồ 3-D. Đọc/ghi boolean.

**Trả về:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

Biểu thị nếu trục giá trị cắt trục danh mục giữa các danh mục. Thuộc tính này chỉ áp dụng cho trục danh mục và không áp dụng cho biểu đồ 3-D. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```

Xác định loại trục danh mục. Đọc/ghi [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Trả về:**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```

Xác định loại trục danh mục. Đọc/ghi [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public final void setCategoryAxisTypeAutomatically()
```

Đặt thuộc tính IAxis.CategoryAxisType với một giá trị được tự động xác định dựa trên dữ liệu trục.

### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```

Biểu thị điểm trên trục mà trục vuông góc cắt qua. Đọc/ghi float.

**Trả về:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

Biểu thị điểm trên trục mà trục vuông góc cắt qua. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```

Xác định giá trị tỷ lệ của các đơn vị hiển thị cho trục giá trị. Đọc/ghi [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Trả về:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```

Xác định giá trị tỷ lệ của các đơn vị hiển thị cho trục giá trị. Đọc/ghi [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```

Xác định giá trị tối đa thực tế trên trục. Gọi phương thức IChart.ValidateChartLayout() trước đó để lấy giá trị thực tế.

**Trả về:**
double

### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

Xác định giá trị tối thiểu thực tế trên trục. Gọi phương thức IChart.ValidateChartLayout() trước đó để lấy giá trị thực tế.

**Trả về:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

Xác định đơn vị chính thực tế của trục. Gọi phương thức IChart.ValidateChartLayout() trước đó để lấy giá trị thực tế.

**Trả về:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

Xác định đơn vị phụ thực tế của trục. Gọi phương thức IChart.ValidateChartLayout() trước đó để lấy giá trị thực tế.

**Trả về:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

Xác định tỷ lệ đơn vị chính thực tế của trục. Gọi phương thức IChart.ValidateChartLayout() trước đó để lấy giá trị thực tế.

**Trả về:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

Xác định tỷ lệ đơn vị phụ thực tế của trục. Gọi phương thức IChart.ValidateChartLayout() trước đó để lấy giá trị thực tế.

**Trả về:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

Cho biết giá trị tối đa có được tự động gán hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

Cho biết giá trị tối đa có được tự động gán hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

Biểu thị giá trị tối đa trên trục giá trị. Đọc/ghi double.

**Trả về:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

Biểu thị giá trị tối đa trên trục giá trị. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

Biểu thị các đơn vị phụ cho trục ngày hoặc giá trị. Đọc/ghi double.

**Trả về:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```

Biểu thị các đơn vị phụ cho trục ngày hoặc giá trị. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```

Cho biết đơn vị phụ của trục có được tự động gán hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```

Cho biết đơn vị phụ của trục có được tự động gán hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```

Biểu thị các đơn vị chính cho trục ngày hoặc giá trị. Đọc/ghi double.

**Trả về:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```

Biểu thị các đơn vị chính cho trục ngày hoặc giá trị. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```

Cho biết đơn vị chính của trục có được tự động gán hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```

Cho biết đơn vị chính của trục có được tự động gán hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```

Cho biết giá trị tối thiểu có được tự động gán hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```

Cho biết giá trị tối thiểu có được tự động gán hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```

Biểu thị giá trị tối thiểu trên trục giá trị. Đọc/ghi double.

**Trả về:**
double

### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```

Biểu thị giá trị tối thiểu trên trục giá trị. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```

Biểu thị nếu loại tỷ lệ trục giá trị là logarit hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```

Biểu thị nếu loại tỷ lệ trục giá trị là logarit hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```

Biểu thị cơ số logarit. Giá trị mặc định là 10. Đọc/ghi double.

**Trả về:**
double

### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```

Biểu thị cơ số logarit. Giá trị mặc định là 10. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public final boolean isPlotOrderReversed()
```

Biểu thị nếu MS PowerPoint vẽ các điểm dữ liệu từ cuối lên đầu. Đọc/ghi boolean.

**Trả về:**
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```

Biểu thị nếu MS PowerPoint vẽ các điểm dữ liệu từ cuối lên đầu. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Biểu thị nếu trục hiển thị. Đọc/ghi boolean.

**Trả về:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

Biểu thị nếu trục hiển thị. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```

Biểu thị loại dấu tick chính cho trục được chỉ định. Đọc/ghi [TickMarkType](../../com.aspose.slides/tickmarktype).

**Trả về:**
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```

Biểu thị loại dấu tick chính cho trục được chỉ định. Đọc/ghi [TickMarkType](../../com.aspose.slides/tickmarktype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```

Biểu thị loại dấu tick phụ cho trục được chỉ định. Đọc/ghi [TickMarkType](../../com.aspose.slides/tickmarktype).

**Trả về:**
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```

Biểu thị loại dấu tick phụ cho trục được chỉ định. Đọc/ghi [TickMarkType](../../com.aspose.slides/tickmarktype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```

Biểu thị vị trí của nhãn tick trên trục được chỉ định. Đọc/ghi [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Trả về:**
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```

Biểu thị vị trí của nhãn tick trên trục được chỉ định. Đọc/ghi [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```

Biểu thị tỷ lệ đơn vị chính cho trục ngày. Đọc/ghi [TimeUnitType](../../com.aspose.slides/timeunittype).

**Trả về:**
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```

Biểu thị tỷ lệ đơn vị chính cho trục ngày. Đọc/ghi [TimeUnitType](../../com.aspose.slides/timeunittype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```

Biểu thị tỷ lệ đơn vị chính cho trục ngày. Đọc/ghi [TimeUnitType](../../com.aspose.slides/timeunittype).

**Trả về:**
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```

Biểu thị tỷ lệ đơn vị chính cho trục ngày. Đọc/ghi [TimeUnitType](../../com.aspose.slides/timeunittype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```

Xác định đơn vị thời gian nhỏ nhất được đại diện trên trục ngày. Đọc/ghi [TimeUnitType](../../com.aspose.slides/timeunittype).

**Trả về:**
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public  int  int  int  public  Int  setBaseUnitScale(int value) 
```

Xác định đơn vị thời gian nhỏ nhất được đại diện trên trục ngày. Đọc/ghi [TimeUnitType](../../com.aspose.slides/timeunittype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```

Biểu thị định dạng lưới phụ trên trục biểu đồ. Chỉ đọc [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Trả về:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMajorGridLinesFormat()
```

Biểu thị định dạng lưới chính trên trục biểu đồ. Chỉ đọc [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Trả về:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```

Để ẩn lưới phụ, đặt MinorGridLinesFormat.Line.FillFormat.FillType thành FillType.NoFill. Chỉ đọc boolean.

**Trả về:**
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```

Để ẩn lưới chính, đặt MajorGridLinesFormat.Line.FillFormat.FillType thành FillType.NoFill. Chỉ đọc boolean.

**Trả về:**
boolean

### getFormat() {#getFormat--}
```
public final IAxisFormat getFormat()
```

Biểu thị định dạng của trục. Chỉ đọc [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Trả về:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Biểu thị định dạng của văn bản. Chỉ đọc [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Trả về:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getTitle() {#getTitle--}
```
public final IChartTitle getTitle()
```

Lấy tiêu đề của trục. Chỉ đọc [IChartTitle](../../com.aspose.slides/icharttitle).

**Trả về:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```

Biểu thị CrossType trên trục được chỉ định nơi trục khác cắt qua. Đọc/ghi [CrossesType](../../com.aspose.slides/crossestype).

**Trả về:**
int

### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```

Biểu thị CrossType trên trục được chỉ định nơi trục khác cắt qua. Đọc/ghi [CrossesType](../../com.aspose.slides/crossestype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```

Biểu thị vị trí của trục. Đọc/ghi [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Trả về:**
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Biểu thị vị trí của trục. Đọc/ghi [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

Xác định liệu trục có tiêu đề hiển thị hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

Xác định liệu trục có tiêu đề hiển thị hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

Biểu thị chuỗi định dạng cho Nhãn Trục. Đọc/ghi String.

**Trả về:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

Biểu thị chuỗi định dạng cho Nhãn Trục. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

Cho biết định dạng có được liên kết với dữ liệu nguồn hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Cho biết định dạng có được liên kết với dữ liệu nguồn hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```

Biểu thị góc quay của nhãn tick. Đọc/ghi float.

**Trả về:**
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```

Biểu thị góc quay của nhãn tick. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```

Xác định số lượng nhãn tick cần bỏ qua giữa các nhãn được vẽ. Áp dụng cho trục danh mục hoặc trục series. Đọc/ghi long.

**Trả về:**
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```

Xác định số lượng nhãn tick cần bỏ qua giữa các nhãn được vẽ. Áp dụng cho trục danh mục hoặc trục series. Đọc/ghi long.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```

Xác định giá trị khoảng cách tự động cho nhãn tick. Nếu false: sử dụng thuộc tính TickLabelSpacing. Đọc/ghi boolean.

**Trả về:**
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```

Xác định giá trị khoảng cách tự động cho nhãn tick. Nếu false: sử dụng thuộc tính TickLabelSpacing. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```

Xác định số lượng dấu tick sẽ bị bỏ qua trước khi dấu tiếp theo được vẽ. Áp dụng cho trục danh mục hoặc trục series. Đọc/ghi int.

**Trả về:**
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```

Xác định số lượng dấu tick sẽ bị bỏ qua trước khi dấu tiếp theo được vẽ. Áp dụng cho trục danh mục hoặc trục series. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```

Xác định giá trị khoảng cách tự động cho dấu tick. Nếu false: sử dụng thuộc tính TickMarksSpacing. Đọc/ghi boolean.

**Trả về:**
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```

Xác định giá trị khoảng cách tự động cho dấu tick. Nếu false: sử dụng thuộc tính TickMarksSpacing. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```

Xác định khoảng cách của nhãn so với trục. Áp dụng cho trục danh mục hoặc trục ngày. Giá trị phải nằm trong khoảng 0% đến 1000%. Đọc/ghi int.

**Trả về:**
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```

Xác định khoảng cách của nhãn so với trục. Áp dụng cho trục danh mục hoặc trục ngày. Giá trị phải nằm trong khoảng 0% đến 1000%. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```

Biểu thị loại tổng hợp của trục danh mục (phân nhóm). Áp dụng cho danh mục. Chỉ dùng với series Histogram hoặc HistogramPareto.

**Trả về:**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```

Biểu thị loại tổng hợp của trục danh mục (phân nhóm). Áp dụng cho danh mục. Chỉ dùng với series Histogram hoặc HistogramPareto.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```

Xác định độ rộng bin khi giá trị thuộc tính AggregationType được đặt thành AxisAggregationType.ByBinWidth. Áp dụng cho trục danh mục. Chỉ dùng với series Histogram hoặc HistogramPareto.

**Trả về:**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```

Xác định độ rộng bin khi giá trị thuộc tính AggregationType được đặt thành AxisAggregationType.ByBinWidth. Áp dụng cho trục danh mục. Chỉ dùng với series Histogram hoặc HistogramPareto.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```

Xác định số lượng bin khi giá trị thuộc tính AggregationType được đặt thành AxisAggregationType.ByNumberOfBins. Áp dụng cho trục danh mục. Chỉ dùng với series Histogram hoặc HistogramPareto.

**Trả về:**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```

Xác định số lượng bin khi giá trị thuộc tính AggregationType được đặt thành AxisAggregationType.ByNumberOfBins. Áp dụng cho trục danh mục. Chỉ dùng với series Histogram hoặc HistogramPareto.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```

Xác định nếu bin tràn được áp dụng. Sử dụng IsAutomaticOverflowBin và OverflowBin để điều chỉnh giá trị bin tràn.

**Trả về:**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```

Xác định nếu bin tràn được áp dụng. Sử dụng IsAutomaticOverflowBin và OverflowBin để điều chỉnh giá trị bin tràn.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```

Xác định giá trị bin tràn tự động. Nếu false: sử dụng thuộc tính OverflowBin.

**Trả về:**
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```

Xác định giá trị bin tràn tự động. Nếu false: sử dụng thuộc tính OverflowBin.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```

Xác định giá trị bin tràn tùy chỉnh. Áp dụng khi thuộc tính IsAutomaticOverflowBin được đặt thành false và thuộc tính IsOverflowBin bằng true.

**Trả về:**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```

Xác định giá trị bin tràn tùy chỉnh. Áp dụng khi thuộc tính IsAutomaticOverflowBin được đặt thành false và thuộc tính IsOverflowBin bằng true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```

Xác định nếu bin thiếu được áp dụng. Sử dụng IsAutomaticUnderflowBin và UnderflowBin để điều chỉnh giá trị bin thiếu.

**Trả về:**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```

Xác định nếu bin thiếu được áp dụng. Sử dụng IsAutomaticUnderflowBin và UnderflowBin để điều chỉnh giá trị bin thiếu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```

Xác định giá trị bin thiếu tự động. Nếu false: sử dụng thuộc tính UnderflowBin.

**Trả về:**
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```

Xác định giá trị bin thiếu tự động. Nếu false: sử dụng thuộc tính UnderflowBin.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```

Xác định giá trị bin thiếu tùy chỉnh. Áp dụng khi thuộc tính IsAutomaticUnderflowBin được đặt thành false và thuộc tính IsUnderflowBin bằng true.

**Trả về:**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```

Xác định giá trị bin thiếu tùy chỉnh. Áp dụng khi thuộc tính IsAutomaticUnderflowBin được đặt thành false và thuộc tính IsUnderflowBin bằng true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Trả về slide cha của FillFormat. Chỉ đọc [BaseSlide](../../com.aspose.slides/baseslide).

**Trả về:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Trả về bản trình bày cha của FillFormat. Chỉ đọc [IPresentation](../../com.aspose.slides/ipresentation).

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation)