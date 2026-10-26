---
title: IBackground class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/ibackground/
---
## IBackground 클래스

슬라이드의 배경을 나타냅니다.

IBackground 형식은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`type`](/slides/python-net/ko/aspose.slides/ibackground/type/) | 배경 채우기의 유형을 반환합니다.<br/>            읽기/쓰기 [`BackgroundType`](/slides/python-net/ko/aspose.slides/backgroundtype). |
| [`fill_format`](/slides/python-net/ko/aspose.slides/ibackground/fill_format/) | BackgroundType.OwnBackground 채우기에 대한 FillFormat을 반환합니다.<br/>            읽기 전용 [`IFillFormat`](/slides/python-net/ko/aspose.slides/ifillformat). |
| [`effect_format`](/slides/python-net/ko/aspose.slides/ibackground/effect_format/) | BackgroundType.OwnBackground 채우기에 대한 EffectFormat을 반환합니다.<br/>            읽기 전용 [`IEffectFormat`](/slides/python-net/ko/aspose.slides/ieffectformat). |
| [`style_color`](/slides/python-net/ko/aspose.slides/ibackground/style_color/) | BackgroundType.Themed 채우기에 대한 ColorFormat을 반환합니다.<br/>            읽기 전용 [`IColorFormat`](/slides/python-net/ko/aspose.slides/icolorformat). |
| [`style_index`](/slides/python-net/ko/aspose.slides/ibackground/style_index/) | background theme 컬렉션에서 BackgroundType.Themed 채우기의 인덱스를 반환합니다.<br/>            0은 채우기가 없음을 의미합니다.<br/>            1..999 - 인덱스.<br/>            읽기/쓰기 **int**. |
| [`slide`](/slides/python-net/ko/aspose.slides/ibackground/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides/ibackground/presentation/) |  |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/ko/aspose.slides/ibackground/get_effective/#) | 상속이 적용된 유효한 배경 데이터를 가져옵니다. |


### 참고
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)