---
title: ITrendlineCollection
second_title: Android용 Aspose.Slides Java API 참조
description: TrendlineEx 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/itrendlinecollection/
---
**모든 구현된 인터페이스:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ITrendlineCollection extends System.Collections.Generic.IGenericEnumerable<ITrendline>
```

TrendlineEx 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 요소를 가져옵니다. |
| [getCount()](#getCount--) | 컬렉션에 실제로 포함된 요소 수를 가져옵니다. |
| [add(int trendlineType)](#add-int-) | 새 Trendline을 컬렉션 끝에 추가하고 반환합니다. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | 지정된 값을 제거합니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITrendline get_Item(int index)
```

지정된 인덱스의 요소를 가져옵니다. 읽기 전용 [ITrendline](../../com.aspose.slides/itrendline).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[ITrendline](../../com.aspose.slides/itrendline)
### getCount() {#getCount--}
```
public abstract int getCount()
```

컬렉션에 실제로 포함된 요소 수를 가져옵니다. 읽기 전용 int.

**반환값:**
int
### add(int trendlineType) {#add-int-}
```
public abstract ITrendline add(int trendlineType)
```

새 Trendline을 컬렉션 끝에 추가하고 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| trendlineType | int | Trendline 유형 [TrendlineType](../../com.aspose.slides/trendlinetype) |

**반환값:**
[ITrendline](../../com.aspose.slides/itrendline) - 새 Trendline [ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public abstract void remove(ITrendline value)
```

지정된 값을 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) | 제거할 Trendline [ITrendline](../../com.aspose.slides/itrendline) |