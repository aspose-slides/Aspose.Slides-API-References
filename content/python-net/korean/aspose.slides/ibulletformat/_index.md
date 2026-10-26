---
title: IBulletFormat class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/ibulletformat/
---
## IBulletFormat 클래스

단락 글머리표 서식 속성을 나타냅니다.

IBulletFormat 유형은 다음 멤버를 노출합니다:

## 속성

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/ko/aspose.slides/ibulletformat/type/) | 단락의 상속이 없는 글머리표 유형을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`BulletType`](/slides/python-net/ko/aspose.slides/bullettype). |
| [`char`](/slides/python-net/ko/aspose.slides/ibulletformat/char/) | 단락의 상속이 없는 글머리표 문자를 반환하거나 설정합니다.<br/>            읽기/쓰기 **System.Char**. |
| [`font`](/slides/python-net/ko/aspose.slides/ibulletformat/font/) | 단락의 상속이 없는 글머리표 폰트를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IFontData`](/slides/python-net/ko/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/ko/aspose.slides/ibulletformat/height/) | 단락의 상속이 없는 글머리표 높이를 반환하거나 설정합니다.<br/>            값 float.NaN 은 글머리표가 단락의 첫 번째 구간에서 높이를 상속받음음을 의미합니다.<br/>            읽기/쓰기 **float**. |
| [`color`](/slides/python-net/ko/aspose.slides/ibulletformat/color/) | 단락의 상속이 없는 글머리표 색상 형식을 반환합니다.<br/>            읽기 전용 [`IColorFormat`](/slides/python-net/ko/aspose.slides/icolorformat). |
| [`picture`](/slides/python-net/ko/aspose.slides/ibulletformat/picture/) | 단락의 상속이 없는 글머리표로 사용되는 그림을 반환합니다.<br/>            읽기 전용 [`ISlidesPicture`](/slides/python-net/ko/aspose.slides/islidespicture). |
| [`numbered_bullet_start_with`](/slides/python-net/ko/aspose.slides/ibulletformat/numbered_bullet_start_with/) | 상속이 없는 번호 매기기 글머리표 그룹에 사용되는 첫 번째 번호를 반환하거나 설정합니다.<br/>            읽기/쓰기 **int**. |
| [`numbered_bullet_style`](/slides/python-net/ko/aspose.slides/ibulletformat/numbered_bullet_style/) | 상속이 없는 번호 매기기 글머리표 스타일을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IBulletFormat.numbered_bullet_style`](/slides/python-net/ko/aspose.slides/ibulletformat/numbered_bullet_style). |
| [`is_bullet_hard_color`](/slides/python-net/ko/aspose.slides/ibulletformat/is_bullet_hard_color/) | 글머리표가 자체 색상을 가지고 있는지 또는 단락의 첫 번째 구간에서 색상을 상속받는지 결정합니다.<br/>            **NullableBool.True** 은 글머리표가 자체 색상을 가질 때이고 **NullableBool.False** 은 글머리표가 단락의 첫 번째 구간에서 색상을 상속받을 때입니다.<br/>            읽기/쓰기 [`NullableBool`](/slides/python-net/ko/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/ko/aspose.slides/ibulletformat/is_bullet_hard_font/) | 글머리표가 자체 폰트를 가지고 있는지 또는 단락의 첫 번째 구간에서 폰트를 상속받는지 결정합니다.<br/>            **NullableBool.True** 은 글머리표가 자체 폰트를 가질 때이고 **NullableBool.False** 은 글머리표가 단락의 첫 번째 구간에서 폰트를 상속받을 때입니다.<br/>            읽기/쓰기 [`NullableBool`](/slides/python-net/ko/aspose.slides/nullablebool). |

## 메서드

| Method | Description |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/ko/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/#) | 글머리표가 활성화된 경우(예: PowerPoint에서 단락 글머리표/번호 매기기를 활성화할 때와 같이) 효과적인 단락 Indent와 MarginLeft에 대한 기본 비영(非零) 이동을 설정합니다. 글머리표가 비활성화된 경우에는 단락 Indent와 MarginLeft를 단순히 재설정합니다(예: PowerPoint에서 단락 글머리표/번호 매기기를 비활성화할 때와 같이). 들여쓰기 이동은 현재 글머리표 컨텍스트인 IBulletFormat.Type, .NumberedBulletStyle 및 첫 번째 구간의 FontHeight를 기준으로 적용됩니다. 비영 이동은 현재 단락의 효과적인 Indent와 MarginLeft에 적용되어 결과 값을 로컬 값으로 만듭니다. |
| [`get_effective(self)`](/slides/python-net/ko/aspose.slides/ibulletformat/get_effective/#) | 상속이 적용된 효과적인 글머리표 서식 데이터를 가져옵니다. |

### 참조
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)