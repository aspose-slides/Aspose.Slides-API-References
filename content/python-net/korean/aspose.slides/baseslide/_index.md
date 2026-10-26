---
title: BaseSlide class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/baseslide/
---
## BaseSlide 클래스

모든 슬라이드 유형에 대한 공통 데이터를 나타냅니다.

BaseSlide 유형은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`shapes`](/slides/python-net/ko/aspose.slides/baseslide/shapes/) | 슬라이드의 도형을 반환합니다.<br/>            읽기 전용 [`IShapeCollection`](/slides/python-net/ko/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/ko/aspose.slides/baseslide/controls/) | 슬라이드에 있는 ActiveX 컨트롤 컬렉션을 반환합니다.<br/>            읽기 전용 [`IControlCollection`](/slides/python-net/ko/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/ko/aspose.slides/baseslide/name/) | 슬라이드의 이름을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`slide_id`](/slides/python-net/ko/aspose.slides/baseslide/slide_id/) | 슬라이드의 ID를 반환합니다.<br/>            읽기 전용 **int**. |
| [`custom_data`](/slides/python-net/ko/aspose.slides/baseslide/custom_data/) | 슬라이드의 사용자 지정 데이터를 반환합니다.<br/>            읽기 전용 [`ICustomData`](/slides/python-net/ko/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/ko/aspose.slides/baseslide/timeline/) | 애니메이션 타임라인 객체를 반환합니다.<br/>            읽기 전용 [`IAnimationTimeLine`](/slides/python-net/ko/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/ko/aspose.slides/baseslide/slide_show_transition/) | 지정된 슬라이드가 슬라이드 쇼 중에 진행되는 방식에 대한 정보를 포함하는 Transition 객체를 반환합니다.<br/>            읽기 전용 [`ISlideShowTransition`](/slides/python-net/ko/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/ko/aspose.slides/baseslide/background/) | 슬라이드 배경을 반환합니다.<br/>            읽기 전용 [`IBackground`](/slides/python-net/ko/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/ko/aspose.slides/baseslide/hyperlink_queries/) | 포함된 하이퍼링크에 대한 쉬운 접근을 제공합니다.<br/>            읽기 전용 [`IHyperlinkQueries`](/slides/python-net/ko/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/ko/aspose.slides/baseslide/show_master_shapes/) | 마스터 슬라이드의 도형이 슬라이드에 표시될지 여부를 지정합니다.<br/>            마스터 슬라이드 자체의 경우 이 속성은 항상 `false`를 반환합니다.<br/>            읽기/쓰기 **bool**. |
| [`presentation`](/slides/python-net/ko/aspose.slides/baseslide/presentation/) | IPresentation 인터페이스를 반환합니다.<br/>            읽기 전용 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation). |
| [`slide`](/slides/python-net/ko/aspose.slides/baseslide/slide/) |  |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ko/aspose.slides/baseslide/join_portions_with_same_formatting/#) | 모든 허용 가능한 도형의 모든 단락에서 동일한 서식의 실행을 결합합니다. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/ko/aspose.slides/baseslide/join_portions_with_same_formatting/#ishapecollection) | 모든 허용 가능한 도형의 모든 단락에서 동일한 서식의 실행을 결합합니다. |
| [`equals(self, slide)`](/slides/python-net/ko/aspose.slides/baseslide/equals/#ibaseslide) | 두 IBaseSlide 인스턴스가 동일한지 여부를 결정합니다.<br/>            반환 값은 슬라이드의 구조와 정적 내용에 기반하여 계산됩니다.<br/>            모든 도형, 스타일, 텍스트, 애니메이션 및 기타 설정 등이 동일하면 두 슬라이드는 동일합니다. 비교에서는 SlideId와 같은 고유 식별자 값이나 현재 날짜 값과 같은 동적 내용은 고려되지 않습니다. |
| [`create_theme_effective(self)`](/slides/python-net/ko/aspose.slides/baseslide/create_theme_effective/#) | 이 슬라이드에 대한 유효한 테마를 반환합니다. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/ko/aspose.slides/baseslide/find_shape_by_alt_text/#str) | 지정된 대체 텍스트를 가진 도형의 첫 번째 발생을 찾습니다. |


### 참조
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)