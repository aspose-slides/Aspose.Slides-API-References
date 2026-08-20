---
title: DataLabelFormat
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho các tùy chọn định dạng cho DataLabel.
type: docs
url: /vi/com.aspose.slides/datalabelformat/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
```
public final class DataLabelFormat extends PVIObject implements IDataLabelFormat
```

Biểu diễn các tùy chọn định dạng cho DataLabel.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Đọc/ghi boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Đọc/ghi boolean. |
| [getNumberFormat()](#getNumberFormat--) | Biểu diễn chuỗi định dạng cho đối tượng DataLabels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Biểu diễn chuỗi định dạng cho đối tượng DataLabels. |
| [getFormat()](#getFormat--) | Biểu diễn định dạng của nhãn dữ liệu. |
| [getPosition()](#getPosition--) | Biểu diễn vị trí của nhãn dữ liệu. |
| [setPosition(int value)](#setPosition-int-) | Biểu diễn vị trí của nhãn dữ liệu. |
| [getShowLegendKey()](#getShowLegendKey--) | Biểu diễn hành vi hiển thị khóa chú giải của nhãn dữ liệu cho biểu đồ được chỉ định. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Biểu diễn hành vi hiển thị khóa chú giải của nhãn dữ liệu cho biểu đồ được chỉ định. |
| [getShowValue()](#getShowValue--) | Biểu diễn hành vi hiển thị giá trị phần trăm của nhãn dữ liệu cho biểu đồ được chỉ định. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Biểu diễn hành vi hiển thị giá trị phần trăm của nhãn dữ liệu cho biểu đồ được chỉ định. |
| [getShowCategoryName()](#getShowCategoryName--) | Biểu diễn hành vi hiển thị tên danh mục của nhãn dữ liệu cho biểu đồ được chỉ định. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Biểu diễn hành vi hiển thị tên danh mục của nhãn dữ liệu cho biểu đồ được chỉ định. |
| [getShowSeriesName()](#getShowSeriesName--) | Trả về hoặc đặt một Boolean để chỉ định hành vi hiển thị tên series cho nhãn dữ liệu trên biểu đồ. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Trả về hoặc đặt một Boolean để chỉ định hành vi hiển thị tên series cho nhãn dữ liệu trên biểu đồ. |
| [getShowPercentage()](#getShowPercentage--) | Biểu diễn hành vi hiển thị giá trị phần trăm của nhãn dữ liệu cho biểu đồ được chỉ định. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Biểu diễn hành vi hiển thị giá trị phần trăm của nhãn dữ liệu cho biểu đồ được chỉ định. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Biểu diễn hành vi hiển thị giá trị kích thước bong bóng của nhãn dữ liệu cho biểu đồ được chỉ định. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Biểu diễn hành vi hiển thị giá trị kích thước bong bóng của nhãn dữ liệu cho biểu đồ được chỉ định. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Biểu diễn hành vi hiển thị đường dẫn dẫn đầu của nhãn dữ liệu cho biểu đồ được chỉ định. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Biểu diễn hành vi hiển thị đường dẫn dẫn đầu của nhãn dữ liệu cho biểu đồ được chỉ định. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Biểu diễn hành vi hiển thị giá trị ô của nhãn dữ liệu cho biểu đồ được chỉ định. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Biểu diễn hành vi hiển thị giá trị ô của nhãn dữ liệu cho biểu đồ được chỉ định. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Xác định liệu nhãn dữ liệu của biểu đồ được chỉ định sẽ được hiển thị dưới dạng chú thích dữ liệu hay dưới dạng nhãn dữ liệu. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Xác định liệu nhãn dữ liệu của biểu đồ được chỉ định sẽ được hiển thị dưới dạng chú thích dữ liệu hay dưới dạng nhãn dữ liệu. |
| [getSeparator()](#getSeparator--) | Đặt hoặc trả về một Variant đại diện cho ký tự phân tách được sử dụng cho các nhãn dữ liệu trên biểu đồ. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Đặt hoặc trả về một Variant đại diện cho ký tự phân tách được sử dụng cho các nhãn dữ liệu trên biểu đồ. |
| [getTextFormat()](#getTextFormat--) | Trả về định dạng văn bản của biểu đồ. |
| [getChart()](#getChart--) | Trả về biểu đồ. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Phiên bản. Chỉ đọc long.

**Trả về:**
long

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

Đọc/ghi boolean.

--------------------

Nếu phụ huynh của đối tượng DataLabelFormat này là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này sẽ lấy hoặc thiết lập giá trị mặc định của thuộc tính IsNumberFormatLinkedToSource cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính IsNumberFormatLinkedToSource của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" gây ra tất cả DataLabels.get_Item(i).isNumberFormatLinkedToSource() bằng với giá trị đó).

**Trả về:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Đọc/ghi boolean.

--------------------

Nếu phụ huynh của đối tượng DataLabelFormat này là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này sẽ lấy hoặc thiết lập giá trị mặc định của thuộc tính IsNumberFormatLinkedToSource cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính IsNumberFormatLinkedToSource của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" gây ra tất cả DataLabels.get_Item(i).isNumberFormatLinkedToSource() bằng với giá trị đó).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

Biểu diễn chuỗi định dạng cho đối tượng DataLabels. Đọc/ghi String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Nếu phụ huynh của đối tượng DataLabelFormat này là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu, thì thuộc tính này sẽ lấy hoặc thiết lập giá trị mặc định của thuộc tính NumberFormat cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Khi thuộc tính này được đặt với một giá trị, giá trị đó cũng được đặt cho thuộc tính NumberFormat của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" gây ra tất cả DataLabels.get_Item(i).getNumberFormat() bằng với giá trị đó).

**Trả về:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

Biểu diễn chuỗi định dạng cho đối tượng DataLabels. Đọc/ghi String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

Nếu phụ huynh của đối tượng DataLabelFormat này là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu, thì thuộc tính này sẽ lấy hoặc thiết lập giá trị mặc định của thuộc tính NumberFormat cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Khi thuộc tính này được đặt với một giá trị, giá trị đó cũng được đặt cho thuộc tính NumberFormat của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" gây ra tất cả DataLabels.get_Item(i).getNumberFormat() bằng với giá trị đó).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Biểu diễn định dạng của nhãn dữ liệu. Chỉ đọc [IFormat](../../com.aspose.slides/iformat).

--------------------

Nếu phụ huynh của đối tượng DataLabelFormat này là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này biểu diễn định dạng mặc định cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection.

**Trả về:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public final int getPosition()
```

Biểu diễn vị trí của nhãn dữ liệu. Đọc/ghi [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Nếu phụ huynh của đối tượng DataLabelFormat này là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này sẽ lấy hoặc thiết lập giá trị mặc định của thuộc tính Position cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Biểu diễn vị trí cho các đối tượng DataLabel. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính Position của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setPosition(val);" gây ra tất cả DataLabels.get_Item(i).getPosition() bằng với giá trị đó).

**Trả về:**
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Biểu diễn vị trí của nhãn dữ liệu. Đọc/ghi [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Nếu phụ huynh của đối tượng DataLabelFormat này là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này sẽ lấy hoặc thiết lập giá trị mặc định của thuộc tính Position cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Biểu diễn vị trí cho các đối tượng DataLabel. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính Position của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setPosition(val);" gây ra tất cả DataLabels.get_Item(i).getPosition() bằng với giá trị đó).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

Biểu diễn hành vi hiển thị khóa chú giải của nhãn dữ liệu cho biểu đồ được chỉ định. True nếu khóa chú giải của nhãn dữ liệu hiển thị. Đọc/ghi boolean.

--------------------

Nếu phụ huynh của đối tượng DataLabelFormat này là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này sẽ lấy hoặc thiết lập giá trị mặc định của thuộc tính ShowLegendKey cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLegendKey của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" gây ra tất cả DataLabels.get_Item(i).getShowLegendKey() bằng với giá trị đó).

**Trả về:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

Biểu diễn hành vi hiển thị khóa chú giải của nhãn dữ liệu cho biểu đồ được chỉ định. True nếu khóa chú giải của nhãn dữ liệu hiển thị. Đọc/ghi boolean.

--------------------

Nếu phụ huynh của đối tượng DataLabelFormat này là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này sẽ lấy hoặc thiết lập giá trị mặc định của thuộc tính ShowLegendKey cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLegendKey của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" gây ra tất cả DataLabels.get_Item(i).getShowLegendKey() bằng với giá trị đó).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

Biểu diễn hành vi hiển thị giá trị phần trăm của nhãn dữ liệu cho biểu đồ được chỉ định. True hiển thị giá trị phần trăm. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu phụ huynh của đối tượng DataLabelFormat này là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này sẽ lấy hoặc thiết lập giá trị mặc định của thuộc tính ShowValue cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowValue của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" gây ra tất cả DataLabels.get_Item(i).getShowValue() bằng với giá trị đó).

**Trả về:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

Biểu diễn hành vi hiển thị giá trị phần trăm của nhãn dữ liệu cho biểu đồ được chỉ định. True hiển thị giá trị phần trăm. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu phụ huynh của đối tượng DataLabelFormat này là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này sẽ lấy hoặc thiết lập giá trị mặc định của thuộc tính ShowValue cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowValue của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" gây ra tất cả DataLabels.get_Item(i).getShowValue() bằng với giá trị đó).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

Biểu diễn hành vi hiển thị tên danh mục của nhãn dữ liệu cho biểu đồ được chỉ định. True để hiển thị tên danh mục cho các nhãn dữ liệu trên biểu đồ. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu phụ huynh của đối tượng DataLabelFormat này là một bộ sưu tập DataLabelCollection của các nhãn dữ liệu thì thuộc tính này sẽ lấy hoặc thiết lập giá trị mặc định của thuộc tính ShowCategoryName cho các nhãn dữ liệu mới trong bộ sưu tập DataLabelCollection. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowCategoryName của tất cả các nhãn dữ liệu trong bộ sưu tập DataLabelCollection (ví dụ "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" gây ra tất cả DataLabels.get_Item(i).getShowCategoryName() bằng với giá trị đó).

**Trả về:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

Biểu diễn hành vi hiển thị tên danh mục của nhãn dữ liệu cho biểu đồ được chỉ định. True để hiển thị tên danh mục cho các nhãn dữ liệu trên biểu đồ. False để ẩn. Đọc/ghi boolean.

--------------------
Nếu cha của đối tượng DataLabelFormat này là một DataLabelCollection collection chứa các nhãn dữ liệu, thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowCategoryName cho các nhãn dữ liệu mới trong DataLabelCollection collection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowCategoryName của tất cả các nhãn dữ liệu trong DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" gây ra tất cả DataLabels.get_Item(i).getShowCategoryName() bằng val).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

Trả về hoặc thiết lập một Boolean để chỉ ra hành vi hiển thị tên chuỗi cho các nhãn dữ liệu trên biểu đồ. True để hiển thị tên chuỗi. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu cha của đối tượng DataLabelFormat này là một DataLabelCollection collection chứa các nhãn dữ liệu, thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowSeriesName cho các nhãn dữ liệu mới trong DataLabelCollection collection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowSeriesName của tất cả các nhãn dữ liệu trong DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" gây ra tất cả DataLabels.get_Item(i).getShowSeriesName() bằng val).

**Trả về:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

Trả về hoặc thiết lập một Boolean để chỉ ra hành vi hiển thị tên chuỗi cho các nhãn dữ liệu trên biểu đồ. True để hiển thị tên chuỗi. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu cha của đối tượng DataLabelFormat này là một DataLabelCollection collection chứa các nhãn dữ liệu, thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowSeriesName cho các nhãn dữ liệu mới trong DataLabelCollection collection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowSeriesName của tất cả các nhãn dữ liệu trong DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" gây ra tất cả DataLabels.get_Item(i).getShowSeriesName() bằng val).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

Biểu diễn hành vi hiển thị giá trị phần trăm của nhãn dữ liệu trên một biểu đồ cụ thể. True để hiển thị giá trị phần trăm. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu cha của đối tượng DataLabelFormat này là một DataLabelCollection collection chứa các nhãn dữ liệu, thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowPercentage cho các nhãn dữ liệu mới trong DataLabelCollection collection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowPercentage của tất cả các nhãn dữ liệu trong DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" gây ra tất cả DataLabels.get_Item(i).getShowPercentage() bằng val).

**Trả về:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

Biểu diễn hành vi hiển thị giá trị phần trăm của nhãn dữ liệu trên một biểu đồ cụ thể. True để hiển thị giá trị phần trăm. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu cha của đối tượng DataLabelFormat này là một DataLabelCollection collection chứa các nhãn dữ liệu, thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowPercentage cho các nhãn dữ liệu mới trong DataLabelCollection collection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowPercentage của tất cả các nhãn dữ liệu trong DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" gây ra tất cả DataLabels.get_Item(i).getShowPercentage() bằng val).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

Biểu diễn hành vi hiển thị giá trị kích thước bong bóng của nhãn dữ liệu trên một biểu đồ cụ thể. True để hiển thị giá trị kích thước bong bóng. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu cha của đối tượng DataLabelFormat này là một DataLabelCollection collection chứa các nhãn dữ liệu, thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowBubbleSize cho các nhãn dữ liệu mới trong DataLabelCollection collection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowBubbleSize của tất cả các nhãn dữ liệu trong DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" gây ra tất cả DataLabels.get_Item(i).getShowBubbleSize() bằng val).

**Trả về:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

Biểu diễn hành vi hiển thị giá trị kích thước bong bóng của nhãn dữ liệu trên một biểu đồ cụ thể. True để hiển thị giá trị kích thước bong bóng. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu cha của đối tượng DataLabelFormat này là một DataLabelCollection collection chứa các nhãn dữ liệu, thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowBubbleSize cho các nhãn dữ liệu mới trong DataLabelCollection collection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowBubbleSize của tất cả các nhãn dữ liệu trong DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" gây ra tất cả DataLabels.get_Item(i).getShowBubbleSize() bằng val).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

Biểu diễn hành vi hiển thị các đường dẫn dẫn (leader lines) của nhãn dữ liệu trên một biểu đồ cụ thể. True để hiển thị các đường dẫn dẫn. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu cha của đối tượng DataLabelFormat này là một DataLabelCollection collection chứa các nhãn dữ liệu, thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowLeaderLines cho các nhãn dữ liệu mới trong DataLabelCollection collection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLeaderLines của tất cả các nhãn dữ liệu trong DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" gây ra tất cả DataLabels.get_Item(i).getShowLeaderLines() bằng val).

**Trả về:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

Biểu diễn hành vi hiển thị các đường dẫn dẫn của nhãn dữ liệu trên một biểu đồ cụ thể. True để hiển thị các đường dẫn dẫn. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu cha của đối tượng DataLabelFormat này là một DataLabelCollection collection chứa các nhãn dữ liệu, thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowLeaderLines cho các nhãn dữ liệu mới trong DataLabelCollection collection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLeaderLines của tất cả các nhãn dữ liệu trong DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" gây ra tất cả DataLabels.get_Item(i).getShowLeaderLines() bằng val).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

Biểu diễn hành vi hiển thị giá trị ô của nhãn dữ liệu trên một biểu đồ cụ thể. True để hiển thị giá trị ô. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu cha của đối tượng DataLabelFormat này là một DataLabelCollection collection chứa các nhãn dữ liệu, thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowLabelValueFromCell cho các nhãn dữ liệu mới trong DataLabelCollection collection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLabelValueFromCell của tất cả các nhãn dữ liệu trong DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" gây ra tất cả DataLabels.get_Item(i).getShowLabelValueFromCell() bằng val).

**Trả về:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

Biểu diễn hành vi hiển thị giá trị ô của nhãn dữ liệu trên một biểu đồ cụ thể. True để hiển thị giá trị ô. False để ẩn. Đọc/ghi boolean.

--------------------

Nếu cha của đối tượng DataLabelFormat này là một DataLabelCollection collection chứa các nhãn dữ liệu, thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowLabelValueFromCell cho các nhãn dữ liệu mới trong DataLabelCollection collection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLabelValueFromCell của tất cả các nhãn dữ liệu trong DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" gây ra tất cả DataLabels.get_Item(i).getShowLabelValueFromCell() bằng val).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

Xác định liệu nhãn dữ liệu của biểu đồ được hiển thị dưới dạng gọi dữ liệu (data callout) hay dưới dạng nhãn dữ liệu.

--------------------

Nếu cha của đối tượng DataLabelFormat này là một DataLabelCollection collection chứa các nhãn dữ liệu, thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowLabelAsDataCallout cho các nhãn dữ liệu mới trong DataLabelCollection collection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLabelAsDataCallout của tất cả các nhãn dữ liệu trong DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" gây ra tất cả DataLabels.get_Item(i).getShowLabelAsDataCallout() bằng val).

**Trả về:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

Xác định liệu nhãn dữ liệu của biểu đồ được hiển thị dưới dạng gọi dữ liệu (data callout) hay dưới dạng nhãn dữ liệu.

--------------------

Nếu cha của đối tượng DataLabelFormat này là một DataLabelCollection collection chứa các nhãn dữ liệu, thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính ShowLabelAsDataCallout cho các nhãn dữ liệu mới trong DataLabelCollection collection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLabelAsDataCallout của tất cả các nhãn dữ liệu trong DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" gây ra tất cả DataLabels.get_Item(i).getShowLabelAsDataCallout() bằng val).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

Đặt hoặc trả về một Variant đại diện cho ký tự ngăn cách được sử dụng cho các nhãn dữ liệu trên một biểu đồ. Đọc/ghi String.

--------------------

Nếu cha của đối tượng DataLabelFormat này là một DataLabelCollection collection chứa các nhãn dữ liệu, thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính Separator cho các nhãn dữ liệu mới trong DataLabelCollection collection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính Separator của tất cả các nhãn dữ liệu trong DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" gây ra tất cả DataLabels.get_Item(i).getSeparator() bằng val).

**Trả về:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

Đặt hoặc trả về một Variant đại diện cho ký tự ngăn cách được sử dụng cho các nhãn dữ liệu trên một biểu đồ. Đọc/ghi String.

--------------------

Nếu cha của đối tượng DataLabelFormat này là một DataLabelCollection collection chứa các nhãn dữ liệu, thì thuộc tính này lấy hoặc đặt giá trị mặc định của thuộc tính Separator cho các nhãn dữ liệu mới trong DataLabelCollection collection. Đặt thuộc tính này với giá trị cũng sẽ đặt giá trị này cho thuộc tính Separator của tất cả các nhãn dữ liệu trong DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" gây ra tất cả DataLabels.get_Item(i).getSeparator() bằng val).
**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Trả về định dạng văn bản biểu đồ. Chỉ đọc [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Trả về:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```

Trả về biểu đồ. Chỉ đọc [IChart](../../com.aspose.slides/ichart).

**Trả về:**
[IChart](../../com.aspose.slides/ichart)