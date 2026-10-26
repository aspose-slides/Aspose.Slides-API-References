---
title: IMasterNotesSlide
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 노트를 위한 마스터 슬라이드를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/imasternotesslide/
---
**전체 구현된 인터페이스:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterNotesSlide extends IBaseSlide, IMasterThemeable
```

노트를 위한 마스터 슬라이드를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 마스터 노트 슬라이드의 HeaderFooter 관리자를 반환합니다. |
| [getNotesStyle()](#getNotesStyle--) | 노트 텍스트의 스타일을 반환합니다. |
| [getDrawingGuides()](#getDrawingGuides--) | 마스터 노트 슬라이드의 드로잉 가이드 컬렉션을 반환합니다. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```


마스터 노트 슬라이드의 HeaderFooter 관리자를 반환합니다. 읽기 전용 [IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager).

**반환:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getNotesStyle() {#getNotesStyle--}
```
public abstract ITextStyle getNotesStyle()
```


노트 텍스트의 스타일을 반환합니다. 읽기 전용 [ITextStyle](../../com.aspose.slides/itextstyle).

**반환:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


마스터 노트 슬라이드의 드로잉 가이드 컬렉션을 반환합니다. 읽기 전용 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // 슬라이드 중앙 아래에 새로운 수평 드로잉 가이드를 추가합니다
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)