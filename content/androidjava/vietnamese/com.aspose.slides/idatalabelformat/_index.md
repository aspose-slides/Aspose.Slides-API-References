---
title: IDataLabelFormat
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn các tùy chọn định dạng cho DataLabel.
type: docs
url: /vi/com.aspose.slides/idatalabelformat/
---
**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

Biểu diễn các tùy chọn định dạng cho DataLabel.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Đọc/ghi boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Đọc/ghi boolean. |
| [getNumberFormat()](#getNumberFormat--) | Biểu diễn chuỗi định dạng cho đối tượng DataLabels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Biểu diễn chuỗi định dạng cho đối tượng DataLabels. |
| [getFormat()](#getFormat--) | Biểu diễn định dạng của nhãn dữ liệu. |
| [getPosition()](#getPosition--) | Biểu diễn vị trí của nhãn dữ liệu. |
| [setPosition(int value)](#setPosition-int-) | Biểu diễn vị trí của nhãn dữ liệu. |
| [getShowLegendKey()](#getShowLegendKey--) | Biểu diễn hành vi hiển thị khóa chú giải nhãn dữ liệu của biểu đồ cụ thể. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Biểu diễn hành vi hiển thị khóa chú giải nhãn dữ liệu của biểu đồ cụ thể. |
| [getShowValue()](#getShowValue--) | Biểu diễn hành vi hiển thị giá trị phần trăm nhãn dữ liệu của biểu đồ cụ thể. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Biểu diễn hành vi hiển thị giá trị phần trăm nhãn dữ liệu của biểu đồ cụ thể. |
| [getShowCategoryName()](#getShowCategoryName--) | Biểu diễn hành vi hiển thị tên danh mục nhãn dữ liệu của biểu đồ cụ thể. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Biểu diễn hành vi hiển thị tên danh mục nhãn dữ liệu của biểu đồ cụ thể. |
| [getShowSeriesName()](#getShowSeriesName--) | Trả về hoặc đặt một Boolean để chỉ ra hành vi hiển thị tên chuỗi cho nhãn dữ liệu trên biểu đồ. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Trả về hoặc đặt một Boolean để chỉ ra hành vi hiển thị tên chuỗi cho nhãn dữ liệu trên biểu đồ. |
| [getShowPercentage()](#getShowPercentage--) | Biểu diễn hành vi hiển thị giá trị phần trăm nhãn dữ liệu của biểu đồ cụ thể. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Biểu diễn hành vi hiển thị giá trị phần trăm nhãn dữ liệu của biểu đồ cụ thể. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Biểu diễn hành vi hiển thị giá trị kích thước bong bóng nhãn dữ liệu của biểu đồ cụ thể. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Biểu diễn hành vi hiển thị giá trị kích thước bong bóng nhãn dữ liệu của biểu đồ cụ thể. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Biểu diễn hành vi hiển thị các đường dẫn nhãn dữ liệu của biểu đồ cụ thể. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Biểu diễn hành vi hiển thị các đường dẫn nhãn dữ liệu của biểu đồ cụ thể. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Xác định liệu nhãn dữ liệu của biểu đồ cụ thể sẽ được hiển thị dưới dạng lời gọi dữ liệu hay là nhãn dữ liệu. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Xác định liệu nhãn dữ liệu của biểu đồ cụ thể sẽ được hiển thị dưới dạng lời gọi dữ liệu hay là nhãn dữ liệu. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Biểu diễn hành vi hiển thị giá trị ô nhãn dữ liệu của biểu đồ cụ thể. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Biểu diễn hành vi hiển thị giá trị ô nhãn dữ liệu của biểu đồ cụ thể. |
| [getSeparator()](#getSeparator--) | Đặt hoặc trả về một Variant đại diện cho dấu phân cách được sử dụng cho các nhãn dữ liệu trên biểu đồ. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Đặt hoặc trả về một Variant đại diện cho dấu phân cách được sử dụng cho các nhãn dữ liệu trên biểu đồ. |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Đọc/ghi boolean.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu, thì thuộc tính này sẽ lấy hoặc đặt giá trị mặc định của thuộc tính IsNumberFormatLinkedToSource cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính IsNumberFormatLinkedToSource của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" sẽ khiến tất cả DataLabels.get\_Item(i).isNumberFormatLinkedToSource() bằng val).

**Trả về:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Đọc/ghi boolean.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu, thì thuộc tính này sẽ lấy hoặc đặt giá trị mặc định của thuộc tính IsNumberFormatLinkedToSource cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính IsNumberFormatLinkedToSource của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" sẽ khiến tất cả DataLabels.get\_Item(i).isNumberFormatLinkedToSource() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Biểu diễn chuỗi định dạng cho đối tượng DataLabels. Đọc/ghi String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu, thì thuộc tính này sẽ lấy hoặc đặt giá trị mặc định của thuộc tính NumberFormat cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Khi thuộc tính này được đặt bằng một giá trị, giá trị đó cũng được đặt cho thuộc tính NumberFormat của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" sẽ khiến tất cả DataLabels.get\_Item(i).getNumberFormat() bằng val).

**Trả về:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Biểu diễn chuỗi định dạng cho đối tượng DataLabels. Đọc/ghi String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu, thì thuộc tính này sẽ lấy hoặc đặt giá trị mặc định của thuộc tính NumberFormat cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Khi thuộc tính này được đặt bằng một giá trị, giá trị đó cũng được đặt cho thuộc tính NumberFormat của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" sẽ khiến tất cả DataLabels.get\_Item(i).getNumberFormat() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Biểu diễn định dạng của nhãn dữ liệu. Chỉ đọc [IFormat](../../com.aspose.slides/iformat).

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này biểu diễn định dạng mặc định cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection.

**Trả về:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Biểu diễn vị trí của nhãn dữ liệu. Đọc/ghi [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này sẽ lấy hoặc đặt giá trị mặc định của thuộc tính Position cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Biểu diễn vị trí cho các đối tượng DataLabel. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính Position của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setPosition(val)" sẽ khiến tất cả DataLabels.get\_Item(i).getPosition() bằng val).

**Trả về:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Biểu diễn vị trí của nhãn dữ liệu. Đọc/ghi [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này sẽ lấy hoặc đặt giá trị mặc định của thuộc tính Position cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Biểu diễn vị trí cho các đối tượng DataLabel. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính Position của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setPosition(val)" sẽ khiến tất cả DataLabels.get\_Item(i).getPosition() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

Biểu diễn hành vi hiển thị khóa chú giải nhãn dữ liệu của biểu đồ cụ thể. True nếu khóa chú giải nhãn dữ liệu hiển thị. Đọc/ghi boolean.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này sẽ lấy hoặc đặt giá trị mặc định của thuộc tính ShowLegendKey cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLegendKey của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" sẽ khiến tất cả DataLabels.get\_Item(i).getShowLegendKey() bằng val).

**Trả về:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

Biểu diễn hành vi hiển thị khóa chú giải nhãn dữ liệu của biểu đồ cụ thể. True nếu khóa chú giải nhãn dữ liệu hiển thị. Đọc/ghi boolean.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này sẽ lấy hoặc đặt giá trị mặc định của thuộc tính ShowLegendKey cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLegendKey của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" sẽ khiến tất cả DataLabels.get\_Item(i).getShowLegendKey() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

Biểu diễn hành vi hiển thị giá trị phần trăm nhãn dữ liệu của biểu đồ cụ thể. True hiển thị giá trị phần trăm. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này sẽ lấy hoặc đặt giá trị mặc định của thuộc tính ShowValue cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowValue của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" sẽ khiến tất cả DataLabels.get\_Item(i).getShowValue() bằng val).

**Trả về:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

Biểu diễn hành vi hiển thị giá trị phần trăm nhãn dữ liệu của biểu đồ cụ thể. True hiển thị giá trị phần trăm. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này sẽ lấy hoặc đặt giá trị mặc định của thuộc tính ShowValue cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowValue của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" sẽ khiến tất cả DataLabels.get\_Item(i).getShowValue() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

Biểu diễn hành vi hiển thị tên danh mục nhãn dữ liệu của biểu đồ cụ thể. True để hiển thị tên danh mục cho các nhãn dữ liệu trên biểu đồ. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này sẽ lấy hoặc đặt giá trị mặc định của thuộc tính ShowCategoryName cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowCategoryName của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" sẽ khiến tất cả DataLabels.get\_Item(i).getShowCategoryName() bằng val).

**Trả về:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

Biểu diễn hành vi hiển thị tên danh mục nhãn dữ liệu của biểu đồ cụ thể. True để hiển thị tên danh mục cho các nhãn dữ liệu trên biểu đồ. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này sẽ lấy hoặc đặt giá trị mặc định của thuộc tính ShowCategoryName cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowCategoryName của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" sẽ khiến tất cả DataLabels.get\_Item(i).getShowCategoryName() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

Trả về hoặc đặt một Boolean để chỉ ra hành vi hiển thị tên chuỗi cho nhãn dữ liệu trên biểu đồ. True để hiển thị tên chuỗi. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này sẽ lấy hoặc đặt giá trị mặc định của thuộc tính ShowSeriesName cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowSeriesName của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" sẽ khiến tất cả DataLabels.get\_Item(i).getShowSeriesName() bằng val).

**Trả về:**
boolean

### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

Trả về hoặc đặt một Boolean để chỉ ra hành vi hiển thị tên chuỗi cho nhãn dữ liệu trên biểu đồ. True để hiển thị tên chuỗi. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này sẽ lấy hoặc đặt giá trị mặc định của thuộc tính ShowSeriesName cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowSeriesName của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" sẽ khiến tất cả DataLabels.get\_Item(i).getShowSeriesName() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

Biểu diễn hành vi hiển thị giá trị phần trăm nhãn dữ liệu của biểu đồ cụ thể. True hiển thị giá trị phần trăm. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này sẽ lấy hoặc đặt giá trị mặc định của thuộc tính ShowPercentage cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowPercentage của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" sẽ khiến tất cả DataLabels.get\_Item(i).getShowPercentage() bằng val).

**Trả về:**
boolean

### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

Biểu diễn hành vi hiển thị giá trị phần trăm nhãn dữ liệu của biểu đồ cụ thể. True hiển thị giá trị phần trăm. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này sẽ lấy hoặc đặt giá trị mặc định của thuộc tính ShowPercentage cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowPercentage của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" sẽ khiến tất cả DataLabels.get\_Item(i).getShowPercentage() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

Biểu diễn hành vi hiển thị giá trị kích thước bong bóng nhãn dữ liệu của biểu đồ cụ thể. True hiển thị giá trị kích thước bong bóng. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này sẽ lấy hoặc đặt giá trị mặc định của thuộc tính ShowBubbleSize cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowBubbleSize của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" sẽ khiến tất cả DataLabels.get\_Item(i).getShowBubbleSize() bằng val).

**Trả về:**
boolean

### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

Biểu diễn hành vi hiển thị giá trị kích thước bong bóng nhãn dữ liệu của biểu đồ cụ thể. True hiển thị giá trị kích thước bong bóng. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này sẽ lấy hoặc đặt giá trị mặc định của thuộc tính ShowBubbleSize cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowBubbleSize của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" sẽ khiến tất cả DataLabels.get\_Item(i).getShowBubbleSize() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

Biểu diễn hành vi hiển thị các đường dẫn nhãn dữ liệu của biểu đồ cụ thể. True hiển thị các đường dẫn. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này sẽ lấy hoặc đặt giá trị mặc định của thuộc tính ShowLeaderLines cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLeaderLines của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" sẽ khiến tất cả DataLabels.get\_Item(i).getShowLeaderLines() bằng val).

**Trả về:**
boolean

### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

Biểu diễn hành vi hiển thị các đường dẫn nhãn dữ liệu của biểu đồ cụ thể. True hiển thị các đường dẫn. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này sẽ lấy hoặc đặt giá trị mặc định của thuộc tính ShowLeaderLines cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLeaderLines của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" sẽ khiến tất cả DataLabels.get\_Item(i).getShowLeaderLines() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```

Xác định liệu nhãn dữ liệu của biểu đồ cụ thể sẽ được hiển thị dưới dạng lời gọi dữ liệu hay là nhãn dữ liệu.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này sẽ lấy hoặc đặt giá trị mặc định của thuộc tính ShowLabelAsDataCallout cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLabelAsDataCallout của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" sẽ khiến tất cả DataLabels.get\_Item(i).getShowLabelAsDataCallout() bằng val).

**Trả về:**
boolean

### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

Xác định liệu nhãn dữ liệu của biểu đồ cụ thể sẽ được hiển thị dưới dạng lời gọi dữ liệu hay là nhãn dữ liệu.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này sẽ lấy hoặc đặt giá trị mặc định của thuộc tính ShowLabelAsDataCallout cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLabelAsDataCallout của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" sẽ khiến tất cả DataLabels.get\_Item(i).getShowLabelAsDataCallout() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

Biểu diễn hành vi hiển thị giá trị ô nhãn dữ liệu của biểu đồ cụ thể. True hiển thị giá trị ô. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này sẽ lấy hoặc đặt giá trị mặc định của thuộc tính ShowLabelValueFromCell cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLabelValueFromCell của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" sẽ khiến tất cả DataLabels.get\_Item(i).getShowLabelValueFromCell() bằng val).

**Trả về:**
boolean

### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

Biểu diễn hành vi hiển thị giá trị ô nhãn dữ liệu của biểu đồ cụ thể. True hiển thị giá trị ô. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này sẽ lấy hoặc đặt giá trị mặc định của thuộc tính ShowLabelValueFromCell cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLabelValueFromCell của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" sẽ khiến tất cả DataLabels.get\_Item(i).getShowLabelValueFromCell() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

Đặt hoặc trả về một Variant đại diện cho dấu phân cách được sử dụng cho các nhãn dữ liệu trên biểu đồ. Đọc/ghi String.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này sẽ lấy hoặc đặt giá trị mặc định của thuộc tính Separator cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính Separator của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" sẽ khiến tất cả DataLabels.get\_Item(i).getSeparator() bằng val).

**Trả về:**
java.lang.String

### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```

Đặt hoặc trả về một Variant đại diện cho dấu phân cách được sử dụng cho các nhãn dữ liệu trên biểu đồ. Đọc/ghi String.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này sẽ lấy hoặc đặt giá trị mặc định của thuộc tính Separator cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính Separator của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" sẽ khiến tất cả DataLabels.get\_Item(i).getSeparator() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |