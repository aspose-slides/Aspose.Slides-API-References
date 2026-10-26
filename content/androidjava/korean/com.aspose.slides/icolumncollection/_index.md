---
title: IColumnCollection
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 테이블의 열 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/icolumncollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IColumnCollection extends IGenericCollection<IColumn>
```

표의 열 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 있는 열을 반환합니다. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | 지정된 템플릿 행의 복사본을 만들어 표의 하단에 삽입합니다. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | 지정된 템플릿 열의 복사본을 만들어 표의 지정된 위치에 삽입합니다. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | 표의 지정된 위치에서 열을 제거합니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```

지정된 인덱스에 있는 열을 반환합니다. 읽기 전용 [IColumn](../../com.aspose.slides/icolumn).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

지정된 템플릿 행의 복사본을 만들어 표의 하단에 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | 템플릿으로 사용되는 열. |
| withAttachedColumns | boolean | 템플릿 행에 연결된 모든 열도 복사하려면 true. |

**반환값:**
com.aspose.slides.IColumn[] - 추가된 열.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

지정된 템플릿 열의 복사본을 만들어 표의 지정된 위치에 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 새 열의 인덱스. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | 템플릿으로 사용되는 열. |
| withAttachedColumns | boolean | 템플릿 열에 연결된 모든 열도 복사하려면 true. |

**반환값:**
com.aspose.slides.IColumn[] - 삽입된 열.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

표의 지정된 위치에서 열을 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| firstColumnIndex | int | 삭제할 열의 인덱스. |
| withAttachedRows | boolean | 연결된 모든 열도 삭제하려면 true. |