---
title: IColumnCollection
second_title: Aspose.Slides for Java API 레퍼런스
description: 테이블의 열 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/icolumncollection/
---
**구현된 모든 인터페이스:**
com.aspose.slides.IGenericCollection
```
public interface IColumnCollection extends IGenericCollection<IColumn>
```

테이블에서 열의 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the column at the specified index. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Creates a copy of the specified template row and inserts it at the bottom of a table. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Creates a copy of the specified template column and insert it at the specified position in a table. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Removes a column at the specified position from a table. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```


지정된 인덱스의 열을 반환합니다. 읽기 전용 [IColumn](../../com.aspose.slides/icolumn).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```


지정된 템플릿 행의 복사본을 만들고 테이블 하단에 삽입합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | 템플릿으로 사용되는 열. |
| withAttachedColumns | boolean | 템플릿 행에 연결된 모든 열도 복사하려면 True. |

**반환값:**
com.aspose.slides.IColumn[] - 추가된 열.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```


지정된 템플릿 열의 복사본을 만들고 테이블의 지정된 위치에 삽입합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 새 열의 인덱스. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | 템플릿으로 사용되는 열. |
| withAttachedColumns | boolean | 템플릿 열에 연결된 모든 열도 복사하려면 True. |

**반환값:**
com.aspose.slides.IColumn[] - 삽입된 열.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```


테이블에서 지정된 위치의 열을 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| firstColumnIndex | int | 삭제할 열의 인덱스. |
| withAttachedRows | boolean | 연결된 모든 열도 삭제하려면 True. |