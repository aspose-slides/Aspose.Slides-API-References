---
title: SpreadsheetOptions
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn các tùy chọn có thể được sử dụng để chỉ định hành vi bổ sung cho bảng tính.
type: docs
url: /vi/com.aspose.slides/spreadsheetoptions/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được thực hiện:**
[com.aspose.slides.ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
```
public class SpreadsheetOptions implements ISpreadsheetOptions
```

Biểu diễn các tùy chọn có thể được sử dụng để chỉ định hành vi bổ sung cho bảng tính.
## Các hàm khởi tạo

| Constructor | Mô tả |
| --- | --- |
| [SpreadsheetOptions()](#SpreadsheetOptions--) | Khởi tạo một thể hiện mới của lớp [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions). |
## Các phương thức

| Method | Mô tả |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Lấy hoặc đặt thông tin văn hoá ưu tiên cho việc tính toán một số hàm được thiết kế cho các ngôn ngữ sử dụng bộ ký tự đôi byte (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Lấy hoặc đặt thông tin văn hoá ưu tiên cho việc tính toán một số hàm được thiết kế cho các ngôn ngữ sử dụng bộ ký tự đôi byte (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Nếu nguồn dữ liệu cho biểu đồ là một workbook bên ngoài và không khả dụng, nó sẽ được phục hồi từ bộ nhớ đệm biểu đồ. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Nếu nguồn dữ liệu cho biểu đồ là một workbook bên ngoài và không khả dụng, nó sẽ được phục hồi từ bộ nhớ đệm biểu đồ. |
### SpreadsheetOptions() {#SpreadsheetOptions--}
```
public SpreadsheetOptions()
```


Khởi tạo một thể hiện mới của lớp [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions).

### getPreferredCulture() {#getPreferredCulture--}
```
public final Locale getPreferredCulture()
```


Lấy hoặc đặt thông tin văn hoá ưu tiên cho việc tính toán một số hàm được thiết kế cho các ngôn ngữ sử dụng bộ ký tự đôi byte (DBCS).

**Trả về:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public final void setPreferredCulture(Locale value)
```


Lấy hoặc đặt thông tin văn hoá ưu tiên cho việc tính toán một số hàm được thiết kế cho các ngôn ngữ sử dụng bộ ký tự đôi byte (DBCS).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public final boolean getRecoverWorkbookFromChartCache()
```


Nếu nguồn dữ liệu cho biểu đồ là một workbook bên ngoài và không khả dụng, nó sẽ được phục hồi từ bộ nhớ đệm biểu đồ.

--------------------

> ```
> Example:
>   
>   SpreadsheetOptions spreadOptions = new SpreadsheetOptions();
>   spreadOptions.setRecoverWorkbookFromChartCache(true);
> 
>   LoadOptions loadOptions = new LoadOptions();
>   loadOptions.setSpreadsheetOptions(spreadOptions);
> 
>   Presentation pres = new Presentation("Presentation.pptx", loadOptions);
>   try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartDataWorkbook recoveredWorkbook = chart.getChartData().getChartDataWorkbook();
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```

**Trả về:**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public final void setRecoverWorkbookFromChartCache(boolean value)
```


Nếu nguồn dữ liệu cho biểu đồ là một workbook bên ngoài và không khả dụng, nó sẽ được phục hồi từ bộ nhớ đệm biểu đồ.

--------------------

> ```
> Example:
>   
>   SpreadsheetOptions spreadOptions = new SpreadsheetOptions();
>   spreadOptions.setRecoverWorkbookFromChartCache(true);
> 
>   LoadOptions loadOptions = new LoadOptions();
>   loadOptions.setSpreadsheetOptions(spreadOptions);
> 
>   Presentation pres = new Presentation("Presentation.pptx", loadOptions);
>   try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartDataWorkbook recoveredWorkbook = chart.getChartData().getChartDataWorkbook();
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |