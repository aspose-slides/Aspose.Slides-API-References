---
title: SlideShowTransition class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.slideshow/slideshowtransition/
---
## SlideShowTransition 클래스

슬라이드 쇼 전환을 나타냅니다.

SlideShowTransition 유형은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`sound`](/slides/python-net/ko/aspose.slides.slideshow/slideshowtransition/sound/) | 내장 오디오 데이터를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IAudio`](/slides/python-net/ko/aspose.slides/iaudio). |
| [`sound_mode`](/slides/python-net/ko/aspose.slides.slideshow/slideshowtransition/sound_mode/) | 슬라이드 전환에 대한 사운드 모드를 설정하거나 반환합니다.<br/>            읽기/쓰기 [`TransitionSoundMode`](/slides/python-net/ko/aspose.slides.slideshow/transitionsoundmode). |
| [`sound_loop`](/slides/python-net/ko/aspose.slides.slideshow/slideshowtransition/sound_loop/) | 이 속성은 사운드가 다음 사운드 이벤트가 슬라이드 쇼에서 발생할 때까지 반복되는지 여부를 지정합니다.<br/>            읽기/쓰기 **bool**. |
| [`advance_on_click`](/slides/python-net/ko/aspose.slides.slideshow/slideshowtransition/advance_on_click/) | 마우스 클릭으로 슬라이드가 넘어갈지 여부를 지정합니다. 이 속성이 지정되지 않은 경우 true 값이 기본으로 가정됩니다.<br/>            읽기/쓰기 **bool**. |
| [`advance_after`](/slides/python-net/ko/aspose.slides.slideshow/slideshowtransition/advance_after/) | 이 속성은 슬라이드 쇼가 일정 시간 후에 다음 슬라이드로 이동할지 여부를 지정합니다.<br/>            읽기/쓰기 **bool**. |
| [`advance_after_time`](/slides/python-net/ko/aspose.slides.slideshow/slideshowtransition/advance_after_time/) | 전환이 시작되어야 하는 시간을 밀리초 단위로 지정합니다. 이 설정은 advClick 속성과 함께 사용할 수 있습니다. 이 속성이 지정되지 않은 경우 자동 진행이 없다고 가정됩니다.<br/>            읽기/쓰기 **int**. |
| [`speed`](/slides/python-net/ko/aspose.slides.slideshow/slideshowtransition/speed/) | 현재 슬라이드에서 다음 슬라이드로 전환할 때 사용될 전환 속도를 지정합니다.<br/>            읽기/쓰기 [`TransitionSpeed`](/slides/python-net/ko/aspose.slides.slideshow/transitionspeed). |
| [`value`](/slides/python-net/ko/aspose.slides.slideshow/slideshowtransition/value/) | 슬라이드 쇼 전환 값.<br/>            읽기 전용 [`ITransitionValueBase`](/slides/python-net/ko/aspose.slides.slideshow/itransitionvaluebase). |
| [`type`](/slides/python-net/ko/aspose.slides.slideshow/slideshowtransition/type/) | 전환 유형.<br/>            읽기/쓰기 [`TransitionType`](/slides/python-net/ko/aspose.slides.slideshow/transitiontype). |
| [`sound_is_built_in`](/slides/python-net/ko/aspose.slides.slideshow/slideshowtransition/sound_is_built_in/) | 이 사운드가 내장 사운드인지 여부를 지정합니다. 이 속성이 true로 설정되면, 생성 애플리케이션은 이 사운드에 대해 지정된 name 속성을 내장 사운드 목록에서 확인하도록 알리고 필요에 따라 사용자 정의 이름이나 UI를 표시할 수 있습니다.<br/>            읽기/쓰기 **bool**. |
| [`sound_name`](/slides/python-net/ko/aspose.slides.slideshow/slideshowtransition/sound_name/) | 전환 사운드에 대한 사람이 읽을 수 있는 이름을 지정합니다. [`SlideShowTransition.sound`](/slides/python-net/ko/aspose.slides.slideshow/slideshowtransition/sound) 속성에 할당하여 사운드 이름을 가져오거나 설정해야 합니다.<br/>            읽기/쓰기 **str**. |
| [`duration`](/slides/python-net/ko/aspose.slides.slideshow/slideshowtransition/duration/) | 슬라이드 전환 효과의 지속 시간을 밀리초 단위로 가져오거나 설정합니다.<br/>            읽기/쓰기 **int**. |

### 참고
* 모듈 [`aspose.slides.slideshow`](/slides/python-net/ko/aspose.slides.slideshow)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)