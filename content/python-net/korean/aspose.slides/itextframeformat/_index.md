---
title: ITextFrameFormat class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/itextframeformat/
---
## ITextFrameFormat 클래스

TextFrame의 서식 속성을 포함합니다.

ITextFrameFormat 형식은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`text_style`](/slides/python-net/ko/aspose.slides/itextframeformat/text_style/) | 텍스트 스타일을 반환합니다.<br/>            읽기 전용 [`ITextStyle`](/slides/python-net/ko/aspose.slides/itextstyle). |
| [`margin_left`](/slides/python-net/ko/aspose.slides/itextframeformat/margin_left/) | TextFrame의 왼쪽 여백(포인트)을 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`margin_right`](/slides/python-net/ko/aspose.slides/itextframeformat/margin_right/) | TextFrame의 오른쪽 여백(포인트)을 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`margin_top`](/slides/python-net/ko/aspose.slides/itextframeformat/margin_top/) | TextFrame의 위쪽 여백(포인트)을 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`margin_bottom`](/slides/python-net/ko/aspose.slides/itextframeformat/margin_bottom/) | TextFrame의 아래쪽 여백(포인트)을 반환하거나 설정합니다.<br/>            읽기/쓰기 **float**. |
| [`wrap_text`](/slides/python-net/ko/aspose.slides/itextframeformat/wrap_text/) | **True** 일 경우 텍스트가 TextFrame의 여백에서 자동 줄 바꿈됩니다.<br/>            읽기/쓰기 [`NullableBool`](/slides/python-net/ko/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/ko/aspose.slides/itextframeformat/anchoring_type/) | TextFrame에서 수직 정렬 텍스트를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`TextAnchorType`](/slides/python-net/ko/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/ko/aspose.slides/itextframeformat/center_text/) | NullableBool.True인 경우 텍스트가 박스 안에서 가로로 가운데 정렬됩니다.<br/>            읽기/쓰기 [`NullableBool`](/slides/python-net/ko/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/ko/aspose.slides/itextframeformat/text_vertical_type/) | 텍스트 방향을 결정합니다.<br/>            이 속성과 속성 RotationAngle의 사용자 지정 각도를 종합한 시각적 텍스트 회전값을 반환합니다.<br/>            읽기/쓰기 [`TextVerticalType`](/slides/python-net/ko/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/ko/aspose.slides/itextframeformat/autofit_type/) | 텍스트의 자동 맞춤 모드를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`TextAutofitType`](/slides/python-net/ko/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/ko/aspose.slides/itextframeformat/column_count/) | 텍스트 영역의 열 수를 반환하거나 설정합니다.<br/>            이 값은 양수여야 합니다. 그렇지 않으면 값이 0으로 설정됩니다. <br/>            값 0은 정의되지 않은 값을 의미합니다.<br/>            읽기/쓰기 **int**. |
| [`column_spacing`](/slides/python-net/ko/aspose.slides/itextframeformat/column_spacing/) | 텍스트 영역의 텍스트 열 사이 간격을 반환하거나 설정합니다(포인트 단위). 이는 열이 1개 이상 존재할 때만 적용됩니다.<br/>            이 값은 양수여야 합니다. 그렇지 않으면 값이 0으로 설정됩니다. <br/>            읽기/쓰기 **float**. |
| [`three_d_format`](/slides/python-net/ko/aspose.slides/itextframeformat/three_d_format/) | 텍스트에 대한 3D 효과 속성을 나타내는 ThreeDFormat 개체를 반환합니다.<br/>            읽기 전용 [`IThreeDFormat`](/slides/python-net/ko/aspose.slides/ithreedformat). |
| [`keep_text_flat`](/slides/python-net/ko/aspose.slides/itextframeformat/keep_text_flat/) | 텍스트를 3D 장면에서 완전히 배제하도록 반환하거나 설정합니다.<br/>            읽기/쓰기 **bool**. |
| [`rotation_angle`](/slides/python-net/ko/aspose.slides/itextframeformat/rotation_angle/) | 바운딩 박스 내 텍스트에 적용되는 사용자 지정 회전을 지정합니다. 지정되지 않은 경우, 동반되는 도형의 회전이 사용됩니다.<br/>            지정된 경우, 이는 도형과 독립적으로 적용됩니다.<br/>            즉, 도형에 회전이 적용될 수 있으며 텍스트 자체에도 회전이 적용됩니다.<br/>            이 속성과 속성 TextVerticalType의 사전 정의된 수직 유형을 종합한 시각적 텍스트 회전값을 반환합니다.<br/>            읽기/쓰기 **float**. |
| [`transform`](/slides/python-net/ko/aspose.slides/itextframeformat/transform/) | 텍스트 감싸기 모양을 가져오거나 설정합니다.<br/>            읽기/쓰기 [`TextShapeType`](/slides/python-net/ko/aspose.slides/textshapetype). |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/ko/aspose.slides/itextframeformat/get_effective/#) | 상속이 적용된 효과적인 텍스트 프레임 서식 데이터를 가져옵니다. |

### 참고
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)