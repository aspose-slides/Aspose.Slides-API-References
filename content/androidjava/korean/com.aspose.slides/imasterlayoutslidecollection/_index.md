---
title: IMasterLayoutSlideCollection
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 정의된 마스터 슬라이드의 모든 레이아웃 슬라이드 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/imasterlayoutslidecollection/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IMasterLayoutSlideCollection extends ILayoutSlideCollection
```

정의된 마스터 슬라이드의 모든 레이아웃 슬라이드 컬렉션을 나타냅니다. ILayoutSlideCollection 인터페이스를 확장하여 마스터의 레이아웃 슬라이드 개별 컬렉션에서 레이아웃 슬라이드를 추가/삽입/제거/복제하는 메서드를 제공합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Adds a copy of a specified layout slide to the end of the collection. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Inserts a copy of a specified layout slide to specified position of the collection. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Adds a new layout slide to the end of the collection. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Inserts a new layout slide to specified position of the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the specified index of the collection. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Moves layout slide from the collection to the specified position. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

지정된 레이아웃 슬라이드의 복사본을 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 복제할 슬라이드. |

--------------------
1) 새 레이아웃은 이 레이아웃 슬라이드 컬렉션의 상위 마스터 슬라이드와 연결됩니다. 따라서 PowerPoint의 "Use Destination Theme" 옵션을 사용한 복사/붙여넣기와 동일합니다. 2) 이 메서드와 동일한 기능은 [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) 메서드이며 [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides) 속성을 통해 접근합니다.

**반환:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 추가된 슬라이드.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

지정된 레이아웃 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 새 슬라이드의 인덱스. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 복제할 슬라이드. |

--------------------
새 레이아웃은 이 레이아웃 슬라이드 컬렉션의 상위 마스터 슬라이드와 연결됩니다. 따라서 PowerPoint의 "Use Destination Theme" 옵션을 사용한 복사/붙여넣기와 동일합니다.

**반환:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 삽입된 슬라이드.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public abstract ILayoutSlide add(byte layoutType, String layoutName)
```

새 레이아웃 슬라이드를 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| layoutType | byte | 새 레이아웃의 레이아웃 유형입니다. 지원되는 레이아웃 유형: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | 새 레이아웃의 이름입니다. 지정된 이름이 이미 사용 중이면 ArgumentException이 발생합니다. null 매개변수가 전달되면 레이아웃 유형에 따라 자동으로 이름이 생성됩니다(예: "Title Slide" 또는 "1_Title Slide", "2_.." 등). |

--------------------
1) layoutType이 SlideLayoutType.Custom인 경우 추가된 레이아웃은 플레이스홀더와 도형이 없습니다. 2) 이 메서드와 동일한 기능은 [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) 메서드이며 [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides) 속성을 통해 접근합니다.

**반환:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 추가된 슬라이드.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public abstract ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

새 레이아웃 슬라이드를 컬렉션의 지정된 위치에 삽입합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 새 슬라이드의 인덱스. |
| layoutType | byte | 새 레이아웃의 레이아웃 유형입니다. 지원되는 레이아웃 유형: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | 새 레이아웃의 이름입니다. 지정된 이름이 이미 사용 중이면 ArgumentException이 발생합니다. null 매개변수가 전달되면 레이아웃 유형에 따라 자동으로 이름이 생성됩니다(예: "Title Slide" 또는 "1_Title Slide", "2_.." 등). |

--------------------
layoutType이 SlideLayoutType.Custom인 경우 삽입된 레이아웃은 플레이스홀더와 도형이 없습니다.

**반환:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 삽입된 슬라이드.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

컬렉션에서 지정된 인덱스에 있는 요소를 제거합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 제거할 요소의 0부터 시작하는 인덱스. |

--------------------
1) PptxEditException이 발생하는 것을 방지하려면 레이아웃의 HasDependingSlides 속성을 사전에 확인하십시오. 2) 또한 코드를 간소화하기 위해 [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) 메서드를 사용할 수 있습니다.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public abstract void reorder(int index, ILayoutSlide layoutSlide)
```

컬렉션에서 레이아웃 슬라이드를 지정된 위치로 이동합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 대상 인덱스. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 이동할 슬라이드. |