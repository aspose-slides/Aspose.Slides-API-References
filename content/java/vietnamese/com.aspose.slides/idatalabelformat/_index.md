---
title: IDataLabelFormat
second_title: Tham khảo API Aspose.Slides cho Java
description: Đại diện cho các tùy chọn định dạng cho DataLabel.
type: docs
url: /vi/com.aspose.slides/idatalabelformat/
---
**Tất cả các giao diện được triển khai:**
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
| [getShowLegendKey()](#getShowLegendKey--) | Biểu diễn hành vi hiển thị khóa chú giải nhãn dữ liệu của biểu đồ được chỉ định. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Biểu diễn hành vi hiển thị khóa chú giải nhãn dữ liệu của biểu đồ được chỉ định. |
| [getShowValue()](#getShowValue--) | Biểu diễn hành vi hiển thị giá trị phần trăm nhãn dữ liệu của biểu đồ được chỉ định. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Biểu diễn hành vi hiển thị giá trị phần trăm nhãn dữ liệu của biểu đồ được chỉ định. |
| [getShowCategoryName()](#getShowCategoryName--) | Biểu diễn hành vi hiển thị tên danh mục nhãn dữ liệu của biểu đồ được chỉ định. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Biểu diễn hành vi hiển thị tên danh mục nhãn dữ liệu của biểu đồ được chỉ định. |
| [getShowSeriesName()](#getShowSeriesName--) | Trả về hoặc đặt một Boolean để chỉ ra hành vi hiển thị tên chuỗi cho nhãn dữ liệu trên biểu đồ. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Trả về hoặc đặt một Boolean để chỉ ra hành vi hiển thị tên chuỗi cho nhãn dữ liệu trên biểu đồ. |
| [getShowPercentage()](#getShowPercentage--) | Biểu diễn hành vi hiển thị giá trị phần trăm nhãn dữ liệu của biểu đồ được chỉ định. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Biểu diễn hành vi hiển thị giá trị phần trăm nhãn dữ liệu của biểu đồ được chỉ định. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Biểu diễn hành vi hiển thị giá trị kích thước bong bóng của nhãn dữ liệu trên biểu đồ được chỉ định. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Biểu diễn hành vi hiển thị giá trị kích thước bong bóng của nhãn dữ liệu trên biểu đồ được chỉ định. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Biểu diễn hành vi hiển thị các đường dẫn của nhãn dữ liệu trên biểu đồ được chỉ định. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Biểu diễn hành vi hiển thị các đường dẫn của nhãn dữ liệu trên biểu đồ được chỉ định. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Xác định nhãn dữ liệu của biểu đồ được chỉ định sẽ được hiển thị dưới dạng lời gọi dữ liệu hay là nhãn dữ liệu. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Xác định nhãn dữ liệu của biểu đồ được chỉ định sẽ được hiển thị dưới dạng lời gọi dữ liệu hay là nhãn dữ liệu. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Biểu diễn hành vi hiển thị giá trị ô của nhãn dữ liệu trên biểu đồ được chỉ định. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Biểu diễn hành vi hiển thị giá trị ô của nhãn dữ liệu trên biểu đồ được chỉ định. |
| [getSeparator()](#getSeparator--) | Đặt hoặc trả về một Variant đại diện cho ký tự phân tách được sử dụng cho nhãn dữ liệu trên biểu đồ. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Đặt hoặc trả về một Variant đại diện cho ký tự phân tách được sử dụng cho nhãn dữ liệu trên biểu đồ. |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Đọc/ghi boolean.

--------------------

Nếu cha của đối tượng DataLabelFormat này là một bộ sưu tập DataLabelCollection chứa các nhãn dữ liệu thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính IsNumberFormatLinkedToSource cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính IsNumberFormatLinkedToSource của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" gây ra tất cả DataLabels.get_Item(i).isNumberFormatLinkedToSource() bằng val).

**Trả về:**  
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Đọc/ghi boolean.

--------------------

Nếu cha của đối tượng DataLabelFormat này là một bộ sưu tập DataLabelCollection chứa các nhãn dữ liệu thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính IsNumberFormatLinkedToSource cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính IsNumberFormatLinkedToSource của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" gây ra tất cả DataLabels.get_Item(i).isNumberFormatLinkedToSource() bằng val).

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

Nếu cha của đối tượng DataLabelFormat này là một bộ sưu tập DataLabelCollection chứa các nhãn dữ liệu, thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính NumberFormat cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Khi thuộc tính này được đặt bằng một giá trị, giá trị đó cũng được đặt cho thuộc tính NumberFormat của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" gây ra tất cả DataLabels.get_Item(i).getNumberFormat() bằng val).

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

Nếu cha của đối tượng DataLabelFormat này là một bộ sưu tập DataLabelCollection chứa các nhãn dữ liệu, thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính NumberFormat cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Khi thuộc tính này được đặt bằng một giá trị, giá trị đó cũng được đặt cho thuộc tính NumberFormat của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" gây ra tất cả DataLabels.get_Item(i).getNumberFormat() bằng val).

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

Nếu cha của đối tượng DataLabelFormat này là một bộ sưu tập DataLabelCollection chứa các nhãn dữ liệu thì thuộc tính này biểu diễn định dạng mặc định cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection.

**Trả về:**  
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Biểu diễn vị trí của nhãn dữ liệu. Đọc/ghi [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Nếu cha của đối tượng DataLabelFormat này là một bộ sưu tập DataLabelCollection chứa các nhãn dữ liệu thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính Position cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Biểu diễn vị trí cho các đối tượng DataLabel. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính Position của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setPosition(val)" gây ra tất cả DataLabels.get_Item(i).getPosition() bằng val).

**Trả về:**  
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Biểu diễn vị trí của nhãn dữ liệu. Đọc/ghi [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Nếu cha của đối tượng DataLabelFormat này là một bộ sưu tập DataLabelCollection chứa các nhãn dữ liệu thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính Position cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Biểu diễn vị trí cho các đối tượng DataLabel. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính Position của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setPosition(val)" gây ra tất cả DataLabels.get_Item(i).getPosition() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

Biểu diễn hành vi hiển thị khóa chú giải nhãn dữ liệu của biểu đồ được chỉ định. True nếu khóa chú giải nhãn dữ liệu hiển thị. Đọc/ghi boolean.

--------------------

Nếu cha của đối tượng DataLabelFormat này là một bộ sưu tập DataLabelCollection chứa các nhãn dữ liệu thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowLegendKey cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLegendKey của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" gây ra tất cả DataLabels.get_Item(i).getShowLegendKey() bằng val).

**Trả về:**  
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

Biểu diễn hành vi hiển thị khóa chú giải nhãn dữ liệu của biểu đồ được chỉ định. True nếu khóa chú giải nhãn dữ liệu hiển thị. Đọc/ghi boolean.

--------------------

Nếu cha của đối tượng DataLabelFormat này là một bộ sưu tập DataLabelCollection chứa các nhãn dữ liệu thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowLegendKey cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLegendKey của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" gây ra tất cả DataLabels.get_Item(i).getShowLegendKey() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

Biểu diễn hành vi hiển thị giá trị phần trăm của nhãn dữ liệu trên biểu đồ được chỉ định. True hiển thị giá trị phần trăm. False ẩn. Đọc/ghi boolean.

--------------------

Nếu cha của đối tượng DataLabelFormat này là một bộ sưu tập DataLabelCollection chứa các nhãn dữ liệu thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowValue cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowValue của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" gây ra tất cả DataLabels.get_Item(i).getShowValue() bằng val).

**Trả về:**  
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

Biểu diễn hành vi hiển thị giá trị phần trăm của nhãn dữ liệu trên biểu đồ được chỉ định. True hiển thị giá trị phần trăm. False ẩn. Đọc/ghi boolean.

--------------------

Nếu cha của đối tượng DataLabelFormat này là một bộ sưu tập DataLabelCollection chứa các nhãn dữ liệu thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowValue cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowValue của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" gây ra tất cả DataLabels.get_Item(i).getShowValue() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

Biểu diễn hành vi hiển thị tên danh mục nhãn dữ liệu của biểu đồ được chỉ định. True để hiển thị tên danh mục cho các nhãn dữ liệu trên biểu đồ. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu cha của đối tượng DataLabelFormat này là một bộ sưu tập DataLabelCollection chứa các nhãn dữ liệu thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowCategoryName cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowCategoryName của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" gây ra tất cả DataLabels.get_Item(i).getShowCategoryName() bằng val).

**Trả về:**  
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

Biểu diễn hành vi hiển thị tên danh mục nhãn dữ liệu của biểu đồ được chỉ định. True để hiển thị tên danh mục cho các nhãn dữ liệu trên biểu đồ. False để ẩn. Đọc/ghi boolean.
Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowCategoryName cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowCategoryName của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" gây ra tất cả DataLabels.get_Item(i).getShowCategoryName() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

Trả về hoặc đặt một Boolean để chỉ định hành vi hiển thị tên chuỗi cho các nhãn dữ liệu trên biểu đồ. True để hiển thị tên chuỗi. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowSeriesName cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowSeriesName của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" gây ra tất cả DataLabels.get_Item(i).getShowSeriesName() bằng val).

**Giá trị trả về:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

Trả về hoặc đặt một Boolean để chỉ định hành vi hiển thị tên chuỗi cho các nhãn dữ liệu trên biểu đồ. True để hiển thị tên chuỗi. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowSeriesName cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowSeriesName của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" gây ra tất cả DataLabels.get_Item(i).getShowSeriesName() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

Đại diện cho hành vi hiển thị giá trị phần trăm của nhãn dữ liệu trên biểu đồ đã chỉ định. True hiển thị giá trị phần trăm. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowPercentage cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowPercentage của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" gây ra tất cả DataLabels.get_Item(i).getShowPercentage() bằng val).

**Giá trị trả về:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

Đại diện cho hành vi hiển thị giá trị phần trăm của nhãn dữ liệu trên biểu đồ đã chỉ định. True hiển thị giá trị phần trăm. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowPercentage cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowPercentage của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" gây ra tất cả DataLabels.get_Item(i).getShowPercentage() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

Đại diện cho hành vi hiển thị giá trị kích thước bong bóng của nhãn dữ liệu trên biểu đồ đã chỉ định. True hiển thị giá trị kích thước bong bóng. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowBubbleSize cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowBubbleSize của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" gây ra tất cả DataLabels.get_Item(i).getShowBubbleSize() bằng val).

**Giá trị trả về:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

Đại diện cho hành vi hiển thị giá trị kích thước bong bóng của nhãn dữ liệu trên biểu đồ đã chỉ định. True hiển thị giá trị kích thước bong bóng. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowBubbleSize cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowBubbleSize của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" gây ra tất cả DataLabels.get_Item(i).getShowBubbleSize() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

Đại diện cho hành vi hiển thị các đường dẫn dẫn (leader lines) của nhãn dữ liệu trên biểu đồ đã chỉ định. True hiển thị các đường dẫn dẫn. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowLeaderLines cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLeaderLines của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" gây ra tất cả DataLabels.get_Item(i).getShowLeaderLines() bằng val).

**Giá trị trả về:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

Đại diện cho hành vi hiển thị các đường dẫn dẫn (leader lines) của nhãn dữ liệu trên biểu đồ đã chỉ định. True hiển thị các đường dẫn dẫn. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowLeaderLines cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLeaderLines của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" gây ra tất cả DataLabels.get_Item(i).getShowLeaderLines() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```

Xác định liệu nhãn dữ liệu của biểu đồ đã chỉ định có được hiển thị dưới dạng gọi dữ liệu (data callout) hay dưới dạng nhãn dữ liệu.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowLabelAsDataCallout cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLabelAsDataCallout của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" gây ra tất cả DataLabels.get_Item(i).getShowLabelAsDataCallout() bằng val).

**Giá trị trả về:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

Xác định liệu nhãn dữ liệu của biểu đồ đã chỉ định có được hiển thị dưới dạng gọi dữ liệu (data callout) hay dưới dạng nhãn dữ liệu.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowLabelAsDataCallout cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLabelAsDataCallout của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" gây ra tất cả DataLabels.get_Item(i).getShowLabelAsDataCallout() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

Đại diện cho hành vi hiển thị giá trị ô của nhãn dữ liệu trên biểu đồ đã chỉ định. True hiển thị giá trị ô. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowLabelValueFromCell cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLabelValueFromCell của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" gây ra tất cả DataLabels.get_Item(i).getShowLabelValueFromCell() bằng val).

**Giá trị trả về:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

Đại diện cho hành vi hiển thị giá trị ô của nhãn dữ liệu trên biểu đồ đã chỉ định. True hiển thị giá trị ô. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowLabelValueFromCell cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLabelValueFromCell của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" gây ra tất cả DataLabels.get_Item(i).getShowLabelValueFromCell() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

Đặt hoặc trả về một Variant đại diện cho ký tự phân tách được sử dụng cho các nhãn dữ liệu trên biểu đồ. Đọc/ghi String.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính Separator cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính Separator của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" gây ra tất cả DataLabels.get_Item(i).getSeparator() bằng val).

**Giá trị trả về:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```

Đặt hoặc trả về một Variant đại diện cho ký tự phân tách được sử dụng cho các nhãn dữ liệu trên biểu đồ. Đọc/ghi String.

--------------------

Nếu đối tượng DataLabelFormat này có cha là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính Separator cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính Separator của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" gây ra tất cả DataLabels.get_Item(i).getSeparator() bằng val).
**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |