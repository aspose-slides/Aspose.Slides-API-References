---
title: IExcelDataCell
second_title: Aspose.Slides Android용 Java API 참조
description: Excel 통합 문서에서 단일 셀을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

Excel 통합 문서에서 단일 셀을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getValue()](#getValue--) | Excel 셀에 포함된 값을 가져옵니다. |
| [getName()](#getName--) | 차트 데이터 셀의 이름을 가져옵니다. |
| [getRow()](#getRow--) | 셀의 위치가 지정된 워크시트에서 행의 0부터 시작하는 인덱스를 가져옵니다. |
| [getColumn()](#getColumn--) | 셀의 위치가 지정된 워크시트에서 열의 0부터 시작하는 인덱스를 가져옵니다. |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

Excel 셀에 포함된 값을 가져옵니다. 읽기 전용  Object .

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**반환:**
java.lang.Object
### getName() {#getName--}
```
public abstract String getName()
```

차트 데이터 셀의 이름을 가져옵니다. 읽기 전용 String.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //출력: "B2"
> ```

**반환:**
java.lang.String
### getRow() {#getRow--}
```
public abstract int getRow()
```

셀의 위치가 지정된 워크시트에서 행의 0부터 시작하는 인덱스를 가져옵니다. 읽기 전용 int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //출력: 1
> ```

**반환:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```

셀이 위치한 워크시트에서 열의 0부터 시작하는 인덱스를 가져옵니다. 읽기 전용 int.

--------------------

> ```
> Example:
>  
> v
> ```

**반환:**
int