---
title: BulletFormat class
second_title: Python용 Aspose.Slides via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/bulletformat/
---
## BulletFormat 클래스

단락 글머리표 서식 속성을 나타냅니다.

**Inheritance:**[`BulletFormat`](/slides/python-net/ko/aspose.slides/bulletformat) → [`PVIObject`](/slides/python-net/ko/aspose.slides/pviobject)

BulletFormat 형식은 다음 멤버를 노출합니다:

## 속성

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/ko/aspose.slides/bulletformat/type/) | 상속 없이 단락의 글머리표 유형을 반환하거나 설정합니다.<br/>읽기/쓰기 [`BulletType`](/slides/python-net/ko/aspose.slides/bullettype). |
| [`char`](/slides/python-net/ko/aspose.slides/bulletformat/char/) | 상속 없이 단락의 글머리표 문자를 반환하거나 설정합니다.<br/>읽기/쓰기 **System.Char**. |
| [`font`](/slides/python-net/ko/aspose.slides/bulletformat/font/) | 상속 없이 단락의 글머리표 글꼴을 반환하거나 설정합니다.<br/>읽기/쓰기 [`IFontData`](/slides/python-net/ko/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/ko/aspose.slides/bulletformat/height/) | 상속 없이 단락의 글머리표 높이를 반환하거나 설정합니다.<br/>값 float.NaN 은 글머리표가 단락의 첫 번째 부분에서 높이를 상속한다는 것을 나타냅니다.<br/>읽기/쓰기 **float**. |
| [`color`](/slides/python-net/ko/aspose.slides/bulletformat/color/) | 상속 없이 단락의 글머리표 색상 형식을 반환합니다.<br/>읽기 전용 [`IColorFormat`](/slides/python-net/ko/aspose.slides/icolorformat). |
| [`numbered_bullet_start_with`](/slides/python-net/ko/aspose.slides/bulletformat/numbered_bullet_start_with/) | 상속 없이 번호 매긴 글머리표 그룹에 사용되는 첫 번째 번호를 반환하거나 설정합니다.<br/>읽기/쓰기 **int**. |
| [`numbered_bullet_style`](/slides/python-net/ko/aspose.slides/bulletformat/numbered_bullet_style/) | 상속 없이 번호 매긴 글머리표의 스타일을 반환하거나 설정합니다.<br/>읽기/쓰기 [`NumberedBulletStyle`](/slides/python-net/ko/aspose.slides/numberedbulletstyle). |
| [`is_bullet_hard_color`](/slides/python-net/ko/aspose.slides/bulletformat/is_bullet_hard_color/) | 글머리표가 자체 색상을 가지고 있는지 또는 단락의 첫 번째 부분에서 색상을 상속받는지 결정합니다.<br/>글머리표가 자체 색상을 가지고 있으면 **NullableBool.True**, 단락의 첫 번째 부분에서 색상을 상속받으면 **NullableBool.False**.<br/>읽기/쓰기 [`NullableBool`](/slides/python-net/ko/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/ko/aspose.slides/bulletformat/is_bullet_hard_font/) | 글머리표가 자체 글꼴을 가지고 있는지 또는 단락의 첫 번째 부분에서 글꼴을 상속받는지 결정합니다.<br/>글머리표가 자체 글꼴을 가지고 있으면 **NullableBool.True**, 단락의 첫 번째 부분에서 글꼴을 상속받으면 **NullableBool.False**.<br/>읽기/쓰기 [`NullableBool`](/slides/python-net/ko/aspose.slides/nullablebool). |
| [`picture`](/slides/python-net/ko/aspose.slides/bulletformat/picture/) | 상속 없이 단락에서 글머리표로 사용되는 그림을 반환합니다.<br/>읽기 전용 [`ISlidesPicture`](/slides/python-net/ko/aspose.slides/islidespicture). |
| [`slide`](/slides/python-net/ko/aspose.slides/bulletformat/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides/bulletformat/presentation/) |  |

## 메서드

| Method | Description |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/ko/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/#) | 글머리표가 활성화된 경우 (PowerPoint에서 단락 글머리표/번호 매기기를 활성화했을 때와 같이) 유효한 단락 들여쓰기와 MarginLeft에 기본 비영(0이 아닌) 이동을 설정합니다. 글머리표가 비활성화된 경우 단락 들여쓰기와 MarginLeft을 재설정합니다 (PowerPoint에서 단락 글머리표/번호 매기기를 비활성화했을 때와 같이). 들여쓰기 이동은 현재 글머리표 컨텍스트인 IBulletFormat.Type, .NumberedBulletStyle 및 첫 번째 부분의 FontHeight를 기준으로 적용됩니다. 비영(0이 아닌) 들여쓰기 이동은 현재 단락의 유효한 Indent와 MarginLeft에 적용되어 결과 값을 로컬 값으로 만듭니다. |
| [`get_effective(self)`](/slides/python-net/ko/aspose.slides/bulletformat/get_effective/#) | 상속이 적용된 유효한 글머리표 서식 데이터를 가져옵니다. |


### 참고
* 클래스 [`BulletFormat`](/slides/python-net/ko/aspose.slides/bulletformat)
* 클래스 [`PVIObject`](/slides/python-net/ko/aspose.slides/pviobject)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)