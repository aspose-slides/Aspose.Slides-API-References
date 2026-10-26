---
title: IMasterSlide
second_title: Aspose.Slides for Java API 레퍼런스
description: 프레젠테이션에서 마스터 슬라이드를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/imasterslide/
---
**구현된 모든 인터페이스:**  
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

프레젠테이션의 마스터 슬라이드를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 마스터 슬라이드의 HeaderFooter 관리자를 반환합니다. |
| [getTitleStyle()](#getTitleStyle--) | 제목 텍스트의 스타일을 반환합니다. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | 현재 마스터 슬라이드를 기반으로 새 마스터 슬라이드를 생성하고 외부 테마를 적용한 후, 생성된 마스터 슬라이드를 모든 종속 슬라이드에 적용합니다. |
| [getBodyStyle()](#getBodyStyle--) | 본문 텍스트의 스타일을 반환합니다. |
| [getOtherStyle()](#getOtherStyle--) | 기타 텍스트의 스타일을 반환합니다. |
| [getLayoutSlides()](#getLayoutSlides--) | 이 마스터 슬라이드에 대한 자식 레이아웃 슬라이드 컬렉션을 반환합니다. |
| [getPreserve()](#getPreserve--) | 해당 마스터를 따르는 모든 슬라이드가 삭제될 때 해당 마스터가 삭제되는지 여부를 결정합니다. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | 해당 마스터를 따르는 모든 슬라이드가 삭제될 때 해당 마스터가 삭제되는지 여부를 결정합니다. |
| [hasDependingSlides()](#hasDependingSlides--) | 이 마스터 슬라이드에 종속된 슬라이드가 하나라도 존재하면 true를 반환합니다. |
| [getDependingSlides()](#getDependingSlides--) | 이 마스터 슬라이드에 종속된 모든 슬라이드의 배열을 반환합니다. |
| [getDrawingGuides()](#getDrawingGuides--) | 마스터 슬라이드에 대한 그리기 가이드 컬렉션을 반환합니다. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

마스터 슬라이드의 HeaderFooter 관리자를 반환합니다. 읽기 전용 [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**반환:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### getTitleStyle() {#getTitleStyle--}
```
public abstract ITextStyle getTitleStyle()
```

제목 텍스트의 스타일을 반환합니다. 읽기 전용 [ITextStyle](../../com.aspose.slides/itextstyle).

**반환:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public abstract IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

현재 마스터 슬라이드를 기반으로 새 마스터 슬라이드를 생성하고 외부 테마를 적용한 후, 생성된 마스터 슬라이드를 모든 종속 슬라이드에 적용합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fname | java.lang.String | 외부 테마 파일(.thmx)의 경로입니다. |

**반환:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - 새 테마가 적용된 MasterSlide.
### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```

본문 텍스트의 스타일을 반환합니다. 읽기 전용 [ITextStyle](../../com.aspose.slides/itextstyle).

**반환:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public abstract ITextStyle getOtherStyle()
```

기타 텍스트의 스타일을 반환합니다. 읽기 전용 [ITextStyle](../../com.aspose.slides/itextstyle).

**반환:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```

이 마스터 슬라이드에 대한 자식 레이아웃 슬라이드 컬렉션을 반환합니다. 읽기 전용 [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

레이아웃 슬라이드를 추가/삽입/제거/복제하기 위한 대체 API에 접근하려면 ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) 속성을 사용할 수 있습니다.

**반환:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```

해당 마스터를 따르는 모든 슬라이드가 삭제될 때 해당 마스터가 삭제되는지 여부를 결정합니다. 참고: Aspose.Slides는 사용되지 않는 마스터를 스스로 제거하지 않으며, 사용되지 않는 마스터를 실제로 제거하려면 [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) 읽기/쓰기 boolean을 호출하십시오.

**반환:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```

해당 마스터를 따르는 모든 슬라이드가 삭제될 때 해당 마스터가 삭제되는지 여부를 결정합니다. 참고: Aspose.Slides는 사용되지 않는 마스터를 스스로 제거하지 않으며, 사용되지 않는 마스터를 실제로 제거하려면 [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) 읽기/쓰기 boolean을 호출하십시오.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

이 마스터 슬라이드에 종속된 슬라이드가 하나라도 존재하면 true를 반환합니다. 읽기 전용 boolean.

**반환:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

이 마스터 슬라이드에 종속된 모든 슬라이드의 배열을 반환합니다.

**반환:**
com.aspose.slides.ISlide[] - [ISlide](../../com.aspose.slides/islide) 배열, 이 마스터 슬라이드에 종속된
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

마스터 슬라이드에 대한 그리기 가이드 컬렉션을 반환합니다. 읽기 전용 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
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


**반환:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)