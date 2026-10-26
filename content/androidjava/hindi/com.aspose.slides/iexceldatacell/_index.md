---
title: IExcelDataCell
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a single cell in an Excel workbook.
type: docs
url: /hi/com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

Excel कार्यपुस्तिका में एक एकल सेल का प्रतिनिधित्व करता है।

## विधियां

| विधि | विवरण |
| --- | --- |
| [getValue()](#getValue--) | Excel सेल में निहित मान प्राप्त करता है। |
| [getName()](#getName--) | चार्ट डेटा सेल का नाम प्राप्त करता है। |
| [getRow()](#getRow--) | उस कार्यपत्र में पंक्ति का शून्य-आधारित सूचकांक प्राप्त करता है जहाँ सेल स्थित है। |
| [getColumn()](#getColumn--) | उस कार्यपत्र में कॉलम का शून्य-आधारित सूचकांक प्राप्त करता है जहाँ सेल स्थित है। |
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Excel सेल में निहित मान प्राप्त करता है। केवल पढ़ने योग्य Object ।

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
```

**वापसी:**  
java.lang.Object
### getName() {#getName--}
```
public abstract String getName()
```


चार्ट डेटा सेल का नाम प्राप्त करता है। केवल पढ़ने योग्य String।

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
public abstract int getRow()
```


उस कार्यपत्र में पंक्ति का शून्य-आधारित सूचकांक प्राप्त करता है जहाँ सेल स्थित है। केवल पढ़ने योग्य int।

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
public abstract int getColumn()
```


उस कार्यपत्र में कॉलम का शून्य-आधारित सूचकांक प्राप्त करता है जहाँ सेल स्थित है। केवल पढ़ने योग्य int।

--------------------

> ```
> Example:
>  
> v
> ```

**वापसी:**  
int