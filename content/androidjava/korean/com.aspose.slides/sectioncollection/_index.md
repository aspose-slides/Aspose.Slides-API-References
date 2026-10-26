---
title: SectionCollection
second_title: Java API를 통한 Android용 Aspose.Slides 참조
description: 섹션 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/sectioncollection/
---
**상속:**
java.lang.Object, com.aspose.slides.DomObject

**구현된 모든 인터페이스:**
[com.aspose.slides.ISectionCollection](../../com.aspose.slides/isectioncollection)
```
public final class SectionCollection extends DomObject<Presentation> implements ISectionCollection
```

섹션 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 요소를 가져옵니다. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | 특정 슬라이드에서 시작하는 슬라이드 섹션을 추가합니다. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | 컬렉션 끝에 빈 섹션을 추가합니다. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | 컬렉션의 지정된 위치에 빈 섹션을 추가합니다. |
| [size()](#size--) | 컬렉션에 실제로 포함된 요소 수를 가져옵니다. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | 컬렉션에서 지정된 섹션의 인덱스를 반환합니다. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | 섹션 및 섹션에 포함된 슬라이드를 제거합니다. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | 섹션을 제거합니다. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | 섹션과 해당 슬라이드를 컬렉션에서 지정된 위치로 이동합니다. |
| [clear()](#clear--) | 컬렉션에서 모든 섹션을 제거합니다. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 전체 컬렉션을 지정된 배열로 복사합니다. |
| [isSynchronized()](#isSynchronized--) | 컬렉션에 대한 액세스가 동기화(스레드 안전)되는지 여부를 나타내는 값을 반환합니다. |
| [getSyncRoot()](#getSyncRoot--) | 동기화 루트를 반환합니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [iteratorJava()](#iteratorJava--) | 전체 컬렉션에 대한 java 이터레이터를 반환합니다. |
### get_Item(int index) {#get-Item-int-}
```
public final ISection get_Item(int index)
```

지정된 인덱스의 요소를 가져옵니다. 읽기 전용 [ISection](../../com.aspose.slides/isection).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public final ISection addSection(String name, ISlide startedFromSlide)
```

특정 슬라이드에서 시작하는 슬라이드 섹션을 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 섹션 이름 |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | 섹션의 첫 번째 슬라이드 |

**반환값:**
[ISection](../../com.aspose.slides/isection) - 추가된 섹션.
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public final ISection appendEmptySection(String name)
```

컬렉션 끝에 빈 섹션을 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 섹션 이름 |

**반환값:**
[ISection](../../com.aspose.slides/isection) - 추가된 섹션.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public final ISection addEmptySection(String name, int index)
```

컬렉션의 지정된 위치에 빈 섹션을 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 섹션 이름 |
| index | int | 새 섹션의 인덱스. |

**반환값:**
[ISection](../../com.aspose.slides/isection) - 추가된 섹션.
### size() {#size--}
```
public final int size()
```

컬렉션에 실제로 포함된 요소 수를 가져옵니다. 읽기 전용 int.

**반환값:**
int
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public final int indexOf(ISection section)
```

컬렉션에서 지정된 섹션의 인덱스를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 찾을 섹션. |

**반환값:**
int - 섹션의 인덱스 또는 이 컬렉션에 속하지 않으면 -1.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public final void removeSectionWithSlides(ISection section)
```

섹션 및 섹션에 포함된 슬라이드를 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 컬렉션에서 제거할 섹션. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public final void removeSection(ISection section)
```

섹션을 제거합니다. 섹션에 포함된 슬라이드는 이전 섹션과 병합됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 컬렉션에서 제거할 섹션. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public final void reorderSectionWithSlides(ISection section, int index)
```

섹션과 해당 슬라이드를 컬렉션에서 지정된 위치로 이동합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 이동할 섹션. |
| index | int | 대상 인덱스. |

### clear() {#clear--}
```
public final void clear()
```

컬렉션에서 모든 섹션을 제거합니다.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

전체 컬렉션을 지정된 배열로 복사합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 대상 배열 |
| index | int | 대상 배열의 인덱스. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

컬렉션에 대한 액세스가 동기화(스레드 안전)되는지 여부를 나타내는 값을 반환합니다. 읽기 전용 boolean.

**반환값:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

동기화 루트를 반환합니다. 읽기 전용 Object.

**반환값:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iterator()
```

컬렉션을 순회하는 열거자를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - 컬렉션을 순회하는 데 사용할 수 있는 IGenericEnumerator
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iteratorJava()
```

전체 컬렉션에 대한 java 이터레이터를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - 전체 컬렉션에 대한 java.util.Iterator