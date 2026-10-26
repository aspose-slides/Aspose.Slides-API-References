---
title: IChartSeriesCollection
second_title: Aspose.Slides for Android을 위한 Java API 레퍼런스
description: 컬렉션을 나타냅니다
type: docs
url: /ko/com.aspose.slides/ichartseriescollection/
---
**구현된 모든 인터페이스:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesCollection extends IGenericCollection<IChartSeries>
```

[IChartSeries](../../com.aspose.slides/ichartseries)의 컬렉션을 나타냅니다
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 요소를 가져옵니다. |
| [add(int type)](#add-int-) | 새 차트 시리즈를 생성하고 컬렉션에 추가합니다. |
| [insert(int index, int type)](#insert-int-int-) | 새 차트 시리즈를 생성하고 컬렉션에 삽입합니다. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | [IChartDataCell](../../com.aspose.slides/ichartdatacell)에서 새 차트 시리즈를 생성하고 컬렉션에 추가합니다. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection)에서 새 차트 시리즈를 생성하고 컬렉션에 추가합니다. |
| [add(String name, int type)](#add-java.lang.String-int-) | 값에서 새 차트 시리즈를 생성하고 컬렉션에 추가합니다. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | 지정된 [IChartSeries](../../com.aspose.slides/ichartseries)를 검색하고 전체 컬렉션에서 첫 번째 발생의 0 기반 인덱스를 반환합니다. |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | 지정된 값을 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스의 요소를 제거합니다. |
| [clear()](#clear--) | 컬렉션에서 모든 요소(차트 스타일 포함)를 제거합니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

지정된 인덱스의 요소를 가져옵니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 지정된 인덱스의 요소.

### add(int type) {#add-int-}
```
public abstract IChartSeries add(int type)
```

새 차트 시리즈를 생성하고 컬렉션에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| type | int | 시리즈 유형 |

**반환값:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 새 차트 시리즈.

### insert(int index, int type) {#insert-int-int-}
```
public abstract IChartSeries insert(int index, int type)
```

새 차트 시리즈를 생성하고 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 삽입을 위한 인덱스 |
| type | int | 차트 유형 [ChartType](../../com.aspose.slides/charttype) |

**반환값:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 새 차트 시리즈 [IChartSeries](../../com.aspose.slides/ichartseries)

### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public abstract IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

[IChartDataCell](../../com.aspose.slides/ichartdatacell)에서 새 차트 시리즈를 생성하고 컬렉션에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 시리즈 이름을 포함하는 셀 |
| type | int | 시리즈 유형 설정

--------------------

같은 셀에서 생성된 차트 시리즈가 이미 컬렉션에 존재한다면 메서드는 아무것도 추가하지 않고 해당 인덱스를 반환합니다. |

**반환값:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 컬렉션에 이미 존재하는 경우에도 추가된 차트 시리즈 또는 기존 시리즈.

### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public abstract IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)에서 새 차트 시리즈를 생성하고 컬렉션에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | 시리즈 이름을 포함하는 셀 |
| type | int | 시리즈 유형 설정

--------------------

같은 셀에서 생성된 차트 시리즈가 이미 컬렉션에 존재한다면 메서드는 아무것도 추가하지 않고 해당 인덱스를 반환합니다. |

**반환값:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 컬렉션에 이미 존재하는 경우에도 추가된 차트 시리즈 또는 기존 시리즈.

### add(String name, int type) {#add-java.lang.String-int-}
```
public abstract IChartSeries add(String name, int type)
```

값에서 새 차트 시리즈를 생성하고 컬렉션에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 시리즈 이름 |
| type | int | 시리즈 유형 설정 |

**반환값:**
[IChartSeries](../../com.aspose.slides/ichartseries) - 추가된 차트 시리즈.

### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public abstract int indexOf(IChartSeries value)
```

지정된 [IChartSeries](../../com.aspose.slides/ichartseries)를 검색하고 전체 컬렉션에서 첫 번째 발생의 0 기반 인덱스를 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | 차트 시리즈 값 |

**반환값:**
int - 값이 전체 CollectionBase 내에서 처음 나타나는 위치의 0 기반 인덱스이며, 찾지 못하면 -1을 반환합니다.

### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public abstract void remove(IChartSeries value)
```

지정된 값을 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | 값.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

지정된 인덱스의 요소를 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 인덱스

### clear() {#clear--}
```
public abstract void clear()
```

컬렉션에서 모든 요소(차트 스타일 포함)를 제거합니다.