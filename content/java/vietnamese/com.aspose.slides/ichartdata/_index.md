---
title: IChartData
second_title: Aspose.Slides for Java API Reference
description: Biểu diễn dữ liệu được sử dụng cho việc vẽ biểu đồ.
type: docs
url: /vi/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

Biểu diễn dữ liệu được sử dụng cho việc vẽ biểu đồ.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Lấy factory của các ô để tạo các ô được sử dụng cho chuỗi hoặc danh mục của biểu đồ. |
| [getSeries()](#getSeries--) | Lấy các chuỗi. |
| [getSeriesGroups()](#getSeriesGroups--) | Lấy các nhóm của chuỗi. |
| [getCategories()](#getCategories--) | Lấy các danh mục chính (hoặc cả danh mục chính và phụ nếu thuộc tính (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) là false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Nếu false thì thuộc tính (\#getSecondaryCategories.getSecondaryCategories) trả về null và dữ liệu trong thuộc tính (\#getCategories.getCategories) được sử dụng cho cả chuỗi chính và phụ. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Nếu false thì thuộc tính (\#getSecondaryCategories.getSecondaryCategories) trả về null và dữ liệu trong thuộc tính (\#getCategories.getCategories) được sử dụng cho cả chuỗi chính và phụ. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Lấy các danh mục phụ nếu thuộc tính (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) là true. |
| [readWorkbookStream()](#readWorkbookStream--) | Ghi workbook Excel được chứa nội bộ vào một luồng bộ nhớ. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Khởi tạo workbook Excel được chứa nội bộ bằng giá trị do người dùng chỉ định. |
| [setRange(String formula)](#setRange-java.lang.String-) | Đặt phạm vi dữ liệu biểu đồ. |
| [getRange()](#getRange--) | Lấy phạm vi dữ liệu biểu đồ. |
| [getDataSourceType()](#getDataSourceType--) | Biểu diễn nguồn dữ liệu của biểu đồ |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Biểu diễn đường dẫn workbook bên ngoài nếu nguồn dữ liệu là bên ngoài, ngược lại null |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Lấy loại của workbook được nhúng. |
| [switchRowColumn()](#switchRowColumn--) | Hoán đổi dữ liệu qua trục. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Đặt workbook bên ngoài làm nguồn dữ liệu cho biểu đồ. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Đặt workbook bên ngoài làm nguồn dữ liệu cho biểu đồ. |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

Lấy factory của các ô để tạo các ô được sử dụng cho chuỗi hoặc danh mục của biểu đồ. Chỉ đọc [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Trả về:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

Lấy các chuỗi. Chỉ đọc [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Trả về:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

Lấy các nhóm của chuỗi. Chỉ đọc [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Mỗi nhóm chuỗi chứa các chuỗi có loại có thể kết hợp. Các nhóm loại chuỗi có thể kết hợp được định nghĩa và mô tả bằng enum CombinableSeriesTypesGroup. Ngoài ra mỗi nhóm chuỗi chứa các chuỗi được vẽ trên trục chính hoặc trục phụ (không cùng lúc trong một nhóm). Do đó, nguyên tắc nhóm chuỗi là nhóm theo các nhóm loại đã đề cập ở trên và theo kiểu vẽ chính/phụ. 2) Nhóm chuỗi chứa một số thuộc tính chuỗi chung cho mỗi chuỗi trong nhóm (“thuộc tính nhóm chuỗi”). “Thuộc tính nhóm chuỗi” trong lớp ChartSeriesGroup là đọc/ghi. Mỗi “thuộc tính nhóm chuỗi” có thể có một phiên bản chỉ đọc trong lớp ChartSeries.

**Trả về:**
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

Nếu thuộc tính (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) là false thì thuộc tính (\#getSecondaryCategories.getSecondaryCategories) trả về null và dữ liệu trong thuộc tính (\#getCategories.getCategories) được sử dụng cho cả chuỗi chính và phụ. Nếu thuộc tính (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) là true thì dữ liệu trong thuộc tính (\#getSecondaryCategories.getSecondaryCategories) được sử dụng cho chuỗi phụ và dữ liệu trong thuộc tính (\#getCategories.getCategories) được sử dụng cho chuỗi chính.

**Trả về:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

Nếu false thì thuộc tính (\#getSecondaryCategories.getSecondaryCategories) trả về null và dữ liệu trong thuộc tính (\#getCategories.getCategories) được sử dụng cho cả chuỗi chính và phụ. Nếu true thì dữ liệu trong thuộc tính (\#getSecondaryCategories.getSecondaryCategories) được sử dụng cho chuỗi phụ và dữ liệu trong thuộc tính (\#getCategories.getCategories) được sử dụng cho chuỗi chính. Đọc/ghi boolean.

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


**Trả về:**
boolean
### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public abstract void setUseSecondaryCategories(boolean value)
```

Nếu false thì thuộc tính (\#getSecondaryCategories.getSecondaryCategories) trả về null và dữ liệu trong thuộc tính (\#getCategories.getCategories) được sử dụng cho cả chuỗi chính và phụ. Nếu true thì dữ liệu trong thuộc tính (\#getSecondaryCategories.getSecondaryCategories) được sử dụng cho chuỗi phụ và dữ liệu trong thuộc tính (\#getCategories.getCategories) được sử dụng cho chuỗi chính. Đọc/ghi boolean.

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


**Tham số:**
| Tham số | Kiểu | Mô tả |
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

Nếu thuộc tính (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) là false thì thuộc tính (\#getSecondaryCategories.getSecondaryCategories) trả về null và dữ liệu trong thuộc tính (\#getCategories.getCategories) được sử dụng cho cả chuỗi chính và phụ. Nếu thuộc tính (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) là true thì dữ liệu trong thuộc tính (\#getSecondaryCategories.getSecondaryCategories) được sử dụng cho chuỗi phụ và dữ liệu trong thuộc tính (\#getCategories.getCategories) được sử dụng cho chuỗi chính.

**Trả về:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

Ghi workbook Excel được chứa nội bộ vào một luồng bộ nhớ.

**Trả về:**
byte[] - Trả về một mảng byte chứa bản sao của workbook Excel được chứa nội bộ.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

Khởi tạo workbook Excel được chứa nội bộ bằng giá trị do người dùng chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| ms | byte[] | Luồng do người dùng cung cấp chứa toàn bộ workbook Excel. |
### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

Đặt phạm vi dữ liệu biểu đồ. Các chuỗi và danh mục sẽ được cập nhật dựa trên phạm vi dữ liệu mới. Nếu số lượng chuỗi trong phạm vi dữ liệu lớn hơn số lượng chuỗi trong dữ liệu biểu đồ thì các chuỗi bổ sung với cùng loại như chuỗi cuối cùng trong tập hiện tại sẽ được thêm vào cuối tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
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


**Trả về:**
java.lang.String - Công thức phạm vi dữ liệu ô. Ví dụ: "Sheet1!$A$1:$C$4"
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

Biểu diễn nguồn dữ liệu của biểu đồ

**Trả về:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

Biểu diễn đường dẫn workbook bên ngoài nếu nguồn dữ liệu là bên ngoài, ngược lại null

**Trả về:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

Lấy loại của workbook được nhúng. Trả về [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) nếu DataSourceType (\#getDataSourceType.getDataSourceType) là [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Chỉ đọc [WorkbookType](../../com.aspose.slides/workbooktype).

**Trả về:**
int
### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

Hoán đổi dữ liệu qua trục. Dữ liệu được vẽ trên trục X sẽ chuyển sang trục Y và ngược lại.
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


**Tham số:**
| Tham số | Kiểu | Mô tả |
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


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| workbookPath | java.lang.String | Đường dẫn tới workbook mục tiêu |
| updateChartData | boolean | Nếu giá trị là false thì chỉ đường dẫn workbook sẽ được cập nhật. Dữ liệu biểu đồ sẽ không được tải và cập nhật từ workbook mục tiêu. Có thể dùng khi workbook mục tiêu không tồn tại hoặc không khả dụng. Nếu giá trị là true thì dữ liệu biểu đồ sẽ được cập nhật từ workbook mục tiêu. |