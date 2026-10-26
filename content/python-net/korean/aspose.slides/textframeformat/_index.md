---
title: TextFrameFormat class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/textframeformat/
---
## TextFrameFormat 클래스

TextFrame의 formatTextFrameFormatting 속성을 포함합니다.

**Inheritance:**[`TextFrameFormat`](/slides/python-net/ko/aspose.slides/textframeformat) → [`PVIObject`](/slides/python-net/ko/aspose.slides/pviobject)

TextFrameFormat 형식은 다음 멤버를 노출합니다:

## 생성자

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ko/aspose.slides/textframeformat/__init__/#) | [`TextFrameFormat`](/slides/python-net/ko/aspose.slides/textframeformat) 클래스의 새로운 인스턴스를 초기화합니다. |

## 속성

| Property | Description |
| :- | :- |
| [`three_d_format`](/slides/python-net/ko/aspose.slides/textframeformat/three_d_format/) | 텍스트에 대한 3d 효과 속성을 나타내는 ThreeDFormat 객체를 반환합니다.<br/>            읽기 전용 [`IThreeDFormat`](/slides/python-net/ko/aspose.slides/ithreedformat). |
| [`margin_left`](/slides/python-net/ko/aspose.slides/textframeformat/margin_left/) | TextFrame에서 왼쪽 여백(포인트)을 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`margin_right`](/slides/python-net/ko/aspose.slides/textframeformat/margin_right/) | TextFrame에서 오른쪽 여백(포인트)을 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`margin_top`](/slides/python-net/ko/aspose.slides/textframeformat/margin_top/) | TextFrame에서 위쪽 여백(포인트)을 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`margin_bottom`](/slides/python-net/ko/aspose.slides/textframeformat/margin_bottom/) | TextFrame에서 아래쪽 여백(포인트)을 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`wrap_text`](/slides/python-net/ko/aspose.slides/textframeformat/wrap_text/) | 텍스트가 TextFrame의 여백에서 자동 줄바꿈되는 경우 **True**.<br/>            읽기/쓰기 [`NullableBool`](/slides/python-net/ko/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/ko/aspose.slides/textframeformat/anchoring_type/) | TextFrame에서 수직 앵커 텍스트를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`TextAnchorType`](/slides/python-net/ko/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/ko/aspose.slides/textframeformat/center_text/) | NullableBool.True이면 텍스트가 박스 안에서 가로로 중앙 정렬되어야 합니다.<br/>            읽기/쓰기 [`NullableBool`](/slides/python-net/ko/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/ko/aspose.slides/textframeformat/text_vertical_type/) | 텍스트 방향을 결정합니다.<br/>            이 속성 및 사용자 지정 각도 속성 RotationAngle에서 요약된 시각적 텍스트 회전값이 결과값이 됩니다.<br/>            읽기/쓰기 [`TextVerticalType`](/slides/python-net/ko/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/ko/aspose.slides/textframeformat/autofit_type/) | 텍스트의 자동 맞춤 모드를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`TextAutofitType`](/slides/python-net/ko/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/ko/aspose.slides/textframeformat/column_count/) | 텍스트 영역의 열 개수를 반환하거나 설정합니다.<br/>            이 값은 양수여야 합니다. 그렇지 않으면 값이 0으로 설정됩니다.<br/>            값 0은 정의되지 않은 값을 의미합니다.<br/>            읽기/쓰기 **int**. |
| [`column_spacing`](/slides/python-net/ko/aspose.slides/textframeformat/column_spacing/) | 텍스트 영역의 열 사이 간격을 포인트 단위로 반환하거나 설정합니다. 이는 열이 2개 이상일 때만 적용됩니다.<br/>            이 값은 양수여야 합니다. 그렇지 않으면 값이 0으로 설정됩니다.<br/>            읽기/쓰기 **float**. |
| [`rotation_angle`](/slides/python-net/ko/aspose.slides/textframeformat/rotation_angle/) | 경계 상자 내 텍스트에 적용되는 사용자 지정 회전을 지정합니다. 지정되지 않은 경우, 동반되는 도형의 회전이 사용됩니다. 지정된 경우 도형의 회전과 독립적으로 적용됩니다.<br/>            이 속성 및 사전 정의된 수직 유형 속성 TextVerticalType에서 요약된 시각적 텍스트 회전값이 결과값이 됩니다.<br/>            읽기/쓰기 **float**. |
| [`transform`](/slides/python-net/ko/aspose.slides/textframeformat/transform/) | 텍스트 자동 줄바꿈 모양을 가져오거나 설정합니다.<br/>            읽기/쓰기 [`TextShapeType`](/slides/python-net/ko/aspose.slides/textshapetype). |
| [`keep_text_flat`](/slides/python-net/ko/aspose.slides/textframeformat/keep_text_flat/) | 3-D 회전 효과가 적용되었더라도 텍스트를 평면으로 유지하도록 설정합니다.<br/>            읽기/쓰기 **bool**. |
| [`slide`](/slides/python-net/ko/aspose.slides/textframeformat/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides/textframeformat/presentation/) |  |
| [`text_style`](/slides/python-net/ko/aspose.slides/textframeformat/text_style/) |  |

## 메서드

| Method | Description |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/ko/aspose.slides/textframeformat/get_effective/#) | 상속이 적용된 효과적인 텍스트 프레임 서식 데이터를 가져옵니다. |

### 참고
* 클래스 [`PVIObject`](/slides/python-net/ko/aspose.slides/pviobject)
* 클래스 [`TextFrameFormat`](/slides/python-net/ko/aspose.slides/textframeformat)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)