---
title: IExcelDataWorkbook
second_title: Aspose.Slides for Java API Reference
description: सामान्य उपयोग के लिए Excel डेटा तक पहुंच प्रदान करने वाली एक वर्कबुक को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/iexceldataworkbook/
---```
public interface IExcelDataWorkbook
```

सामान्य उपयोग के लिए Excel डेटा तक पहुंच प्रदान करने वाली एक वर्कबुक को दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | निर्दिष्ट सूत्र से मेल खाने वाले वर्कबुक के सेल्स का संग्रह प्राप्त करता है। |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | निर्दिष्ट वर्कशीट से उसके इंडेक्स और सेल निर्देशांक का उपयोग करके एक सेल प्राप्त करता है। |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | निर्दिष्ट वर्कशीट से उसके नाम और सेल निर्देशांक का उपयोग करके एक सेल प्राप्त करता है। |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | निर्दिष्ट वर्कशीट से उसके इंडेक्स और Excel-शैली के सेल नाम (जैसे, "B2") का उपयोग करके एक सेल प्राप्त करता है। |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | निर्दिष्ट वर्कशीट से Excel-शैली के सेल नाम (जैसे, "B2") का उपयोग करके एक सेल प्राप्त करता है। |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Excel वर्कबुक के निर्दिष्ट वर्कशीट में सभी चार्ट्स के इंडेक्स और नामों वाला शब्दकोश प्राप्त करता है। |
| [getWorksheetNames()](#getWorksheetNames--) | Excel वर्कबुक में सम्मिलित सभी वर्कशीट्स के नाम प्राप्त करता है। |
### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public abstract System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

निर्दिष्ट सूत्र से मेल खाने वाले वर्कबुक के सेल्स का संग्रह प्राप्त करता है।

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //आउटपुट: 5
>  ```


**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| formula | java.lang.String | लक्ष्य सेल्स को पहचानने के लिए प्रयुक्त सूत्र या रेंज अभिव्यक्ति (जैसे, "Sheet1!A1:B3")। |
| skipHiddenCells | boolean | यदि true होता है, तो छिपे हुए सेल्स (जैसे, छिपी पंक्तियों या कॉलमों में) परिणाम से बाहर कर दिए जाएंगे। |

**वापसी:**  
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - निर्दिष्ट सूत्र से मेल खाने वाले सेल्स की एक केवल-पढ़ने योग्य सूची।

### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

निर्दिष्ट वर्कशीट से उसके इंडेक्स और सेल निर्देशांक का उपयोग करके एक सेल प्राप्त करता है।

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
| worksheetIndex | int | वर्कशीट का शून्य-आधारित इंडेक्स। |
| row | int | सेल की शून्य-आधारित पंक्ति इंडेक्स। |
| column | int | सेल की शून्य-आधारित कॉलम इंडेक्स। |

**वापसी:**  
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - निर्दिष्ट स्थान पर स्थित सेल।

### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IExcelDataCell getCell(String worksheetName, int row, int column)
```

निर्दिष्ट वर्कशीट से उसके नाम और सेल निर्देशांक का उपयोग करके एक सेल प्राप्त करता है।

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
| worksheetName | java.lang.String | वर्कशीट का नाम। |
| row | int | सेल की शून्य-आधारित पंक्ति इंडेक्स। |
| column | int | सेल की शून्य-आधारित कॉलम इंडेक्स। |

**वापसी:**  
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - निर्दिष्ट स्थान पर स्थित सेल।

### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, String cellName)
```

निर्दिष्ट वर्कशीट से उसके इंडेक्स और Excel-शैली के सेल नाम (जैसे, "B2") का उपयोग करके एक सेल प्राप्त करता है।

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
| worksheetIndex | int | वर्कशीट का शून्य-आधारित इंडेक्स। |
| cellName | java.lang.String | Excel-शैली की सेल संदर्भ (जैसे, "A1", "C5")। |

**वापसी:**  
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - निर्दिष्ट स्थान पर स्थित सेल।

### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public abstract IExcelDataCell getCell(String worksheetName, String cellName)
```

निर्दिष्ट वर्कशीट से Excel-शैली के सेल नाम (जैसे, "B2") का उपयोग करके एक सेल प्राप्त करता है।

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
| worksheetName | java.lang.String | वर्कशीट का नाम। |
| cellName | java.lang.String | Excel-शैली की सेल संदर्भ (जैसे, "A1", "C5")। |

**वापसी:**  
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - निर्दिष्ट स्थान पर स्थित सेल।

### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public abstract System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

निर्दिष्ट वर्कशीट में सभी चार्ट्स के इंडेक्स और नामों वाला शब्दकोश प्राप्त करता है।

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
| worksheetName | java.lang.String | चार्ट्स की खोज के लिए वर्कशीट का नाम। |

**वापसी:**  
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - एक शब्दकोश जहाँ कुंजी चार्ट का इंडेक्स और मान चार्ट का नाम है।

### getWorksheetNames() {#getWorksheetNames--}
```
public abstract System.Collections.Generic.List<String> getWorksheetNames()
```

Excel वर्कबुक में सम्मिलित सभी वर्कशीट्स के नाम प्राप्त करता है।

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
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - वर्कशीट नामों की एक सूची