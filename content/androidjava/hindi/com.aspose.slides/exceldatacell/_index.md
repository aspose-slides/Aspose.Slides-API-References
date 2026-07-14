---
title: ExcelDataCell
second_title: Aspose.Slides for Android द्वारा Java API संदर्भ
description: Excel कार्यपुस्तिका में एकल सेल का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/exceldatacell/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफेस:**
[com.aspose.slides.IExcelDataCell](../../com.aspose.slides/iexceldatacell)
```
public class ExcelDataCell implements IExcelDataCell
```

Excel कार्यपुस्तिका में एकल सेल का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getValue()](#getValue--) | Excel सेल में निहित मान प्राप्त करता है। |
| [getName()](#getName--) | चार्ट डेटा सेल का नाम प्राप्त करता है। |
| [getRow()](#getRow--) | कार्यपत्रक में उस पंक्ति का शून्य-आधारित अनुक्रमांक प्राप्त करता है जहाँ सेल स्थित है। |
| [getColumn()](#getColumn--) | कार्यपत्रक में उस स्तंभ का शून्य-आधारित अनुक्रमांक प्राप्त करता है जहाँ सेल स्थित है। |
### getValue() {#getValue--}
```
public final Object getValue()
```


Excel सेल में निहित मान प्राप्त करता है।

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**रिटर्न:**
java.lang.Object
### getName() {#getName--}
```
public final String getName()
```


चार्ट डेटा सेल का नाम प्राप्त करता है।

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //आउटपुट: "B2"
> ```

**रिटर्न:**
java.lang.String
### getRow() {#getRow--}
```
public final int getRow()
```


कार्यपत्रक में उस पंक्ति का शून्य-आधारित अनुक्रमांक प्राप्त करता है जहाँ सेल स्थित है। केवल-पढ़ने योग्य int।

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //आउटपुट: 1
> ```


**रिटर्न:**
int
### getColumn() {#getColumn--}
```
public final int getColumn()
```


कार्यपत्रक में उस स्तंभ का शून्य-आधारित अनुक्रमांक प्राप्त करता है जहाँ सेल स्थित है। केवल-पढ़ने योग्य int।

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getColumn()); //आउटपुट: 1
> ```


**रिटर्न:**
int