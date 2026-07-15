---
title: ISpreadsheetOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Đại diện cho các tùy chọn có thể được sử dụng để chỉ định hành vi bổ sung cho bảng tính.
type: docs
url: /vi/com.aspose.slides/ispreadsheetoptions/
---```
public interface ISpreadsheetOptions
```

Đại diện cho các tùy chọn có thể được sử dụng để chỉ định hành vi bổ sung cho bảng tính.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Lấy hoặc đặt thông tin vùng miền ưu tiên để tính một số hàm dành cho các ngôn ngữ sử dụng bộ ký tự đôi (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Lấy hoặc đặt thông tin vùng miền ưu tiên để tính một số hàm dành cho các ngôn ngữ sử dụng bộ ký tự đôi (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Nếu nguồn dữ liệu cho biểu đồ là một workbook bên ngoài và nó không khả dụng, nó sẽ được khôi phục từ bộ nhớ cache của biểu đồ. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Nếu nguồn dữ liệu cho biểu đồ là một workbook bên ngoài và nó không khả dụng, nó sẽ được khôi phục từ bộ nhớ cache của biểu đồ. |
### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```

Lấy hoặc đặt thông tin vùng miền ưu tiên để tính một số hàm dành cho các ngôn ngữ sử dụng bộ ký tự đôi (DBCS).

**Trả về:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```

Lấy hoặc đặt thông tin vùng miền ưu tiên để tính một số hàm dành cho các ngôn ngữ sử dụng bộ ký tự đôi (DBCS).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public abstract boolean getRecoverWorkbookFromChartCache()
```

Nếu nguồn dữ liệu cho biểu đồ là một workbook bên ngoài và nó không khả dụng, nó sẽ được khôi phục từ bộ nhớ cache của biểu đồ.

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
public abstract void setRecoverWorkbookFromChartCache(boolean value)
```

Nếu nguồn dữ liệu cho biểu đồ là một workbook bên ngoài và nó không khả dụng, nó sẽ được khôi phục từ bộ nhớ cache của biểu đồ.

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