---
title: HtmlExternalResolver class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.importing/htmlexternalresolver/
---
## HtmlExternalResolver 클래스

HTML 가져오기 루틴에서 이미지와 같은 참조 객체를 얻기 위해 사용되는 콜백 객체.
이 해결자를 사용하면 클라이언트가 제공한 HTML 파일이 서버 소프트웨어가 로컬 또는 네트워크 파일을 가져오게 할 경우 취약점이 발생할 수 있습니다. 사용에 주의하십시오. HtmlExternalResolver를 전혀 지정하지 않는 것이 권장됩니다(임베디드 객체만 읽힙니다) 또는 지정된 uri가 유효한지 확인하는 서브클래스를 생성하십시오.

HtmlExternalResolver 유형은 다음 멤버를 노출합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ko/aspose.slides.importing/htmlexternalresolver/__init__/#) |  |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/ko/aspose.slides.importing/htmlexternalresolver/resolve_uri/#str-str) | 절대 URI를 기본 및 상대 URI에서 해결합니다. |
| [`get_entity(self, absolute_uri)`](/slides/python-net/ko/aspose.slides.importing/htmlexternalresolver/get_entity/#str) | URI를 실제 리소스를 포함하는 객체에 매핑합니다. |


### 참조
* 모듈 [`aspose.slides.importing`](/slides/python-net/ko/aspose.slides.importing)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)