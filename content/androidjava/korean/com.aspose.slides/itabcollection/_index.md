---
title: ITabCollection
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 탭 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/itabcollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ITabCollection extends IGenericCollection<ITab>
```

탭 컬렉션을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 요소를 가져옵니다. |
| [add(double position, int align)](#add-double-int-) | Tab을 컬렉션에 추가합니다. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Tab을 컬렉션에 추가합니다. |
| [clear()](#clear--) | 컬렉션의 모든 요소를 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 컬렉션에서 지정된 인덱스의 요소를 제거합니다. |

### get_Item(int index) {#get-Item-int-}
```
public abstract ITab get_Item(int index)
```

지정된 인덱스의 요소를 가져옵니다. 읽기 전용 [ITab](../../com.aspose.slides/itab).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[ITab](../../com.aspose.slides/itab)

### add(double position, int align) {#add-double-int-}
```
public abstract ITab add(double position, int align)
```

Tab을 컬렉션에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | double | Tab 위치. |
| align | int | Tab 정렬. |

**반환값:**
[ITab](../../com.aspose.slides/itab) - 추가된 탭.

### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public abstract int add(ITab value)
```

Tab을 컬렉션에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | 컬렉션 끝에 추가될 Tab 객체. |

**반환값:**
int - 탭이 추가된 인덱스.

### clear() {#clear--}
```
public abstract void clear()
```

컬렉션의 모든 요소를 제거합니다.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

컬렉션에서 지정된 인덱스의 요소를 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 제거할 요소의 0부터 시작하는 인덱스. |