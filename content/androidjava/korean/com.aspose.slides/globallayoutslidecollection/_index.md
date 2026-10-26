---
title: GlobalLayoutSlideCollection
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 프레젠테이션의 모든 레이아웃 슬라이드 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/globallayoutslidecollection/
---
**상속:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**구현된 모든 인터페이스:**
[com.aspose.slides.IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
```
public final class GlobalLayoutSlideCollection extends LayoutSlideCollection implements IGlobalLayoutSlideCollection
```

프레젠테이션의 모든 레이아웃 슬라이드 컬렉션을 나타냅니다. LayoutSlideCollection 클래스를 확장하여 마스터 레이아웃 슬라이드의 개별 컬렉션을 통합하는 컨텍스트에서 레이아웃 슬라이드를 추가/복제하는 메서드를 제공합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | 지정된 레이아웃 슬라이드의 복사본을 프레젠테이션에 추가합니다. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | 지정된 레이아웃 슬라이드의 복사본을 프레젠테이션에 추가합니다. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | 새 레이아웃 슬라이드를 프레젠테이션에 추가합니다. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

지정된 레이아웃 슬라이드의 복사본을 프레젠테이션에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 복제할 슬라이드. |

---

다른 프레젠테이션 간에 레이아웃을 복제할 때 레이아웃의 마스터도 복제되어 원본 서식을 유지할 수 있습니다. 내부 레지스트리를 사용하여 자동으로 복제된 마스터를 추적하고 동일한 마스터 슬라이드의 다중 복제 생성을 방지합니다. 마스터 슬라이드의 수동 복제는 방지되거나 등록되지 않습니다.

**반환값:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 추가된 슬라이드.
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

지정된 레이아웃 슬라이드의 복사본을 프레젠테이션에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | 복제할 슬라이드. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | 새 레이아웃을 위한 마스터 슬라이드. |

1) 새 레이아웃은 대상 프레젠테이션에 정의된 마스터와 연결됩니다. 따라서 이것은 PowerPoint의 "Use Destination Theme" 옵션을 사용한 복사/붙여넣기와 유사합니다. 2) 이 메서드와 유사한 메서드는 [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-)이며 ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) 속성을 통해 접근합니다.

**반환값:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 추가된 슬라이드.
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

새 레이아웃 슬라이드를 프레젠테이션에 추가합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | 새 레이아웃을 위한 마스터 슬라이드. |
| layoutType | byte | 새 레이아웃을 위한 레이아웃 유형. 지원되는 레이아웃 유형: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. 현재 지원되지 않는 레이아웃 유형: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | 새 레이아웃의 이름. 전달된 이름이 이미 사용 중이면 ArgumentException이 발생합니다. null 매개변수가 전달되면 전달된 레이아웃 유형에 따라 이름이 자동으로 생성됩니다(예: "Title Slide" 또는 "1_Title Slide", "2_.." 등). |

1) layoutType이 SlideLayoutType.Custom인 경우 추가된 레이아웃에는 자리표시자와 도형이 포함되지 않습니다. 2) 이 메서드와 유사한 메서드는 [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-)이며 ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) 속성을 통해 접근합니다.

**반환값:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - 추가된 슬라이드.