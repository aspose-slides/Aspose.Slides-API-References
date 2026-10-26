---
title: IRowCollection
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 테이블 행 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/irowcollection/
---
**구현된 모든 인터페이스:**
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

테이블 행 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 있는 요소를 가져옵니다. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | 지정된 템플릿 행의 복사본을 만든 다음 테이블 하단에 삽입합니다. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | 지정된 템플릿 행의 복사본을 만든 다음 테이블의 지정된 위치에 삽입합니다. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | 지정된 위치에서 테이블의 행을 제거합니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```

지정된 인덱스에 있는 요소를 가져옵니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] addClone(IRow templ, boolean withAttachedRows)
```

지정된 템플릿 행의 복사본을 만든 다음 테이블 하단에 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | 템플릿으로 사용되는 행. |
| withAttachedRows | boolean | 템플릿 행에 연결된 모든 행도 복사하려면 true. |

**반환값:**
com.aspose.slides.IRow[] - Added rows.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

지정된 템플릿 행의 복사본을 만든 다음 테이블의 지정된 위치에 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 새 행의 인덱스. |
| templ | [IRow](../../com.aspose.slides/irow) | 템플릿으로 사용되는 행. |
| withAttachedRows | boolean | 템플릿 행에 연결된 모든 행도 복사하려면 true. |

**반환값:**
com.aspose.slides.IRow[] - Inserted rows.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```

지정된 위치에서 테이블의 행을 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| firstRowIndex | int | 삭제할 행의 인덱스. |
| withAttachedRows | boolean | 연결된 모든 행도 삭제하려면 true. |