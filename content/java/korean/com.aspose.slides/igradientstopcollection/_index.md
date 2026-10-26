---
title: IGradientStopCollection
second_title: Aspose.Slides for Java API 레퍼런스
description: 그라디언트 스톱 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/igradientstopcollection/
---
**구현된 모든 인터페이스:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

그라디언트 스톱 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 인덱스로 그라디언트 스톱을 반환합니다. |
| [add(float position, Color color)](#add-float-java.awt.Color-) | 새로운 그라디언트 스톱을 생성하고 컬렉션 끝에 추가합니다. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | 새로운 그라디언트 스톱을 생성하고 컬렉션 끝에 추가합니다. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | 새로운 그라디언트 스톱을 생성하고 컬렉션 끝에 추가합니다. |
| [insert(int index, float position, Color color)](#insert-int-float-java.awt.Color-) | 새로운 그라디언트 스톱을 생성하고 지정된 인덱스에 컬렉션에 삽입합니다. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | 새로운 그라디언트 스톱을 생성하고 지정된 인덱스에 컬렉션에 삽입합니다. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | 새로운 그라디언트 스톱을 생성하고 지정된 인덱스에 컬렉션에 삽입합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스에 있는 그라디언트 스톱을 제거합니다. |
| [clear()](#clear--) | 컬렉션에서 모든 그라디언트 스톱을 제거합니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```

인덱스로 그라디언트 스톱을 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Color color) {#add-float-java.awt.Color-}
```
public abstract IGradientStop add(float position, Color color)
```

새로운 그라디언트 스톱을 생성하고 컬렉션 끝에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| position | float | 새로운 그라디언트 스톱의 위치. |
| color | java.awt.Color | 새로운 그라디언트 스톱의 색상. |

**반환값:**
[IGradientStop](../../com.aspose.slides/igradientstop) - 컬렉션에서 새로운 그라디언트 스톱의 인덱스.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```

새로운 그라디언트 스톱을 생성하고 컬렉션 끝에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| position | float | 새로운 그라디언트 스톱의 위치. |
| presetColor | int | 새로운 그라디언트 스톱의 색상. |

**반환값:**
[IGradientStop](../../com.aspose.slides/igradientstop) - 컬렉션에서 새로운 그라디언트 스톱의 인덱스.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```

새로운 그라디언트 스톱을 생성하고 컬렉션 끝에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| position | float | 새로운 그라디언트 스톱의 위치. |
| schemeColor | int | 새로운 그라디언트 스톱의 색상. |

**반환값:**
[IGradientStop](../../com.aspose.slides/igradientstop) - 컬렉션에서 새로운 그라디언트 스톱의 인덱스.
### insert(int index, float position, Color color) {#insert-int-float-java.awt.Color-}
```
public abstract void insert(int index, float position, Color color)
```

새로운 그라디언트 스톱을 생성하고 지정된 인덱스에 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 새 그라디언트 스톱이 삽입될 컬렉션의 인덱스. |
| position | float | 새로운 그라디언트 스톱의 위치. |
| color | java.awt.Color | 새로운 그라디언트 스톱의 색상. |
### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```

새로운 그라디언트 스톱을 생성하고 지정된 인덱스에 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 새 그라디언트 스톱이 삽입될 컬렉션의 인덱스. |
| position | float | 새로운 그라디언트 스톱의 위치. |
| presetColor | int | 새로운 그라디언트 스톱의 색상. |
### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```

새로운 그라디언트 스톱을 생성하고 지정된 인덱스에 컬렉션에 삽입합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 새 그라디언트 스톱이 삽입될 컬렉션의 인덱스. |
| position | float | 새로운 그라디언트 스톱의 위치. |
| schemeColor | int | 새로운 그라디언트 스톱의 색상. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

지정된 인덱스에 있는 그라디언트 스톱을 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 삭제될 그라디언트 스톱의 인덱스. |
### clear() {#clear--}
```
public abstract void clear()
```

컬렉션에서 모든 그라디언트 스톱을 제거합니다.