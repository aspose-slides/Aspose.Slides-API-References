---
title: FontsManager class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/fontsmanager/
---
## FontsManager 클래스

프레젠테이션 전체에서 글꼴을 관리합니다.

FontsManager 형식은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/ko/aspose.slides/fontsmanager/font_subst_rule_list/) | 렌더링 시 사용할 글꼴 대체.<br/>            읽기/쓰기 [`IFontSubstRuleCollection`](/slides/python-net/ko/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/ko/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | 사용자의 FontFallBack 규칙 컬렉션을 나타내며, 글꼴의 올바른 대체를 위한 컬렉션을 관리합니다.<br/>            읽기/쓰기 [`IFontFallBackRulesCollection`](/slides/python-net/ko/aspose.slides/ifontfallbackrulescollection). |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/ko/aspose.slides/fontsmanager/get_substitutions/#) | 프레젠테이션 렌더링 시 교체될 글꼴에 대한 정보를 가져옵니다. |
| [`get_substitutions(self, slides)`](/slides/python-net/ko/aspose.slides/fontsmanager/get_substitutions/#listint) | 지정된 슬라이드 렌더링 중 교체될 글꼴에 대한 정보를 가져옵니다. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/ko/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | 임베드된 글꼴을 추가합니다.<br/>            글꼴을 복사할 때 대부분의 글꼴이 저작권이 있음을 기억하십시오. 먼저 글꼴의 라이선스를 찾아서 다른 머신으로 자유롭게 전송할 수 있는지 확인하십시오. 글꼴 데이터가 None이거나 이미 임베드된 경우 ArgumentException이 발생할 수 있습니다. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/ko/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | 임베드된 글꼴을 추가합니다.<br/>            글꼴을 복사할 때 대부분의 글꼴이 저작권이 있음을 기억하십시오. 먼저 글꼴의 라이선스를 찾아서 다른 머신으로 자유롭게 전송할 수 있는지 확인하십시오. 글꼴 데이터가 None이거나 이미 임베드된 경우 ArgumentException이 발생할 수 있습니다. |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/ko/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | 프레젠테이션의 글꼴을 교체합니다. |
| [`replace_font(self, subst_rule)`](/slides/python-net/ko/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | [`FontSubstRule`](/slides/python-net/ko/aspose.slides/fontsubstrule)에 제공된 정보를 사용하여 프레젠테이션의 글꼴을 교체합니다. |
| [`replace_font(self, subst_rules)`](/slides/python-net/ko/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | [`FontSubstRule`](/slides/python-net/ko/aspose.slides/fontsubstrule) 컬렉션에 제공된 정보를 사용하여 프레젠테이션의 글꼴을 교체합니다. |
| [`get_fonts(self)`](/slides/python-net/ko/aspose.slides/fontsmanager/get_fonts/#) | 프레젠테이션에 사용된 글꼴을 반환합니다. |
| [`get_embedded_fonts(self)`](/slides/python-net/ko/aspose.slides/fontsmanager/get_embedded_fonts/#) | 프레젠테이션에 임베드된 글꼴을 반환합니다. |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/ko/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | 임베드된 글꼴을 제거합니다. |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/ko/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | 지정된 글꼴 스타일 및 글꼴 데이터에 대한 글꼴 데이터를 나타내는 바이트 배열을 검색합니다. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/ko/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | 주어진 바이트 배열 및 글꼴 이름으로부터 글꼴의 임베드 수준을 결정합니다. |

### 관련 항목
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)