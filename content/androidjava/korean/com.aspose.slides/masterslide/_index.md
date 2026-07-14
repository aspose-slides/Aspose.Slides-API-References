---
title: MasterSlide
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 프레젠테이션에서 마스터 슬라이드를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/masterslide/
---
**상속:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**구현된 모든 인터페이스:**
[com.aspose.slides.IMasterSlide](../../com.aspose.slides/imasterslide)
```
public class MasterSlide extends BaseSlide implements IMasterSlide
```

프레젠테이션에서 마스터 슬라이드를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 마스터 슬라이드의 HeaderFooter 관리자를 반환합니다. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | 현재 마스터 슬라이드를 기반으로 새 마스터 슬라이드를 생성하고 외부 테마를 적용한 후, 생성된 마스터 슬라이드를 모든 종속 슬라이드에 적용합니다. |
| [getTitleStyle()](#getTitleStyle--) | 제목 텍스트의 스타일을 반환합니다. |
| [getBodyStyle()](#getBodyStyle--) | 본문 텍스트의 스타일을 반환합니다. |
| [getOtherStyle()](#getOtherStyle--) | 다른 텍스트의 스타일을 반환합니다. |
| [getLayoutSlides()](#getLayoutSlides--) | 이 마스터 슬라이드에 대한 자식 레이아웃 슬라이드 컬렉션을 반환합니다. |
| [getPreserve()](#getPreserve--) | 해당 마스터를 따르는 모든 슬라이드가 삭제될 때 해당 마스터가 삭제되는지 여부를 결정합니다. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | 해당 마스터를 따르는 모든 슬라이드가 삭제될 때 해당 마스터가 삭제되는지 여부를 결정합니다. |
| [getDependingSlides()](#getDependingSlides--) | 이 마스터 슬라이드에 의존하는 모든 슬라이드의 배열을 반환합니다. |
| [hasDependingSlides()](#hasDependingSlides--) | 이 마스터 슬라이드에 의존하는 슬라이드가 하나라도 존재하면 true를 반환합니다. |
| [getThemeManager()](#getThemeManager--) | 테마 관리자를 반환합니다. |
| [getName()](#getName--) | 마스터 슬라이드의 이름을 반환하거나 설정합니다. |
| [setName(String value)](#setName-java.lang.String-) | 마스터 슬라이드의 이름을 반환하거나 설정합니다. |
| [getShowMasterShapes()](#getShowMasterShapes--) | 마스터 슬라이드의 도형을 슬라이드에 표시할지 여부를 지정합니다. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | 마스터 슬라이드의 도형을 슬라이드에 표시할지 여부를 지정합니다. |
| [getDrawingGuides()](#getDrawingGuides--) | 마스터 슬라이드에 대한 그리기 가이드 컬렉션을 반환합니다. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

마스터 슬라이드의 HeaderFooter 관리자를 반환합니다. 읽기 전용 [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**반환값:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

현재 마스터 슬라이드를 기반으로 새 마스터 슬라이드를 생성하고 외부 테마를 적용한 후, 생성된 마스터 슬라이드를 모든 종속 슬라이드에 적용합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| fname | java.lang.String | .thmx 파일인 외부 테마 파일의 경로. |

**반환값:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - 새 테마가 적용된 MasterSlide.
### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```

제목 텍스트의 스타일을 반환합니다. 읽기 전용 [ITextStyle](../../com.aspose.slides/itextstyle).

**반환값:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```

본문 텍스트의 스타일을 반환합니다. 읽기 전용 [ITextStyle](../../com.aspose.slides/itextstyle).

**반환값:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```

다른 텍스트의 스타일을 반환합니다. 읽기 전용 [ITextStyle](../../com.aspose.slides/itextstyle).

**반환값:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```

이 마스터 슬라이드에 대한 자식 레이아웃 슬라이드 컬렉션을 반환합니다. 읽기 전용 [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

레이아웃 슬라이드를 추가/삽입/제거/복제하기 위한 대체 API에 접근하려면 ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) 속성을 사용할 수 있습니다.

**반환값:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```

해당 마스터를 따르는 모든 슬라이드가 삭제될 때 해당 마스터가 삭제되는지 여부를 결정합니다. 참고: Aspose.Slides는 사용되지 않는 마스터를 자동으로 제거하지 않으며, 실제로 사용되지 않는 마스터를 제거하려면 [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-)를 호출하십시오 읽기/쓰기 boolean .

**반환값:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```

해당 마스터를 따르는 모든 슬라이드가 삭제될 때 해당 마스터가 삭제되는지 여부를 결정합니다. 참고: Aspose.Slides는 사용되지 않는 마스터를 자동으로 제거하지 않으며, 실제로 사용되지 않는 마스터를 제거하려면 [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-)를 호출하십시오 읽기/쓰기 boolean .

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

이 마스터 슬라이드에 의존하는 모든 슬라이드의 배열을 반환합니다.

**반환값:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

이 마스터 슬라이드에 의존하는 슬라이드가 하나라도 존재하면 true를 반환합니다. 읽기 전용 boolean .

**반환값:**
boolean
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

테마 관리자를 반환합니다. 읽기 전용 [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**반환값:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getName() {#getName--}
```
public String getName()
```

마스터 슬라이드의 이름을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환값:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

마스터 슬라이드의 이름을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

마스터 슬라이드의 도형을 슬라이드에 표시할지 여부를 지정합니다. 마스터 슬라이드 자체의 경우 이 속성은 항상 false를 반환합니다. 읽기/쓰기 boolean .

**반환값:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

마스터 슬라이드의 도형을 슬라이드에 표시할지 여부를 지정합니다. 마스터 슬라이드 자체의 경우 이 속성은 항상 false를 반환합니다. 읽기/쓰기 boolean .

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

마스터 슬라이드에 대한 그리기 가이드 컬렉션을 반환합니다. 읽기 전용 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // 새로운 수직 그리기 가이드를 슬라이드 중앙 오른쪽에 추가합니다
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환값:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)