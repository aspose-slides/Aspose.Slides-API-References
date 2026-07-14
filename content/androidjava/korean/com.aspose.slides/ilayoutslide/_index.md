---
title: ILayoutSlide
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 레이아웃 슬라이드를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ilayoutslide/
---
**모든 구현된 인터페이스:**  
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)  
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

레이아웃 슬라이드를 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | layout 슬라이드의 HeaderFooter 관리자를 반환합니다. |
| [getPlaceholderManager()](#getPlaceholderManager--) | layout 슬라이드의 placeholder 관리자를 반환합니다. |
| [getMasterSlide()](#getMasterSlide--) | 레이아웃에 대한 마스터 슬라이드를 반환하거나 설정합니다. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | 레이아웃에 대한 마스터 슬라이드를 반환하거나 설정합니다. |
| [getLayoutType()](#getLayoutType--) | 이 레이아웃 슬라이드의 레이아웃 유형을 반환합니다. |
| [hasDependingSlides()](#hasDependingSlides--) | 이 레이아웃 슬라이드에 의존하는 슬라이드가 하나라도 존재하면 true를 반환합니다. |
| [getDependingSlides()](#getDependingSlides--) | 이 레이아웃 슬라이드에 의존하는 모든 슬라이드를 포함하는 배열을 반환합니다. |
| [remove()](#remove--) | 프레젠테이션에서 레이아웃을 제거합니다. |
| [getDrawingGuides()](#getDrawingGuides--) | 레이아웃 슬라이드에 대한 drawing guides 컬렉션을 반환합니다. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

layout 슬라이드의 HeaderFooter 관리자를 반환합니다. 읽기 전용 [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**반환값:**  
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)

### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```

layout 슬라이드의 placeholder 관리자를 반환합니다. 읽기 전용 [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**반환값:**  
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)

### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```

레이아웃에 대한 마스터 슬라이드를 반환하거나 설정합니다. 읽기/쓰기 [IMasterSlide](../../com.aspose.slides/imasterslide).

**반환값:**  
[IMasterSlide](../../com.aspose.slides/imasterslide)

### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```

레이아웃에 대한 마스터 슬라이드를 반환하거나 설정합니다. 읽기/쓰기 [IMasterSlide](../../com.aspose.slides/imasterslide).

**매개변수:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |

### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```

이 레이아웃 슬라이드의 레이아웃 유형을 반환합니다. 읽기 전용 [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**반환값:**  
byte

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

이 레이아웃 슬라이드에 의존하는 슬라이드가 하나라도 존재하면 true를 반환합니다. 읽기 전용 boolean.

**반환값:**  
boolean

### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

이 레이아웃 슬라이드에 의존하는 모든 슬라이드를 포함하는 배열을 반환합니다.

**반환값:**  
com.aspose.slides.ISlide[] - 이 레이아웃 슬라이드에 의존하는 모든 슬라이드를 포함하는 Array

### remove() {#remove--}
```
public abstract void remove()
```

프레젠테이션에서 레이아웃을 제거합니다.

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

레이아웃 슬라이드에 대한 drawing guides 컬렉션을 반환합니다. 읽기 전용 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // 새로운 수직 그리기 가이드를 슬라이드 중앙 왼쪽에 추가합니다
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환값:**  
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)