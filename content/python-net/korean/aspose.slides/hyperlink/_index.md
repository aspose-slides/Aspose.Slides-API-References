---
title: Hyperlink class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/hyperlink/
---
## Hyperlink 클래스

하이퍼링크를 나타냅니다.

**상속:**[`Hyperlink`](/slides/python-net/ko/aspose.slides/hyperlink) → [`PVIObject`](/slides/python-net/ko/aspose.slides/pviobject)

Hyperlink 유형은 다음 구성원을 노출합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self, url)`](/slides/python-net/ko/aspose.slides/hyperlink/__init__/#str) | 하이퍼링크 인스턴스를 생성합니다. |
| [`__init__(self, slide)`](/slides/python-net/ko/aspose.slides/hyperlink/__init__/#islide) | 특정 슬라이드를 가리키는 하이퍼링크 인스턴스를 생성합니다.<br/>            참고: 생성된 하이퍼링크는 동일 프레젠테이션의 객체에 할당해야 하며, 그렇지 않으면 링크가 NoAction으로 저장됩니다. |
| [`__init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click)`](/slides/python-net/ko/aspose.slides/hyperlink/__init__/#hyperlink-str-str-bool-bool-bool) | 다른 하이퍼링크를 소스로 사용하여 하이퍼링크 인스턴스를 생성하고, 보조 속성을 재정의합니다. |

## 속성

| 속성 | 설명 |
| :- | :- |
| [`no_action`](/slides/python-net/ko/aspose.slides/hyperlink/no_action/) | 특수 "do nothing" 하이퍼링크를 반환합니다.<br/>            읽기 전용 [`Hyperlink`](/slides/python-net/ko/aspose.slides/hyperlink). |
| [`media`](/slides/python-net/ko/aspose.slides/hyperlink/media/) | 특수 "play mediafile" 하이퍼링크를 반환합니다. AudioFrame 및 VideoFrame에서 사용됩니다.<br/>            읽기 전용 [`Hyperlink`](/slides/python-net/ko/aspose.slides/hyperlink). |
| [`next_slide`](/slides/python-net/ko/aspose.slides/hyperlink/next_slide/) | 다음 슬라이드로의 하이퍼링크를 반환합니다.<br/>            읽기 전용 [`Hyperlink`](/slides/python-net/ko/aspose.slides/hyperlink). |
| [`previous_slide`](/slides/python-net/ko/aspose.slides/hyperlink/previous_slide/) | 이전 슬라이드로의 하이퍼링크를 반환합니다.<br/>            읽기 전용 [`Hyperlink`](/slides/python-net/ko/aspose.slides/hyperlink). |
| [`first_slide`](/slides/python-net/ko/aspose.slides/hyperlink/first_slide/) | 프레젠테이션 첫 슬라이드로의 하이퍼링크를 반환합니다.<br/>            읽기 전용 [`Hyperlink`](/slides/python-net/ko/aspose.slides/hyperlink). |
| [`last_slide`](/slides/python-net/ko/aspose.slides/hyperlink/last_slide/) | 프레젠테이션 마지막 슬라이드로의 하이퍼링크를 반환합니다.<br/>            읽기 전용 [`Hyperlink`](/slides/python-net/ko/aspose.slides/hyperlink). |
| [`last_vieved_slide`](/slides/python-net/ko/aspose.slides/hyperlink/last_vieved_slide/) | 마지막으로 본 슬라이드로의 하이퍼링크를 반환합니다.<br/>            읽기 전용 [`Hyperlink`](/slides/python-net/ko/aspose.slides/hyperlink). |
| [`end_show`](/slides/python-net/ko/aspose.slides/hyperlink/end_show/) | 쇼를 종료하는 하이퍼링크를 반환합니다.<br/>            읽기 전용 [`Hyperlink`](/slides/python-net/ko/aspose.slides/hyperlink). |
| [`action_type`](/slides/python-net/ko/aspose.slides/hyperlink/action_type/) | Hyperlink의 동작 유형을 반환합니다.<br/>            읽기 전용 [`HyperlinkActionType`](/slides/python-net/ko/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/ko/aspose.slides/hyperlink/external_url/) | 외부 URL을 지정합니다.<br/>            읽기 전용 **str**. |
| [`target_slide`](/slides/python-net/ko/aspose.slides/hyperlink/target_slide/) | Hyperlink가 특정 슬라이드를 대상으로 하면 해당 슬라이드를 반환합니다.<br/>            읽기 전용 [`ISlide`](/slides/python-net/ko/aspose.slides/islide). |
| [`external_url_original`](/slides/python-net/ko/aspose.slides/hyperlink/external_url_original/) | 이 부분의 실제 내용과 무관하게 이 부분에 설정된 하이퍼링크를 나타냅니다.<br/>            <br/>            PowerPoint은 해당 부분의 링크와 해당 텍스트에 대해 특수하게 동작합니다.<br/>            링크의 실제 주소와 다른 유효한 URL 형태로 하이퍼링크 텍스트를 만들 수 있습니다.<br/>            이 경우, 편집 창에서 링크를 볼 때 텍스트 부분에 맞게 변경됩니다.<br/>            이 속성은 하이퍼링크의 원래 값을 나타냅니다. |
| [`target_frame`](/slides/python-net/ko/aspose.slides/hyperlink/target_frame/) | 상위 하이퍼링크의 대상이 존재할 경우, 상위 HTML 프레임셋 내의 프레임을 반환합니다.<br/>            읽기/쓰기 **str**. |
| [`tooltip`](/slides/python-net/ko/aspose.slides/hyperlink/tooltip/) | 상위 하이퍼링크와 연관된 사용자 인터페이스에 표시될 수 있는 문자열을 반환합니다.<br/>            읽기/쓰기 **str**. |
| [`history`](/slides/python-net/ko/aspose.slides/hyperlink/history/) | 상위 하이퍼링크가 호출될 때 해당 대상이 본 하이퍼링크 목록에 추가될지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`highlight_click`](/slides/python-net/ko/aspose.slides/hyperlink/highlight_click/) | 클릭 시 하이퍼링크를 강조 표시할지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`stop_sound_on_click`](/slides/python-net/ko/aspose.slides/hyperlink/stop_sound_on_click/) | 하이퍼링크 클릭 시 사운드를 중지할지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`sound`](/slides/python-net/ko/aspose.slides/hyperlink/sound/) | 하이퍼링크의 재생 사운드를 나타냅니다.<br/>            읽기/쓰기 [`IAudio`](/slides/python-net/ko/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/ko/aspose.slides/hyperlink/color_source/) | 하이퍼링크 색상의 원본을 나타냅니다 - 스타일 또는 부분 서식 중 하나.<br/>            읽기/쓰기 [`HyperlinkColorSource`](/slides/python-net/ko/aspose.slides/hyperlinkcolorsource). |
| [`slide`](/slides/python-net/ko/aspose.slides/hyperlink/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides/hyperlink/presentation/) |  |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/ko/aspose.slides/hyperlink/equals/#ihyperlink) | 두 Hyperlink 인스턴스가 동일한지 여부를 결정합니다. |

### 관련 항목
* 클래스 [`Hyperlink`](/slides/python-net/ko/aspose.slides/hyperlink)
* 클래스 [`PVIObject`](/slides/python-net/ko/aspose.slides/pviobject)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)