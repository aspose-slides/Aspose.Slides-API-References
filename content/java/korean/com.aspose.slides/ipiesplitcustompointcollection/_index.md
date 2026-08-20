---
title: IPieSplitCustomPointCollection
second_title: Aspose.Slides for Java API 레퍼런스
description: 사용자 지정 분할이 있는 파이-바 차트 또는 파이-파이 차트의 두 번째 파이 또는 막대에 그려야 할 점들의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ipiesplitcustompointcollection/
---
**구현된 모든 인터페이스:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

사용자 지정 분할이 있는 파이-바 차트 또는 파이-파이 차트의 두 번째 파이 또는 막대에 그려야 할 점들의 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 인덱스로 차트 데이터 포인트를 반환합니다. |
| [add(int dataPointIndex)](#add-int-) | 부모 시리즈 포인트 컬렉션에서 인덱스로 데이터 포인트를 추가합니다. |
| [remove(int dataPointIndex)](#remove-int-) | 부모 시리즈 포인트 컬렉션에서 인덱스로 컬렉션 항목을 제거합니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

인덱스로 차트 데이터 포인트를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 데이터 포인트의 인덱스. |

**반환값:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 차트 데이터 포인트.
### add(int dataPointIndex) {#add-int-}
```
public abstract void add(int dataPointIndex)
```

부모 시리즈 포인트 컬렉션에서 인덱스로 데이터 포인트를 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dataPointIndex | int | 부모 시리즈 포인트 컬렉션에서 데이터 포인트의 인덱스. |

### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```

부모 시리즈 포인트 컬렉션에서 인덱스로 컬렉션 항목을 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dataPointIndex | int | 부모 시리즈 포인트 컬렉션에서 데이터 포인트의 인덱스.. |