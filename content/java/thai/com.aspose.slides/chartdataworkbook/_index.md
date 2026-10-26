---
title: ChartDataWorkbook
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: ให้การเข้าถึงเวิร์กบุ๊ก Excel ที่ฝังอยู่
type: docs
url: /th/com.aspose.slides/chartdataworkbook/
---
**การสืบทอด:**  
java.lang.Object, com.aspose.slides.DomObject

**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**  
[com.aspose.slides.IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)  
```
public class ChartDataWorkbook extends DomObject<ChartData> implements IChartDataWorkbook
```

ให้การเข้าถึงเวิร์กบุ๊ก Excel ที่ฝังอยู่

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getWorksheets()](#getWorksheets--) | ดึงคอลเลกชันของแผ่นงาน. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | ดึงชุดของเซลล์. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | ดึงเซลล์ที่สามารถใช้สำหรับซีรีส์หรือประเภทของแผนภูมิ |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | ดึงเซลล์ที่สามารถใช้สำหรับซีรีส์หรือประเภทของแผนภูมิ |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | ดึงเซลล์ที่สามารถใช้สำหรับซีรีส์หรือประเภทของแผนภูมิ |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | ดึงเซลล์ที่สามารถใช้สำหรับซีรีส์หรือประเภทของแผนภูมิ |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | ดึงเซลล์ที่สามารถใช้สำหรับซีรีส์หรือประเภทของแผนภูมิ |
| [clear(int sheetIndex)](#clear-int-) | ลบค่าทั้งหมดของเซลล์ในแผ่น |
| [calculateFormulas()](#calculateFormulas--) | คำนวณสูตรทั้งหมดในเวิร์กบุ๊กและอัปเดตค่าของเซลล์ที่สอดคล้องกัน. |

### getWorksheets() {#getWorksheets--}
```
public final IChartDataWorksheetCollection getWorksheets()
```

ดึงคอลเลกชันของแผ่นงาน.

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

**ส่งกลับ:**  
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)

### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public final IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```

ดึงชุดของเซลล์.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| formula | java.lang.String | สูตร Excel เช่น “Sheet1!$A$2:$A$5”. |
| skipHiddenCells | boolean | หากเป็น true เมธอดจะคืนค่าคอลเลกชันโดยไม่มีเซลล์ที่ซ่อนอยู่. |

**ส่งกลับ:**  
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IChartDataCell getCell(String worksheetName, int row, int column)
```

ดึงเซลล์ที่สามารถใช้สำหรับซีรีส์หรือประเภทของแผนภูมิ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| worksheetName | java.lang.String | ชื่อของแผ่นงาน. |
| row | int | แถว. |
| column | int | คอลัมน์. |

**ส่งกลับ:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column)
```

ดึงเซลล์ที่สามารถใช้สำหรับซีรีส์หรือประเภทของแผนภูมิ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| worksheetIndex | int | ดัชนีของแผ่นงาน. |
| row | int | แถว. |
| column | int | คอลัมน์. |

**ส่งกลับ:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName)
```

ดึงเซลล์ที่สามารถใช้สำหรับซีรีส์หรือประเภทของแผนภูมิ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| worksheetIndex | int | ดัชนีของแผ่นงาน. |
| cellName | java.lang.String | ชื่อของเซลล์. |

**ส่งกลับ:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```

ดึงเซลล์ที่สามารถใช้สำหรับซีรีส์หรือประเภทของแผนภูมิ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| worksheetIndex | int | ดัชนีของแผ่นงาน. |
| cellName | java.lang.String | ชื่อของเซลล์. |
| value | java.lang.Object | ค่า. |

**ส่งกลับ:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```

ดึงเซลล์ที่สามารถใช้สำหรับซีรีส์หรือประเภทของแผนภูมิ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| worksheetIndex | int | ดัชนีของแผ่นงาน. |
| row | int | แถว. |
| column | int | คอลัมน์. |
| value | java.lang.Object | ค่า. |

**ส่งกลับ:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object

### clear(int sheetIndex) {#clear-int-}
```
public final void clear(int sheetIndex)
```

ลบค่าทั้งหมดของเซลล์ในแผ่น

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| sheetIndex | int | ดัชนีของแผ่น |

### calculateFormulas() {#calculateFormulas--}
```
public final void calculateFormulas()
```

คำนวณสูตรทั้งหมดในเวิร์กบุ๊กและอัปเดตค่าของเซลล์ที่สอดคล้องกัน.

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