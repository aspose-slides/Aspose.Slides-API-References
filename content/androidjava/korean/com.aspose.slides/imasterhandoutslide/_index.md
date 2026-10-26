---
title: IMasterHandoutSlide
second_title: Java API를 통한 Android용 Aspose.Slides 레퍼런스
description: 핸드아웃용 마스터 슬라이드를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/imasterhandoutslide/
---
**구현된 모든 인터페이스:**  
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)  
```
public interface IMasterHandoutSlide extends IBaseSlide, IMasterThemeable
```

핸드아웃용 마스터 슬라이드를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 마스터 핸드아웃 슬라이드의 HeaderFooter 관리자를 반환합니다. |
| [getDrawingGuides()](#getDrawingGuides--) | 마스터 핸드아웃 슬라이드용 그리기 가이드의 컬렉션을 반환합니다. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```

마스터 핸드아웃 슬라이드의 HeaderFooter 관리자를 반환합니다. 읽기 전용 [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**반환:**  
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

마스터 핸드아웃 슬라이드용 그리기 가이드의 컬렉션을 반환합니다. 읽기 전용 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // 슬라이드 중앙 위에 새로운 수평 그리기 가이드를 추가합니다
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환:**  
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)