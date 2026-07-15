---
title: IChartData
second_title: Aspose.Slides for Android via Java API Reference
description: Represents data used for a chart plotting.
type: docs
url: /vi/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

Đại diện cho dữ liệu được sử dụng để vẽ biểu đồ.
## Phương thức

| Method | Description |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Lấy nhà máy ô để tạo các ô được sử dụng cho series hoặc danh mục của biểu đồ. |
| [getSeries()](#getSeries--) | Lấy series. |
| [getSeriesGroups()](#getSeriesGroups--) | Lấy các nhóm series. |
| [getCategories()](#getCategories--) | Lấy các danh mục chính (hoặc cả danh mục chính và phụ nếu thuộc tính (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) là false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Nếu false thì thuộc tính (\#getSecondaryCategories.getSecondaryCategories) trả về null và dữ liệu trong thuộc tính (\#getCategories.getCategories) được sử dụng cho cả series chính và phụ. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Nếu false thì thuộc tính (\#getSecondaryCategories.getSecondaryCategories) trả về null và dữ liệu trong thuộc tính (\#getCategories.getCategories) được sử dụng cho cả series chính và phụ. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Lấy các danh mục phụ nếu thuộc tính (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) là true. |
| [readWorkbookStream()](#readWorkbookStream--) | Ghi workbook Excel được chứa nội bộ vào một luồng bộ nhớ. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Khởi tạo workbook Excel được chứa nội bộ bằng giá trị do người dùng chỉ định. |
| [setRange(String formula)](#setRange-java.lang.String-) | Đặt phạm vi dữ liệu biểu đồ. |
| [getRange()](#getRange--) | Lấy phạm vi dữ liệu biểu đồ. |
| [getDataSourceType()](#getDataSourceType--) | Đại diện cho nguồn dữ liệu của biểu đồ |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Đại diện cho đường dẫn workbook bên ngoài nếu nguồn dữ liệu là bên ngoài, nếu không thì null |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Lấy loại workbook nhúng. |
| [switchRowColumn()](#switchRowColumn--) | Đảo dữ liệu qua trục. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Đặt workbook bên ngoài làm nguồn dữ liệu cho biểu đồ. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Đặt workbook bên ngoài làm nguồn dữ liệu cho biểu đồ. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

Lấy nhà máy ô để tạo các ô được sử dụng cho series hoặc danh mục của biểu đồ. Chỉ đọc [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Returns:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

Lấy series. Chỉ đọc [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Returns:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

Lấy các nhóm series. Chỉ đọc [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Mỗi nhóm series chứa các series có kiểu có thể kết hợp với nhau. Các nhóm kiểu series có thể kết hợp được định nghĩa và mô tả bằng enum CombinableSeriesTypesGroup. Ngoài ra, mỗi nhóm series chứa các series được vẽ trên trục chính hoặc trục phụ (không có cả hai trường hợp trong cùng một nhóm). Do đó, nguyên tắc nhóm series là nhóm dựa trên các nhóm kiểu đã nêu ở trên và dựa trên kiểu vẽ trên trục chính/phụ. 2) Nhóm series chứa một số thuộc tính series chung cho mỗi series trong nhóm ("thuộc tính nhóm series"). "Thuộc tính nhóm series" trong lớp ChartSeriesGroup có thể đọc/ghi. Mỗi "thuộc tính nhóm series" có thể có một phiên bản chỉ đọc trong lớp ChartSeries.

**Returns:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

Lấy các danh mục chính (hoặc cả danh mục chính và phụ nếu thuộc tính (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) là false). Chỉ đọc [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // các danh mục liên quan là series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // các danh mục liên quan là series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

Nếu thuộc tính (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) là false thì thuộc tính (\#getSecondaryCategories.getSecondaryCategories) trả về null và dữ liệu trong thuộc tính (\#getCategories.getCategories) này được sử dụng cho cả series chính và phụ. Nếu thuộc tính (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) là true thì dữ liệu trong thuộc tính (\#getSecondaryCategories.getSecondaryCategories) được sử dụng cho series phụ và dữ liệu trong thuộc tính (\#getCategories.getCategories) này được sử dụng cho series chính.

**Returns:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

Nếu false thì thuộc tính (\#getSecondaryCategories.getSecondaryCategories) trả về null và dữ liệu trong thuộc tính (\#getCategories.getCategories) được sử dụng cho cả series chính và phụ. Nếu true thì dữ liệu trong thuộc tính (\#getSecondaryCategories.getSecondaryCategories) được sử dụng cho series phụ và dữ liệu trong thuộc tính (\#getCategories.getCategories) được sử dụng cho series chính. Đọc/ghi boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // các danh mục liên quan là series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // các danh mục liên quan là series.getChart().getChartData().getCategories()
>  }
> ```

**Returns:**
boolean

### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public abstract void setUseSecondaryCategories(boolean value)
```

Nếu false thì thuộc tính (\#getSecondaryCategories.getSecondaryCategories) trả về null và dữ liệu trong thuộc tính (\#getCategories.getCategories) được sử dụng cho cả series chính và phụ. Nếu true thì dữ liệu trong thuộc tính (\#getSecondaryCategories.getSecondaryCategories) được sử dụng cho series phụ và dữ liệu trong thuộc tính (\#getCategories.getCategories) được sử dụng cho series chính. Đọc/ghi boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // các danh mục liên quan là series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // các danh mục liên quan là series.getChart().getChartData().getCategories()
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public abstract IChartCategoryCollection getSecondaryCategories()
```

Lấy các danh mục phụ nếu thuộc tính (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) là true. Chỉ đọc [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // các danh mục liên quan là series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // các danh mục liên quan là series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

Nếu thuộc tính (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) là false thì thuộc tính (\#getSecondaryCategories.getSecondaryCategories) trả về null và dữ liệu trong thuộc tính (\#getCategories.getCategories) được sử dụng cho cả series chính và phụ. Nếu thuộc tính (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) là true thì dữ liệu trong thuộc tính (\#getSecondaryCategories.getSecondaryCategories) được sử dụng cho series phụ và dữ liệu trong thuộc tính (\#getCategories.getCategories) được sử dụng cho series chính.

**Returns:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

Ghi workbook Excel được chứa nội bộ vào một luồng bộ nhớ.

**Returns:**
byte[] - Trả về một mảng byte chứa bản sao của workbook Excel được chứa nội bộ.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

Khởi tạo workbook Excel được chứa nội bộ bằng giá trị do người dùng chỉ định.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ms | byte[] | Luồng do người dùng cung cấp chứa toàn bộ workbook Excel. |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

Đặt phạm vi dữ liệu biểu đồ. Series và danh mục sẽ được cập nhật dựa trên phạm vi dữ liệu mới. Nếu số lượng series trong phạm vi dữ liệu lớn hơn số lượng series trong dữ liệu biểu đồ thì các series bổ sung có cùng kiểu với series cuối cùng trong bộ sưu tập hiện tại sẽ được thêm vào cuối bộ sưu tập.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | Công thức phạm vi dữ liệu ô. Ví dụ: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### getRange() {#getRange--}
```
public abstract String getRange()
```

Lấy phạm vi dữ liệu biểu đồ.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**Returns:**
java.lang.String - Công thức phạm vi dữ liệu ô. Ví dụ: "Sheet1!$A$1:$C$4"

### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

Đại diện cho nguồn dữ liệu của biểu đồ

**Returns:**
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

Đại diện cho đường dẫn workbook bên ngoài nếu nguồn dữ liệu là bên ngoài, nếu không thì null

**Returns:**
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

Lấy loại của workbook nhúng. Trả về [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) nếu DataSourceType (\#getDataSourceType.getDataSourceType) là [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Chỉ đọc [WorkbookType](../../com.aspose.slides/workbooktype).

**Returns:**
int

### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

Đảo dữ liệu qua trục. Dữ liệu được vẽ trên trục X sẽ chuyển sang trục Y và ngược lại.

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```

Đặt workbook bên ngoài làm nguồn dữ liệu cho biểu đồ. Dữ liệu biểu đồ sẽ được cập nhật từ workbook mục tiêu.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>     IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>     IChartData chartData = chart.getChartData();
>     ((ChartData)chartData).setExternalWorkbook("../../workbook.xlsx");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | Đường dẫn tới workbook mục tiêu |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Đặt workbook bên ngoài làm nguồn dữ liệu cho biểu đồ.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>     IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>     IChartData chartData = chart.getChartData();
>     ((ChartData)chartData).setExternalWorkbook("http://path/doesnt/exists", false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | Đường dẫn tới workbook mục tiêu |
| updateChartData | boolean | Nếu giá trị là false thì chỉ đường dẫn workbook sẽ được cập nhật. Dữ liệu biểu đồ sẽ không được tải và cập nhật từ workbook mục tiêu. Có thể dùng khi workbook mục tiêu không tồn tại hoặc không khả dụng. Nếu giá trị là true thì dữ liệu biểu đồ sẽ được cập nhật từ workbook mục tiêu. |