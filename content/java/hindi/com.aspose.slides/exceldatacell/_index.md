---
title: ExcelDataCell
second_title: Aspose.Slides for Java API संदर्भ
description: Excel कार्यपुस्तिका में एकल कोशिका का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/exceldatacell/
---
**विरासत:**  
java.lang.Object

**सभी कार्यान्वित इंटरफ़ेस:**  
[com.aspose.slides.IExcelDataCell](../../com.aspose.slides/iexceldatacell)  
```
public class ExcelDataCell implements IExcelDataCell
```

Excel कार्यपुस्तिका में एकल कोशिका का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getValue()](#getValue--) | Excel कोशिका में सम्मिलित मान को प्राप्त करता है। |
| [getName()](#getName--) | चार्ट डेटा कोशिका का नाम प्राप्त करता है। |
| [getRow()](#getRow--) | वह पंक्ति का शून्य-आधारित सूचकांक प्राप्त करता है जहाँ कोशिका कार्यपत्र में स्थित है। |
| [getColumn()](#getColumn--) | वह स्तंभ का शून्य-आधारित सूचकांक प्राप्त करता है जहाँ कोशिका कार्यपत्र में स्थित है। |

### getValue() {#getValue--}
```
public final Object getValue()
```

Excel कोशिका में सम्मिलित मान को प्राप्त करता है।

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```


**वापसी:**  
java.lang.Object

### getName() {#getName--}
```
public final String getName()
```

चार्ट डेटा कोशिका का नाम प्राप्त करता है।

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //आउटपुट: "B2"
> ```


**वापसी:**  
java.lang.String

### getRow() {#getRow--}
```
public final int getRow()
```

कार्यपत्र में वह पंक्ति का शून्य-आधारित सूचकांक प्राप्त करता है जहाँ कोशिका स्थित है। केवल-पढ़ने योग्य int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //आउटपुट: 1
> ```


**वापसी:**  
int

### getColumn() {#getColumn--}
```
public final int getColumn()
```

कार्यपत्र में वह स्तंभ का शून्य-आधारित सूचकांक प्राप्त करता है जहाँ कोशिका स्थित है। केवल-पढ़ने योग्य int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getColumn()); //आउटपुट: 1
> ```


**वापसी:**  
int