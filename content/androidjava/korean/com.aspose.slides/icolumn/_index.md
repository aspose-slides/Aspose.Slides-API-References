---
title: IColumn
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 테이블의 열을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/icolumn/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IColumn extends ICellCollection, IBulkTextFormattable
```

테이블의 열을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getWidth()](#getWidth--) | 열의 너비를 반환하거나 설정합니다. |
| [setWidth(double value)](#setWidth-double-) | 열의 너비를 반환하거나 설정합니다. |
| [getColumnFormat()](#getColumnFormat--) | 이 열에 대한 서식 속성을 포함하는 ColumnFormat 객체를 반환합니다. |
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

열의 너비를 반환하거나 설정합니다. 읽기/쓰기 double.

**반환:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

열의 너비를 반환하거나 설정합니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | double |  |

### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```

이 열에 대한 서식 속성을 포함하는 ColumnFormat 객체를 반환합니다. 읽기 전용 [IColumnFormat](../../com.aspose.slides/icolumnformat).

**반환:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)