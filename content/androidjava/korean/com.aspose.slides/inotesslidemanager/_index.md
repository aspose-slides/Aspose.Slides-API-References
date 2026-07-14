---
title: INotesSlideManager
second_title: Aspose.Slides for Android via Java API Reference
description: Notes slide manager.
type: docs
url: /ko/com.aspose.slides/inotesslidemanager/
---```
public interface INotesSlideManager
```

노트 슬라이드 관리자.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getNotesSlide()](#getNotesSlide--) | 현재 슬라이드에 대한 노트 슬라이드를 반환합니다. |
| [addNotesSlide()](#addNotesSlide--) | 현재 슬라이드에 대한 노트 슬라이드를 반환합니다. 없을 경우 새로 생성합니다. |
| [removeNotesSlide()](#removeNotesSlide--) | 현재 슬라이드의 노트 슬라이드를 제거합니다. |
### getNotesSlide() {#getNotesSlide--}
```
public abstract INotesSlide getNotesSlide()
```

현재 슬라이드에 대한 노트 슬라이드를 반환합니다. 슬라이드에 노트 슬라이드가 없으면 null을 반환합니다. 읽기 전용 [INotesSlide](../../com.aspose.slides/inotesslide).

**반환값:**
[INotesSlide](../../com.aspose.slides/inotesslide)
### addNotesSlide() {#addNotesSlide--}
```
public abstract INotesSlide addNotesSlide()
```

현재 슬라이드에 대한 노트 슬라이드를 반환합니다. 없을 경우 새로 생성합니다.

**반환값:**
[INotesSlide](../../com.aspose.slides/inotesslide) - [INotesSlide](../../com.aspose.slides/inotesslide) 이 슬라이드에 대해.
### removeNotesSlide() {#removeNotesSlide--}
```
public abstract void removeNotesSlide()
```

현재 슬라이드의 노트 슬라이드를 제거합니다.