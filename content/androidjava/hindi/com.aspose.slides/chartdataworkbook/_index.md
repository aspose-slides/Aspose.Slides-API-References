---
title: ChartDataWorkbook
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: एंबेडेड Excel वर्कबुक तक पहुँच प्रदान करता है
type: docs
url: /hi/com.aspose.slides/chartdataworkbook/
---
**विरासत:**
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
```
public class ChartDataWorkbook extends DomObject<ChartData> implements IChartDataWorkbook
```

एंबेडेड Excel वर्कबुक तक पहुँच प्रदान करता है
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getWorksheets()](#getWorksheets--) | वर्कशीट्स का संग्रह प्राप्त करता है। |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | सेल्स का सेट प्राप्त करता है। |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | ऐसा सेल प्राप्त करता है जिसका उपयोग चार्ट सीरीज़ या श्रेणियों के लिए किया जा सकता है |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | ऐसा सेल प्राप्त करता है जिसका उपयोग चार्ट सीरीज़ या श्रेणियों के लिए किया जा सकता है |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | ऐसा सेल प्राप्त करता है जिसका उपयोग चार्ट सीरीज़ या श्रेणियों के लिए किया जा सकता है |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | ऐसा सेल प्राप्त करता है जिसका उपयोग चार्ट सीरीज़ या श्रेणियों के लिए किया जा सकता है |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | ऐसा सेल प्राप्त करता है जिसका उपयोग चार्ट सीरीज़ या श्रेणियों के लिए किया जा सकता है |
| [clear(int sheetIndex)](#clear-int-) | शीट पर सभी सेल मान साफ़ करें |
| [calculateFormulas()](#calculateFormulas--) | वर्कबुक में सभी फ़ॉर्मूले की गणना करता है और संबंधित सेल मानों को अपडेट करता है। |
### getWorksheets() {#getWorksheets--}
```
public final IChartDataWorksheetCollection getWorksheets()
```

वर्कशीट्स का संग्रह प्राप्त करता है।

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

**रिटर्न:**
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)
### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public final IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```

सेल्स का सेट प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| formula | java.lang.String | Excel फ़ॉर्मूला जैसे "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | यदि true हो तो विधि छुपे हुए सेल्स के बिना संग्रह लौटाती है। |

**रिटर्न:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IChartDataCell getCell(String worksheetName, int row, int column)
```

ऐसा सेल प्राप्त करता है जिसका उपयोग चार्ट सीरीज़ या श्रेणियों के लिए किया जा सकता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| worksheetName | java.lang.String | वर्कशीट का नाम। |
| row | int | पंक्ति। |
| column | int | कॉलम। |

**रिटर्न:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell ऑब्जेक्ट
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column)
```

ऐसा सेल प्राप्त करता है जिसका उपयोग चार्ट सीरीज़ या श्रेणियों के लिए किया जा सकता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| worksheetIndex | int | वर्कशीट का सूचकांक। |
| row | int | पंक्ति। |
| column | int | कॉलम। |

**रिटर्न:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell ऑब्जेक्ट
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName)
```

ऐसा सेल प्राप्त करता है जिसका उपयोग चार्ट सीरीज़ या श्रेणियों के लिए किया जा सकता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| worksheetIndex | int | वर्कशीट का सूचकांक। |
| cellName | java.lang.String | सेल का नाम। |

**रिटर्न:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell ऑब्जेक्ट
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```

ऐसा सेल प्राप्त करता है जिसका उपयोग चार्ट सीरीज़ या श्रेणियों के लिए किया जा सकता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| worksheetIndex | int | वर्कशीट का सूचकांक। |
| cellName | java.lang.String | सेल का नाम। |
| value | java.lang.Object | मान। |

**रिटर्न:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell ऑब्जेक्ट
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```

ऐसा सेल प्राप्त करता है जिसका उपयोग चार्ट सीरीज़ या श्रेणियों के लिए किया जा सकता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| worksheetIndex | int | वर्कशीट का सूचकांक। |
| row | int | पंक्ति। |
| column | int | कॉलम। |
| value | java.lang.Object | मान। |

**रिटर्न:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell ऑब्जेक्ट
### clear(int sheetIndex) {#clear-int-}
```
public final void clear(int sheetIndex)
```

शीट पर सभी सेल मान साफ़ करें

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sheetIndex | int | शीट का सूचकांक |

### calculateFormulas() {#calculateFormulas--}
```
public final void calculateFormulas()
```

वर्कबुक में सभी फ़ॉर्मूले की गणना करता है और संबंधित सेल मानों को अपडेट करता है।

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