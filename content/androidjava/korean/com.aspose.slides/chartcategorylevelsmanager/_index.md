---
title: ChartCategoryLevelsManager
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 차트 카테고리 레벨 값들을 관리하는 컨테이너.
type: docs
url: /ko/com.aspose.slides/chartcategorylevelsmanager/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)  
```
public class ChartCategoryLevelsManager implements IChartCategoryLevelsManager
```

차트 범주 레벨의 값을 관리하는 컨테이너.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | 정의된 레벨에 대한 IChartDataCell 객체를 반환합니다. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | 정의된 레벨에 대한 그룹화 항목을 설정합니다. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | 정의된 레벨에 대한 그룹화 항목을 삭제합니다. |

### get_Item(int level) {#get-Item-int-}
```
public final IChartDataCell get_Item(int level)
```

정의된 레벨에 대한 IChartDataCell 객체를 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| level | int |  |

**반환:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public final void setGroupingItem(int level, Object value)
```

정의된 레벨에 대한 그룹화 항목을 설정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| level | int |  |
| value | java.lang.Object |  |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public final void deleteGroupingItem(int level)
```

정의된 레벨에 대한 그룹화 항목을 삭제합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| level | int |  |