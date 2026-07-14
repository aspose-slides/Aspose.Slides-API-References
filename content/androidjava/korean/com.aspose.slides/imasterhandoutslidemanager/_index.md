---
title: IMasterHandoutSlideManager
second_title: Aspose.Slides for Android via Java API Reference
description: Master handout slide manager.
type: docs
url: /ko/com.aspose.slides/imasterhandoutslidemanager/
---```
public interface IMasterHandoutSlideManager
```

마스터 핸드아웃 슬라이드 관리자.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getMasterHandoutSlide()](#getMasterHandoutSlide--) | 이 프레젠테이션에 메모 슬라이드가 있는 경우 해당 슬라이드의 마스터를 반환하고, 없으면 null을 반환합니다. |
| [setDefaultMasterHandoutSlide()](#setDefaultMasterHandoutSlide--) | 관련 핸드아웃 슬라이드에 기본 마스터 핸드아웃 슬라이드를 설정합니다. |
| [removeMasterHandoutSlide()](#removeMasterHandoutSlide--) | 마스터 핸드아웃 슬라이드를 제거합니다. |
### getMasterHandoutSlide() {#getMasterHandoutSlide--}
```
public abstract IMasterHandoutSlide getMasterHandoutSlide()
```

이 프레젠테이션에 메모 슬라이드가 있는 경우 해당 슬라이드의 마스터를 반환하고, 없으면 null을 반환합니다. 읽기 전용 [IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide).

**반환:**
[IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
### setDefaultMasterHandoutSlide() {#setDefaultMasterHandoutSlide--}
```
public abstract IMasterHandoutSlide setDefaultMasterHandoutSlide()
```

관련 핸드아웃 슬라이드에 기본 마스터 핸드아웃 슬라이드를 설정합니다.

**반환:**
[IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide) - Master handout slide [IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
### removeMasterHandoutSlide() {#removeMasterHandoutSlide--}
```
public abstract void removeMasterHandoutSlide()
```

마스터 핸드아웃 슬라이드를 제거합니다.