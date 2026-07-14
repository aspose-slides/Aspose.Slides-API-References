---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Managed container of the values of the chart category levels.
type: docs
url: /ko/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

차트 카테고리 레벨 값들의 관리 컨테이너입니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | 정의된 레벨에 대한 IChartDataCell 객체를 반환합니다. |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | 정의된 레벨에 대한 그룹화 항목을 설정합니다. |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | 정의된 레벨에 대한 그룹화 항목을 삭제합니다. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```

정의된 레벨에 대한 IChartDataCell 객체를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| level | int |  |

**반환값:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public abstract void setGroupingItem(int level, Object value)
```

정의된 레벨에 대한 그룹화 항목을 설정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| level | int | 카테고리 레벨 int |
| value | java.lang.Object | 그룹화 항목 Object |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```

정의된 레벨에 대한 그룹화 항목을 삭제합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| level | int | 카테고리 레벨 int |