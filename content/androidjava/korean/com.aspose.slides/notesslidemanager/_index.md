---
title: NotesSlideManager
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 노트 슬라이드 관리자.
type: docs
url: /ko/com.aspose.slides/notesslidemanager/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
```
public final class NotesSlideManager extends DomObject<Slide> implements INotesSlideManager
```

노트 슬라이드 관리자.

--------------------

> ```
> The following example shows how to Add Notes to specific ProwerPoint Presentation slide.
>  
>  // 프레젠테이션 파일을 나타내는 Presentation 객체를 인스턴스화합니다
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // 첫 번째 슬라이드에 노트를 추가합니다
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      INotesSlide noteSlide = mgr.addNotesSlide();
>      noteSlide.getNotesTextFrame().setText("Your Notes");
>      // 프레젠테이션을 디스크에 저장합니다
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to remove Notes from PowerPoint Presentation's specific slide.
>  
>  // 프레젠테이션 파일을 나타내는 Presentation 객체를 인스턴스화합니다
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try {
>      // 첫 번째 슬라이드의 노트를 제거합니다
>      INotesSlideManager mgr = pres.getSlides().get_Item(0).getNotesSlideManager();
>      mgr.removeNotesSlide();
>      // 프레젠테이션을 디스크에 저장합니다
>      pres.save("RemoveNotesAtSpecificSlide_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | 현재 슬라이드에 대한 노트 슬라이드를 반환합니다. |
| [addNotesSlide()](#addNotesSlide--) | 현재 슬라이드에 대한 노트 슬라이드를 반환하며, 없을 경우 생성합니다. |
| [removeNotesSlide()](#removeNotesSlide--) | 현재 슬라이드의 노트 슬라이드를 제거합니다. |
### getNotesSlide() {#getNotesSlide--}
```
public final INotesSlide getNotesSlide()
```

현재 슬라이드에 대한 노트 슬라이드를 반환합니다. 슬라이드에 노트 슬라이드가 없으면 null을 반환합니다. 읽기 전용 [INotesSlide](../../com.aspose.slides/inotesslide).

**반환:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public final INotesSlide addNotesSlide()
```

현재 슬라이드에 대한 노트 슬라이드를 반환하며, 없을 경우 생성합니다.

**반환:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [NotesSlide](../../com.aspose.slides/notesslide)(\#getNotesSlide.getNotesSlide) 이 슬라이드에 대해.
### removeNotesSlide() {#removeNotesSlide--}
```
public final void removeNotesSlide()
```

현재 슬라이드의 노트 슬라이드를 제거합니다.