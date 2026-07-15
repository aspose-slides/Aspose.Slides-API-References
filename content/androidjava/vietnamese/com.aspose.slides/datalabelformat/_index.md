---
title: DataLabelFormat
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Mô tả các tùy chọn định dạng cho DataLabel.
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

Mô tả các tùy chọn định dạng cho DataLabel.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Đọc/ghi boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Đọc/ghi boolean. |
| [getNumberFormat()](#getNumberFormat--) | Mô tả chuỗi định dạng cho đối tượng DataLabels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Mô tả chuỗi định dạng cho đối tượng DataLabels. |
| [getFormat()](#getFormat--) | Mô tả định dạng của nhãn dữ liệu. |
| [getPosition()](#getPosition--) | Mô tả vị trí của nhãn dữ liệu. |
| [setPosition(int value)](#setPosition-int-) | Mô tả vị trí của nhãn dữ liệu. |
| [getShowLegendKey()](#getShowLegendKey--) | Mô tả hành vi hiển thị khóa chú giải của nhãn dữ liệu trên biểu đồ đã chỉ định. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Mô tả hành vi hiển thị khóa chú giải của nhãn dữ liệu trên biểu đồ đã chỉ định. |
| [getShowValue()](#getShowValue--) | Mô tả hành vi hiển thị giá trị phần trăm của nhãn dữ liệu trên biểu đồ đã chỉ định. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Mô tả hành vi hiển thị giá trị phần trăm của nhãn dữ liệu trên biểu đồ đã chỉ định. |
| [getShowCategoryName()](#getShowCategoryName--) | Mô tả hành vi hiển thị tên danh mục của nhãn dữ liệu trên biểu đồ đã chỉ định. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Mô tả hành vi hiển thị tên danh mục của nhãn dữ liệu trên biểu đồ đã chỉ định. |
| [getShowSeriesName()](#getShowSeriesName--) | Trả về hoặc đặt một Boolean để chỉ ra hành vi hiển thị tên series cho các nhãn dữ liệu trên biểu đồ. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Trả về hoặc đặt một Boolean để chỉ ra hành vi hiển thị tên series cho các nhãn dữ liệu trên biểu đồ. |
| [getShowPercentage()](#getShowPercentage--) | Mô tả hành vi hiển thị giá trị phần trăm của nhãn dữ liệu trên biểu đồ đã chỉ định. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Mô tả hành vi hiển thị giá trị phần trăm của nhãn dữ liệu trên biểu đồ đã chỉ định. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Mô tả hành vi hiển thị giá trị kích thước bong bóng của nhãn dữ liệu trên biểu đồ đã chỉ định. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Mô tả hành vi hiển thị giá trị kích thước bong bóng của nhãn dữ liệu trên biểu đồ đã chỉ định. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Mô tả hành vi hiển thị các đường dẫn cho nhãn dữ liệu trên biểu đồ đã chỉ định. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Mô tả hành vi hiển thị các đường dẫn cho nhãn dữ liệu trên biểu đồ đã chỉ định. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Mô tả hành vi hiển thị giá trị ô của nhãn dữ liệu trên biểu đồ đã chỉ định. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Mô tả hành vi hiển thị giá trị ô của nhãn dữ liệu trên biểu đồ đã chỉ định. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Xác định liệu nhãn dữ liệu của biểu đồ đã chỉ định sẽ được hiển thị dưới dạng lời chú thích dữ liệu hay là nhãn dữ liệu. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Xác định liệu nhãn dữ liệu của biểu đồ đã chỉ định sẽ được hiển thị dưới dạng lời chú thích dữ liệu hay là nhãn dữ liệu. |
| [getSeparator()](#getSeparator--) | Đặt hoặc trả về một Variant mô tả dấu phân tách được sử dụng cho các nhãn dữ liệu trên biểu đồ. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Đặt hoặc trả về một Variant mô tả dấu phân tách được sử dụng cho các nhãn dữ liệu trên biểu đồ. |
| [getTextFormat()](#getTextFormat--) | Trả về định dạng văn bản biểu đồ. |
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

Nếu đối tượng cha của DataLabelFormat này là một DataLabelCollection, thuộc tính này nhận hoặc đặt giá trị mặc định của thuộc tính IsNumberFormatLinkedToSource cho các nhãn dữ liệu mới trong bộ sưu tập. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính IsNumberFormatLinkedToSource của mọi nhãn dữ liệu trong DataLabelCollection (ví dụ: “DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);” khiến tất cả DataLabels.get_Item(i).isNumberFormatLinkedToSource() bằng val).

**Trả về:**  
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Đọc/ghi boolean.

--------------------

Nếu đối tượng cha của DataLabelFormat này là một DataLabelCollection, thuộc tính này nhận hoặc đặt giá trị mặc định của thuộc tính IsNumberFormatLinkedToSource cho các nhãn dữ liệu mới trong bộ sưu tập. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính IsNumberFormatLinkedToSource của mọi nhãn dữ liệu trong DataLabelCollection (ví dụ: “DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);” khiến tất cả DataLabels.get_Item(i).isNumberFormatLinkedToSource() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

Mô tả chuỗi định dạng cho đối tượng DataLabels. Đọc/ghi String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Nếu đối tượng cha của DataLabelFormat này là một DataLabelCollection, thuộc tính này nhận hoặc đặt giá trị mặc định của thuộc tính NumberFormat cho các nhãn dữ liệu mới trong bộ sưu tập. Khi thuộc tính này được đặt bằng một giá trị, giá trị đó cũng sẽ được đặt cho thuộc tính NumberFormat của mọi nhãn dữ liệu trong DataLabelCollection (ví dụ: “DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);” khiến tất cả DataLabels.get_Item(i).getNumberFormat() bằng val).

**Trả về:**  
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

Mô tả chuỗi định dạng cho đối tượng DataLabels. Đọc/ghi String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Nếu đối tượng cha của DataLabelFormat này là một DataLabelCollection, thuộc tính này nhận hoặc đặt giá trị mặc định của thuộc tính NumberFormat cho các nhãn dữ liệu mới trong bộ sưu tập. Khi thuộc tính này được đặt bằng một giá trị, giá trị đó cũng sẽ được đặt cho thuộc tính NumberFormat của mọi nhãn dữ liệu trong DataLabelCollection (ví dụ: “DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);” khiến tất cả DataLabels.get_Item(i).getNumberFormat() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Mô tả định dạng của nhãn dữ liệu. Chỉ đọc [IFormat](../../com.aspose.slides/iformat).

--------------------

Nếu đối tượng cha của DataLabelFormat này là một DataLabelCollection, thuộc tính này đại diện cho định dạng mặc định cho các nhãn dữ liệu mới trong bộ sưu tập.

**Trả về:**  
[IFormat](../../com.aspose.slides/iformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Mô tả vị trí của nhãn dữ liệu. Đọc/ghi [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Nếu đối tượng cha của DataLabelFormat này là một DataLabelCollection, thuộc tính này nhận hoặc đặt giá trị mặc định của thuộc tính Position cho các nhãn dữ liệu mới trong bộ sưu tập. Đại diện cho vị trí của các đối tượng DataLabel. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính Position của mọi nhãn dữ liệu trong DataLabelCollection (ví dụ: “DataLabels.getDefaultDataLabelFormat().setPosition(val);” khiến tất cả DataLabels.get_Item(i).getPosition() bằng val).

**Trả về:**  
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Mô tả vị trí của nhãn dữ liệu. Đọc/ghi [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Nếu đối tượng cha của DataLabelFormat này là một DataLabelCollection, thuộc tính này nhận hoặc đặt giá trị mặc định của thuộc tính Position cho các nhãn dữ liệu mới trong bộ sưu tập. Đại diện cho vị trí của các đối tượng DataLabel. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính Position của mọi nhãn dữ liệu trong DataLabelCollection (ví dụ: “DataLabels.getDefaultDataLabelFormat().setPosition(val);” khiến tất cả DataLabels.get_Item(i).getPosition() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

Mô tả hành vi hiển thị khóa chú giải của nhãn dữ liệu trên biểu đồ đã chỉ định. True nếu khóa chú giải hiển thị. Đọc/ghi boolean.

--------------------

Nếu đối tượng cha của DataLabelFormat này là một DataLabelCollection, thuộc tính này nhận hoặc đặt giá trị mặc định của thuộc tính ShowLegendKey cho các nhãn dữ liệu mới trong bộ sưu tập. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLegendKey của mọi nhãn dữ liệu trong DataLabelCollection (ví dụ: “DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);” khiến tất cả DataLabels.get_Item(i).getShowLegendKey() bằng val).

**Trả về:**  
boolean
### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

Mô tả hành vi hiển thị khóa chú giải của nhãn dữ liệu trên biểu đồ đã chỉ định. True nếu khóa chú giải hiển thị. Đọc/ghi boolean.

--------------------

Nếu đối tượng cha của DataLabelFormat này là một DataLabelCollection, thuộc tính này nhận hoặc đặt giá trị mặc định của thuộc tính ShowLegendKey cho các nhãn dữ liệu mới trong bộ sưu tập. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLegendKey của mọi nhãn dữ liệu trong DataLabelCollection (ví dụ: “DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);” khiến tất cả DataLabels.get_Item(i).getShowLegendKey() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

Mô tả hành vi hiển thị giá trị phần trăm của nhãn dữ liệu trên biểu đồ đã chỉ định. True hiển thị giá trị phần trăm. False ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng cha của DataLabelFormat này là một DataLabelCollection, thuộc tính này nhận hoặc đặt giá trị mặc định của thuộc tính ShowValue cho các nhãn dữ liệu mới trong bộ sưu tập. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowValue của mọi nhãn dữ liệu trong DataLabelCollection (ví dụ: “DataLabels.getDefaultDataLabelFormat().setShowValue(val);” khiến tất cả DataLabels.get_Item(i).getShowValue() bằng val).

**Trả về:**  
boolean
### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

Mô tả hành vi hiển thị giá trị phần trăm của nhãn dữ liệu trên biểu đồ đã chỉ định. True hiển thị giá trị phần trăm. False ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng cha của DataLabelFormat này là một DataLabelCollection, thuộc tính này nhận hoặc đặt giá trị mặc định của thuộc tính ShowValue cho các nhãn dữ liệu mới trong bộ sưu tập. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowValue của mọi nhãn dữ liệu trong DataLabelCollection (ví dụ: “DataLabels.getDefaultDataLabelFormat().setShowValue(val);” khiến tất cả DataLabels.get_Item(i).getShowValue() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

Mô tả hành vi hiển thị tên danh mục của nhãn dữ liệu trên biểu đồ đã chỉ định. True hiển thị tên danh mục. False ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng cha của DataLabelFormat này là một DataLabelCollection, thuộc tính này nhận hoặc đặt giá trị mặc định của thuộc tính ShowCategoryName cho các nhãn dữ liệu mới trong bộ sưu tập. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowCategoryName của mọi nhãn dữ liệu trong DataLabelCollection (ví dụ: “DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);” khiến tất cả DataLabelCollection.get_Item(i).getShowCategoryName() bằng val).

**Trả về:**  
boolean
### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

Mô tả hành vi hiển thị tên danh mục của nhãn dữ liệu trên biểu đồ đã chỉ định. True hiển thị tên danh mục. False ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng cha của DataLabelFormat này là một DataLabelCollection, thuộc tính này nhận hoặc đặt giá trị mặc định của thuộc tính ShowCategoryName cho các nhãn dữ liệu mới trong bộ sưu tập. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowCategoryName của mọi nhãn dữ liệu trong DataLabelCollection (ví dụ: “DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);” khiến tất cả DataLabelCollection.get_Item(i).getShowCategoryName() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

Trả về hoặc đặt một Boolean để chỉ ra hành vi hiển thị tên series cho các nhãn dữ liệu trên biểu đồ. True hiển thị tên series. False ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng cha của DataLabelFormat này là một DataLabelCollection, thuộc tính này nhận hoặc đặt giá trị mặc định của thuộc tính ShowSeriesName cho các nhãn dữ liệu mới trong bộ sưu tập. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowSeriesName của mọi nhãn dữ liệu trong DataLabelCollection (ví dụ: “DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);” khiến tất cả DataLabelCollection.get_Item(i).getShowSeriesName() bằng val).

**Trả về:**  
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

Trả về hoặc đặt một Boolean để chỉ ra hành vi hiển thị tên series cho các nhãn dữ liệu trên biểu đồ. True hiển thị tên series. False ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng cha của DataLabelFormat này là một DataLabelCollection, thuộc tính này nhận hoặc đặt giá trị mặc định của thuộc tính ShowSeriesName cho các nhãn dữ liệu mới trong bộ sưu tập. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowSeriesName của mọi nhãn dữ liệu trong DataLabelCollection (ví dụ: “DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);” khiến tất cả DataLabelCollection.get_Item(i).getShowSeriesName() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

Mô tả hành vi hiển thị giá trị phần trăm của nhãn dữ liệu trên biểu đồ đã chỉ định. True hiển thị giá trị phần trăm. False ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng cha của DataLabelFormat này là một DataLabelCollection, thuộc tính này nhận hoặc đặt giá trị mặc định của thuộc tính ShowPercentage cho các nhãn dữ liệu mới trong bộ sưu tập. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowPercentage của mọi nhãn dữ liệu trong DataLabelCollection (ví dụ: “DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);” khiến tất cả DataLabelCollection.get_Item(i).getShowPercentage() bằng val).

**Trả về:**  
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

Mô tả hành vi hiển thị giá trị phần trăm của nhãn dữ liệu trên biểu đồ đã chỉ định. True hiển thị giá trị phần trăm. False ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng cha của DataLabelFormat này là một DataLabelCollection, thuộc tính này nhận hoặc đặt giá trị mặc định của thuộc tính ShowPercentage cho các nhãn dữ liệu mới trong bộ sưu tập. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowPercentage của mọi nhãn dữ liệu trong DataLabelCollection (ví dụ: “DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);” khiến tất cả DataLabelCollection.get_Item(i).getShowPercentage() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

Mô tả hành vi hiển thị giá trị kích thước bong bóng của nhãn dữ liệu trên biểu đồ đã chỉ định. True hiển thị giá trị kích thước bong bóng. False ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng cha của DataLabelFormat này là một DataLabelCollection, thuộc tính này nhận hoặc đặt giá trị mặc định của thuộc tính ShowBubbleSize cho các nhãn dữ liệu mới trong bộ sưu tập. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowBubbleSize của mọi nhãn dữ liệu trong DataLabelCollection (ví dụ: “DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);” khiến tất cả DataLabelCollection.get_Item(i).getShowBubbleSize() bằng val).

**Trả về:**  
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

Mô tả hành vi hiển thị giá trị kích thước bong bóng của nhãn dữ liệu trên biểu đồ đã chỉ định. True hiển thị giá trị kích thước bong bóng. False ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng cha của DataLabelFormat này là một DataLabelCollection, thuộc tính này nhận hoặc đặt giá trị mặc định của thuộc tính ShowBubbleSize cho các nhãn dữ liệu mới trong bộ sưu tập. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowBubbleSize của mọi nhãn dữ liệu trong DataLabelCollection (ví dụ: “DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);” khiến tất cả DataLabelCollection.get_Item(i).getShowBubbleSize() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

Mô tả hành vi hiển thị các đường dẫn cho nhãn dữ liệu trên biểu đồ đã chỉ định. True hiển thị các đường dẫn. False ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng cha của DataLabelFormat này là một DataLabelCollection, thuộc tính này nhận hoặc đặt giá trị mặc định của thuộc tính ShowLeaderLines cho các nhãn dữ liệu mới trong bộ sưu tập. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLeaderLines của mọi nhãn dữ liệu trong DataLabelCollection (ví dụ: “DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);” khiến tất cả DataLabelCollection.get_Item(i).getShowLeaderLines() bằng val).

**Trả về:**  
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

Mô tả hành vi hiển thị các đường dẫn cho nhãn dữ liệu trên biểu đồ đã chỉ định. True hiển thị các đường dẫn. False ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng cha của DataLabelFormat này là một DataLabelCollection, thuộc tính này nhận hoặc đặt giá trị mặc định của thuộc tính ShowLeaderLines cho các nhãn dữ liệu mới trong bộ sưu tập. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLeaderLines của mọi nhãn dữ liệu trong DataLabelCollection (ví dụ: “DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);” khiến tất cả DataLabelCollection.get_Item(i).getShowLeaderLines() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

Mô tả hành vi hiển thị giá trị ô của nhãn dữ liệu trên biểu đồ đã chỉ định. True hiển thị giá trị ô. False ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng cha của DataLabelFormat này là một DataLabelCollection, thuộc tính này nhận hoặc đặt giá trị mặc định của thuộc tính ShowLabelValueFromCell cho các nhãn dữ liệu mới trong bộ sưu tập. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLabelValueFromCell của mọi nhãn dữ liệu trong DataLabelCollection (ví dụ: “DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);” khiến tất cả DataLabelCollection.get_Item(i).getShowLabelValueFromCell() bằng val).

**Trả về:**  
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

Mô tả hành vi hiển thị giá trị ô của nhãn dữ liệu trên biểu đồ đã chỉ định. True hiển thị giá trị ô. False ẩn. Đọc/ghi boolean.

--------------------

Nếu đối tượng cha của DataLabelFormat này là một DataLabelCollection, thuộc tính này nhận hoặc đặt giá trị mặc định của thuộc tính ShowLabelValueFromCell cho các nhãn dữ liệu mới trong bộ sưu tập. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLabelValueFromCell của mọi nhãn dữ liệu trong DataLabelCollection (ví dụ: “DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);” khiến tất cả DataLabelCollection.get_Item(i).getShowLabelValueFromCell() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

Xác định liệu nhãn dữ liệu của biểu đồ đã chỉ định sẽ được hiển thị dưới dạng lời chú thích dữ liệu hay là nhãn dữ liệu.

--------------------

Nếu đối tượng cha của DataLabelFormat này là một DataLabelCollection, thuộc tính này nhận hoặc đặt giá trị mặc định của thuộc tính ShowLabelAsDataCallout cho các nhãn dữ liệu mới trong bộ sưu tập. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLabelAsDataCallout của mọi nhãn dữ liệu trong DataLabelCollection (ví dụ: “DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);” khiến tất cả DataLabelCollection.get_Item(i).getShowLabelAsDataCallout() bằng val).

**Trả về:**  
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

Xác định liệu nhãn dữ liệu của biểu đồ đã chỉ định sẽ được hiển thị dưới dạng lời chú thích dữ liệu hay là nhãn dữ liệu.

--------------------

Nếu đối tượng cha của DataLabelFormat này là một DataLabelCollection, thuộc tính này nhận hoặc đặt giá trị mặc định của thuộc tính ShowLabelAsDataCallout cho các nhãn dữ liệu mới trong bộ sưu tập. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính ShowLabelAsDataCallout của mọi nhãn dữ liệu trong DataLabelCollection (ví dụ: “DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);” khiến tất cả DataLabelCollection.get_Item(i).getShowLabelAsDataCallout() bằng val).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

Đặt hoặc trả về một Variant mô tả dấu phân tách được sử dụng cho các nhãn dữ liệu trên biểu đồ. Đọc/ghi String.

--------------------

Nếu đối tượng cha của DataLabelFormat này là một DataLabelCollection, thuộc tính này nhận hoặc đặt giá trị mặc định của thuộc tính Separator cho các nhãn dữ liệu mới trong bộ sưu tập. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính Separator của mọi nhãn dữ liệu trong DataLabelCollection (ví dụ: “DataLabels.getDefaultDataLabelFormat().setSeparator(val);” khiến tất cả DataLabelCollection.get_Item(i).getSeparator() bằng val).

**Trả về:**  
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

Đặt hoặc trả về một Variant mô tả dấu phân tách được sử dụng cho các nhãn dữ liệu trên biểu đồ. Đọc/ghi String.

--------------------

Nếu đối tượng cha của DataLabelFormat này là một DataLabelCollection, thuộc tính này nhận hoặc đặt giá trị mặc định của thuộc tính Separator cho các nhãn dữ liệu mới trong bộ sưu tập. Đặt thuộc tính này với một giá trị cũng sẽ đặt giá trị này cho thuộc tính Separator của mọi nhãn dữ liệu trong DataLabelCollection (ví dụ: “DataLabels.getDefaultDataLabelFormat().setSeparator(val);” khiến tất cả DataLabelCollection.get_Item(i).getSeparator() bằng val).

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