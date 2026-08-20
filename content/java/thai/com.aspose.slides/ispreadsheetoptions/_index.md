---
title: ISpreadsheetOptions
second_title: Aspose.Slides for Java API Reference
description: แสดงตัวเลือกที่สามารถใช้เพื่อระบุพฤติกรรมเพิ่มเติมของสเปรดชีต
type: docs
url: /th/com.aspose.slides/ispreadsheetoptions/
---```
public interface ISpreadsheetOptions
```

แสดงตัวเลือกที่สามารถใช้เพื่อระบุพฤติกรรมเพิ่มเติมของสเปรดชีต
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | รับหรือกำหนดข้อมูลวัฒนธรรมที่ต้องการสำหรับการคำนวณฟังก์ชันบางอย่างที่ออกแบบมาเพื่อใช้กับภาษาที่ใช้ชุดอักขระสองไบต์ (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | รับหรือกำหนดข้อมูลวัฒนธรรมที่ต้องการสำหรับการคำนวณฟังก์ชันบางอย่างที่ออกแบบมาเพื่อใช้กับภาษาที่ใช้ชุดอักขระสองไบต์ (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | หากแหล่งข้อมูลของแผนภูมิเกิดจากเวิร์คบุ๊กภายนอกและไม่พร้อมใช้งาน ระบบจะกู้คืนจากแคชของแผนภูมิ. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | หากแหล่งข้อมูลของแผนภูมิเกิดจากเวิร์คบุ๊กภายนอกและไม่พร้อมใช้งาน ระบบจะกู้คืนจากแคชของแผนภูมิ. |
### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```

รับหรือกำหนดข้อมูลวัฒนธรรมที่ต้องการสำหรับการคำนวณฟังก์ชันบางอย่างที่ออกแบบมาเพื่อใช้กับภาษาที่ใช้ชุดอักขระสองไบต์ (DBCS).

**คืนค่า:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```

รับหรือกำหนดข้อมูลวัฒนธรรมที่ต้องการสำหรับการคำนวณฟังก์ชันบางอย่างที่ออกแบบมาเพื่อใช้กับภาษาที่ใช้ชุดอักขระสองไบต์ (DBCS).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public abstract boolean getRecoverWorkbookFromChartCache()
```

หากแหล่งข้อมูลของแผนภูมิเกิดจากเวิร์คบุ๊กภายนอกและไม่พร้อมใช้งาน ระบบจะกู้คืนจากแคชของแผนภูมิ.

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

**คืนค่า:**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public abstract void setRecoverWorkbookFromChartCache(boolean value)
```

หากแหล่งข้อมูลของแผนภูมิเจิดจากเวิร์คบุ๊กภายนอกและไม่พร้อมใช้งาน ระบบจะกู้คืนจากแคชของแผนภูมิ.

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

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |