---
title: IMasterHandoutSlideManager
second_title: Aspose.Slides for Java API Reference
description: 마스터 핸드아웃 슬라이드 관리자.
type: docs
url: /ko/com.aspose.slides/imasterhandoutslidemanager/
---```
public interface IMasterHandoutSlideManager
```

마스터 핸드아웃 슬라이드 관리자.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getMasterHandoutSlide()](#getMasterHandoutSlide--) | 프레젠테이션에 마스터가 있으면 모든 노트 슬라이드의 마스터를 반환하고, 없으면 null을 반환합니다. |
| [setDefaultMasterHandoutSlide()](#setDefaultMasterHandoutSlide--) | 기본 마스터 핸드아웃 슬라이드를 관련 핸드아웃 슬라이드로 설정합니다. |
| [removeMasterHandoutSlide()](#removeMasterHandoutSlide--) | 마스터 핸드아웃 슬라이드를 제거합니다. |
### getMasterHandoutSlide() {#getMasterHandoutSlide--}
```
public abstract IMasterHandoutSlide getMasterHandoutSlide()
```

프레젠테이션에 마스터가 있으면 모든 노트 슬라이드의 마스터를 반환하고, 없으면 null을 반환합니다. 읽기 전용 [IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide).

**반환:**  
[IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
### setDefaultMasterHandoutSlide() {#setDefaultMasterHandoutSlide--}
```
public abstract IMasterHandoutSlide setDefaultMasterHandoutSlide()
```

기본 마스터 핸드아웃 슬라이드를 관련 핸드아웃 슬라이드로 설정합니다.

**반환:**  
[IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide) - Master handout slide [IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
### removeMasterHandoutSlide() {#removeMasterHandoutSlide--}
```
public abstract void removeMasterHandoutSlide()
```

마스터 핸드아웃 슬라이드를 제거합니다.