---
title: IBaseSlide class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/ibaseslide/
---
## IBaseSlide 클래스

모든 슬라이드 유형에 대한 공통 데이터를 나타냅니다.

IBaseSlide 유형은 다음 멤버를 노출합니다:

## 속성

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/ko/aspose.slides/ibaseslide/shapes/) | 슬라이드의 모양을 반환합니다.<br/>            읽기 전용 [`IShapeCollection`](/slides/python-net/ko/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/ko/aspose.slides/ibaseslide/controls/) | 슬라이드의 ActiveX 컨트롤 컬렉션을 반환합니다.<br/>            읽기 전용 [`IControlCollection`](/slides/python-net/ko/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/ko/aspose.slides/ibaseslide/name/) | 슬라이드의 이름을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`slide_id`](/slides/python-net/ko/aspose.slides/ibaseslide/slide_id/) | 슬라이드의 ID를 반환합니다.<br/>            읽기 전용 **int**. |
| [`custom_data`](/slides/python-net/ko/aspose.slides/ibaseslide/custom_data/) | 슬라이드의 사용자 지정 데이터를 반환합니다.<br/>            읽기 전용 [`ICustomData`](/slides/python-net/ko/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/ko/aspose.slides/ibaseslide/timeline/) | 애니메이션 타임라인 객체를 반환합니다.<br/>            읽기 전용 [`IAnimationTimeLine`](/slides/python-net/ko/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/ko/aspose.slides/ibaseslide/slide_show_transition/) | 지정된 슬라이드가 슬라이드 쇼 중에 어떻게 전환되는지를 포함하는 TransitionEx 객체를 반환합니다.<br/>            읽기 전용 [`ISlideShowTransition`](/slides/python-net/ko/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/ko/aspose.slides/ibaseslide/background/) | 슬라이드의 배경을 반환합니다.<br/>            읽기 전용 [`IBackground`](/slides/python-net/ko/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/ko/aspose.slides/ibaseslide/hyperlink_queries/) | 포함된 하이퍼링크에 쉽게 접근할 수 있습니다.<br/>            읽기 전용 [`IHyperlinkQueries`](/slides/python-net/ko/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/ko/aspose.slides/ibaseslide/show_master_shapes/) | 마스터 슬라이드의 모양이 슬라이드에 표시될지 여부를 지정합니다.<br/>            마스터 슬라이드 자체의 경우 이 속성은 항상 `false`를 반환합니다.<br/>            읽기/쓰기 **bool**. |
| [`slide`](/slides/python-net/ko/aspose.slides/ibaseslide/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides/ibaseslide/presentation/) |  |

## 메서드

| Method | Description |
| :- | :- |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ko/aspose.slides/ibaseslide/find_shape_by_alt_text/#str) | 지정된 대체 텍스트를 가진 모양의 첫 번째 발생을 찾습니다. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ko/aspose.slides/ibaseslide/join_portions_with_same_formatting/#) | 모든 허용 가능한 모양의 모든 단락에서 동일한 서식을 가진 실행을 결합합니다. |
| [`equals(self, slide)`](/slides/python-net/ko/aspose.slides/ibaseslide/equals/#ibaseslide) | 두 IBaseSlide 인스턴스가 동일한지 여부를 결정합니다.<br/>            반환 값은 슬라이드의 구조와 정적 콘텐츠를 기반으로 계산됩니다.<br/>            모든 모양, 스타일, 텍스트, 애니메이션 및 기타 설정 등이 동일하면 두 슬라이드는 동일합니다. 비교에서는 SlideId와 같은 고유 식별자 값 및 날짜 플레이스홀더의 현재 날짜 값과 같은 동적 콘텐츠는 고려되지 않습니다. |
| [`create_theme_effective(self)`](/slides/python-net/ko/aspose.slides/ibaseslide/create_theme_effective/#) |  |


### 참고
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)