---
title: IExcelDataCell
second_title: Aspose.Slides for Java API Reference
description: Excel कार्यपुस्तिका में एक एकल सेल का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

एक Excel कार्यपुस्तिका में एक एकल सेल का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getValue()](#getValue--) | Excel सेल में निहित मान प्राप्त करता है। |
| [getName()](#getName--) | चार्ट डेटा सेल का नाम प्राप्त करता है। |
| [getRow()](#getRow--) | कार्यशीट में जहाँ सेल स्थित है, उस पंक्ति का शून्य-आधारित सूचकांक प्राप्त करता है। |
| [getColumn()](#getColumn--) | कार्यशीट में जहाँ सेल स्थित है, उस कॉलम का शून्य-आधारित सूचकांक प्राप्त करता है। |
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Excel सेल में निहित मान प्राप्त करता है। केवल-पढ़ने योग्य Object .

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
public abstract String getName()
```


चार्ट डेटा सेल का नाम प्राप्त करता है। केवल-पढ़ने योग्य String.

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
public abstract int getRow()
```


कार्यशील शीट में जहाँ सेल स्थित है, उस पंक्ति का शून्य-आधारित सूचकांक प्राप्त करता है। केवल-पढ़ने योग्य int.

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
public abstract int getColumn()
```


कार्यशील शीट में जहाँ सेल स्थित है, उस कॉलम का शून्य-आधारित सूचकांक प्राप्त करता है। केवल-पढ़ने योग्य int.

--------------------

> ```
> Example:
>  
> v
> ```

**रिटर्न:**
int