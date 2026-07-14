---
title: ISectionCollection
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 섹션 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/isectioncollection/
---
**구현된 모든 인터페이스:**
com.aspose.slides.IGenericCollection
```
public interface ISectionCollection extends IGenericCollection<ISection>
```

섹션 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 요소를 가져옵니다. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | 특정 슬라이드에서 시작하는 새 섹션을 추가합니다. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | 컬렉션의 지정된 위치에 빈 섹션을 추가합니다. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | 섹션 및 해당 섹션에 포함된 슬라이드를 제거합니다. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | 섹션을 제거합니다. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | 섹션 및 해당 슬라이드를 컬렉션에서 지정된 위치로 이동합니다. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | 컬렉션 끝에 빈 섹션을 추가합니다. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | 컬렉션에서 지정된 섹션의 인덱스를 반환합니다. |
| [clear()](#clear--) | 컬렉션의 모든 섹션을 제거합니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISection get_Item(int index)
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
public abstract ISection addSection(String name, ISlide startedFromSlide)
```

특정 슬라이드에서 시작하는 새 섹션을 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 섹션 이름 |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | 섹션의 첫 번째 슬라이드 |

**반환값:**
[ISection](../../com.aspose.slides/isection) - 추가된 섹션.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public abstract ISection addEmptySection(String name, int index)
```

컬렉션의 지정된 위치에 빈 섹션을 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 섹션 이름 |
| index | int | 새 섹션의 인덱스. |

**반환값:**
[ISection](../../com.aspose.slides/isection) - 추가된 섹션.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public abstract void removeSectionWithSlides(ISection section)
```

섹션 및 해당 섹션에 포함된 슬라이드를 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 컬렉션에서 제거할 섹션. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public abstract void removeSection(ISection section)
```

섹션을 제거합니다. 섹션에 포함된 슬라이드는 이전 섹션과 병합됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 컬렉션에서 제거할 섹션. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public abstract void reorderSectionWithSlides(ISection section, int index)
```

섹션 및 해당 슬라이드를 컬렉션에서 지정된 위치로 이동합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 이동할 섹션. |
| index | int | 대상 인덱스. |

### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public abstract ISection appendEmptySection(String name)
```

컬렉션의 끝에 빈 섹션을 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | java.lang.String | 섹션 이름 |

**반환값:**
[ISection](../../com.aspose.slides/isection) - 추가된 섹션.
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public abstract int indexOf(ISection section)
```

컬렉션에서 지정된 섹션의 인덱스를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 찾을 섹션. |

**반환값:**
int - 섹션의 인덱스 또는 섹션이 이 컬렉션에 없으면 -1을 반환합니다.
### clear() {#clear--}
```
public abstract void clear()
```

컬렉션의 모든 섹션을 제거합니다.