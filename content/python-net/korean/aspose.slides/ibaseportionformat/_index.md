---
title: IBasePortionFormat class
second_title: Python용 Aspose.Slides via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat 클래스

이 클래스는 텍스트 구간 서식 속성을 포함합니다. [`IPortionFormatEffectiveData`](/slides/python-net/ko/aspose.slides/iportionformateffectivedata)와 달리, 이 클래스의 모든 속성은 쓰기 가능합니다.

IBasePortionFormat 형식은 다음 멤버를 노출합니다:

## 속성

| Property | Description |
| :- | :- |
| [`line_format`](/slides/python-net/ko/aspose.slides/ibaseportionformat/line_format/) | 텍스트 외곽선에 대한 LineFormat 속성을 반환합니다. 상속이 적용되지 않습니다.<br/>            읽기 전용 [`ILineFormat`](/slides/python-net/ko/aspose.slides/ilineformat). |
| [`fill_format`](/slides/python-net/ko/aspose.slides/ibaseportionformat/fill_format/) | 텍스트 FillFormat 속성을 반환합니다. 상속이 적용되지 않습니다.<br/>            읽기 전용 [`IFillFormat`](/slides/python-net/ko/aspose.slides/ifillformat). |
| [`effect_format`](/slides/python-net/ko/aspose.slides/ibaseportionformat/effect_format/) | 텍스트 EffectFormat 속성을 반환합니다. 상속이 적용되지 않습니다.<br/>            읽기 전용 [`IEffectFormat`](/slides/python-net/ko/aspose.slides/ieffectformat). |
| [`highlight_color`](/slides/python-net/ko/aspose.slides/ibaseportionformat/highlight_color/) | 텍스트 강조에 사용되는 색상을 반환합니다. 상속이 적용되지 않습니다.<br/>            읽기 전용 [`IColorFormat`](/slides/python-net/ko/aspose.slides/icolorformat). |
| [`underline_line_format`](/slides/python-net/ko/aspose.slides/ibaseportionformat/underline_line_format/) | 밑줄 선의 외곽선에 사용되는 LineFormat 속성을 반환합니다. 상속이 적용되지 않습니다.<br/>            읽기 전용 [`ILineFormat`](/slides/python-net/ko/aspose.slides/ilineformat). |
| [`underline_fill_format`](/slides/python-net/ko/aspose.slides/ibaseportionformat/underline_fill_format/) | 밑줄 선 FillFormat 속성을 반환합니다. 상속이 적용되지 않습니다.<br/>            읽기 전용 [`IFillFormat`](/slides/python-net/ko/aspose.slides/ifillformat). |
| [`font_bold`](/slides/python-net/ko/aspose.slides/ibaseportionformat/font_bold/) | 폰트가 굵게인지 여부를 결정합니다. 상속이 적용되지 않습니다.<br/>            읽기/쓰기 [`NullableBool`](/slides/python-net/ko/aspose.slides/nullablebool). |
| [`font_italic`](/slides/python-net/ko/aspose.slides/ibaseportionformat/font_italic/) | 폰트가 이탤릭인지 여부를 결정합니다. 상속이 적용되지 않습니다.<br/>            읽기/쓰기 [`NullableBool`](/slides/python-net/ko/aspose.slides/nullablebool). |
| [`kumimoji`](/slides/python-net/ko/aspose.slides/ibaseportionformat/kumimoji/) | 숫자가 텍스트의 동아시아 언어별 수직 레이아웃을 무시해야 하는지 여부를 결정합니다. 상속이 적용되지 않습니다.<br/>            읽기/쓰기 [`NullableBool`](/slides/python-net/ko/aspose.slides/nullablebool). |
| [`normalise_height`](/slides/python-net/ko/aspose.slides/ibaseportionformat/normalise_height/) | 텍스트 높이를 정규화할지 여부를 결정합니다. 상속이 적용되지 않습니다.<br/>            읽기/쓰기 [`NullableBool`](/slides/python-net/ko/aspose.slides/nullablebool). |
| [`proof_disabled`](/slides/python-net/ko/aspose.slides/ibaseportionformat/proof_disabled/) | 텍스트를 교정하지 않을지 여부를 결정합니다. 상속이 적용되지 않습니다.<br/>            읽기/쓰기 [`NullableBool`](/slides/python-net/ko/aspose.slides/nullablebool). |
| [`font_underline`](/slides/python-net/ko/aspose.slides/ibaseportionformat/font_underline/) | 텍스트 밑줄 유형을 반환하거나 설정합니다. 상속이 적용되지 않습니다.<br/>            읽기/쓰기 [`TextUnderlineType`](/slides/python-net/ko/aspose.slides/textunderlinetype). |
| [`text_cap_type`](/slides/python-net/ko/aspose.slides/ibaseportionformat/text_cap_type/) | 텍스트 대소문자 유형을 반환하거나 설정합니다. 상속이 적용되지 않습니다.<br/>            읽기/쓰기 [`TextCapType`](/slides/python-net/ko/aspose.slides/textcaptype). |
| [`strikethrough_type`](/slides/python-net/ko/aspose.slides/ibaseportionformat/strikethrough_type/) | 텍스트 취소선 유형을 반환하거나 설정합니다. 상속이 적용되지 않습니다.<br/>            읽기/쓰기 [`TextStrikethroughType`](/slides/python-net/ko/aspose.slides/textstrikethroughtype). |
| [`is_hard_underline_line`](/slides/python-net/ko/aspose.slides/ibaseportionformat/is_hard_underline_line/) | 밑줄 스타일이 자체 LineFormat 속성을 가지고 있는지 아니면 텍스트의 LineFormat 속성으로부터 상속받는지 여부를 결정합니다.<br/>            읽기/쓰기 [`NullableBool`](/slides/python-net/ko/aspose.slides/nullablebool). |
| [`is_hard_underline_fill`](/slides/python-net/ko/aspose.slides/ibaseportionformat/is_hard_underline_fill/) | 밑줄 스타일이 자체 FillFormat 속성을 가지고 있는지 아니면 텍스트의 FillFormat 속성으로부터 상속받는지 여부를 결정합니다.<br/>            읽기/쓰기 [`NullableBool`](/slides/python-net/ko/aspose.slides/nullablebool). |
| [`font_height`](/slides/python-net/ko/aspose.slides/ibaseportionformat/font_height/) | 구간의 폰트 높이를 반환하거나 설정합니다.<br/>            **float.NaN** 은 높이가 정의되지 않았으며 마스터로부터 상속되어야 함을 의미합니다.<br/>            읽기/쓰기 **float**. |
| [`latin_font`](/slides/python-net/ko/aspose.slides/ibaseportionformat/latin_font/) | 라틴 폰트 정보를 반환하거나 설정합니다.<br/>            Null 은 폰트가 정의되지 않았으며 마스터로부터 상속되어야 함을 의미합니다.<br/>            읽기/쓰기 [`IFontData`](/slides/python-net/ko/aspose.slides/ifontdata). |
| [`east_asian_font`](/slides/python-net/ko/aspose.slides/ibaseportionformat/east_asian_font/) | 동아시아 폰트 정보를 반환하거나 설정합니다.<br/>            Null 은 폰트가 정의되지 않았으며 마스터로부터 상속되어야 함을 의미합니다.<br/>            읽기/쓰기 [`IFontData`](/slides/python-net/ko/aspose.slides/ifontdata). |
| [`complex_script_font`](/slides/python-net/ko/aspose.slides/ibaseportionformat/complex_script_font/) | 복합 스크립트 폰트 정보를 반환하거나 설정합니다.<br/>            Null 은 폰트가 정의되지 않았으며 마스터로부터 상속되어야 함을 의미합니다.<br/>            읽기/쓰기 [`IFontData`](/slides/python-net/ko/aspose.slides/ifontdata). |
| [`symbol_font`](/slides/python-net/ko/aspose.slides/ibaseportionformat/symbol_font/) | 기호 폰트 정보를 반환하거나 설정합니다.<br/>            Null 은 폰트가 정의되지 않았으며 마스터로부터 상속되어야 함을 의미합니다.<br/>            읽기/쓰기 [`IFontData`](/slides/python-net/ko/aspose.slides/ifontdata). |
| [`escapement`](/slides/python-net/ko/aspose.slides/ibaseportionformat/escapement/) | 위 첨자 또는 아래 첨자 텍스트를 반환하거나 설정합니다.<br/>            -100% (아래 첨자)부터 100% (위 첨자)까지의 값.<br/>            **float.NaN** 은 값이 정의되지 않았으며 마스터로부터 상속되어야 함을 의미합니다.<br/>            읽기/쓰기 **float**. |
| [`kerning_minimal_size`](/slides/python-net/ko/aspose.slides/ibaseportionformat/kerning_minimal_size/) | 커닝을 켜야 하는 최소 폰트 크기를 반환하거나 설정합니다.<br/>            **float.NaN** 은 값이 정의되지 않았으며 마스터로부터 상속되어야 함을 의미합니다.<br/>            읽기/쓰기 **float**. |
| [`language_id`](/slides/python-net/ko/aspose.slides/ibaseportionformat/language_id/) | 교정 언어의 Id를 반환하거나 설정합니다. 맞춤법 및 문법 확인에 사용됩니다.<br/>            읽기/쓰기 **str**. |
| [`alternative_language_id`](/slides/python-net/ko/aspose.slides/ibaseportionformat/alternative_language_id/) | 대체 언어의 Id를 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`spacing`](/slides/python-net/ko/aspose.slides/ibaseportionformat/spacing/) | 문자 간 간격 증가량을 반환하거나 설정합니다.<br/>            **float.NaN** 은 값이 정의되지 않았으며 마스터로부터 상속되어야 함을 의미합니다.<br/>            읽기/쓰기 **float**. |
| [`spell_check`](/slides/python-net/ko/aspose.slides/ibaseportionformat/spell_check/) | 텍스트 구간에 대해 맞춤법 검사가 활성화되어 있는지 여부를 반환하거나 설정합니다.<br/>            이 속성이 false 로 설정되면 텍스트 요소에 대한 맞춤법 검사가 억제됩니다.<br/>            true 로 설정하면 맞춤법 검사가 허용됩니다.<br/>            기본값은 `false` 입니다. |


### 비고

이 클래스는 특정 구간에 대해 정의된 텍스트 구간 서식 속성을 반환하고 조작하는 데 사용됩니다. 이는 값을 가져올 때 상속이 적용되지 않으므로 대부분의 경우 값이 "정의되지 않음"을 의미한다는 것을 의미합니다.

상속을 포함한 실제 서식 매개변수 값을 얻으려면 [`IPortionFormat.get_effective`](/slides/python-net/ko/aspose.slides/iportionformat/get_effective) 메서드를 사용해야 하며, 이 메서드는 [`IPortionFormatEffectiveData`](/slides/python-net/ko/aspose.slides/iportionformateffectivedata) 인스턴스를 반환합니다.


### 참조
* 클래스 [`IPortionFormatEffectiveData`](/slides/python-net/ko/aspose.slides/iportionformateffectivedata)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)