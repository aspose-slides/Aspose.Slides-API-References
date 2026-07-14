---
title: IRow
second_title: Aspose.Slides Android용 Java API 레퍼런스
description: 테이블에서 행을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/irow/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IRow extends ICellCollection, IBulkTextFormattable
```

테이블에서 행을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getHeight()](#getHeight--) | 행의 높이를 반환합니다. |
| [getMinimalHeight()](#getMinimalHeight--) | 행의 가능한 최소 높이를 반환하거나 설정합니다. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | 행의 가능한 최소 높이를 반환하거나 설정합니다. |
| [getRowFormat()](#getRowFormat--) | 이 행에 대한 서식 속성을 포함하는 RowFormat 객체를 반환합니다. |
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

행의 높이를 반환합니다. 읽기 전용 double.

**반환값:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

행의 가능한 최소 높이를 반환하거나 설정합니다. 읽기/쓰기 double.

**반환값:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public abstract void setMinimalHeight(double value)
```

행의 가능한 최소 높이를 반환하거나 설정합니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getRowFormat() {#getRowFormat--}
```
public abstract IRowFormat getRowFormat()
```

이 행에 대한 서식 속성을 포함하는 RowFormat 객체를 반환합니다. 읽기 전용 [IRowFormat](../../com.aspose.slides/irowformat).

**반환값:**
[IRowFormat](../../com.aspose.slides/irowformat)