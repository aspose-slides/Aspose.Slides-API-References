---
title: ChartData
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn dữ liệu được sử dụng để vẽ biểu đồ.
type: docs
url: /vi/com.aspose.slides/chartdata/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)
```
public class ChartData extends DomObject<Chart> implements IChartData
```

Biểu diễn dữ liệu được sử dụng cho việc vẽ biểu đồ.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Lấy nhà máy ô để tạo các ô được sử dụng cho chuỗi hoặc danh mục của biểu đồ. |
| [getSeries()](#getSeries--) | Lấy chuỗi. |
| [getSeriesGroups()](#getSeriesGroups--) | Lấy các nhóm của chuỗi. |
| [getCategories()](#getCategories--) | Lấy các danh mục chính (hoặc cả danh mục chính và phụ nếu thuộc tính #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) là false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Nếu false thì thuộc tính #getSecondaryCategories.getSecondaryCategories trả về null và dữ liệu trong thuộc tính #getCategories.getCategories được sử dụng cho cả chuỗi chính và phụ. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Nếu false thì thuộc tính #getSecondaryCategories.getSecondaryCategories trả về null và dữ liệu trong thuộc tính #getCategories.getCategories được sử dụng cho cả chuỗi chính và phụ. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Lấy các danh mục phụ nếu thuộc tính #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) là true. |
| [readWorkbookStream()](#readWorkbookStream--) | Ghi workbook Excel được chứa nội bộ vào một luồng bộ nhớ. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Khởi tạo workbook Excel được chứa nội bộ với giá trị do người dùng chỉ định. |
| [getDataSourceType()](#getDataSourceType--) | Biểu thị đường dẫn workbook bên ngoài nếu nguồn dữ liệu là bên ngoài, nếu không thì null. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Biểu thị nguồn dữ liệu của biểu đồ. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Lấy loại của workbook nhúng. |
| [getRange()](#getRange--) | Lấy phạm vi dữ liệu biểu đồ. |
| [setRange(String formula)](#setRange-java.lang.String-) | Đặt phạm vi dữ liệu biểu đồ. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Đặt workbook bên ngoài làm nguồn dữ liệu cho biểu đồ. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Đặt workbook bên ngoài làm nguồn dữ liệu cho biểu đồ. |
| [switchRowColumn()](#switchRowColumn--) | Hoán đổi dữ liệu qua trục. |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```


Lấy nhà máy ô để tạo các ô được sử dụng cho chuỗi hoặc danh mục của biểu đồ. Chỉ đọc [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Trả về:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```


Lấy chuỗi. Chỉ đọc [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Trả về:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```


Lấy các nhóm của chuỗi. Chỉ đọc [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

Mỗi nhóm chuỗi chứa các chuỗi có kiểu có thể kết hợp. Các nhóm kiểu chuỗi có thể kết hợp được định nghĩa và mô tả bằng enum CombinableSeriesTypesGroup. Ngoài ra, mỗi nhóm chuỗi chứa các chuỗi được vẽ trên trục chính hoặc trục phụ (không có cả hai trường hợp trong một nhóm). Do đó, nguyên tắc nhóm chuỗi là nhóm theo các nhóm kiểu đã đề cập ở trên và theo loại vẽ trên trục chính/ phụ.

**Trả về:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```


Lấy các danh mục chính (hoặc cả danh mục chính và phụ nếu thuộc tính #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) là false). Chỉ đọc [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Nếu thuộc tính #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) là false thì thuộc tính (#getSecondaryCategories.getSecondaryCategories) trả về null và dữ liệu trong thuộc tính #getCategories.getCategories này được sử dụng cho cả chuỗi chính và phụ. Nếu thuộc tính #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) là true thì dữ liệu trong thuộc tính (#getSecondaryCategories.getSecondaryCategories) được sử dụng cho chuỗi phụ và dữ liệu trong thuộc tính #getCategories.getCategories này được sử dụng cho chuỗi chính.

**Trả về:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```


Nếu false thì thuộc tính #getSecondaryCategories.getSecondaryCategories trả về null và dữ liệu trong thuộc tính #getCategories.getCategories được sử dụng cho cả chuỗi chính và phụ. Nếu true thì dữ liệu trong thuộc tính #getSecondaryCategories.getSecondaryCategories được sử dụng cho chuỗi phụ và dữ liệu trong thuộc tính #getCategories.getCategories được sử dụng cho chuỗi chính. Đọc/ghi boolean.

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
public final void setUseSecondaryCategories(boolean value)
```


Nếu false thì thuộc tính #getSecondaryCategories.getSecondaryCategories trả về null và dữ liệu trong thuộc tính #getCategories.getCategories được sử dụng cho cả chuỗi chính và phụ. Nếu true thì dữ liệu trong thuộc tính #getSecondaryCategories.getSecondaryCategories được sử dụng cho chuỗi phụ và dữ liệu trong thuộc tính #getCategories.getCategories được sử dụng cho chuỗi chính. Đọc/ghi boolean.

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
public final IChartCategoryCollection getSecondaryCategories()
```


Lấy các danh mục phụ nếu thuộc tính #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) là true. Chỉ đọc [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Nếu thuộc tính #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) là false thì thuộc tính (#getSecondaryCategories.getSecondaryCategories) trả về null và dữ liệu trong thuộc tính #getCategories.getCategories được sử dụng cho cả chuỗi chính và phụ. Nếu thuộc tính #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) là true thì dữ liệu trong thuộc tính #getSecondaryCategories.getSecondaryCategories này được sử dụng cho chuỗi phụ và dữ liệu trong thuộc tính #getCategories.getCategories được sử dụng cho chuỗi chính.

**Trả về:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```


Ghi workbook Excel được chứa nội bộ vào một luồng bộ nhớ.

**Trả về:**
byte[] - Trả về một thể hiện của mảng byte chứa bản sao của workbook Excel được chứa nội bộ.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```


Khởi tạo workbook Excel được chứa nội bộ với giá trị do người dùng chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| ms | byte[] | Luồng do người dùng cung cấp chứa toàn bộ workbook Excel. |
### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```


Biểu thị đường dẫn workbook bên ngoài nếu nguồn dữ liệu là bên ngoài, nếu không thì null.

**Trả về:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```


Biểu thị nguồn dữ liệu của biểu đồ.

**Trả về:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```


Lấy loại của workbook nhúng. Trả về [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) nếu DataSourceType (#getDataSourceType.getDataSourceType) là [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Chỉ đọc [WorkbookType](../../com.aspose.slides/workbooktype).

**Trả về:**
int
### getRange() {#getRange--}
```
public final String getRange()
```


Lấy phạm vi dữ liệu biểu đồ.

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 0, 0, 100, 100);
>       String result = ((ChartData)chart.getChartData()).getRange();
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Trả về:**
java.lang.String - Công thức phạm vi dữ liệu ô. Ví dụ: "Sheet1!$A$1:$C$4"
### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```


Đặt phạm vi dữ liệu biểu đồ. Các chuỗi và danh mục sẽ được cập nhật dựa trên phạm vi dữ liệu mới. Nếu số lượng chuỗi trong phạm vi dữ liệu lớn hơn số lượng chuỗi trong dữ liệu biểu đồ thì các chuỗi bổ sung có cùng kiểu với chuỗi cuối cùng trong bộ hiện tại sẽ được thêm vào cuối bộ.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| formula | java.lang.String | Công thức phạm vi dữ liệu ô. Ví dụ: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |
### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
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
>     if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| workbookPath | java.lang.String | Đường dẫn đến workbook mục tiêu |
### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```


Đặt workbook bên ngoài làm nguồn dữ liệu cho biểu đồ.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>      IChartData chartData = chart.getChartData();
>      ((ChartData).setExternalWorkbook("http://path/doesnt/exists", false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| workbookPath | java.lang.String | Đường dẫn đến workbook mục tiêu |
| updateChartData | boolean | Nếu giá trị là false thì chỉ đường dẫn workbook sẽ được cập nhật. Dữ liệu biểu đồ sẽ không được tải và cập nhật từ workbook mục tiêu. Có thể dùng khi workbook mục tiêu không tồn tại hoặc không khả dụng. Nếu giá trị là true thì dữ liệu biểu đồ sẽ được cập nhật từ workbook mục tiêu. |
### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```


Hoán đổi dữ liệu qua trục. Dữ liệu được vẽ trên trục X sẽ chuyển sang trục Y và ngược lại.