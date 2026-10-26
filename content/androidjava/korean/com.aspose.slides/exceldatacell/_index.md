---
title: ExcelDataCell
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: Excel 통합 문서의 단일 셀을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/exceldatacell/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.IExcelDataCell](../../com.aspose.slides/iexceldatacell)  
```
public class ExcelDataCell implements IExcelDataCell
```

Excel 통합 문서의 단일 셀을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getValue()](#getValue--) | Excel 셀에 포함된 값을 가져옵니다. |
| [getName()](#getName--) | 차트 데이터 셀의 이름을 가져옵니다. |
| [getRow()](#getRow--) | 셀의 위치가 있는 워크시트에서 행의 0부터 시작하는 인덱스를 가져옵니다. |
| [getColumn()](#getColumn--) | 셀의 위치가 있는 워크시트에서 열의 0부터 시작하는 인덱스를 가져옵니다. |

### getValue() {#getValue--}
```
public final Object getValue()
```

Excel 셀에 포함된 값을 가져옵니다.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**반환값:**  
java.lang.Object

### getName() {#getName--}
```
public final String getName()
```

차트 데이터 셀의 이름을 가져옵니다.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //출력: "B2"
> ```

**반환값:**  
java.lang.String

### getRow() {#getRow--}
```
public final int getRow()
```

셀의 위치가 있는 워크시트에서 행의 0부터 시작하는 인덱스를 가져옵니다. 읽기 전용 int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //출력: 1
> ```

**반환값:**  
int

### getColumn() {#getColumn--}
```
public final int getColumn()
```

셀의 위치가 있는 워크시트에서 열의 0부터 시작하는 인덱스를 가져옵니다. 읽기 전용 int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getColumn()); //출력: 1
> ```

**반환값:**  
int