---
title: IMasterNotesSlideManager
second_title: Aspose.Slides for Android via Java API Reference
description: Master notes slide manager.
type: docs
url: /ko/com.aspose.slides/imasternotesslidemanager/
---```
public interface IMasterNotesSlideManager
```

마스터 노트 슬라이드 관리자.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getMasterNotesSlide()](#getMasterNotesSlide--) | 프레젠테이션에 마스터가 있으면 모든 노트 슬라이드에 대한 마스터를 반환하고, 없으면 null을 반환합니다. |
| [setDefaultMasterNotesSlide()](#setDefaultMasterNotesSlide--) | 관련 노트 슬라이드에 대한 기본 마스터 노트 슬라이드를 설정합니다. |
| [removeMasterNotesSlide()](#removeMasterNotesSlide--) | 마스터 노트 슬라이드를 제거합니다. |
### getMasterNotesSlide() {#getMasterNotesSlide--}
```
public abstract IMasterNotesSlide getMasterNotesSlide()
```


프레젠테이션에 마스터가 있으면 모든 노트 슬라이드에 대한 마스터를 반환하고, 없으면 null을 반환합니다. 읽기 전용 [IMasterNotesSlide](../../com.aspose.slides/imasternotesslide).

**반환:**
[IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
### setDefaultMasterNotesSlide() {#setDefaultMasterNotesSlide--}
```
public abstract IMasterNotesSlide setDefaultMasterNotesSlide()
```


관련 노트 슬라이드에 대한 기본 마스터 노트 슬라이드를 설정합니다.

**반환:**
[IMasterNotesSlide](../../com.aspose.slides/imasternotesslide) - 기본 마스터 노트 슬라이드 [IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
### removeMasterNotesSlide() {#removeMasterNotesSlide--}
```
public abstract void removeMasterNotesSlide()
```


마스터 노트 슬라이드를 제거합니다.