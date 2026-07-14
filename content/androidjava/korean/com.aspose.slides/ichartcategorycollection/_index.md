---
title: IChartCategoryCollection
second_title: Java API 레퍼런스 - Android용 Aspose.Slides
description: 컬렉션을 나타냅니다
type: docs
url: /ko/com.aspose.slides/ichartcategorycollection/
---
**모든 구현된 인터페이스:**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

컬렉션을 나타냅니다 [IChartCategory](../../com.aspose.slides/ichartcategory)
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 요소를 가져옵니다. |
| [getUseCells()](#getUseCells--) | true이면 워크시트가 카테고리를 저장하는 데 사용됩니다(이 경우 다중 레벨 카테고리를 지원합니다). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | true이면 워크시트가 카테고리를 저장하는 데 사용됩니다(이 경우 다중 레벨 카테고리를 지원합니다). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | 사용된 카테고리 그룹화 수준의 개수를 반환합니다. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | 컬렉션에 카테고리가 존재하면 반환합니다. |
| [add(Object value)](#add-java.lang.Object-) | 값으로부터 새 [IChartCategory](../../com.aspose.slides/ichartcategory)을 생성하고 컬렉션에 추가합니다. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | 지정된 [IChartCategory](../../com.aspose.slides/ichartcategory)를 검색하고 전체 컬렉션 내 첫 번째 발생의 0 기반 인덱스를 반환합니다. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | 지정된 값을 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 주어진 인덱스의 요소를 제거합니다. |
| [clear()](#clear--) | 컬렉션의 모든 요소를 제거합니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
```

지정된 인덱스의 요소를 가져옵니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - 지정된 인덱스의 요소.

### getUseCells() {#getUseCells--}
```
public abstract boolean getUseCells()
```

true이면 워크시트가 카테고리를 저장하는 데 사용됩니다(이 경우 다중 레벨 카테고리를 지원합니다). false이면 워크시트가 값을 저장하는 데 사용되지 않습니다(이 경우 다중 레벨 카테고리를 지원하지 않습니다). 읽기/쓰기 부울.

**반환값:**
boolean

### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```

true이면 워크시트가 카테고리를 저장하는 데 사용됩니다(이 경우 다중 레벨 카테고리를 지원합니다). false이면 워크시트가 값을 저장하는 데 사용되지 않습니다(이 경우 다중 레벨 카테고리를 지원하지 않습니다). 읽기/쓰기 부울.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```

사용된 카테고리 그룹화 수준의 개수를 반환합니다. 다중 레벨 카테고리의 경우 1보다 큽니다. 읽기 전용 정수.

**반환값:**
int

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract IChartCategory add(IChartDataCell chartDataCell)
```

컬렉션에 카테고리가 존재하면 반환합니다. 그렇지 않으면 [IChartDataCell](../../com.aspose.slides/ichartdatacell)로부터 새로운 차트 카테고리를 생성하고 컬렉션에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 차트 카테고리를 생성하는 데 사용되는 셀. |

**반환값:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - 추가되었거나 기존 카테고리.

### add(Object value) {#add-java.lang.Object-}
```
public abstract IChartCategory add(Object value)
```

값으로부터 새 [IChartCategory](../../com.aspose.slides/ichartcategory)을 생성하고 컬렉션에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.Object | 값. |

--------------------

이 메서드는 이름이 AUTO_DATA인 워크시트를 추가하고 모든 값을 그곳에 추가합니다. [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)를 사용하여 셀 값을 추가하거나 편집하는 경우, 이 워크시트를 사용하지 않도록 하십시오. 이 메서드를 사용하여 추가되는 값의 최대 수는 16711680을 초과해서는 안 됩니다 |

**반환값:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - 추가된 [IChartCategory](../../com.aspose.slides/ichartcategory).

### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```

지정된 [IChartCategory](../../com.aspose.slides/ichartcategory)를 검색하고 전체 컬렉션 내 첫 번째 발생의 0 기반 인덱스를 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | 차트 카테고리. |

**반환값:**
int - 값이 전체 CollectionBase 내에서 첫 번째로 발생한 0 기반 인덱스(찾은 경우); 찾지 못하면 -1.

### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public abstract void remove(IChartCategory value)
```

지정된 값을 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | 값. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

주어진 인덱스의 요소를 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 제거할 카테고리의 인덱스. |

### clear() {#clear--}
```
public abstract void clear()
```

컬렉션의 모든 요소를 제거합니다.