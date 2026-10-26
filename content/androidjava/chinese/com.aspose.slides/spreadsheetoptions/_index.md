---
title: SpreadsheetOptions
second_title: Aspose.Slides for Android via Java API 参考
description: 表示可用于指定附加电子表格行为的选项。
type: docs
url: /zh/com.aspose.slides/spreadsheetoptions/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
```
public class SpreadsheetOptions implements ISpreadsheetOptions
```

表示可用于指定附加电子表格行为的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SpreadsheetOptions()](#SpreadsheetOptions--) | 初始化 [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions) 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | 获取或设置用于计算某些函数的首选文化信息，这些函数旨在用于使用双字节字符集 (DBCS) 的语言。 |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | 获取或设置用于计算某些函数的首选文化信息，这些函数旨在用于使用双字节字符集 (DBCS) 的语言。 |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | 如果图表的数据源是外部工作簿且不可用，则会从图表缓存中恢复。 |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | 如果图表的数据源是外部工作簿且不可用，则会从图表缓存中恢复。 |

### SpreadsheetOptions() {#SpreadsheetOptions--}
```
public SpreadsheetOptions()
```

初始化 [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions) 类的新实例。

### getPreferredCulture() {#getPreferredCulture--}
```
public final Locale getPreferredCulture()
```

获取或设置用于计算某些函数的首选文化信息，这些函数旨在用于使用双字节字符集 (DBCS) 的语言。

**返回值：**
java.util.Locale

### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public final void setPreferredCulture(Locale value)
```

获取或设置用于计算某些函数的首选文化信息，这些函数旨在用于使用双字节字符集 (DBCS) 的语言。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public final boolean getRecoverWorkbookFromChartCache()
```

如果图表的数据源是外部工作簿且不可用，则会从图表缓存中恢复。

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

**Returns:**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public final void setRecoverWorkbookFromChartCache(boolean value)
如果图表的数据源是外部工作簿且不可用，则会从图表缓存中恢复。

--------------------

> ```
> 示例：
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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |