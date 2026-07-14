---
title: GradientStopCollection
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 그라디언트 스톱 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/gradientstopcollection/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
```
public final class GradientStopCollection extends PVIObject implements IGradientStopCollection
```

그라디언트 스톱들의 컬렉션을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [size()](#size--) | 컬렉션에 포함된 그라디언트 스톱의 수를 반환합니다. |
| [get_Item(int index)](#get-Item-int-) | 인덱스로 그라디언트 스톱을 반환합니다. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | 새 그라디언트 스톱을 생성하고 컬렉션 끝에 추가합니다. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | 새 그라디언트 스톱을 생성하고 컬렉션 끝에 추가합니다. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | 새 그라디언트 스톱을 생성하고 컬렉션 끝에 추가합니다. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | 새 그라디언트 스톱을 생성하고 지정된 인덱스에 컬렉션에 삽입합니다. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | 새 그라디언트 스톱을 생성하고 지정된 인덱스에 컬렉션에 삽입합니다. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | 새 그라디언트 스톱을 생성하고 지정된 인덱스에 컬렉션에 삽입합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스의 그라디언트 스톱을 제거합니다. |
| [clear()](#clear--) | 컬렉션의 모든 그라디언트 스톱을 제거합니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java iterator를 반환합니다. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 컬렉션의 모든 요소를 지정된 배열에 복사합니다. |
| [isSynchronized()](#isSynchronized--) | 컬렉션에 대한 접근이 동기화(스레드 안전)되어 있는지 여부를 나타내는 값을 반환합니다. |
| [getSyncRoot()](#getSyncRoot--) | 동기화 루트를 반환합니다. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

버전. 읽기 전용 long.

**반환값:**
long

### size() {#size--}
```
public final int size()
```

컬렉션에 포함된 그라디언트 스톱의 수를 반환합니다. 읽기 전용 int .

**반환값:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IGradientStop get_Item(int index)
```

인덱스로 그라디언트 스톱을 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[IGradientStop](../../com.aspose.slides/igradientstop)

### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public final IGradientStop add(float position, Integer color)
```

새 그라디언트 스톱을 생성하고 컬렉션 끝에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | float | 새 그라디언트 스톱의 위치. |
| color | java.lang.Integer | 새 그라디언트 스톱의 색상. |

**반환값:**
[IGradientStop](../../com.aspose.slides/igradientstop) - 컬렉션에서 새로운 그라디언트 스톱의 인덱스.

### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public final IGradientStop addPresetColor(float position, int presetColor)
```

새 그라디언트 스톱을 생성하고 컬렉션 끝에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | float | 새 그라디언트 스톱의 위치. |
| presetColor | int | 새 그라디언트 스톱의 색상. |

**반환값:**
[IGradientStop](../../com.aspose.slides/igradientstop) - 컬렉션에서 새로운 그라디언트 스톱의 인덱스.

### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public final IGradientStop addSchemeColor(float position, int schemeColor)
```

새 그라디언트 스톱을 생성하고 컬렉션 끝에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | float | 새 그라디언트 스톱의 위치. |
| schemeColor | int | 새 그라디언트 스톱의 색상. |

**반환값:**
[IGradientStop](../../com.aspose.slides/igradientstop) - 컬렉션에서 새로운 그라디언트 스톱의 인덱스.

### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public final void insert(int index, float position, Integer color)
```

새 그라디언트 스톱을 생성하고 지정된 인덱스에 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 새 그라디언트 스톱이 삽입될 컬렉션 내 인덱스. |
| position | float | 새 그라디언트 스톱의 위치. |
| color | java.lang.Integer | 새 그라디언트 스톱의 색상. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```

새 그라디언트 스톱을 생성하고 지정된 인덱스에 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 새 그라디언트 스톱이 삽입될 컬렉션 내 인덱스. |
| position | float | 새 그라디언트 스톱의 위치. |
| presetColor | int | 새 그라디언트 스톱의 색상. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```

새 그라디언트 스톱을 생성하고 지정된 인덱스에 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 새 그라디언트 스톱이 삽입될 컬렉션 내 인덱스. |
| position | float | 새 그라디언트 스톱의 위치. |
| schemeColor | int | 새 그라디언트 스톱의 색상. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

지정된 인덱스의 그라디언트 스톱을 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 삭제할 그라디언트 스톱의 인덱스. |

### clear() {#clear--}
```
public final void clear()
```

컬렉션의 모든 그라디언트 스톱을 제거합니다.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iterator()
```

컬렉션을 순회하는 열거자를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - 컬렉션을 순회하는 데 사용할 수 있는 IGenericEnumerator.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```

전체 컬렉션에 대한 java iterator를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - 전체 컬렉션에 대한 java.util.Iterator.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

컬렉션의 모든 요소를 지정된 배열에 복사합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 대상 배열. |
| index | int | 대상 배열의 시작 인덱스. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

컬렉션에 대한 접근이 동기화(스레드 안전)되어 있는지 여부를 나타내는 값을 반환합니다. 읽기 전용 boolean .

**반환값:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

동기화 루트를 반환합니다. 읽기 전용 Object.

**반환값:**
java.lang.Object