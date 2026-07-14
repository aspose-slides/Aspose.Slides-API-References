---
title: IGradientStopCollection
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 그라디언트 스톱의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/igradientstopcollection/
---
**구현된 모든 인터페이스:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

그라디언트 스톱의 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 인덱스로 그라디언트 스톱을 반환합니다. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | 새 그라디언트 스톱을 생성하고 컬렉션의 끝에 추가합니다. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | 새 그라디언트 스톱을 생성하고 컬렉션의 끝에 추가합니다. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | 새 그라디언트 스톱을 생성하고 컬렉션의 끝에 추가합니다. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | 새 그라디언트 스톱을 생성하고 지정된 인덱스에 삽입합니다. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | 새 그라디언트 스톱을 생성하고 지정된 인덱스에 삽입합니다. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | 새 그라디언트 스톱을 생성하고 지정된 인덱스에 삽입합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스의 그라디언트 스톱을 삭제합니다. |
| [clear()](#clear--) | 컬렉션에서 모든 그라디언트 스톱을 삭제합니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```


인덱스로 그라디언트 스톱을 반환합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**반환값:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public abstract IGradientStop add(float position, Integer color)
```


새 그라디언트 스톱을 생성하고 컬렉션의 끝에 추가합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | float | 새 그라디언트 스톱의 위치. |
| color | java.lang.Integer | 새 그라디언트 스톱의 색상. |

**반환값:**
[IGradientStop](../../com.aspose.slides/igradientstop) - 새로운 그라디언트 스톱이 컬렉션에 위치한 인덱스.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```


새 그라디언트 스톱을 생성하고 컬렉션의 끝에 추가합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | float | 새 그라디언트 스톱의 위치. |
| presetColor | int | 새 그라디언트 스톱의 색상. |

**반환값:**
[IGradientStop](../../com.aspose.slides/igradientstop) - 새로운 그라디언트 스톱이 컬렉션에 위치한 인덱스.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```


새 그라디언트 스톱을 생성하고 컬렉션의 끝에 추가합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | float | 새 그라디언트 스톱의 위치. |
| schemeColor | int | 새 그라디언트 스톱의 색상. |

**반환값:**
[IGradientStop](../../com.aspose.slides/igradientstop) - 새로운 그라디언트 스톱이 컬렉션에 위치한 인덱스.
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public abstract void insert(int index, float position, Integer color)
```


새 그라디언트 스톱을 생성하고 지정된 인덱스에 삽입합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 새 그라디언트 스톱이 삽입될 컬렉션 내 인덱스. |
| position | float | 새 그라디언트 스톱의 위치. |
| color | java.lang.Integer | 새 그라디언트 스톱의 색상. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```


새 그라디언트 스톱을 생성하고 지정된 인덱스에 삽입합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 새 그라디언트 스톱이 삽입될 컬렉션 내 인덱스. |
| position | float | 새 그라디언트 스톱의 위치. |
| presetColor | int | 새 그라디언트 스톱의 색상. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```


새 그라디언트 스톱을 생성하고 지정된 인덱스에 삽입합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 새 그라디언트 스톱이 삽입될 컬렉션 내 인덱스. |
| position | float | 새 그라디언트 스톱의 위치. |
| schemeColor | int | 새 그라디언트 스톱의 색상. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


지정된 인덱스의 그라디언트 스톱을 삭제합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 삭제될 그라디언트 스톱의 인덱스. |

### clear() {#clear--}
```
public abstract void clear()
```


컬렉션에서 모든 그라디언트 스톱을 삭제합니다.