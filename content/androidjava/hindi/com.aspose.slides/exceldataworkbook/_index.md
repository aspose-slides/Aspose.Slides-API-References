---
title: ExcelDataWorkbook
second_title: Aspose.Slides Android के लिए Java API संदर्भ
description: एक कार्यपुस्तिका का प्रतिनिधित्व करता है जो सामान्य उपयोग के लिए Excel डेटा तक पहुँच प्रदान करती है।
type: docs
url: /hi/com.aspose.slides/exceldataworkbook/
---
**विरासत:**
java.lang.Object

**सभी लागू किए गए इंटरफ़ेस:**
[com.aspose.slides.IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook)
```
public class ExcelDataWorkbook implements IExcelDataWorkbook
```

Represents a workbook that provides access to Excel data for general use.

## कंस्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [ExcelDataWorkbook(String filePath)](#ExcelDataWorkbook-java.lang.String-) | निर्दिष्ट फ़ाइल पथ का उपयोग करके एक नया उदाहरण प्रारंभ करता है। |
| [ExcelDataWorkbook(InputStream stream)](#ExcelDataWorkbook-java.io.InputStream-) | प्रदान किए गए स्ट्रीम का उपयोग करके क्लास का एक नया उदाहरण प्रारंभ करता है। |

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | निर्दिष्ट सूत्र से मेल खाने वाले कार्यपुस्तिका से कोशिकाओं का संग्रह प्राप्त करता है। |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | निर्दिष्ट कार्यपत्रिका से उसकी अनुक्रमांक और कोशिका निर्देशांक का उपयोग करके एक कोशिका प्राप्त करता है। |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | निर्दिष्ट कार्यपत्रिका से उसका नाम और कोशिका निर्देशांक उपयोग करके एक कोशिका प्राप्त करता है। |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | निर्दिष्ट कार्यपत्रिका से उसकी अनुक्रमांक और Excel-शैली की कोशिका नाम (जैसे, "B2") का उपयोग करके एक कोशिका प्राप्त करता है। |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | निर्दिष्ट कार्यपत्रिका से Excel-शैली की कोशिका नाम (जैसे, "B2") का उपयोग करके एक कोशिका प्राप्त करता है। |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | एक Excel कार्यपुस्तिका की निर्दिष्ट कार्यपत्रिका में सभी चार्ट के अनुक्रमांक और नाम सम्मिलित शब्दकोश प्राप्त करता है। |
| [getWorksheetNames()](#getWorksheetNames--) | Excel कार्यपुस्तिका में सम्मिलित सभी कार्यपत्रिकाओं के नाम प्राप्त करता है। |

### ExcelDataWorkbook(String filePath) {#ExcelDataWorkbook-java.lang.String-}
```
public ExcelDataWorkbook(String filePath)
```

निर्दिष्ट फ़ाइल पथ का उपयोग करके एक नया उदाहरण प्रारंभ करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | java.lang.String | Excel कार्यपुस्तिका फ़ाइल का पूर्ण पथ। |

### ExcelDataWorkbook(InputStream stream) {#ExcelDataWorkbook-java.io.InputStream-}
```
public ExcelDataWorkbook(InputStream stream)
```

प्रदान किए गए स्ट्रीम का उपयोग करके क्लास का एक नया उदाहरण प्रारंभ करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.InputStream | Excel कार्यपुस्तिका डेटा समाहित करने वाला स्ट्रीम। |

### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public final System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

निर्दिष्ट सूत्र से मेल खाने वाले कार्यपुस्तिका से कोशिकाओं का संग्रह प्राप्त करता है।

--------------------

> ```
> ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //आउटपुट: 5
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| formula | java.lang.String | लक्ष्य कोशिकाओं की पहचान के लिए उपयोग किया गया सूत्र या रेंज अभिव्यक्ति (जैसे, "Sheet1!A1:B3")। |
| skipHiddenCells | boolean | यदि true है, तो छिपी हुई कोशिकाएँ (जैसे, छिपी हुई पंक्तियों या स्तंभों में) परिणाम से बाहर रखी जाएँगी। |

**वापसी:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - निर्दिष्ट सूत्र से मेल खाने वाली केवल-पठन योग्य कोशिकाओं की सूची।

### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

निर्दिष्ट कार्यपत्रिका से उसकी अनुक्रमांक और कोशिका निर्देशांक का उपयोग करके एक कोशिका प्राप्त करता है।

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| worksheetIndex | int | कार्यपत्रिका का शून्य-आधारित अनुक्रमांक। |
| row | int | कोशिका की शून्य-आधारित पंक्ति अनुक्रमांक। |
| column | int | कोशिका की शून्य-आधारित स्तंभ अनुक्रमांक। |

**वापसी:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - निर्दिष्ट स्थान पर स्थित कोशिका।

### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IExcelDataCell getCell(String worksheetName, int row, int column)
```

निर्दिष्ट कार्यपत्रिका से उसका नाम और कोशिका निर्देशांक का उपयोग करके एक कोशिका प्राप्त करता है।

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| worksheetName | java.lang.String | कार्यपत्रिका का नाम। |
| row | int | कोशिका की शून्य-आधारित पंक्ति अनुक्रमांक। |
| column | int | कोशिका की शून्य-आधारित स्तंभ अनुक्रमांक। |

**वापसी:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - निर्दिष्ट स्थान पर स्थित कोशिका।

### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IExcelDataCell getCell(int worksheetIndex, String cellName)
```

निर्दिष्ट कार्यपत्रिका से उसकी अनुक्रमांक और Excel-शैली की कोशिका नाम (जैसे, "B2") का उपयोग करके एक कोशिका प्राप्त करता है।

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| worksheetIndex | int | कार्यपत्रिका का शून्य-आधारित अनुक्रमांक। |
| cellName | java.lang.String | Excel-शैली की कोशिका संदर्भ (जैसे, "A1", "C5")। |

**वापसी:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - निर्दिष्ट स्थान पर स्थित कोशिका।

### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public final IExcelDataCell getCell(String worksheetName, String cellName)
```

निर्दिष्ट कार्यपत्रिका से Excel-शैली की कोशिका नाम (जैसे, "B2") का उपयोग करके एक कोशिका प्राप्त करता है।

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| worksheetName | java.lang.String | कार्यपत्रिका का नाम। |
| cellName | java.lang.String | Excel-शैली की कोशिका संदर्भ (जैसे, "A1", "C5")। |

**वापसी:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - निर्दिष्ट स्थान पर स्थित कोशिका।

### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public final System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

एक Excel कार्यपुस्तिका की निर्दिष्ट कार्यपत्रिका में सभी चार्ट के अनुक्रमांक और नाम सम्मिलित शब्दकोश प्राप्त करता है।

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  Dictionary.Enumerator<Integer, String> sheetCharts = wb.getChartsFromWorksheet("worksheetName").iterator();
>  while (sheetCharts.hasNext())
>  {
>      KeyValuePair<Integer, String> chart = sheetCharts.next();
>      System.out.println(chart.getKey() + " : " + chart.getValue());
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| worksheetName | java.lang.String | चार्ट खोजने के लिए कार्यपत्रिका का नाम। |

**वापसी:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - एक शब्दकोश जहाँ कुंजी चार्ट का अनुक्रमांक है और मान चार्ट का नाम है।

### getWorksheetNames() {#getWorksheetNames--}
```
public final System.Collections.Generic.List<String> getWorksheetNames()
```

Excel कार्यपुस्तिका में सम्मिलित सभी कार्यपत्रिकाओं के नाम प्राप्त करता है।

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```

**वापसी:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - एक कार्यपत्रिका नामों की सूची