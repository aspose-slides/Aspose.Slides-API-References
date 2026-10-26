---
title: ExcelDataWorkbook
second_title: Aspose.Slides के लिए Java API संदर्भ
description: एक कार्यपुस्तिका को दर्शाता है जो सामान्य उपयोग के लिए Excel डेटा तक पहुँच प्रदान करती है।
type: docs
url: /hi/com.aspose.slides/exceldataworkbook/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook)  
```
public class ExcelDataWorkbook implements IExcelDataWorkbook
```

एक कार्यपुस्तिका का प्रतिनिधित्व करता है जो सामान्य उपयोग के लिए Excel डेटा तक पहुँच प्रदान करता है।

## Constructors

| Constructor | Description |
| --- | --- |
| [ExcelDataWorkbook(String filePath)](#ExcelDataWorkbook-java.lang.String-) | निर्दिष्ट फ़ाइल पथ का उपयोग करके एक नया उदाहरण आरंभ करता है। |
| [ExcelDataWorkbook(InputStream stream)](#ExcelDataWorkbook-java.io.InputStream-) | प्रदान किए गए स्ट्रीम का उपयोग करके वर्ग का एक नया उदाहरण आरंभ करता है। |

## Methods

| Method | Description |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | कार्यपुस्तिका से उन कोशिकाओं का संग्रह पुनः प्राप्त करता है जो निर्दिष्ट सूत्र से मेल खाते हैं। |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | निर्दिष्ट कार्यपत्रिका से उसकी अनुक्रमणिका और कोशिका निर्देशांक का उपयोग करके एक कोशिका पुनः प्राप्त करता है। |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | निर्दिष्ट कार्यपत्रिका से उसका नाम और कोशिका निर्देशांक का उपयोग करके एक कोशिका पुनः प्राप्त करता है। |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | निर्दिष्ट कार्यपत्रिका से उसकी अनुक्रमणिका और Excel-शैली कोशिका नाम (उदाहरण: "B2") का उपयोग करके एक कोशिका पुनः प्राप्त करता है। |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | निर्दिष्ट कार्यपत्रिका से Excel-शैली कोशिका नाम (उदाहरण: "B2") का उपयोग करके एक कोशिका पुनः प्राप्त करता है। |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | निर्दिष्ट Excel कार्यपुस्तिका की कार्यपत्रिका में सभी चार्ट्स के अनुक्रमणिका और नामों वाला शब्दकोश पुनः प्राप्त करता है। |
| [getWorksheetNames()](#getWorksheetNames--) | Excel कार्यपुस्तिका में मौजूद सभी कार्यपत्रिकाओं के नाम पुनः प्राप्त करता है। |

### ExcelDataWorkbook(String filePath) {#ExcelDataWorkbook-java.lang.String-}
```
public ExcelDataWorkbook(String filePath)
```

निर्दिष्ट फ़ाइल पथ का उपयोग करके एक नया उदाहरण आरंभ करता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Excel कार्यपुस्तिका फ़ाइल का पूर्ण पथ। |

### ExcelDataWorkbook(InputStream stream) {#ExcelDataWorkbook-java.io.InputStream-}
```
public ExcelDataWorkbook(InputStream stream)
```

प्रदान किए गए स्ट्रीम का उपयोग करके वर्ग का एक नया उदाहरण आरंभ करता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Excel कार्यपुस्तिका डेटा समाहित करने वाला स्ट्रीम। |

### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public final System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

निर्दिष्ट सूत्र से मेल खाने वाली कोशिकाओं का संग्रह पुनः प्राप्त करता है।

--------------------

> ```
> ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //आउटपुट: 5
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | लक्ष्य कोशिकाओं की पहचान करने के लिये उपयोग किया जाने वाला सूत्र या रेंज अभिव्यक्ति (उदाहरण: "Sheet1!A1:B3")। |
| skipHiddenCells | boolean | यदि true हो, तो छुपी हुई कोशिकाएँ (जैसे छुपी पंक्तियों या स्तंभों में) परिणाम में शामिल नहीं होंगी। |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - एक पढ़ने-के-लिए-केवल सूची जिसमें निर्दिष्ट सूत्र से मेल खाने वाली कोशिकाएँ होती हैं।

### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

निर्दिष्ट कार्यपत्रिका से उसकी अनुक्रमणिका और कोशिका निर्देशांक का उपयोग करके एक कोशिका पुनः प्राप्त करता है।

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | कार्यपत्रिका का शून्य-आधारित अनुक्रमणिका। |
| row | int | कोशिका की शून्य-आधारित पंक्ति अनुक्रमणिका। |
| column | int | कोशिका की शून्य-आधारित स्तंभ अनुक्रमणिका। |

**Returns:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - निर्दिष्ट स्थान पर स्थित कोशिका।

### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IExcelDataCell getCell(String worksheetName, int row, int column)
```

निर्दिष्ट कार्यपत्रिका से उसका नाम और कोशिका निर्देशांक का उपयोग करके एक कोशिका पुनः प्राप्त करता है।

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | java.lang.String | कार्यपत्रिका का नाम। |
| row | int | कोशिका की शून्य-आधारित पंक्ति अनुक्रमणिका। |
| column | int | कोशिका की शून्य-आधारित स्तंभ अनुक्रमणिका। |

**Returns:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - निर्दिष्ट स्थान पर स्थित कोशिका।

### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IExcelDataCell getCell(int worksheetIndex, String cellName)
```

निर्दिष्ट कार्यपत्रिका से उसकी अनुक्रमणिका और Excel-शैली कोशिका नाम (उदाहरण: "B2") का उपयोग करके एक कोशिका पुनः प्राप्त करता है।

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | int | कार्यपत्रिका का शून्य-आधारित अनुक्रमणिका। |
| cellName | java.lang.String | Excel-शैली कोशिका संदर्भ (उदाहरण: "A1", "C5")। |

**Returns:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - निर्दिष्ट स्थान पर स्थित कोशिका।

### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public final IExcelDataCell getCell(String worksheetName, String cellName)
```

निर्दिष्ट कार्यपत्रिका से Excel-शैली कोशिका नाम (उदाहरण: "B2") का उपयोग करके एक कोशिका पुनः प्राप्त करता है।

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | java.lang.String | कार्यपत्रिका का नाम। |
| cellName | java.lang.String | Excel-शैली कोशिका संदर्भ (उदाहरण: "A1", "C5")। |

**Returns:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - निर्दिष्ट स्थान पर स्थित कोशिका।

### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public final System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

निर्दिष्ट Excel कार्यपुस्तिका की कार्यपत्रिका में सभी चार्ट्स के अनुक्रमणिका और नामों वाला शब्दकोश पुनः प्राप्त करता है।

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | java.lang.String | चार्ट्स की खोज हेतु कार्यपत्रिका का नाम। |

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - एक शब्दकोश जहाँ कुंजी चार्ट की अनुक्रमणिका है और मान चार्ट का नाम है।

### getWorksheetNames() {#getWorksheetNames--}
```
public final System.Collections.Generic.List<String> getWorksheetNames()
```

Excel कार्यपुस्तिका में सम्मिलित सभी कार्यपत्रिकाओं के नाम पुनः प्राप्त करता है।

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - कार्यपत्रिका नामों की एक सूची