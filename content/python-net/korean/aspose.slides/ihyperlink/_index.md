---
title: IHyperlink class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/ihyperlink/
---
## IHyperlink 클래스

Represents a hyperlink.

The IHyperlink type exposes the following members:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`action_type`](/slides/python-net/ko/aspose.slides/ihyperlink/action_type/) | HyperLinkEx 작업의 유형을 반환합니다.<br/>            읽기 전용 [`HyperlinkActionType`](/slides/python-net/ko/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/ko/aspose.slides/ihyperlink/external_url/) | 외부 URL을 지정합니다.<br/>            이 속성이 None이 아니게 되면 속성 TargetSlide는 None이 됩니다.<br/>            읽기 전용 **str**. |
| [`external_url_original`](/slides/python-net/ko/aspose.slides/ihyperlink/external_url_original/) | 이 구간의 실제 내용과 무관하게 이 구간에 설정된 하이퍼링크를 나타냅니다.<br/>            <br/>            PowerPoint는 구간 내 링크와 해당 텍스트에 대해 특별히 동작합니다.<br/>            유효한 URL 형태의 텍스트를 실제 링크 주소와 다르게 하이퍼링크에 생성할 수 있게 합니다.<br/>            이 경우 편집 창에서 링크를 볼 때 텍스트 구간에 맞게 변경됩니다.<br/>            이 속성은 하이퍼링크의 원래 값을 나타냅니다. |
| [`target_slide`](/slides/python-net/ko/aspose.slides/ihyperlink/target_slide/) | HyperlinkEx가 특정 슬라이드를 대상이면 해당 슬라이드를 반환합니다.<br/>            이 속성이 None이 아니게 되면 속성 ExternalUrl은 None이 됩니다.<br/>            읽기 전용 [`ISlide`](/slides/python-net/ko/aspose.slides/islide). |
| [`target_frame`](/slides/python-net/ko/aspose.slides/ihyperlink/target_frame/) | 대상의<br/>            부모 하이퍼링크가 존재할 경우 부모 HTML 프레임셋 내 프레임을 반환합니다.<br/>            읽기/쓰기 **str**. |
| [`tooltip`](/slides/python-net/ko/aspose.slides/ihyperlink/tooltip/) | 사용자 인터페이스에 표시될 수 있는 문자열을 반환합니다.<br/>            부모 하이퍼링크와 연관되어.<br/>            읽기/쓰기 **str**. |
| [`history`](/slides/python-net/ko/aspose.slides/ihyperlink/history/) | 부모 하이퍼링크의 대상이 호출될 때<br/>            본 보기 하이퍼링크 리스트에 추가될지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`highlight_click`](/slides/python-net/ko/aspose.slides/ihyperlink/highlight_click/) | 클릭 시 하이퍼링크를 강조 표시할지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`stop_sound_on_click`](/slides/python-net/ko/aspose.slides/ihyperlink/stop_sound_on_click/) | 하이퍼링크 클릭 시 사운드를 중지할지 여부를 결정합니다.<br/>            읽기/쓰기 **bool**. |
| [`sound`](/slides/python-net/ko/aspose.slides/ihyperlink/sound/) | 하이퍼링크의 재생 사운드를 나타냅니다.<br/>            읽기/쓰기 [`IAudio`](/slides/python-net/ko/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/ko/aspose.slides/ihyperlink/color_source/) | 하이퍼링크 색상의 원본을 나타냅니다 - 스타일이든 구간 형식이든.<br/>            읽기/쓰기 [`HyperlinkColorSource`](/slides/python-net/ko/aspose.slides/hyperlinkcolorsource). |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/ko/aspose.slides/ihyperlink/equals/#ihyperlink) | 두 Hyperlink 인스턴스가 동일한지 여부를 결정합니다. |

### 참조
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)