---
title: INotesSlide
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 프레젠테이션의 노트 슬라이드를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/inotesslide/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface INotesSlide extends IBaseSlide, IOverrideThemeable
```

프레젠테이션의 노트 슬라이드를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 노트 슬라이드의 HeaderFooter 관리자를 반환합니다. |
| [getNotesTextFrame()](#getNotesTextFrame--) | 노트 텍스트가 있으면 TextFrame을 반환합니다. |
| [getParentSlide()](#getParentSlide--) | ParentSlide 읽기 전용 [ISlide](../../com.aspose.slides/islide)를 반환합니다. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract INotesSlideHeaderFooterManager getHeaderFooterManager()
```


노트 슬라이드의 HeaderFooter 관리자를 반환합니다. 읽기 전용 [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**반환:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public abstract ITextFrame getNotesTextFrame()
```


노트 텍스트가 있으면 TextFrame을 반환합니다. 읽기 전용 [ITextFrame](../../com.aspose.slides/itextframe).

**반환:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getParentSlide() {#getParentSlide--}
```
public abstract ISlide getParentSlide()
```


ParentSlide 읽기 전용 [ISlide](../../com.aspose.slides/islide)를 반환합니다.

**반환:**
[ISlide](../../com.aspose.slides/islide)