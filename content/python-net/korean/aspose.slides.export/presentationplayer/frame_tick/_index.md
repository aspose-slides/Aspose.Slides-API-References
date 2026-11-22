---
title: frame_tick event
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.export/presentationplayer/frame_tick/
weight: 30
---
## frame_tick 이벤트
frame_tick 이벤트.

플레이어가 [`PresentationAnimationsGenerator`](/slides/python-net/ko/aspose.slides.export/presentationanimationsgenerator)에 의해 생성된 애니메이션의 각 프레임을 생성할 때 발생합니다.

### 정의:
```python
def on_frame_tick(sender, args):
    ...

obj.frame_tick += on_frame_tick
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| sender | [`PresentationPlayer`](/slides/python-net/ko/aspose.slides.export/presentationplayer) |  |
| args | [`FrameTickEventArgs`](/slides/python-net/ko/aspose.slides.export/frametickeventargs) |  |

### 참고
* 클래스 [`FrameTickEventArgs`](/slides/python-net/ko/aspose.slides.export/frametickeventargs)
* 클래스 [`PresentationAnimationsGenerator`](/slides/python-net/ko/aspose.slides.export/presentationanimationsgenerator)
* 클래스 [`PresentationPlayer`](/slides/python-net/ko/aspose.slides.export/presentationplayer)
* 모듈 [`aspose.slides.export`](/slides/python-net/ko/aspose.slides.export)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)