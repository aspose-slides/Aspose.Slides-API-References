---
title: LayoutSlide
second_title: Aspose.Slides Android용 Java API 참조
description: 레이아웃 슬라이드를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/layoutslide/
---
**상속:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**구현된 모든 인터페이스:**
[com.aspose.slides.ILayoutSlide](../../com.aspose.slides/ilayoutslide)
```
public final class LayoutSlide extends BaseSlide implements ILayoutSlide
```

레이아웃 슬라이드를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 레이아웃 슬라이드의 HeaderFooter 관리자를 반환합니다. |
| [getPlaceholderManager()](#getPlaceholderManager--) | 레이아웃 슬라이드의 자리표시자 관리자를 반환합니다. |
| [getMasterSlide()](#getMasterSlide--) | 레이아웃의 마스터 슬라이드를 반환하거나 설정합니다. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | 레이아웃의 마스터 슬라이드를 반환하거나 설정합니다. |
| [remove()](#remove--) | 프레젠테이션에서 레이아웃을 제거합니다. |
| [getThemeManager()](#getThemeManager--) | 오버라이딩 테마 관리자를 반환합니다. |
| [getLayoutType()](#getLayoutType--) | 이 레이아웃 슬라이드의 레이아웃 유형을 반환합니다. |
| [getDependingSlides()](#getDependingSlides--) | 이 레이아웃 슬라이드에 의존하는 모든 슬라이드의 배열을 반환합니다. |
| [hasDependingSlides()](#hasDependingSlides--) | 이 레이아웃 슬라이드에 의존하는 슬라이드가 하나라도 존재하면 true를 반환합니다. |
| [getShowMasterShapes()](#getShowMasterShapes--) | 마스터 슬라이드의 도형을 슬라이드에 표시할지 여부를 지정합니다. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | 마스터 슬라이드의 도형을 슬라이드에 표시할지 여부를 지정합니다. |
| [getDrawingGuides()](#getDrawingGuides--) | 레이아웃 슬라이드의 드로잉 가이드 컬렉션을 반환합니다. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```


레이아웃 슬라이드의 HeaderFooter 관리자를 반환합니다. 읽기 전용 [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**반환값:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```


레이아웃 슬라이드의 자리표시자 관리자를 반환합니다. 읽기 전용 [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**반환값:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public final IMasterSlide getMasterSlide()
```


레이아웃의 마스터 슬라이드를 반환하거나 설정합니다. 읽기/쓰기 [IMasterSlide](../../com.aspose.slides/imasterslide).

**반환값:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```


레이아웃의 마스터 슬라이드를 반환하거나 설정합니다. 읽기/쓰기 [IMasterSlide](../../com.aspose.slides/imasterslide).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### remove() {#remove--}
```
public final void remove()
```


프레젠테이션에서 레이아웃을 제거합니다.

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```


오버라이딩 테마 관리자를 반환합니다. 읽기 전용 [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**반환값:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getLayoutType() {#getLayoutType--}
```
public final byte getLayoutType()
```


이 레이아웃 슬라이드의 레이아웃 유형을 반환합니다. 읽기 전용 [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**반환값:**
byte
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```


이 레이아웃 슬라이드에 의존하는 모든 슬라이드의 배열을 반환합니다.

**반환값:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```


이 레이아웃 슬라이드에 의존하는 슬라이드가 하나라도 존재하면 true를 반환합니다. 읽기 전용 boolean .

**반환값:**
boolean
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


마스터 슬라이드의 도형을 슬라이드에 표시할지 여부를 지정합니다. 읽기/쓰기 boolean .

**반환값:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


마스터 슬라이드의 도형을 슬라이드에 표시할지 여부를 지정합니다. 읽기/쓰기 boolean .

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


레이아웃 슬라이드의 드로잉 가이드 컬렉션을 반환합니다. 읽기 전용 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Adding the new vertical drawing guide to the left of the slide center
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환값:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)