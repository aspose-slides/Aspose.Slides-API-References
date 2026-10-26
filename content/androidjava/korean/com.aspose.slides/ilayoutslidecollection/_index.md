---
title: ILayoutSlideCollection
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 레이아웃 슬라이드 컬렉션의 기본 클래스를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ilayoutslidecollection/
---
**구현된 모든 인터페이스:**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

레이아웃 슬라이드 컬렉션의 기본 클래스를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 인덱스로 레이아웃 슬라이드를 반환합니다. |
| [getByType(byte type)](#getByType-byte-) | 지정된 유형의 첫 번째 레이아웃 슬라이드를 반환합니다. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | 컬렉션에서 레이아웃을 제거합니다. |
| [removeUnused()](#removeUnused--) | 사용되지 않는 레이아웃 슬라이드를 제거합니다 (HasDependingSlides가 false인 레이아웃 슬라이드). |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```


인덱스로 레이아웃 슬라이드를 반환합니다. 읽기 전용 [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public abstract ILayoutSlide getByType(byte type)
```


지정된 유형의 첫 번째 레이아웃 슬라이드를 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| type | byte | 찾을 레이아웃 슬라이드의 유형. |

**반환값:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 지정된 유형의 [ILayoutSlide](../../com.aspose.slides/ilayoutslide) 또는 레이아웃이 없으면 null.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public abstract void remove(ILayoutSlide value)
```


컬렉션에서 레이아웃을 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 컬렉션에서 제거할 레이아웃 슬라이드.

1) PptxEditException이 발생하는 것을 방지하려면 레이아웃의 HasDependingSlides 속성을 먼저 확인하십시오. 2) 코드를 단순화하려면 [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) 메서드도 사용할 수 있습니다.
### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```


사용되지 않는 레이아웃 슬라이드를 제거합니다 (HasDependingSlides가 false인 레이아웃 슬라이드).