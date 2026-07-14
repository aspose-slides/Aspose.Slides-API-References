---
title: NotesSlide
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 프레젠테이션의 노트 슬라이드를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/notesslide/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**All Implemented Interfaces:**  
[com.aspose.slides.INotesSlide](../../com.aspose.slides/inotesslide)  
```
public class NotesSlide extends BaseSlide implements INotesSlide
```

프레젠테이션의 노트 슬라이드를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 노트 슬라이드의 HeaderFooter 관리자를 반환합니다. |
| [getNotesTextFrame()](#getNotesTextFrame--) | 노트 텍스트가 있는 경우 TextFrame을 반환합니다. |
| [getThemeManager()](#getThemeManager--) | 오버라이드된 테마 관리자를 반환합니다. |
| [getParentSlide()](#getParentSlide--) | 부모 슬라이드를 반환합니다. |
| [getShowMasterShapes()](#getShowMasterShapes--) | 마스터 슬라이드의 도형을 슬라이드에 표시할지 여부를 지정합니다. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | 마스터 슬라이드의 도형을 슬라이드에 표시할지 여부를 지정합니다. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final INotesSlideHeaderFooterManager getHeaderFooterManager()
```

노트 슬라이드의 HeaderFooter 관리자를 반환합니다. 읽기 전용 [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**반환값:**  
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public final ITextFrame getNotesTextFrame()
```

노트 텍스트가 있는 경우 TextFrame을 반환합니다. 읽기 전용 [ITextFrame](../../com.aspose.slides/itextframe).

**반환값:**  
[ITextFrame](../../com.aspose.slides/itextframe)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

오버라이드된 테마 관리자를 반환합니다. 읽기 전용 [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**반환값:**  
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getParentSlide() {#getParentSlide--}
```
public final ISlide getParentSlide()
```

부모 슬라이드를 반환합니다. 읽기 전용 [ISlide](../../com.aspose.slides/islide).

**반환값:**  
[ISlide](../../com.aspose.slides/islide)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

마스터 슬라이드의 도형을 슬라이드에 표시할지 여부를 지정합니다. 읽기/쓰기 부울.

**반환값:**  
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

마스터 슬라이드의 도형을 슬라이드에 표시할지 여부를 지정합니다. 읽기/쓰기 부울.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |