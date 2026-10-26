---
title: IChartDataWorkbook
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: ให้การเข้าถึงเวิร์กบุ๊ก Excel ที่ฝังไว้
type: docs
url: /th/com.aspose.slides/ichartdataworkbook/
---```
public interface IChartDataWorkbook
```

ให้การเข้าถึงเวิร์กบุ๊ก Excel ที่ฝังไว้
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [calculateFormulas()](#calculateFormulas--) | คำนวณสูตรทั้งหมดในเวิร์กบุ๊กและอัปเดตค่าของเซลล์ที่สอดคล้อง |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | รับชุดของเซลล์ |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | รับเซลล์ที่สามารถใช้สำหรับชุดข้อมูลหรือประเภทของแผนภูมิ |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | รับเซลล์ที่สามารถใช้สำหรับชุดข้อมูลหรือประเภทของแผนภูมิ |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | รับเซลล์ที่สามารถใช้สำหรับชุดข้อมูลหรือประเภทของแผนภูมิ |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | รับเซลล์ที่สามารถใช้สำหรับชุดข้อมูลหรือประเภทของแผนภูมิ |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | รับเซลล์ที่สามารถใช้สำหรับชุดข้อมูลหรือประเภทของแผนภูมิ |
| [clear(int sheetIndex)](#clear-int-) | ลบค่าทั้งหมดของเซลล์ในแผ่นงาน |
| [getWorksheets()](#getWorksheets--) | รับคอลเลกชันของ worksheets |
### calculateFormulas() {#calculateFormulas--}
```
public abstract void calculateFormulas()
```

คำนวณสูตรทั้งหมดในเวิร์กบุ๊กและอัปเดตค่าของเซลล์ที่สอดคล้อง

--------------------

> ```
> Example shows how to assign a formula to the cell and to calculate a value. The value of the "B4" cell is getting set to 5.
>   
>   Presentation pres = new Presentation();
>   try {
>       IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 100, 100, 300, 400);
>       IChartDataWorkbook wb = chart.getChartData().getChartDataWorkbook();
>       wb.getCell(0, "B2", 2);
>       wb.getCell(0, "B3", 3);
>       wb.getCell(0, "B4").setFormula("B2+B3");
>       wb.calculateFormulas();
>       ...
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public abstract IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```

รับชุดของเซลล์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| formula | java.lang.String | สูตร Excel เช่น "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | หากเป็น true เมธอดจะคืนคอลเลกชันโดยไม่รวมเซลล์ที่ซ่อนอยู่ |

**คืนค่า:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection) - ชุดของเซลล์ [IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IChartDataCell getCell(String worksheetName, int row, int column)
```

รับเซลล์ที่สามารถใช้สำหรับชุดข้อมูลหรือประเภทของแผนภูมิ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| worksheetName | java.lang.String | ชื่อของ worksheet |
| row | int | แถว |
| column | int | คอลัมน์ |

**คืนค่า:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column)
```

รับเซลล์ที่สามารถใช้สำหรับชุดข้อมูลหรือประเภทของแผนภูมิ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| worksheetIndex | int | ดัชนีของ worksheet |
| row | int | แถว |
| column | int | คอลัมน์ |

**คืนค่า:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName)
```

รับเซลล์ที่สามารถใช้สำหรับชุดข้อมูลหรือประเภทของแผนภูมิ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| worksheetIndex | int | ดัชนีของ worksheet |
| cellName | java.lang.String | ชื่อของเซลล์ |

**คืนค่า:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```

รับเซลล์ที่สามารถใช้สำหรับชุดข้อมูลหรือประเภทของแผนภูมิ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| worksheetIndex | int | ดัชนีของ worksheet |
| cellName | java.lang.String | ชื่อของเซลล์ |
| value | java.lang.Object | ค่า |

**คืนค่า:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```

รับเซลล์ที่สามารถใช้สำหรับชุดข้อมูลหรือประเภทของแผนภูมิ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| worksheetIndex | int | ดัชนีของ worksheet |
| row | int | แถว |
| column | int | คอลัมน์ |
| value | java.lang.Object | ค่า |

**คืนค่า:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### clear(int sheetIndex) {#clear-int-}
```
public abstract void clear(int sheetIndex)
```

ลบค่าทั้งหมดของเซลล์ในแผ่นงาน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sheetIndex | int | ดัชนีของแผ่นงาน |

### getWorksheets() {#getWorksheets--}
```
public abstract IChartDataWorksheetCollection getWorksheets()
```

รับคอลเลกชันของ worksheets

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 500);
>      IChartDataWorkbook workbook =  chart.getChartData().getChartDataWorkbook();
>      for (IChartDataWorksheet worksheet : workbook.getWorksheets())
>      {
>          String worksheetName = worksheet.getName();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)