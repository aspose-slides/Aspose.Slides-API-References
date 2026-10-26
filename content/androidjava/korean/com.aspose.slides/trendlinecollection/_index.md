---
title: TrendlineCollection
second_title: Aspose.Slides for Android용 Java API 참조
description: Trendline 컬렉션을 나타냅니다
type: docs
url: /ko/com.aspose.slides/trendlinecollection/
---
**상속:**  
java.lang.Object, com.aspose.slides.DomObject

**구현된 모든 인터페이스:**  
[com.aspose.slides.ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)  
```
public class TrendlineCollection extends DomObject<ChartSeries> implements ITrendlineCollection
```

Trendline 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 있는 요소를 가져옵니다. |
| [add(int trendlineType)](#add-int-) | 새 Trendline을 컬렉션 끝에 추가하고 반환합니다. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | 지정된 값을 제거합니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java iterator를 반환합니다. |
| [getCount()](#getCount--) | 컬렉션에 실제로 포함된 요소 수를 가져옵니다. |

### get_Item(int index) {#get-Item-int-}
```
public final ITrendline get_Item(int index)
```

지정된 인덱스에 있는 요소를 가져옵니다. 읽기 전용 [Trendline](../../com.aspose.slides/trendline).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[ITrendline](../../com.aspose.slides/itrendline)

### add(int trendlineType) {#add-int-}
```
public final ITrendline add(int trendlineType)
```

새 Trendline을 컬렉션 끝에 추가하고 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| trendlineType | int |  |

**반환값:**
[ITrendline](../../com.aspose.slides/itrendline)

### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public final void remove(ITrendline value)
```

지정된 값을 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iterator()
```

컬렉션을 순회하는 열거자를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - 컬렉션을 순회하는 데 사용할 수 있는 IGenericEnumerator.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iteratorJava()
```

전체 컬렉션에 대한 java iterator를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - 전체 컬렉션에 대한 java.util.Iterator.

### getCount() {#getCount--}
```
public final int getCount()
```

컬렉션에 실제로 포함된 요소 수를 가져옵니다. 읽기 전용 int.

**반환값:**
int